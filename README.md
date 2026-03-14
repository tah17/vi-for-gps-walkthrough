# vi-for-gps-walkthrough

## Table of contents
* [Introduction](#Introduction)
* [Technologies](#Technologies)
* [Setup](#Setup)
* [Usage](#Usage)
* [License](#License)
* [References](#References)

## Introduction
This repository is intended to be a quick walkthrough of using Variational Inference (VI) to fit Gaussian Process (GP) models using `GPflow`. Technical explanations follow those in (Williams and Rasmussen, 2006), (Blei _et al._ 2017) and (Leibfried _et al._ 2020) and code examples follow advice given in the [GPflow documentation](https://gpflow.github.io/GPflow/2.9.1/).

## Technologies
The code is written in Python (v3.11.14). Details of the packages are in the [environment.yml](environment.yml) file.

## Setup
First, clone or download the repository to your machine. To download the correct versions of the packages, use conda to copy the conda environment from the [environment.yml](environment.yml) file following instructions on the conda [website](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#creating-an-environment-from-an-environment-yml-file). Briefly, navigate to the repository folder and run the following in the terminal:

```
conda env create -f environment.yml
```

## Usage
The [`01_classical_gpr.ipynb`](#01_classical_gpr.ipynb) notebook is intended to be used first and contains the walkthrough on classical GP regression (GPR), which is included as a refresher on classical fitting of GP models. Next, the [`02_vi_gp.ipynb`](#02_vi_gp.ipynb) notebook should be used and this contains the quick walkthrough of fitting GPs using VI in `GPflow`.

## License
Licensed under the MIT license. See [LICENSE](LICENSE) for more information.

## References
- Williams CK, Rasmussen CE. Gaussian processes for machine learning. Cambridge, MA: MIT press; 2006 Dec.
- Blei DM, Kucukelbir A, McAuliffe JD. Variational inference: A review for statisticians. Journal of the American statistical Association. 2017 Apr 3;112(518):859-77.
- Leibfried F, Dutordoir V, John ST, Durrande N. A tutorial on sparse Gaussian processes and variational inference. arXiv preprint arXiv:2012.13962. 2020 Dec 27.
