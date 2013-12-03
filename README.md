puddle uses virtualenv and lots of tricks to cache Python packages and
install them in the current directory.  Inspired by bundler.

To install a virtualenv with setuptools, pip, simple, and virtualenv:

    bin/puddle init

To cache a pip:

    bin/puddle cache [package]

To install a pip from the cache:

    bin/puddle install [package]
