# ML
## Topic
1. Good explain about machine learning: https://monkeylearn.com/blog/gentle-guide-to-machine-learning/
2. 10 best algorithm:https://towardsdatascience.com/ten-machine-learning-algorithms-you-should-know-to-become-a-data-scientist-8dc93d8ca52e

## Environment
Try this:
https://tensorflow-object-detection-api-tutorial.readthedocs.io/en/latest/install.html
### Add Virtual Environment to Jupyter Notebook
First, you need to activate your virtual environment. Next, install ipykernel which provides the IPython kernel for Jupyter:  
```ini
pip install --user ipykernel  
```
Next you can add your virtual environment to Jupyter by typing:  
```ini
python -m ipykernel install --user --name=tensorflow_cpu  
```
This should print the following:  
```ini
Installed kernelspec myenv in /home/user/.local/share/jupyter/kernels/tensorflow_cpu    
```
Remove virtual environment from jupyter notebook.  
First list up env
```ini
jupyter kernelspec list
```
It will show as:
```ini
Available kernels:
  myenv      /home/user/.local/share/jupyter/kernels/tensorflow_cpu
  python3    /usr/local/share/jupyter/kernels/python3
```
```ini
jupyter kernelspec uninstall myenv
```
To deactive environment, type
```ini
conda deactive
```
To list all environments
```ini
conda env list
```
To remove an environment
```ini
conda env remove -n tensorflow_cpu
```
### If there is some SSL certificate problems  
```ini
conda config --set ssl_verify no
```
Then  
+ Alt - R: input %appdata%  
+ Create folder/file: pip/pip.ini  
```ini
[global]
trusted-host = pypi.org
			files.pythonhosted.org
			pypi.python.org
```
  
  ***** thandongtb/learn-machine-learning-in-two-months  
  https://viblo.asia/p/phan-2-deep-learning-cho-chatbot-tao-mot-retrieval-based-model-chatbot-QpmleEDDlrd  
  https://paperswithcode.com/sota
