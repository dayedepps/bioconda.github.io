.. _`gatk`:

gatk
====

|downloads|

The full Genome Analysis Toolkit (GATK) framework, license restricted.

======== ===========
Home     https://www.broadinstitute.org/gatk/
Versions 3.6, 3.5
License  https://www.broadinstitute.org/gatk/about/#licensing
Recipe   https://github.com/bioconda/bioconda-recipes/tree/master/recipes/gatk
======== ===========

Installation
------------

.. highlight: bash

With an activated Bioconda channel (see :ref:`setup`), install with::

   conda install gatk

and update with::

   conda update gatk

Notes
-----

Due to license restrictions, this recipe cannot distribute and install GATK directly. To fully install GATK, you must download a licensed copy of GATK from the Broad Institute (https://www.broadinstitute.org/gatk/download/), install this package, and call "gatk-register /path/to/GenomeAnalysisTK[-$PKG_VERSION.tar.bz2|.jar]", which will copy GATK into your conda environment.

Link to this page
-----------------

Render an |badge| badge with the following Markdown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat-square)](http://bioconda.github.io/recipes/gatk/README.html)

.. |badge| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat-square
           :target: http://bioconda.github.io/recipes/gatk/README.html
.. |downloads| image:: https://anaconda.org/bioconda/gatk/badges/downloads.svg
               :target: https://anaconda.org/bioconda/gatk
