# Lagou Tutorial on Data Science in Python
Author: Fido Wong

This repository contain files and other info associated with Lagou Data Science Introduction Tutorial on python.

To open notebooks in IPython, download the files to a directory on your computer and from that directory run:

    $ ipython notebook

This will open a new page in your browser with a list of the available notebooks.

A previous introduction by Rong in Python Programming can be found in https://github.com/ghostrong/idiomatic_python

## Installation Notes
This tutorial requires the following packages:

- Python version 2.6-2.7 or 3.3-3.4
- `numpy` version 1.5 or later: http://www.numpy.org/
- `scipy` version 0.10 or later: http://www.scipy.org/
- `pandas` version 0.17.0 or later: http://pandas.pydata.org/
- `matplotlib` version 1.3 or later: http://matplotlib.org/
- `scikit-learn` version 0.14 or later: http://scikit-learn.org
- `ipython` version 2.0 or later, with notebook support: http://ipython.org
- `seaborn` version 0.5 or later: http://web.stanford.edu/~mwaskom/software/seaborn/

The easiest way to get these is to use the [conda](https://store.continuum.io/) environment manager.
I suggest downloading and installing [miniconda](http://conda.pydata.org/miniconda.html).

Once `miniconda` is installed, the following command will install all required packages in your Python environment:
```
$ conda install numpy scipy matplotlib scikit-learn ipython-notebook seaborn
```

Alternatively, you can download and install the (very large) Anaconda software distribution, found at https://store.continuum.io/.

## Downloading the Tutorial Materials
Downloading of the materials is highly recommended by using git.  
Once git is installed, you can clone the material in this tutorial by using the git address shown above:

    git clone git://github.com/jakevdp/sklearn_pycon2015.git

If you can't or don't want to install git, there is a link above to download
the contents of this repository as a zip file.  Further changes would be making 
since I may have new idea on its form.

## Reference
This tutorial is partially referred from [sklearn-tutorial, PyCon 2015](https://github.com/jakevdp/sklearn_pycon2015)
