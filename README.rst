========
Overview
========

Import Jupyter notebooks as Python modules. Based on the Jupyter documentation example_.

.. _example: http://jupyter-notebook.readthedocs.io/en/latest/examples/Notebook/Importing%20Notebooks.html

Installation
============

::

    pip install -e git@github.com:snitramodranoel/backpack@HEAD#egg=backpack

Documentation
=============

Suppose you have a Jupyter notebook `My Notebook.ipynb` sitting in your working directory that you want to import.
From your current notebook:

::

    import backpack
    import My_Notebook as mynb
