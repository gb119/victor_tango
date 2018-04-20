Victor-Tango
============

Introduction
------------

Victor-Tango is a collection of pyTango and Sardarna macros used to construct recipes on the Sir henry ROyce Institute Multi-technique depostion system hosted 
by the Condensed Matter Physics Group at the University of Leeds. OF the four different growth chambers on the deposition system, 3 plus the interlinking
distribution system and sample preparation station were purchased from Prevac and run the company's control software which is based on the Open Source tango
platform. The complete system has been given the codename "victor" after the well known manufacturer of penknives, reflecting the 'tool for every job' nature
of the system - hence our layer of control macros is called victor-tango.

Installation
------------

The code is not ready yet to be installed as a package

Usage
-----

The macros can be imported at the standard ipython console with::

    import victor_tango as vt

    vt.organics.set_target(...)
    vt.organics.gow(....)

Documentation
-------------

Current documentation can be fond on this repository's `gh-pages`_ branch:

License, Copyright and Authors
------------------------------

This code is Licensed under a 3-clause BSD license - see LICENSE.txt. 

This code is (C) University of Leeds, 2018 and was written by Gavin Burnell and Mannan Ali

.. _gh-pages:  https://gb119.github.io/victor_tango/