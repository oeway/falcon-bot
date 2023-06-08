# Falcon Bot

## Installation

```
conda create -n falcon python=3.9 -y
conda install pytorch torchvision torchaudio pytorch-cuda=11.7 -c pytorch -c nvidia
pip install transformers chardet einops accelerate -y
```


## Usage

```
conda activate falcon
python run-falcon-7b.py 
```