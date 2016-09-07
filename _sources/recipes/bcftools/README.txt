.. _`bcftools`:

bcftools
========

|downloads|

BCFtools is a set of utilities that manipulate variant calls in the Variant Call Format (VCF) and its binary counterpart BCF. All commands work transparently with both VCFs and BCFs, both uncompressed and BGZF-compressed.  Most commands accept VCF, bgzipped VCF and BCF with filetype detected automatically even when streaming from a pipe. Indexed VCF and BCF will work in all situations. Un-indexed VCF and BCF and streams will work in most, but not all situations.

======== ===========
Home     https://github.com/samtools/bcftools
Versions 1.3.1, 1.3, 1.2
License  MIT
Recipe   https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bcftools/1.3.1
======== ===========

Installation
------------

.. highlight: bash

With an activated Bioconda channel (see :ref:`setup`), install with::

   conda install bcftools

and update with::

   conda update bcftools



Link to this page
-----------------

Render an |badge| badge with the following Markdown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat-square)](http://bioconda.github.io/recipes/bcftools/README.html)

.. |badge| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat-square
           :target: http://bioconda.github.io/recipes/bcftools/README.html
.. |downloads| image:: https://anaconda.org/bioconda/bcftools/badges/downloads.svg
               :target: https://anaconda.org/bioconda/bcftools
