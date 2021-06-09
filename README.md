# csquare default deep learning image

This Docker image is meant to be use as default runtime on the csquare platform.

## Included software

See the [Dockerfile](./Dockerfile) for more details.

| Software                                    | Version             |
| ------------------------------------------- | ------------------- |
| [TensorFlow](https://www.tensorflow.org)    | 2.3.0               |
| [PyTorch](https://pytorch.org)              | 1.6.0               |
| [torchvision](https://pytorch.org/vision)   | 2.3.0               |
| [cuDNN](https://developer.nvidia.com/cudnn) | 7.6.5.32-1+cuda10.1 |
| [NCCL](https://developer.nvidia.com/nccl)   | 2.7.8-1+cuda10.1    |
| [MXNet](https://mxnet.apache.org)           | 1.6.0.post0         |
