# csquare default deep learning image

This Docker image is meant to be use as default runtime on the csquare platform.

This image comes with two flavours:

- `single` (or `latest`) to train models on a single node
- `parallel` which uses OpenMPI and optionally Horovod to train models on multiple nodes

## Included software

### Basic programs

- [cmake](https://cmake.org)
- [curl](https://curl.se)
- [git](https://git-scm.com)
- [g++](https://gcc.gnu.org)
- [vim](https://www.vim.org)
- [wget](https://www.gnu.org/software/wget)

### Training frameworks/tools

See the [Dockerfile](./Dockerfile) for more details.

| Software                                    | Version             |
| ------------------------------------------- | ------------------- |
| [TensorFlow](https://www.tensorflow.org)    | 2.3.0               |
| [PyTorch](https://pytorch.org)              | 1.6.0               |
| [torchvision](https://pytorch.org/vision)   | 2.3.0               |
| [cuDNN](https://developer.nvidia.com/cudnn) | 7.6.5.32-1+cuda10.1 |
| [NCCL](https://developer.nvidia.com/nccl)   | 2.7.8-1+cuda10.1    |
| [MXNet](https://mxnet.apache.org)           | 1.6.0.post0         |
