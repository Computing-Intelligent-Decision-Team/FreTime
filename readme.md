# FreTime

## Getting Started

### 1、Environment Requirements

To get started, ensure you have Conda installed on your system and follow these steps to set up the environment:

```
conda create -n FreTime python=3.11
conda activate FreTime
pip install -r requirements.txt
```



### 3、Training Example

For datasets with a small number of variables, such as ETTh, ETTm, and Exchange, we recommend using **FreTime** as follows:
```
bash ./scripts/ETTm1.sh
bash ./scripts/ETTm2.sh
bash ./scripts/ETTh2.sh
```

For datasets with a large number of variables such as ECL, Traffic, and weather, it is recommended to use **FreTime** as follows:
```
bash ./scripts/Solar.sh
bash ./scripts/Weather.sh
```


## Acknowledgement

We appreciate the following GitHub repositories for providing valuable code bases and datasets:

https://github.com/wanghq21/MICN

https://github.com/thuml/TimesNet

https://github.com/aikunyi/FreTS

https://github.com/VEWOXIC/FITS

https://github.com/plumprc/RTSF

https://github.com/cure-lab/LTSF-Linear

https://github.com/zhouhaoyi/Informer2020

https://github.com/thuml/Autoformer

https://github.com/ant-research/Pyraformer

https://github.com/MAZiqing/FEDformer

https://github.com/yuqinie98/PatchTST

https://github.com/thuml/iTransformer

https://github.com/thuml/Time-Series-Library
