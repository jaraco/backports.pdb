.. image:: https://img.shields.io/pypi/v/backports.pdb.svg
   :target: https://pypi.org/project/backports.pdb

.. image:: https://img.shields.io/pypi/pyversions/backports.pdb.svg

.. image:: https://github.com/jaraco/backports.pdb/actions/workflows/main.yml/badge.svg
   :target: https://github.com/jaraco/backports.pdb/actions?query=workflow%3A%22tests%22
   :alt: tests

.. image:: https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/astral-sh/ruff/main/assets/badge/v2.json
    :target: https://github.com/astral-sh/ruff
    :alt: Ruff

.. .. image:: https://readthedocs.org/projects/PROJECT_RTD/badge/?version=latest
..    :target: https://PROJECT_RTD.readthedocs.io/en/latest/?badge=latest

.. image:: https://img.shields.io/badge/skeleton-2025-informational
   :target: https://blog.jaraco.com/skeleton

Backport of `pdb <https://docs.python.org/3/library/pdb.html>`_ from
later Python versions to older ones::

    from backports import pdb

Including support for the ``-m`` option::

    $ python -m backports.pdb -m mymodule
