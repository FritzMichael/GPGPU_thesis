# Bachelor Thesis on the topic of GPGPU Signal Processing

## Abstract

The Python programming language has established itself as the most popular programming language for scientific computing and data processing due to its simple syntax and vast ecosystem.
The Python reference implementation, however, is limited in the performance it can achieve in computationally intensive tasks due to it being dynamically typed and interpreted at run-time.
To address this performance limitation, various packages and modules, which aim to circumvent those restrictions, have been developed for Python.
Libraries commonly used in the domain such as Numpy and SciPy provide interfaces to highly optimized and often parallelized C/C++ and Fortran libraries.

One particularly promising method for further improvements is the integration of Graphics Processing Units (GPUs) for computation tasks, which lend themselves to parallel execution.
In recent years GPUs have been extensively used in conjunction with Python in the field of Deep Learning.
This led to a number of Python packages, which offer accessible ways to leverage the GPU's computing capabilities.
In this thesis, we investigate the use of GPUs to accelerate signal processing in Python, with a focus on the FFT algorithm.
We explore suitable libraries available to Python users, such as PyTorch (a framework commonly used in deep-learning that offers offloading tasks to GPUs) or CuPy (a GPU aware replacement for Numpy).
We also implement our own GPU-accelerated FFT using idiomatic CUDA-C and integrate that routine into a Python program.

Our experimental results demonstrate that GPU-accelerated libraries can provide substantial speedups in FFT calculations compared to CPU based implementations.
This is especially true for batched transforms or transforms of higher dimensions.
While our work is limited to a specific set of hardware and software configurations and small subset of algorithms, our findings can serve as a starting point for further exploration of GPU-accelerated signal processing in Python.

## Demo of an interactive low-pass filter using OpenCV and CUDA

[demo.webm](https://user-images.githubusercontent.com/30218588/224945367-67d5e474-56bf-4e73-8dfd-3349ccdcf846.webm)
