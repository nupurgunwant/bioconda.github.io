.. _`bioconductor-bhc`:

bioconductor-bhc
================

|downloads|

The method performs bottom\-up hierarchical clustering\, using a Dirichlet Process \(infinite mixture\) to model uncertainty in the data and Bayesian model selection to decide at each step which clusters to merge\.  This avoids several limitations of traditional methods\, for example how many clusters there should be and how to choose a principled distance metric\.  This implementation accepts multinomial \(i\.e\. discrete\, with 2\+ categories\) or time\-series data\. This version also includes a randomised algorithm which is more efficient for larger data sets\.

============= ===========
Home          http://bioconductor.org/packages/3.6/bioc/html/BHC.html
Versions      1.28.0, 1.30.0
License       GPL-3
Recipe        https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-bhc



============= ===========



Installation
------------

.. highlight: bash

With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

   conda install bioconductor-bhc

and update with::

   conda update bioconductor-bhc



|docker|

A Docker container is available at https://quay.io/repository/biocontainers/bioconductor-bhc.

Link to this page
-----------------

Render an |badge| badge with the following Markdown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat-square)](http://bioconda.github.io/recipes/bioconductor-bhc/README.html)

.. |badge| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat-square
           :target: http://bioconda.github.io/recipes/bioconductor-bhc/README.html
.. |downloads| image:: https://anaconda.org/bioconda/bioconductor-bhc/badges/downloads.svg
               :target: https://anaconda.org/bioconda/bioconductor-bhc
.. |docker| image:: https://quay.io/repository/biocontainers/bioconductor-bhc/status
                :target: https://quay.io/repository/biocontainers/bioconductor-bhc

