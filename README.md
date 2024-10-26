# Readme
## Create conda environment
```bash
conda create -n deep
conda activate deep
```
## Install dependencies
```bash
pip install -r requirements.txt
```

## Using CUDA
Select your OS, and select pip and select the latest CUDA: https://pytorch.org/get-started/locally/.
Then download the corresponding CUDA toolkit from https://developer.nvidia.com/cuda-toolkit-archive.
Then run the command showing on PyTorch after activating conda enviroment, e.g.
```bash
    pip install torch torchvision --index-url https://download.pytorch.org/whl/cu124
```

## Without CUDA
```bash
    pip install torch torchvision
```
