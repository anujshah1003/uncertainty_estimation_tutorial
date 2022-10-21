# uncertainty_estimation_tutorial
This repository attempts to understand the concepts of uncertainty estimation.

***I think it is much more interesting to live not knowing than to have answers that might be wrong - Richard P Feynman***

## Installation

Tensorflow
```bash
# cpu version 
pip install --upgrade tensorflow
```
Based on your python selct the GPU Wheel accrodingly [check here](https://www.tensorflow.org/install/pip)
```bash
# gpu version
pip install --upgrade https://storage.googleapis.com/tensorflow/linux/gpu/tensorflow_gpu-2.8.0-cp37-cp37m-manylinux2010_x86_64.whl
```
Uncertainty Baseline
```bash
pip install "git+https://github.com/google/uncertainty-baselines.git#egg=uncertainty_baselines"
```
Installing other dependencies
```bash
cd UncertaintyEstimation_tfp
pip install -r requirements.txt
```
