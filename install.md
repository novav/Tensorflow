1、install anacoda

2、install tensorflow-gpu
-    conda create -n tensorflow-gpu python=3.5 //必须项目
-    conda create -n tensorflow-gpu python=3.5 anaconda // 很多lib都会安装

3、 avtiave
-  cmd: cd D:\Tools\Tensoflow
-  cmd: activate tensorflow-gpu

4\ Run

```python 
  python
  import tensorflow as tf
  tf.__version__
```
ImportError: Could not find 'cudart64_80.dll'. TensorFlow requires that this DLL be installed in a directory that is named in your %PATH% environment variable. Download and install CUDA 8.0 from this URL: https://developer.nvidia.com/cuda-toolkit


