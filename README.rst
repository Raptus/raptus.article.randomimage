Introduction
============

Provides components which display a random image contained in the article.

The following features for raptus.article are provided by this package:

Components
----------
    * Random image (Random image displayed over the whole width)
    * Random image left (Random image displayed on the left side)
    * Random image right (Random image displayed on the right side)
    * Random image teaser (Random image displayed over the whole width and displayed above the columns)

Dependencies
------------
    * raptus.article.images

Installation
============

To install raptus.article.randomimage into your Plone instance, locate the file
buildout.cfg in the root of your Plone instance directory on the file system,
and open it in a text editor.

Add the actual raptus.article.randomimage add-on to the "eggs" section of
buildout.cfg. Look for the section that looks like this::

    eggs =
        Plone

This section might have additional lines if you have other add-ons already
installed. Just add the raptus.article.randomimage on a separate line, like this::

    eggs =
        Plone
        raptus.article.randomimage

Note that you have to run buildout like this::

    $ bin/buildout

Then go to the "Add-ons" control panel in Plone as an administrator, and
install or reinstall the "raptus.article.default" product.

Note that if you do not use the raptus.article.default package you have to
include the zcml of raptus.article.randomimage either by adding it
to the zcml list in your buildout or by including it in another package's
configure.zcml.

Usage
=====

Components
----------
Navigate to the "Components" tab of your article and select one of the random image
components and press "save and view". Note that at least one image has to be contained
in the article in which this component is active.

Copyright and credits
=====================

raptus.article is copyrighted by `Raptus AG <http://raptus.com>`_ and licensed under the GPL. 
See LICENSE.txt for details.
