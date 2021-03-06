.. _`biodiff`:

biodiff
=======

|downloads|

exact comparison of biological sequences

============= ===========
Home          https://gitlab.com/LPCDRP/biodiff
Versions      0.2.2
License       GPLv3+
Recipe        https://github.com/bioconda/bioconda-recipes/tree/master/recipes/biodiff



============= ===========

biodiff is a variant caller that determines the exact differences between two biological sequences\. It can operate on DNA and protein sequences\, as long as they are in fasta format\. The sequences to be compared must have the same fasta header \(up to the first whitespace\)\. If the reference and query each have only one sequence\, however\, the header need not match and the comparison will be done\, but a warning will be emitted\. Output is in the Variant Call Format\.


Installation
------------

.. highlight: bash

With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

   conda install biodiff

and update with::

   conda update biodiff



|docker|

A Docker container is available at https://quay.io/repository/biocontainers/biodiff.

Link to this page
-----------------

Render an |badge| badge with the following Markdown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat-square)](http://bioconda.github.io/recipes/biodiff/README.html)

.. |badge| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat-square
           :target: http://bioconda.github.io/recipes/biodiff/README.html
.. |downloads| image:: https://anaconda.org/bioconda/biodiff/badges/downloads.svg
               :target: https://anaconda.org/bioconda/biodiff
.. |docker| image:: https://quay.io/repository/biocontainers/biodiff/status
                :target: https://quay.io/repository/biocontainers/biodiff

