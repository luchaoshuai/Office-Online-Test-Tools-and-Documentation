
:orphan:

OneNote
=======

Integration with OneNote Online is not currently supported through the
`Office 365 Cloud Storage Partner Program <http://dev.office.com/programs/officecloudstorage>`_.


.. _Folders endpoint:

Folders endpoint
================

..  include:: /fragments/deprecated_endpoint.rst

The Folders endpoint provides access to folder-level operations. This endpoint exposes the :ref:`CheckFolderInfo`
operation, which returns information about a folder, the permissions that the user has on that folder, and the
capabilities that the WOPI host has on the folder.


.. _Folder contents endpoint:

Folder contents endpoint
========================

..  include:: /fragments/deprecated_endpoint.rst

The Folder contents endpoint provides access to folder contents. This endpoint exposes the :ref:`EnumerateChildren`
operation, which returns the contents of a folder on the WOPI server.
