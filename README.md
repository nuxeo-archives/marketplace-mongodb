marketplace-mongodb
===================

Introduction
------------

This Nuxeo Marketplace package is an EXPERIMENTAL package to allow testing of
the preliminary (alpha) code (nuxeo-storage-mongodb) that uses MongoDB
as a storage backend instead of a SQL database.

It applies currently on top of a Nuxeo Platform 5.9.4 distribution.

Building this package requires that the branch feature-NXP-14278-NXP-14279-mongodb of nuxeo-core
has already built some artifacts (with version 5.9.5-mongodb-SNAPSHOT). It also pulls some
5.9.5-SNAPSHOT packages from the master branch.

When installed, a new "mongodb" template is activated, which contains
configuration for an additional Nuxeo repository (in addition to the
default one) using MongoDB as a backend. The `nuxeo.conf` property `nuxeo.mongodb.server`
can be set if your MongoDB server doesn't run on the default `localhost:27017`.

About Nuxeo
-----------

Nuxeo provides a modular, extensible Java-based
[open source software platform for enterprise content management](http://www.nuxeo.com/en/products/ep),
and packaged applications for [document management](http://www.nuxeo.com/en/products/document-management),
[digital asset management](http://www.nuxeo.com/en/products/dam) and
[case management](http://www.nuxeo.com/en/products/case-management).

Designed by developers for developers, the Nuxeo platform offers a modern
architecture, a powerful plug-in model and extensive packaging
capabilities for building content applications.

More information on: <http://www.nuxeo.com/>
