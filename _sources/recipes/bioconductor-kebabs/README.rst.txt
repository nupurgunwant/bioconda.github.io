.. _`bioconductor-kebabs`:

bioconductor-kebabs
===================

|downloads|

The package provides functionality for kernel\-based analysis of DNA\, RNA\, and amino acid sequences via SVM\-based methods\. As core functionality\, kebabs implements following sequence kernels\: spectrum kernel\, mismatch kernel\, gappy pair kernel\, and motif kernel\. Apart from an efficient implementation of standard position\-independent functionality\, the kernels are extended in a novel way to take the position of patterns into account for the similarity measure\. Because of the flexibility of the kernel formulation\, other kernels like the weighted degree kernel or the shifted weighted degree kernel with constant weighting of positions are included as special cases\. An annotation\-specific variant of the kernels uses annotation information placed along the sequence together with the patterns in the sequence\. The package allows for the generation of a kernel matrix or an explicit feature representation in dense or sparse format for all available kernels which can be used with methods implemented in other R packages\. With focus on SVM\-based methods\, kebabs provides a framework which simplifies the usage of existing SVM implementations in kernlab\, e1071\, and LiblineaR\. Binary and multi\-class classification as well as regression tasks can be used in a unified way without having to deal with the different functions\, parameters\, and formats of the selected SVM\. As support for choosing hyperparameters\, the package provides cross validation \- including grouped cross validation\, grid search and model selection functions\. For easier biological interpretation of the results\, the package computes feature weights for all SVMs and prediction profiles which show the contribution of individual sequence positions to the prediction result and indicate the relevance of sequence sections for the learning result and the underlying biological functions\.

============= ===========
Home          http://bioconductor.org/packages/3.6/bioc/html/kebabs.html
Versions      1.12.0
License       GPL (>= 2.1)
Recipe        https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-kebabs



============= ===========



Installation
------------

.. highlight: bash

With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

   conda install bioconductor-kebabs

and update with::

   conda update bioconductor-kebabs



|docker|

A Docker container is available at https://quay.io/repository/biocontainers/bioconductor-kebabs.

Link to this page
-----------------

Render an |badge| badge with the following Markdown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat-square)](http://bioconda.github.io/recipes/bioconductor-kebabs/README.html)

.. |badge| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat-square
           :target: http://bioconda.github.io/recipes/bioconductor-kebabs/README.html
.. |downloads| image:: https://anaconda.org/bioconda/bioconductor-kebabs/badges/downloads.svg
               :target: https://anaconda.org/bioconda/bioconductor-kebabs
.. |docker| image:: https://quay.io/repository/biocontainers/bioconductor-kebabs/status
                :target: https://quay.io/repository/biocontainers/bioconductor-kebabs

