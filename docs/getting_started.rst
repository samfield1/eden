Getting Started
===============

Welcome to Eden! A datasci enceinitiative to identify the perfect city. 

Installation
------------
Eden is built as both a library for building custom models leveraging the Eden database, 
and a click and run software to get instant results. 
However, despite the ambitious nature of the project the setup has been optimized to be as simple as possible.

The first thing you should do is to setup a virutal enviroment (VE). 
While this is not necessary, it is good practice and may help prevent annoying dependency conflicts. 
You can use your favorite VE. Here we illustrate the setup using a Conda VE.

::

    $ conda create --name eden
    $ conda activate eden

Install dependencies
--------------------
::

    $ conda install -c anaconda requests
    $ conda install -c anaconda beautifulsoup4
    $ conda install -c anaconda pandas
    $ conda install -c plotly plotly_express
    $ pip install sphinx sphinx_rtd_theme
    $ conda install -c conda-forge sphinx-autoapi
    $ pip install https://github.com/revitron/revitron-sphinx-theme/archive/master.zip

Install package
---------------
::

    $ pip install -e .

Run a pipeline
--------------
::
    
    $ python pipelines.py