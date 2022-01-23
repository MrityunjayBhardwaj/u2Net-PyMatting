<p align="center">
  <img width="320" height="320" src="figures/U2Net_Logo.png">
  
  <h1 align="center">U<sup>2</sup>-Net: U Square Net</h1>
    
</p>

## Description:
Improving u2Net performance using classical alpha metting techniques.

## BaseCode: 
pymatting: https://github.com/pymatting/pymatting
u2Net: https://github.com/xuebinqin/U-2-Net/blob/master/u2net_train.py


## Setup:

1. Install All the Dependencies ( its recommended to create a new env.)
```
pip install -r requirements.txt
```
2. Download DUTS Dataset from ![here](http://saliencydetection.net/duts/).

3. Put DUTS-TR inside `train_data/DUTS/`

4. you can also download the pretrained models from ![here](https://drive.google.com/drive/folders/1x48NDDqtXwY9NWdYpZZk6cA8fyoYeXK0?usp=sharing) and put it inside `saved_models` folder

5. run the training script:

```
python u2net_train.py
```



## Architecture:

![architecture](figures/u2net_pymatting.png)

## Results:
![chart](figures/chart.png)

