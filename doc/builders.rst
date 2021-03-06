builders
========

The following outlines the Sphinx builders provided by this extension.

.. contents:: :local:

confluence
----------

The ``confluence`` builder allows a user to process a Sphinx-supported
documentation set to generate a Confluence-supported representation. Individual
documents will generate Confluence-supported documents, which in turn can be
published to a configured Confluence instance:

.. code-block:: shell

    sphinx-build -b confluence . _build/confluence -E -a

singleconfluence
----------------

.. versionadded:: 1.3

The ``singleconfluence`` builder allows a user to process a Sphinx-supported
documentation set to generate a single document in a Confluence-supported
representation. The generated document can in turn be published to a configured
Confluence instance:

.. code-block:: shell

    sphinx-build -b singleconfluence . _build/singleconfluence -E -a
