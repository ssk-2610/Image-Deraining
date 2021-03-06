# BTP | GROUP B21MG06
- #### Pradum Singh S20180010136
- #### Shubham Kawatgi S20180010079
 - #### Sushant Bondle S20180010030

## Setting up project

1. Download the following dependencies using pip
  ```sh
   pip install yacs joblib natsort h5py tqdm 
   ```
## Training
- Download the Datasets

- Train the model with default arguments by running

```
python train.py
```


## Evaluation

1. Download the [model](https://drive.google.com/file/d/1O3WEJbcat7eTY6doXWeorAbQ1l_WmMnM/view?usp=sharing) and place it in `./pretrained_models/`

2. Download test datasets (Test100, Rain100H, Rain100L, Test1200, Test2800) from [here](https://drive.google.com/drive/folders/1PDWggNh8ylevFmrjo-JEvlmqsDlWWvZs?usp=sharing) and place them in `./Datasets/Synthetic_Rain_Datasets/test/`

3. Run
```
python test.py
```
## Results

![](pic/1.png)
![](pic/2.png)
![](pic/3.png)
![](pic/4.png)




