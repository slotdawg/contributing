.. _installsphinx:

--------------
Install Sphinx
--------------

Why install Sphinx local?
+++++++++++++++++++++++++

To check your created documents for Sphinx, and to be pushed on to the nutanixworkshop.com, you can install Sphinx compiler.

Installation
++++++++++++

.. note:: This document assumes the pre-requisite package Python has been installed. If not, use: https://docs.python-guide.org/starting/installation/

1. Open a commandline

2. Uses the pip install command to install the need sphinx and depended tools

Run the following commands (https://www.sphinx-doc.org/en/master/usage/installation.html#installation-from-pypi):

* pip install sphinx

* pip install sphinxcontrib-fulltoc

* pip install sphinx-bootstrap-theme

* pip install sphinx_fontawesome


After this installation, you can use the command sphinx-build to generate the HTML version of the created pages. To understand what Sphinx does, have a look here: https://youtu.be/oJsUvBQyHBs. As you have already "copied" the template, you do not have to run the ``sphinx-quickstart`` command. You can go directly to run ``sphinx-build`` with parameters.
