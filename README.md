# pyspark-code-optimization
Some examples of pyspark code optimization techniques.

# Requirements

1-A computer with docker installation and git installation.
2-Download file "datos.json" from this url: https://drive.google.com/file/d/1rPiwk7ByPDzhKgnf8F4tQ9GsuPxHnzR3/view?usp=sharing

# Installation:

1-Download this repository.
2-Copy file "datos.json" into repository folder download.   
3-Execute docker run -it --rm -p 8888:8888 -v /repository/folder/download:/home/jovyan/data jupyter/pyspark-notebook
4-Open url that's apear on console with web browser.
5-Open terminal in Jupiter Notebooks and execute next commands:
$ pip install sparkmonitor 
$ ipython profile create
$ echo "c.InteractiveShellApp.extensions.append('sparkmonitor.kernelextension')" >>  $(ipython profile locate default)/ipython_kernel_config.py
6-Restart Kernel from Jupiter Notebooks.




