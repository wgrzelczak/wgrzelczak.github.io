# AI Notes

* [course.fast.ai](course.fast.ai)
* [Gymnasium](https://github.com/Farama-Foundation/Gymnasium)


# Torch + CUDA Installation
* install CUDA from [developer.nvidia.com](https://developer.nvidia.com/cuda-toolkit-archive)
* run 
```
    pip install torch==2.0.1+cu118 torchvision==0.11.2+cu118 torchaudio==0.10.1+cu118 -f https://download.pytorch.org/whl/cu118/torch_stable.html`
```
* to verify run 
```
    python -c "import torch; print(torch.version.cuda)"
    python -c "import torch; print(torch.cuda.is_available())"
```                                                         
