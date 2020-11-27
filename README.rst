.. image:: https://img.shields.io/pypi/v/backports.pdb.svg
   :target: `PyPI link`_

.. image:: https://img.shields.io/pypi/pyversions/backports.pdb.svg
   :target: `PyPI link`_

.. _PyPI link: https://pypi.org/project/backports.pdb

.. image:: https://github.com/jaraco/backports.pdb/workflows/Automated%20Tests/badge.svg
   :target: https://github.com/jaraco/backports.pdb/actions?query=workflow%3A%22Automated+Tests%22
   :alt: Automated Tests

.. image:: https://img.shields.io/badge/code%20style-black-000000.svg
   :target: https://github.com/psf/black
   :alt: Code style: Black

.. .. image:: https://readthedocs.org/projects/skeleton/badge/?version=latest
..    :target: https://skeleton.readthedocs.io/en/latest/?badge=latest


Backport of `pdb <https://docs.python.org/3/library/pdb.html>`_ from
later Python versions to older ones::

    from backports import pdb

Including support for the ``-m`` option::

    $ python -m backports.pdb -m mymodule
