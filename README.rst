================
 PyData Bermuda
================

Here is a place to keep notes, ideas and plans for a PyData conference
in Bermuda.

It will is hosted on github for now,

We can work on the ideas during meetings, use this as a place to keep
track of things.

If more information is needed on anything, just ask.

Getting started
===============

To get a copy of the git repository::

  git clone https://github.com/openbermuda/pydata

Building docs
=============

The docs here are currently in restructured text.  Markdown can be
supported too as well as jupyter notebooks.

The documentation can be turned into many formats by `sphinx`_

To build the docs you will need a machine with *python* installed.

You will then need to install sphinx::

  pip install sphinx

Then you should be able to just run::

   make html

The docs are built in a *_build* sub-directory.  The index for the
*html* docs is at:

    _build/html/index.html

  

,, _sphinx: http://www.sphinx-doc.org/en/stable/

