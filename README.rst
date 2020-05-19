=============================
crm-mapped
=============================

.. image:: https://badge.fury.io/py/crm-mapped.svg
    :target: https://badge.fury.io/py/crm-mapped

.. image:: https://travis-ci.org/dcopm999/crm-mapped.svg?branch=master
    :target: https://travis-ci.org/dcopm999/crm-mapped

.. image:: https://codecov.io/gh/dcopm999/crm-mapped/branch/master/graph/badge.svg
    :target: https://codecov.io/gh/dcopm999/crm-mapped

Django application for GIS map generat

Documentation
-------------

The full documentation is at https://crm-mapped.readthedocs.io.

Quickstart
----------

Install crm-mapped::

    pip install crm-mapped

Add it to your `INSTALLED_APPS`:

.. code-block:: python

    INSTALLED_APPS = (
        ...
        'mapped.apps.MappedConfig',
        ...
    )

Add crm-mapped's URL patterns:

.. code-block:: python

    from mapped import urls as mapped_urls


    urlpatterns = [
        ...
        url(r'^', include(mapped_urls)),
        ...
    ]

Features
--------

* TODO

Running Tests
-------------

Does the code actually work?

::

    source <YOURVIRTUALENV>/bin/activate
    (myenv) $ pip install tox
    (myenv) $ tox

Credits
-------

Tools used in rendering this package:

*  Cookiecutter_
*  `cookiecutter-djangopackage`_

.. _Cookiecutter: https://github.com/audreyr/cookiecutter
.. _`cookiecutter-djangopackage`: https://github.com/pydanny/cookiecutter-djangopackage
