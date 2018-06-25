# Tenssorflow tutorial for MLSS Algiers
This tutorial teaches the main concepts of tensorflow, necessary to extend and develop new machine learning models and algorithms.
The tutorial is split into 4 parts. 
- Part 1 introduces the basics or mechanics of tensorflow
- In part 2, you will implement our first Machine Learning model and training algorithm with the low-level tf API.
- In part 3, we introduce very practical and useful high-level APIs to facilitate implementation and debugging.
- In part 4, you will adapt your model from classification to a regression problem.
### Requirements
We only need tensorflow, numpy, matplotlib, and jupyter notebook, preferably with python3.
In this tutorial, we work with simple models and toy data, so we don't need GPU support.
### Install
 - Install python3 and pip
 - Recommended: virtualenv with virtualenvwrapper (to create isolated environment with python packages for this tutorial).
     - sudo pip install virtualenv virtualenvwrapper
     - add the following lines to your ~/.bashrc or ~/.zshrc or ~/.bash_profile (depends what you are using)
     
           export WORKON_HOME=$HOME/.virtualenvs
           export VIRTUALENVWRAPPER_PYTHON=/usr/local/bin/python3
           export VIRTUALENVWRAPPER_VIRTUALENV=/usr/local/bin/virtualenv
           export VIRTUALENVWRAPPER_VIRTUALENV_ARGS='--no-site-packages'
     - mkvirtualenv tf_tutorial --python=python3
     - workon tf_tutorial
 - pip install tensorflow numpy tensorflow jupyter notebook
