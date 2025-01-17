.. :changelog:

History
-------
0.3.0 (2024-01-29)
-----------------

* Support Django >= 4.2.9

0.2.2 (2017-07-28)
-----------------

* Excluding tests from being installed

0.2.1 (2017-04-26)
-----------------

* Fix bug related to default urlconf value.

0.2.0 (2017-04-26)
~~~~~~~~~~~~~~~~~~

* Added ``Step.urlconf`` attribute.
  Allows to use other urlconfigs for running test step.
* Added ``Step.content_type`` attribute.
  Allows to specify custom content types while submitting requests.
* Added ``Step.override_settings`` attribute.
  Allows to override Django settings while making a request.
* Fixed some typos in docstrings.

0.1.0 (2017-03-22)
~~~~~~~~~~~~~~~~~~

* First release on PyPI.
