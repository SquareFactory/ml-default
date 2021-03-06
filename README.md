# csquare default deep learning image

This Docker image is meant to be use as default runtime on the csquare platform.

This image comes with two flavours:

- `csquareai/ml-default:single` (or `csquareai/ml-default:latest`) to train models on a single node
- `csquareai/ml-default:parallel` which uses OpenMPI and optionally Horovod to train models on multiple nodes

See the list of [available tags](https://hub.docker.com/r/csquareai/ml-default/tags) for more information.

## Included software

### Basic programs

- [cmake](https://cmake.org)
- [curl](https://curl.se)
- [git](https://git-scm.com)
- [g++](https://gcc.gnu.org)
- [vim](https://www.vim.org)
- [wget](https://www.gnu.org/software/wget)

If you need additional software, please [open an issue](https://github.com/csquare-ai/ml-default/issues/new)!

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
