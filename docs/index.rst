python-cybox |release| Documentation
====================================

The python-cybox library provides an API for developing and consuming Cyber
Observable eXpression (CybOX) content. Developers can leverage the API to
create applications that create, consume, translate, or otherwise work with
CybOX content.

Versions
--------
Each version of python-cybox is designed to work with a single version of the
CybOX Language.  The table below shows the latest version the library for each
version of CybOX.

============= ====================
CybOX Version python-cybox Version
============= ====================
2.1           2.1.0.19.dev0 (`PyPI`__) (`GitHub`__)
2.0.1         2.0.1.4 (`PyPI`__) (`GitHub`__)
2.0           2.0.0.1 (`PyPI`__) (`GitHub`__)
1.0           1.0.0b3 (`PyPI`__) (`GitHub`__)
============= ====================

__ https://pypi.python.org/pypi/cybox/2.1.0.19.dev0
__ https://github.com/CybOXProject/python-cybox/tree/v2.1.0.19.dev0
__ https://pypi.python.org/pypi/cybox/2.0.1.4
__ https://github.com/CybOXProject/python-cybox/tree/v2.0.1.4
__ https://pypi.python.org/pypi/cybox/2.0.0.1
__ https://github.com/CybOXProject/python-cybox/tree/v2.0.0.1
__ https://pypi.python.org/pypi/cybox/1.0.0b3
__ https://github.com/CybOXProject/python-cybox/tree/v1.0.0b3


Contents
--------

.. toctree::
   :maxdepth: 2

   getting_started
   installation
   overview
   examples
   contributing


API Reference
=============

.. toctree::
   :maxdepth: 2

   api/index
   api/coverage


FAQ
===

- My RAM consumption rises when processing a large amount of files.
    This is a known behavior caused the caching mechanism built into the
    :class:`cybox.core.object.Object` class. To prevent this issue from happening
    use the :class:`cybox.utils.caches.cache_clear` method in your code/script to
    release the cached resources as appropriate. For example, it could be every
    time you parse or serialize a document.


Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
