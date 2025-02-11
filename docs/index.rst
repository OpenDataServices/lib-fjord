LibFJord
========

This library ultimately supports CoVE web applications, among others.

CoVE exists to help people:

* Convert data between common formats (e.g. csv to json)
* Validate data against rules
* Explore data, that machines find easy, but humans find harder to read

However, CoVE Web App is a separate library
so that you can take the functionality of this library and reuse it in your own applications with your own custom UI.

Hence this libraries and the libraries that directly use it are pure Python libraries with no UI provided (beyond maybe a simple CLI).

It is a collection of helper Python functions that may be used by other libraries.

This gives maximum flexibility to other data standard specific libraries while avoiding those libraries reinventing the wheel.
It also means that if one data standard has a special requirement,
that can usually be handled by the data standard specific library with no need to change this core library.


.. toctree::
   :maxdepth: 2

   python-api/index.rst
   migration-from-lib-cove.rst
   used-by.rst

