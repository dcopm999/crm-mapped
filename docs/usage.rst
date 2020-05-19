=====
Usage
=====

To use crm-mapped in a project, add it to your `INSTALLED_APPS`:

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
