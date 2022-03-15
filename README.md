# ml-in-genomics-2022
Hands on session for the day on GWAS in the context of the PSL Intensive Week on ML and Genomics 2022

Course website: https://data-psl.github.io/intensive-week-genomics-2022/

# Practical session
Prepared by [Chloé-Agathe Azencott](https://github.com/chagaz) with the help of [Vivien Goepp](https://github.com/vgoepp).
## Notebooks
The notebooks cover the same tools as the lecture:
* Practical 1:
  * T-test and Manhattan plots
  * Linear regression
  * Lasso
* Practical 2:
  * Elastic-net
  * Multi-task lasso
  * Network-constrained lasso

The practicals require writting very little code: most questions are about commenting on the results. We will provide solutions.

## Slides
Slides will be made available.

## Setting up
### Obtaining the code
You can either
* Download the repository as zip under the green "Code" button on the top right corner of this page

or
* Fork the repository (using the "Fork" button in the upper right corner), then clone ''your'' version of the repo (with URL ``https://github.com/<your_github_username>/ml-in-genomics-2022/`` to your machine using instructions under the  green "Code" button on the top right corner of the page, then add the original repo as an upstream branch with ``git remote add upstream git@github.com:chagaz/ml-in-genomics-2022.git``
Then whenever you want to synchronize your version with the upstream version, you can use 
``git checkout main
git fetch upstream
git merge upstream/main``

### Environment
You will need Python3, a few numerical python librairies (numpy, matplotlib, pandas, seaborn, scikit-learn) and Jupyter Lab/Notebook. An easy way to set up from scratch is to 
* [Install miniconda](https://github.com/goepp/ml-in-genomics-2021/blob/master/miniconda)
* Create a conda environment using the `environment.yml` file in this repo : ``conda env create --file=environment.yml -n mlgen`` which you can then activate using ``conda activate mlgen``
* Start Jupyter from this environment and navigate to the notebook you want to run.
