## Installation

```
conda create --name triton python=3.10
conda install pytorch==2.0.1 torchvision==0.15.2 torchaudio==2.0.2 pytorch-cuda=11.7 -c pytorch -c nvidia
pip install ninja cmake wheel pytest
apt-get install zlib1g-dev
withporxy TRITON_BUILD_WITH_CLANG_LLD=1 pip install -e ./python
withporxy TRITON_BUILD_WITH_CLANG_LLD=1 pip install -e './python[tutorials]'
withproxy pip install flash-attn==2.4.2 --no-build-isolation
```
