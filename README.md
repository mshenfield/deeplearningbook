# Deep Learning Book Journal
A journal to keep track of my progress through http://www.deeplearningbook.org/.

This includes jupyter notebooks used for examples and exercises, and in the future may include
AMIs or Vagrant files or instructions for setting up cloud development environments, CUDA code,
and other odds and ends.

# Installation
This has been tested with Python 3 on macOS 10.10. To install requirements in a [virtualenv](https://virtualenvwrapper.readthedocs.io/en/latest/), run

```bash
cd [project directory]
mkvirtual deeplearningbook && workon deeplearningbook
pip install -e requirements.txt
```

This will add
* [Jupyter Notebook](http://jupyter.org/)
* [Theano](http://deeplearning.net/software/theano/)
* [Cython](http://cython.org/)
* [scikit-learn](scikit-learn.org)
* [Matplotlib](http://matplotlib.org/)

# Running Notebooks
In the base of the project directory run

`jupyter notebook notebooks`

# License
MIT
