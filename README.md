
# Multi-Label-Text-Classification
Towards Data Science article [Deep dive into multi-label classification..!](https://towardsdatascience.com/journey-to-the-center-of-multi-label-classification-384c40229bff)

Attempts to solve [Kaggle Toxic Comments Challenge](https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge)


With continuous increase in available data, there is a pressing need to organize it and modern classification problems often involve the prediction of multiple labels simultaneously associated with a single instance.
Known as Multi-Label Classification, it is one such task which is omnipresent in many real world problems.

In this project, using a Kaggle problem as example, we explore different aspects of multi-label classification.

### Bird’s-eye view of the project:
* Part-1: Overview of Multi-label classification.
* Part-2: Problem definition & evaluation metrics.
* Part-3: Exploratory data analysis (EDA).
* Part-4: Data pre-processing.
* Part-5: Multi-label classification techniques.


Detailed blog about this project can be found here [https://medium.com/@nkartik94/journey-to-the-center-of-multi-label-classification-384c40229bff]



## GETTING STARTED
 
FORK GIT REPO

DOWNLOAD DATA
- https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge/data

### PACKAGES

Install all dependencies for a project (including dev):
```
$ . ~/.conda_init
$ conda create -n multi-label-text_dev python=3.7 pandas numpy  matplotlib seaborn jupyter
$ conda activate multi-label-text_dev
$ conda run jupyter notebook  
```

WORD CLOUD
```
$ conda install -c conda-forge wordcloud
Collecting package metadata (current_repodata.json): done
Solving environment: done


==> WARNING: A newer version of conda exists. <==
  current version: 4.7.12
  latest version: 4.8.0rc0

Please update conda by running

    $ conda update -n base -c defaults conda



## Package Plan ##

  environment location: /usr/local/Caskroom/miniconda/base/envs/multi-label-text_dev

  added / updated specs:
    - wordcloud


The following packages will be downloaded:

    package                    |            build
    ---------------------------|-----------------
    ca-certificates-2019.9.11  |       hecc5488_0         143 KB  conda-forge
    certifi-2019.9.11          |           py37_0         147 KB  conda-forge
    olefile-0.46               |             py_0          31 KB  conda-forge
    openssl-1.1.1d             |       h0b31af3_0         1.9 MB  conda-forge
    pillow-6.2.1               |   py37hb68e598_0         602 KB
    wordcloud-1.5.0            |py37h0b31af3_1000         167 KB  conda-forge
    ------------------------------------------------------------
                                           Total:         2.9 MB

The following NEW packages will be INSTALLED:

  libtiff            pkgs/main/osx-64::libtiff-4.1.0-hcb84e12_0
  olefile            conda-forge/noarch::olefile-0.46-py_0
  pillow             pkgs/main/osx-64::pillow-6.2.1-py37hb68e598_0
  wordcloud          conda-forge/osx-64::wordcloud-1.5.0-py37h0b31af3_1000
  zstd               pkgs/main/osx-64::zstd-1.3.7-h5bba6e5_0

The following packages will be SUPERSEDED by a higher-priority channel:

  ca-certificates    pkgs/main::ca-certificates-2019.10.16~ --> conda-forge::ca-certificates-2019.9.11-hecc5488_0
  certifi                                         pkgs/main --> conda-forge
  openssl              pkgs/main::openssl-1.1.1d-h1de35cc_3 --> conda-forge::openssl-1.1.1d-h0b31af3_0


Proceed ([y]/n)? 

```
Test the environment
```python
$ python test_env.py
EVERYTHING LOADED!
$

```

