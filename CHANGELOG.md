Changelog
=========

2.0.0
-----

Released 2.0.0

2.0.0-RC2
---------

* **2017-02-06**: [BC BREAK] Controller excpects the template to be called
  `$template` and no longer `$contentTemplate`. If you use the CmfRoutingBundle,
  you don't need to do anything as it was renamed there as well. If you extend
  this controller or have a different routing, you need to adjust.

2.0.0-RC1
---------

* **2016-12-07**: [BC BREAK] Moved all Sonata admin integration to the
  CmfSonataAdminIntegrationBundle

1.3.0
-----

* Support PHP 7
* **2015-08-31**: Added IvoryCKEditorBundle integration and added the
  `ivory_ckeditor` settings.

1.2.0
-----

1.2.0-RC1
---------

* **2014-06-06**: Updated to PSR-4 autoloading

1.1.0
-----

Release 1.1.0

1.1.0-RC2
---------

* **2014-04-11**: drop Symfony 2.2 compatibility

1.1.0-RC1
---------

* **2014-03-24**: [PHPCR-ODM Documents] setParent() and getParent() are now
  deprecated. Use setParentDocument() and getParentDocument() instead.
  When using Sonata Admin, enable the ChildExtension from the CoreBundle.

1.0.1
-----

* **2013-11-26**: Improve json/xml output when params contain a single variable

1.0.0-RC3
---------

* **2013-09-02**: Removed __toString() method
* **2013-09-01**: Adopt schema.org RDFa mapping

1.0.0-RC1
---------

* **2013-07-29**: Removed dedicated entity for Multilang. Multilang is now
  supported by default. All additional features are now bundled in the
  StaticContent document, and core functionality is in StaticContentBase.
* **2013-07-28**: [DependencyInjection] moved phpcr specific configuration
  under `persistence.phpcr`.
