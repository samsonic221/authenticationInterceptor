========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |requires|
        | |coveralls|
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|
.. |docs| image:: https://readthedocs.org/projects/python-authenticationinterceptor/badge/?style=flat
    :target: https://readthedocs.org/projects/python-authenticationinterceptor
    :alt: Documentation Status

.. |requires| image:: https://requires.io/github/samsonic221/python-authenticationinterceptor/requirements.svg?branch=master
    :alt: Requirements Status
    :target: https://requires.io/github/samsonic221/python-authenticationinterceptor/requirements/?branch=master

.. |coveralls| image:: https://coveralls.io/repos/samsonic221/python-authenticationinterceptor/badge.svg?branch=master&service=github
    :alt: Coverage Status
    :target: https://coveralls.io/r/samsonic221/python-authenticationinterceptor

.. |version| image:: https://img.shields.io/pypi/v/authenticationinterceptor.svg
    :alt: PyPI Package latest release
    :target: https://pypi.org/project/authenticationinterceptor

.. |wheel| image:: https://img.shields.io/pypi/wheel/authenticationinterceptor.svg
    :alt: PyPI Wheel
    :target: https://pypi.org/project/authenticationinterceptor

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/authenticationinterceptor.svg
    :alt: Supported versions
    :target: https://pypi.org/project/authenticationinterceptor

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/authenticationinterceptor.svg
    :alt: Supported implementations
    :target: https://pypi.org/project/authenticationinterceptor

.. |commits-since| image:: https://img.shields.io/github/commits-since/samsonic221/python-authenticationinterceptor/v0.0.1.svg
    :alt: Commits since latest release
    :target: https://github.com/samsonic221/python-authenticationinterceptor/compare/v0.0.1...master



.. end-badges

jwt token verification

Installation
============

::

    pip install authenticationinterceptor

You can also install the in-development version with::

    pip install https://github.com/samsonic221/python-authenticationinterceptor/archive/master.zip


Documentation
=============


https://python-authenticationinterceptor.readthedocs.io/


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
