Welcome to django-fluent-contents' documentation!
=================================================

This documentation covers the latest release of django-fluent-contents, a collection of applications
to build an end user CMS for the `Django <http://www.djangoproject.com>`_ administration interface.
django-fluent-contents includes:

* A ``PlaceholderField`` to display various content on a model.
* A ``PlaceholderEditorAdmin`` to build CMS interfaces.
* A default set of plugins to display WYSIWYG content, reStructuredText, highlighted code, Gist snippets and more.
* an extensible plugin API.

To get up and running quickly, consult the :ref:`quick-start guide <quickstart>`.
The chapters below describe the configuration of each specific plugin in more detail.

Preview
-------

.. image:: /images/admin/placeholdereditoradmin1.png
   :width: 770px
   :height: 362px
   :alt: django-fluent-contents placeholder editor preview


Getting started
---------------

.. toctree::
   :maxdepth: 2

   quickstart
   configuration


Using the plugins
-----------------

.. toctree::
   :maxdepth: 2

   newplugins/index
   plugins/index


Advanced topics
---------------

.. toctree::
   :maxdepth: 2

   cms


API documentation
-----------------

.. toctree::
   :maxdepth: 2

   api/admin
   api/analyzer
   api/cache
   api/extensions
   api/forms
   api/models
   api/rendering
   api/templatetags/placeholder_tags
   api/utils


Roadmap
=======

The following features are on the radar for future releases:

* Frontend editing support
* Global / shared placeholders
* Gracefully handle errors when removing plugins (currently causes errors in django-polymorphic_ / `django.contrib.contenttypes`_)
* Bridging other plugin systems, like Django CMS
* Inline support (e.g. building a linklist plugin).

Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`


.. _django-polymorphic: https://github.com/chrisglass/django_polymorphic
.. _django.contrib.contenttypes: https://docs.djangoproject.com/en/dev/ref/contrib/contenttypes/
