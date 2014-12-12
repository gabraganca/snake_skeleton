Snake Skeleton
==============

.. image:: https://travis-ci.org/gabraganca/snake_skeleton.svg
    :target: https://travis-ci.org/gabraganca/snake_skeleton

.. image:: https://coveralls.io/repos/gabraganca/snake_skeleton/badge.png
    :target: https://coveralls.io/r/gabraganca/snake_skeleton

This serves as an skeleton to build a python package.

Continous Integration
---------------------


According to `Wikipedia <https://en.wikipedia.org/wiki/Continuous_integration>`_:

  Continuous integration (CI) is the practice, in software engineering, of merging
  all developer working copies with a shared mainline several times a day.

  ...

  CI was originally intended to be used in combination with automated unit tests written
  through the practices of test-driven development. Initially this was conceived of as
  running all unit tests in the developer's local environment and verifying they all passed
  before committing to the mainline. This helps avoid one developer's work in progress breaking
  another developer's copy.

Thus, we set up a configuration to run the code on a CI. `Travic CI <https://travis-ci.org/>`_
offers continous integration to repositories hosted in GitHub. The configurations for it can
be found in the `.travis.yml` file located in the root directory.
Documentation for it can be found `here <http://docs.travis-ci.com/user/languages/python/>`_.
