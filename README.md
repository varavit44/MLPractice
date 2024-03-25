# Objective
I have stored the source code while practicing machine learning here.
# Where did I run the code
I run this on Google colab and Jupyter notebook.
# Environment setting
My environment installation in Anaconda for Jupyter notebook.
## For CPU
> step 1: create environment python 3.10.4
> step 2: install seaborn
> step 3: install scikit-learn
> step 4: install opencv, libopencv, py-opencv 4.6.0
> step 5: install tensorflow, tensorboard, tensorflow-base
> if ImportError: DLL load failed: The specified module could not be found.
    step 1: make sure you have Visual C++ redistributable 2015(x64) installed
    step 2: Apps & features --> Microsoft Visual C++ redistributable 2015(x64) click and select 'change' --> 'repair' then restart your computer
    step 3: download opencv_python-4.5.5-cp310-cp310-win_amd64.whls from https://www.lfd.uci.edu/~gohlke/pythonlibs/
    step 4: pip install opencv_python-4.5.5-cp310-cp310-win_amd64.whl
> if ModuleNotFoundError: No module named 'wrapt'
    pip install wrapt

