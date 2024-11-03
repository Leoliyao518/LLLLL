# LLLLL

## Setup
We implement this repo with the following environment:
- Ubuntu 22.04
- Python 3.8
- Pytorch 2.1.2
- CUDA 12.1

Install the other package via:
``` bash
pip install -r requirement.txt
```
## Data Download and Preprocess

### Dataset

- The `MVTec AD` dataset can be download from the [Official Website of MVTec AD](https://www.mvtec.com/company/research/datasets/mvtec-ad). 

- The `BTAD` dataset can be download from the [Official Website of BTAD](http://avires.dimi.uniud.it/papers/btad/btad.zip). 

After download, put the dataset in `dataset` folder.

## Train

```bash
python main.py
```

## Test

```bash
python eval.py
```
