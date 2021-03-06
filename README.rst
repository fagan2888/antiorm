=============================================
   antiorm: Pythonic Helper for SQL Access
=============================================

.. contents:: Table of Contents


Description
===========

Anti-ORM is not an ORM, and it certainly does not want to be.  Anti-ORM is a
simple Python module that provides a pythonic syntax for making it more
convenient to build SQL queries over the DBAPI-2.0 interface.

In practice, if you're the kind of person that likes it to the bare metal, it's
almost as good as the ORMs.  At least there is no magic, and it just works.

.. note:: This open source package contains ``dbapiext``, a simple module for
          making it much easier to write SQL queries.


Dependencies
============

- Python 2.4
- Some DBAPI-2.0 compliant module.


Documentation
=============

Use the source.  If you can't use the source, well, you should not be using this
library.  This is simple!

.. note:: I did a short presentation of ``dbapiext`` at PyCon 2007, the slides
          for the presentation are `available here
          <doc/talks/dbapiext/dbapiext-pres.pdf>`_.


Download
========

A Mercurial repository can be found at:

  http://github.com/blais/antiorm


`Download only antipool.py </antiorm/lib/python/antipool.py>`_


Copyright and License
=====================

Copyright (C) 2005-2007  Martin Blais.
This code is distributed under the `GNU General Public License <COPYING>`_.


Author
======

Martin Blais <blais@furius.ca>


Credits
=======

Judson Neer <jud.neer at gmail.com> for porting to Python-3.
