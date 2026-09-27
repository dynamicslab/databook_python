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

# Python virtual environment setup

```
python -m venv .venv
source .venv/bin/activate
pip install ipykernel
python -m ipykernel install --user --name=myenv --display-name "Python (.venv)"
```
Now you'll be able to choose the kernel assocaited with .venv when executing code in jupyter
