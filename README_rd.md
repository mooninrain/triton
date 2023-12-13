## Installation

```
conda create --name triton python=3.10 
conda install pytorch==2.0.1 torchvision==0.15.2 torchaudio==2.0.2 pytorch-cuda=11.7 -c pytorch -c nvidia
pip install ninja cmake wheel
apt-get install zlib1g-dev
pip install -e ./python
pip install -e './python[tutorials]' 
```