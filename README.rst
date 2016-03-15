======================
lsst-pypackage
======================

LSST template for a Python package. See https://github.com/lsst-ts/lsst-pypackage

* Vanilla testing setup with `unittest` and `python setup.py test`
* Jenkins_ CI: LSST Jenkins continous integration is configured with travis.yml plugin
* Tox_ testing: Setup to easily test for Python 2.6, 2.7, 3.3, 3.4
* Sphinx_ docs: Documentation ready for generation with, for example, ReadTheDocs_

Usage
-----

Generate a Python package project::

    cookiecutter https://github.com/lsst-ts/lsst-pypackage.git

Then:

* Create a repo and put it there.
* Add the repo to the LSST Jenkins server https://ts-ci.lsst.org/
* Add the repo to your ReadTheDocs account + turn on the ReadTheDocs service hook.
* Release your package the standard Python way. Here's a release checklist: https://gist.github.com/audreyr/5990987

.. _Tox: http://testrun.org/tox/
.. _Sphinx: http://sphinx-doc.org/
.. _ReadTheDocs: https://readthedocs.org/
.. _Jenkins: https://jenkins-ci.org/
