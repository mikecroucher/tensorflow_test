# Installing

```
conda create -n Tensortest Python=3.7
conda activate Tensortest
conda install tensorflow
conda install jupyter
conda install keras
```

# Checking it works

Run an example:

```
git clone https://github.com/aymericdamien/TensorFlow-Examples
cd TensorFlow-Examples
cd examples
cd TensorFlow-Examples
python helloworld.py
```

I got 

```
WARNING: Logging before flag parsing goes to stderr.
W0829 13:42:38.948628  9508 deprecation_wrapper.py:119] From helloworld.py:22: The name tf.Session is deprecated. Please use tf.compat.v1.Session instead.

2019-08-29 13:42:38.951885: I tensorflow/core/platform/cpu_feature_guard.cc:145] This TensorFlow binary is optimized with Intel(R) MKL-DNN to use the following CPU instructions in performance critical operations:  AVX AVX2
To enable them in non-MKL-DNN operations, rebuild TensorFlow with the appropriate compiler flags.
2019-08-29 13:42:38.964533: I tensorflow/core/common_runtime/process_util.cc:115] Creating new thread pool with default inter op setting: 8. Tune using inter_op_parallelism_threads for best performance.
b'Hello, TensorFlow!'
```
