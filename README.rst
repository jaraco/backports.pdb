.. image:: https://img.shields.io/pypi/v/backports.pdb.svg
   :target: https://pypi.org/project/backports.pdb

.. image:: https://img.shields.io/pypi/pyversions/backports.pdb.svg

.. image:: https://img.shields.io/travis/jaraco/backports.pdb/master.svg
   :target: https://travis-ci.org/jaraco/backports.pdb

.. image:: https://readthedocs.org/projects/backportspdb/badge/?version=latest
   :target: https://backportspdb.readthedocs.io/en/latest/?badge=latest


Backport of `pdb from Python 3.7
<https://docs.python.org/3.7/library/pdb.html>`_::

    from backports import pdb

Including support for the ``-m`` option::

    $ python -m backports.pdb -m mymodule
