# ML
## Topic
1. Good explain about machine learning: https://monkeylearn.com/blog/gentle-guide-to-machine-learning/
2. 10 best algorithm:https://towardsdatascience.com/ten-machine-learning-algorithms-you-should-know-to-become-a-data-scientist-8dc93d8ca52e

## Environment
Try this:
https://tensorflow-object-detection-api-tutorial.readthedocs.io/en/latest/install.html
### Add Virtual Environment to Jupyter Notebook
First, you need to activate your virtual environment. Next, install ipykernel which provides the IPython kernel for Jupyter:  
pip install --user ipykernel  
Next you can add your virtual environment to Jupyter by typing:  
python -m ipykernel install --user --name=tensorflow_cpu  
This should print the following:  
Installed kernelspec myenv in /home/user/.local/share/jupyter/kernels/tensorflow_cpu    
* if cerfification error: conda config --set ssl_verify no

Or
1. Python (3.6)  
2. Anaconda  
https://www.anaconda.com/download/  
https://repo.anaconda.com/archive/  (Anaconda3-5.2.0  for Python 3.6)  
http://docs.anaconda.com/anaconda/user-guide/faq/#how-do-i-get-the-latest-anaconda-with-python-3-5  

3. Install python 3.6 for latest anaconda  
*** conda install python=3.6  

4. Install tensorflow  
*** pip install --no-cache tensorflow  

If there is some SSL certificate problems  
+ Alt - R: input %appdata%  
+ Create folder/file: pip/pip.ini  
```ini
[global]
trusted-host = pypi.org
			files.pythonhosted.org
			pypi.python.org
```
conda create -n tensorflow_env python=3.6  
conda activate tensorflow_env  
conda install -c conda-forge tensorflow  

*local  
pip install --ignore-installed --upgrade path_of_tensorflow_3.6  
  
  
  
   
  ***** thandongtb/learn-machine-learning-in-two-months  
  https://viblo.asia/p/phan-2-deep-learning-cho-chatbot-tao-mot-retrieval-based-model-chatbot-QpmleEDDlrd  
  https://paperswithcode.com/sota
