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

## Most important stuff to evaluate
- Which activation function
- Which type of layers and how many
- Which loss function
- Which optimizer
- Which learning rate
- Which batch size
- Which number of epochs

## Validation vs. test
- Overfitting
- Keep test out of the training, since it will learn based on these samples.

# Using CUDA
Select your OS, and select pip and select the latest CUDA: https://pytorch.org/get-started/locally/.
Then download the corresponding CUDA toolkit from https://developer.nvidia.com/cuda-toolkit-archive.
Then run the command showing on PyTorch after activating conda enviroment, e.g.
```bash
    pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu124
```