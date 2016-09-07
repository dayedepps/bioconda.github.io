.. _`variant-effect-predictor`:

variant-effect-predictor
========================

|downloads|

The VEP determines the effect of your variants (SNPs, insertions, deletions, CNVs or structural variants) on genes, transcripts, and protein sequence, as well as regulatory regions.

======== ===========
Home     http://www.ensembl.org/info/docs/tools/vep/index.html
Versions 83
License  Apache 2.0
Recipe   https://github.com/bioconda/bioconda-recipes/tree/master/recipes/variant-effect-predictor
======== ===========

Installation
------------

.. highlight: bash

With an activated Bioconda channel (see :ref:`setup`), install with::

   conda install variant-effect-predictor

and update with::

   conda update variant-effect-predictor

Notes
-----

This package installs only the variant effect predictor (VEP) library
code. To install data libraries, you can use the 'vep_install.pl' command
installed along with it. For example, to install the VEP library for human
hg19/GRCh37 to a directory

vep_install.pl -a c -s homo_sapiens_vep_83_GRCh37 -c /output/path/to/hg19/vep
vep_convert_cache.pl -species home_sapiens -version 83_GRCh37 -d /output/path/to/hg19/vep

(note that vep_install.pl is renamed from INSTALL.pl
 and vep_convert_cache.pl from covert_cache.pl
 to avoid having generic script names in the PATH)

The convert cache step is not required but improves lookup speeds during
runs. See the VEP documentation for more details

http://useast.ensembl.org/info/docs/tools/vep/script/vep_cache.html


Link to this page
-----------------

Render an |badge| badge with the following Markdown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat-square)](http://bioconda.github.io/recipes/variant-effect-predictor/README.html)

.. |badge| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat-square
           :target: http://bioconda.github.io/recipes/variant-effect-predictor/README.html
.. |downloads| image:: https://anaconda.org/bioconda/variant-effect-predictor/badges/downloads.svg
               :target: https://anaconda.org/bioconda/variant-effect-predictor
