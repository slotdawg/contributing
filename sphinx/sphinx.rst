.. _installsphinx:

--------------
Install Sphinx
--------------

Why install Sphinx local?
+++++++++++++++++++++++++

To check your created documents for Sphinx, and to be pushed on to the nutanixworkshop.com, you can install Sphinx compiler.

Installation
++++++++++++

.. note:: This document assumes the pre-requisite package Python has been installed

1. Open a commandline

2. Uses the pip install command to install the need sphinx and depended tools

Run the following commands (http://www.sphinx-doc.org/en/master/usage/installation.html):

* pip install sphinx

* pip install sphinxcontrib-fulltoc

* pip install sphinx-bootstrap-theme

* pip install sphinx_fontawesome


After this installation, you can use the command sphinx-build to generate the HTML version of the created pages.

Initial Configuration
+++++++++++++++++++++

To have the nutanixworkshop.com layout, you need to get some files first and use them as a template. The location for these template files are on a GitHub location.

* Create a directory where you want to store the to be pulled data. Example might be **Documents/github/**.

* From the command line go to the newly created directory and type **git pull https://github.com/nutanixworkshops/workshop-repo-template**.

* After the command exited correctly you will have the files local on your machine and can use them as a template for your work.
