# Data_Driven_Science_Python_Demos

<img src="http://www.databookuw.com/files/stacks-image-5bffc53-882x1200.png" alt="Data Driven Book Cover" width="200"/>

IPython notebooks with demo code intended as a companion to the book:  


Data Driven Science & Engineering: Machine Learning, Dynamical Systems, and Control  
by S. L. Brunton and J. N. Kutz  
Cambridge Textbook, 2019  
Copyright 2019, All Rights Reserved  
http://databookuw.com/

Python code library by Daniel Dylewsky. There are a few items that are only available in the Matlab version. Many of these notebooks make use of third-party Python modules. Download links for the more obscure ones are provided inline.

MATLAB versions of these demos are available at https://github.com/dynamicslab/databook_matlab

Please cite this book when using this code/data.

## Setting up a python3 environment for this repo using Anaconda

[Anaconda](https://www.anaconda.com/) is a python package management framework that makes managing development environments easy.  After installing Anaconda, you can setup a development environment for following along with the Jupyter notebooks in this repository by executing:

```bash
conda env create -f {path-to-this-repo}/environment.yml
```

After the environment is created, you can enable it by executing:

```bash
conda activate databookuw
```

When you want to disable the current environment, execute:

```bash
conda deactivate
```
