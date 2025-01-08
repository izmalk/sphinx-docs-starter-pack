.. _quickstart:

================
Quickstart guide
================

Initial setup
=============

Clone the `Starter pack <https://github.com/canonical/sphinx-docs-starter-pack>`_ repository to a temporary local folder.

If this is to be incorporated into another software repository: rename it (to :file:`docs`, by preference). Move it to the root of the repository. Delete :file:`.git`, :file:`.gitignore`, :file:`LICENSE`, :file:`README.rst`.


Build and run the local server
==============================

Prerequisites (which you probably have installed already) are:

* ``make`` 
* ``python3``
* ``python3-venv``
* ``python3-pip`` 

In :file:`docs` run::

    make run

This: creates and activates a virtual environment in :file:`docs/.sphinx/venv`, builds the documentation and serves it at :literalref:`http://127.0.0.1:8000/`.

The server watches the source files, including :file:`conf.py`, and rebuilds automatically on changes.


Configure :file:`conf.py`
=========================

Work through the settings in :file:`conf.py`. At this stage most can be left as they are, or simply ignored. They can all be changed later.


Update content
==============

The landing page is :file:`docs/index.rst`. Other pages are under :file:`docs/content`.

See also: 

* :ref:`setup`
* :ref:`build`
* :ref:`guidance`
* :ref:`edit`
