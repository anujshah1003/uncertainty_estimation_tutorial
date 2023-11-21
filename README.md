# uncertainty_estimation_tutorial
This repository attempts to understand the concepts of uncertainty estimation.

***I think it is much more interesting to live not knowing than to have answers that might be wrong - Richard P Feynman***

## Tutorials
1. Understanding weight matrices of different ensemble approaches for uncertainty estimation: Deep Ensemble vs Batch Ensemble vs Rank-1 BNN
  - Video Part-1: [Understanding](https://www.youtube.com/watch?v=KZNrVt8Vspc&t=401s) 
  - Video Part-2: [Demo Example](https://www.youtube.com/watch?v=4t4eEAGRJ8s)
  - Code: [comparison_parameter_deep_batch_rank_1_ens.ipynb](https://github.com/anujshah1003/uncertainty_estimation_tutorial/blob/main/comparison_parameter_deep_batch_rank_1_ens.ipynb)
  - Docs: [different_ensemble_comparison.pdf](https://github.com/anujshah1003/uncertainty_estimation_tutorial/blob/main/supporting_docs/different_ensemble_comparison.pdf)

2. Model Calibration
  - Medium Blog: [A step towards trustworthy and reliable AI](https://medium.com/@anuj_shah/model-calibration-a-step-towards-trustworthy-and-reliable-ai-1181f2fef2c3)
  - Code: [notebooks](https://github.com/anujshah1003/uncertainty_estimation_tutorial/tree/model_calibration/model_calibration/notebooks)
## Installation

Tensorflow
```bash
# cpu version 
pip install --upgrade tensorflow
```
Based on your Python select the GPU Wheel accordingly [check here](https://www.tensorflow.org/install/pip)
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
cd uncertainty_estmation_tutorial
pip install -r requirements.txt
```

## Papers
1. [Deep Ensemble](https://arxiv.org/abs/1612.01474)
2. [Batch Ensemble](https://arxiv.org/abs/2002.06715)
3. [Rank-1 BNN](https://arxiv.org/pdf/2005.07186.pdf)

## Code References
* Uncertainty Baseline: https://github.com/google/uncertainty-baselines
* Deep Ensemble
    * https://github.com/hayoung-kim/tf2-deep-ensemble-uncertainty
