# Python Use Hello World From Server

This is some example code that is part of a [blog post on using GitHub (or other providers) as a PyPy Server](
https://medium.freecodecamp.org/how-to-use-github-as-a-pypi-server-1c3b0d07db2).

This repository defines a dependency to a python_hello, which in turn has a dependency to python_world. This is defined in requirements.txt so you can create a Virtualenv, and an environment.yml, so you can create a Conda environment. 

The "--extra-index-url" parameter is defined for the dependency, which specifies the PyPy server at which this dependency can be found.

If has one module which can print "hello world" using this dependency
