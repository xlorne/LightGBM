<img src=https://github.com/microsoft/LightGBM/blob/master/docs/logo/LightGBM_logo_black_text.svg width=300 />

Light Gradient Boosting Machine Test
===============================

[![Python-package GitHub Actions Build Status](https://github.com/microsoft/LightGBM/actions/workflows/python_package.yml/badge.svg?branch=master)](https://github.com/microsoft/LightGBM/actions/workflows/python_package.yml)
[![R-package GitHub Actions Build Status](https://github.com/microsoft/LightGBM/actions/workflows/r_package.yml/badge.svg?branch=master)](https://github.com/microsoft/LightGBM/actions/workflows/r_package.yml)
[![CUDA Version GitHub Actions Build Status](https://github.com/microsoft/LightGBM/actions/workflows/cuda.yml/badge.svg?branch=master)](https://github.com/microsoft/LightGBM/actions/workflows/cuda.yml)
[![Static Analysis GitHub Actions Build Status](https://github.com/microsoft/LightGBM/actions/workflows/static_analysis.yml/badge.svg?branch=master)](https://github.com/microsoft/LightGBM/actions/workflows/static_analysis.yml)
[![Azure Pipelines Build Status](https://lightgbm-ci.visualstudio.com/lightgbm-ci/_apis/build/status/Microsoft.LightGBM?branchName=master)](https://lightgbm-ci.visualstudio.com/lightgbm-ci/_build/latest?definitionId=1)
[![Appveyor Build Status](https://ci.appveyor.com/api/projects/status/1ys5ot401m0fep6l/branch/master?svg=true)](https://ci.appveyor.com/project/guolinke/lightgbm/branch/master)
[![Documentation Status](https://readthedocs.org/projects/lightgbm/badge/?version=latest)](https://lightgbm.readthedocs.io/)
[![Link checks](https://github.com/microsoft/LightGBM/actions/workflows/linkchecker.yml/badge.svg?branch=master)](https://github.com/microsoft/LightGBM/actions/workflows/linkchecker.yml)
[![License](https://img.shields.io/github/license/microsoft/lightgbm.svg)](https://github.com/microsoft/LightGBM/blob/master/LICENSE)
[![EffVer Versioning](https://img.shields.io/badge/version_scheme-EffVer-0097a7)](https://jacobtomlinson.dev/effver)
[![Python Versions](https://img.shields.io/pypi/pyversions/lightgbm.svg?logo=python&logoColor=white)](https://pypi.org/project/lightgbm)
[![PyPI Version](https://img.shields.io/pypi/v/lightgbm.svg?logo=pypi&logoColor=white)](https://pypi.org/project/lightgbm)
[![conda Version](https://img.shields.io/conda/vn/conda-forge/lightgbm?logo=conda-forge&logoColor=white&label=conda)](https://anaconda.org/conda-forge/lightgbm)
[![CRAN Version](https://www.r-pkg.org/badges/version/lightgbm)](https://cran.r-project.org/package=lightgbm)
[![NuGet Version](https://img.shields.io/nuget/v/lightgbm?logo=nuget&logoColor=white)](https://www.nuget.org/packages/LightGBM)

LightGBM is a gradient boosting framework that uses tree based learning algorithms. It is designed to be distributed and efficient with the following advantages:

- Faster training speed and higher efficiency.
- Lower memory usage.
- Better accuracy.
- Support of parallel, distributed, and GPU learning.
- Capable of handling large-scale data.

For further details, please refer to [Features](https://github.com/microsoft/LightGBM/blob/master/docs/Features.rst).

Benefiting from these advantages, LightGBM is being widely-used in many [winning solutions](https://github.com/microsoft/LightGBM/blob/master/examples/README.md#machine-learning-challenge-winning-solutions) of machine learning competitions.

[Comparison experiments](https://github.com/microsoft/LightGBM/blob/master/docs/Experiments.rst#comparison-experiment) on public datasets show that LightGBM can outperform existing boosting frameworks on both efficiency and accuracy, with significantly lower memory consumption. What's more, [distributed learning experiments](https://github.com/microsoft/LightGBM/blob/master/docs/Experiments.rst#parallel-experiment) show that LightGBM can achieve a linear speed-up by using multiple machines for training in specific settings.

Get Started and Documentation
-----------------------------

Our primary documentation is at https://lightgbm.readthedocs.io/ and is generated from this repository. If you are new to LightGBM, follow [the installation instructions](https://lightgbm.readthedocs.io/en/latest/Installation-Guide.html) on that site.

Next you may want to read:

- [**Examples**](https://github.com/microsoft/LightGBM/tree/master/examples) showing command line usage of common tasks.
- [**Features**](https://github.com/microsoft/LightGBM/blob/master/docs/Features.rst) and algorithms supported by LightGBM.
- [**Parameters**](https://github.com/microsoft/LightGBM/blob/master/docs/Parameters.rst) is an exhaustive list of customization you can make.
- [**Distributed Learning**](https://github.com/microsoft/LightGBM/blob/master/docs/Parallel-Learning-Guide.rst) and [**GPU Learning**](https://github.com/microsoft/LightGBM/blob/master/docs/GPU-Tutorial.rst) can speed up computation.
- [**FLAML**](https://www.microsoft.com/en-us/research/project/fast-and-lightweight-automl-for-large-scale-data/articles/flaml-a-fast-and-lightweight-automl-library/) provides automated tuning for LightGBM ([code examples](https://microsoft.github.io/FLAML/docs/Examples/AutoML-for-LightGBM/)).
- [**Optuna Hyperparameter Tuner**](https://medium.com/optuna/lightgbm-tuner-new-optuna-integration-for-hyperparameter-optimization-8b7095e99258) provides automated tuning for LightGBM hyperparameters ([code examples](https://github.com/optuna/optuna-examples/blob/main/lightgbm/lightgbm_tuner_simple.py)).
- [**Understanding LightGBM Parameters (and How to Tune Them using Neptune)**](https://neptune.ai/blog/lightgbm-parameters-guide).

Documentation for contributors:

- [**How we update readthedocs.io**](https://github.com/microsoft/LightGBM/blob/master/docs/README.rst).
- Check out the [**Development Guide**](https://github.com/microsoft/LightGBM/blob/master/docs/Development-Guide.rst).

News
----

Please refer to changelogs at [GitHub releases](https://github.com/microsoft/LightGBM/releases) page.

External (Unofficial) Repositories
----------------------------------

Projects listed here offer alternative ways to use LightGBM.
They are not maintained or officially endorsed by the `LightGBM` development team.

JPMML (Java PMML converter): https://github.com/jpmml/jpmml-lightgbm

Nyoka (Python PMML converter): https://github.com/SoftwareAG/nyoka

Treelite (model compiler for efficient deployment): https://github.com/dmlc/treelite

lleaves (LLVM-based model compiler for efficient inference): https://github.com/siboehm/lleaves

Hummingbird (model compiler into tensor computations): https://github.com/microsoft/hummingbird

GBNet (use `LightGBM` as a [PyTorch Module](https://docs.pytorch.org/docs/stable/generated/torch.nn.Module.html)): https://github.com/mthorrell/gbnet

cuML Forest Inference Library (GPU-accelerated inference): https://github.com/rapidsai/cuml

daal4py (Intel CPU-accelerated inference): https://github.com/intel/scikit-learn-intelex/tree/master/daal4py

m2cgen (model appliers for various languages): https://github.com/BayesWitnesses/m2cgen

leaves (Go model applier): https://github.com/dmitryikh/leaves

ONNXMLTools (ONNX converter): https://github.com/onnx/onnxmltools

SHAP (model output explainer): https://github.com/slundberg/shap

Shapash (model visualization and interpretation): https://github.com/MAIF/shapash

dtreeviz (decision tree visualization and model interpretation): https://github.com/parrt/dtreeviz

supertree (interactive visualization of decision trees): https://github.com/mljar/supertree

SynapseML (LightGBM on Spark): https://github.com/microsoft/SynapseML

Kubeflow Fairing (LightGBM on Kubernetes): https://github.com/kubeflow/fairing

Kubeflow Operator (LightGBM on Kubernetes): https://github.com/kubeflow/xgboost-operator

lightgbm_ray (LightGBM on Ray): https://github.com/ray-project/lightgbm_ray

Mars (LightGBM on Mars): https://github.com/mars-project/mars

ML.NET (.NET/C#-package): https://github.com/dotnet/machinelearning

LightGBM.NET (.NET/C#-package): https://github.com/rca22/LightGBM.Net

LightGBM Ruby (Ruby gem): https://github.com/ankane/lightgbm-ruby

LightGBM4j (Java high-level binding): https://github.com/metarank/lightgbm4j

LightGBM4J (JVM interface for LightGBM written in Scala): https://github.com/seek-oss/lightgbm4j

Julia-package: https://github.com/IQVIA-ML/LightGBM.jl

lightgbm3 (Rust binding): https://github.com/Mottl/lightgbm3-rs

MLServer (inference server for LightGBM): https://github.com/SeldonIO/MLServer

MLflow (experiment tracking, model monitoring framework): https://github.com/mlflow/mlflow

FLAML (AutoML library for hyperparameter optimization): https://github.com/microsoft/FLAML

MLJAR AutoML (AutoML on tabular data): https://github.com/mljar/mljar-supervised

Optuna (hyperparameter optimization framework): https://github.com/optuna/optuna

LightGBMLSS (probabilistic modelling with LightGBM): https://github.com/StatMixedML/LightGBMLSS

mlforecast (time series forecasting with LightGBM): https://github.com/Nixtla/mlforecast

skforecast (time series forecasting with LightGBM): https://github.com/JoaquinAmatRodrigo/skforecast

`{bonsai}` (R `{parsnip}`-compliant interface): https://github.com/tidymodels/bonsai

`{mlr3extralearners}` (R `{mlr3}`-compliant interface): https://github.com/mlr-org/mlr3extralearners

lightgbm-transform (feature transformation binding): https://github.com/microsoft/lightgbm-transform

`postgresml` (LightGBM training and prediction in SQL, via a Postgres extension): https://github.com/postgresml/postgresml

`pyodide` (run `lightgbm` Python-package in a web browser): https://github.com/pyodide/pyodide

`vaex-ml` (Python DataFrame library with its own interface to LightGBM): https://github.com/vaexio/vaex

Support
-------

- Ask a question [on Stack Overflow with the `lightgbm` tag](https://stackoverflow.com/questions/ask?tags=lightgbm), we monitor this for new questions.
- Open **bug reports** and **feature requests** on [GitHub issues](https://github.com/microsoft/LightGBM/issues).

How to Contribute
-----------------

Check [CONTRIBUTING](https://github.com/microsoft/LightGBM/blob/master/CONTRIBUTING.md) page.

Microsoft Open Source Code of Conduct
-------------------------------------

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

Reference Papers
----------------

Yu Shi, Guolin Ke, Zhuoming Chen, Shuxin Zheng, Tie-Yan Liu. "Quantized Training of Gradient Boosting Decision Trees" ([link](https://papers.nips.cc/paper_files/paper/2022/hash/77911ed9e6e864ca1a3d165b2c3cb258-Abstract.html)). Advances in Neural Information Processing Systems 35 (NeurIPS 2022), pp. 18822-18833.

Guolin Ke, Qi Meng, Thomas Finley, Taifeng Wang, Wei Chen, Weidong Ma, Qiwei Ye, Tie-Yan Liu. "[LightGBM: A Highly Efficient Gradient Boosting Decision Tree](https://papers.nips.cc/paper/6907-lightgbm-a-highly-efficient-gradient-boosting-decision-tree)". Advances in Neural Information Processing Systems 30 (NIPS 2017), pp. 3149-3157.

Qi Meng, Guolin Ke, Taifeng Wang, Wei Chen, Qiwei Ye, Zhi-Ming Ma, Tie-Yan Liu. "[A Communication-Efficient Parallel Algorithm for Decision Tree](https://proceedings.neurips.cc/paper/2016/hash/10a5ab2db37feedfdeaab192ead4ac0e-Abstract.html)". Advances in Neural Information Processing Systems 29 (NIPS 2016), pp. 1279-1287.

Huan Zhang, Si Si and Cho-Jui Hsieh. "[GPU Acceleration for Large-scale Tree Boosting](https://arxiv.org/abs/1706.08359)". SysML Conference, 2018.

License
-------

This project is licensed under the terms of the MIT license. See [LICENSE](https://github.com/microsoft/LightGBM/blob/master/LICENSE) for additional details.
