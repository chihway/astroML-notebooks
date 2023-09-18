ASTR 340
=========

This is a readme file for the ASTR340 class at the University of Chicago Astronomy and Astrophysics Department. We will be using this fork of the astroML-notebooks repo for the class. The repo is largely the same as the original repo, but we will add some material specific to the class.

We recommend runing the following lines to create a conda environment for the class, to clone the notebook repo, and to set the directory where the downloaded data will live.

``conda create -n astr340 python=3.9``

``conda activate astr340``

``conda install -c astropy astroML``

``git clone https://github.com/chihway/astroML-notebooks.git``

``cd astroML-notebooks``

``mkdir data``

``export ASTRML_DATA=XXX``
