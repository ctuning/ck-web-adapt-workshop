CK repository for ADAPT workshop website
========================================

[![compatibility](https://github.com/ctuning/ck-guide-images/blob/master/ck-compatible.svg)](https://github.com/ctuning/ck)
[![DOI](https://zenodo.org/badge/39291424.svg)](https://zenodo.org/badge/latestdoi/39291424)
[![License](https://img.shields.io/badge/License-BSD%203--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause)

Prerequisites
=============
* [Collective Knowledge Framework](http://github.com/ctuning/ck)

Description
===========

CK web front-end templates, styles and images.

Usage:

 > ck pull repo:ck-web-adapt-workshop

 (dependency on ck-web repo will be automatically resolved)

 > ck start web

 > Open web page: http://localhost:3344/?template=adapt-workshop&page=index

 That's all.

Note, that it is possible to create a static website
(as we use at http://adapt-workshop.org)

Just go to script/compile-website-adapt-workshop
and run on Linux:
 > create_website.sh

or on Windows:
 > create_website.bat

This will create static html pages in tmp-website sub-directory
that you can upload to your web server.
