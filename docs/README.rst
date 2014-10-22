Plone Intranet Documentviewer
=============================

.. image:: https://travis-ci.org/ploneintranet/ploneintranet.documentviewer.svg?branch=master
    :target: https://travis-ci.org/ploneintranet/ploneintranet.documentviewer
.. image:: https://coveralls.io/repos/ploneintranet/ploneintranet.documentviewer/badge.png?branch=master
  :target: https://coveralls.io/r/ploneintranet/ploneintranet.documentviewer?branch=master

This package provides the following:

Provide thumbnails for documents
--------------------------------

As a default the mimetype icon will be served.
If the document mimetype is a known one,
a proper preview of the document will be generated.

Provide thumbnails for documents
--------------------------------

Testing buildout
----------------

The package comes with a testing buildout.
You can launch it like this::

   git clone git@github.com:ploneintranet/ploneintranet.documentviewer.git
   cd ploneintranet.documentviewer
   virtualenv-2.7 --no-site-packages -p `which python` .
   . bin/activate
   ./bin/python2.7 bootstrap.py -v 1.6.3
   ./bin/buildout

