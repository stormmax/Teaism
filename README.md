## Teaism

A light weighted, flexible, and efficient deep learning library for CUDA-based embedded and mobile devices.

## Dependencies

- C++0x
- CUDA 8.0
- CMake 3.5

## Files
```
.
├── CMakeLists.txt
├── Makefile
├── README.md
├── basics
│   ├── initializer.hpp
│   ├── layer.hpp
│   ├── session.hpp
│   └── tensor.cu
├── initializers
│   ├── const_initializer.hpp
│   └── gaussian_kernel_initializer.cu
├── layers
│   ├── conv2d.cu
│   ├── data.cu
│   ├── pooling.cu
│   ├── relu.cu
│   ├── softmax.cu
│   └── softmax_loss.cu
├── main.cu
├── tests
│   ├── tests_conv2d.cu
│   ├── tests_data.cu
│   ├── tests_gaussian_initializer.cu
│   ├── tests_pooling.cu
│   ├── tests_relu.cu
│   ├── tests_softmax.cu
│   └── tests_tensor.cu
└── utils
    ├── bitmap_image.hpp
    ├── helper_cuda.h
    └── helper_string.h
```
