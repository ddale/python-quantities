Development
===========

Quantities development uses the principles of test-driven development. New
features or bug fixes need to be accompanied by unit tests based on Python's
unittest package. Unit tests can be run with the following::

  python setup.py test

This works with the version of unittest provided by the python-2.7 and
python-3.2 standard library. If you are running python-2.6 or python-3.1, you
need to install unittest2 to run the test suite.
