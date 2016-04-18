========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |travis| |appveyor| |requires|
        | |coveralls|
        | |landscape| |codacy| |codeclimate|
    * - package
      - |version| |downloads| |wheel| |supported-versions| |supported-implementations|

.. |docs| image:: https://readthedocs.org/projects/python-pgm/badge/?style=flat
    :target: https://readthedocs.org/projects/python-pgm
    :alt: Documentation Status

.. |travis| image:: https://travis-ci.org/redwardstern/python-pgm.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/redwardstern/python-pgm

.. |appveyor| image:: https://ci.appveyor.com/api/projects/status/github/redwardstern/python-pgm?branch=master&svg=true
    :alt: AppVeyor Build Status
    :target: https://ci.appveyor.com/project/redwardstern/python-pgm

.. |requires| image:: https://requires.io/github/redwardstern/python-pgm/requirements.svg?branch=master
    :alt: Requirements Status
    :target: https://requires.io/github/redwardstern/python-pgm/requirements/?branch=master

.. |coveralls| image:: https://coveralls.io/repos/redwardstern/python-pgm/badge.svg?branch=master&service=github
    :alt: Coverage Status
    :target: https://coveralls.io/r/redwardstern/python-pgm

.. |landscape| image:: https://landscape.io/github/redwardstern/python-pgm/master/landscape.svg?style=flat
    :target: https://landscape.io/github/redwardstern/python-pgm/master
    :alt: Code Quality Status

.. |codacy| image:: https://img.shields.io/codacy/REPLACE_WITH_PROJECT_ID.svg?style=flat
    :target: https://www.codacy.com/app/redwardstern/python-pgm
    :alt: Codacy Code Quality Status

.. |codeclimate| image:: https://codeclimate.com/github/redwardstern/python-pgm/badges/gpa.svg
   :target: https://codeclimate.com/github/redwardstern/python-pgm
   :alt: CodeClimate Quality Status

.. |version| image:: https://img.shields.io/pypi/v/pgm.svg?style=flat
    :alt: PyPI Package latest release
    :target: https://pypi.python.org/pypi/pgm

.. |downloads| image:: https://img.shields.io/pypi/dm/pgm.svg?style=flat
    :alt: PyPI Package monthly downloads
    :target: https://pypi.python.org/pypi/pgm

.. |wheel| image:: https://img.shields.io/pypi/wheel/pgm.svg?style=flat
    :alt: PyPI Wheel
    :target: https://pypi.python.org/pypi/pgm

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/pgm.svg?style=flat
    :alt: Supported versions
    :target: https://pypi.python.org/pypi/pgm

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/pgm.svg?style=flat
    :alt: Supported implementations
    :target: https://pypi.python.org/pypi/pgm


.. end-badges

foray into structured prediction and pgm

* Free software: BSD license

Installation
============

::

    pip install pgm

Documentation
=============

https://python-pgm.readthedocs.org/

Development
===========

To run the all tests run::

    tox

Note, to combine the coverage data from all the tox environments run:

.. list-table::
    :widths: 10 90
    :stub-columns: 1

    - - Windows
      - ::

            set PYTEST_ADDOPTS=--cov-append
            tox

    - - Other
      - ::

            PYTEST_ADDOPTS=--cov-append tox
