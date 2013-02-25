robotframework-ipaddrlibrary
=============

A Robot Framework library for querying address and hostnames, and performing IP 
subnet math

Description
-----------

IPAddrLibrary is a library for Robot Framework which provides keywords for
manipulating IP addresses and hostnames.  This library will provide basic
host-to-ip and ip-to-host conversion, as well as IP address subnet math.

This library depends on python-iplib (http://www.mimante.net/soft/iplib)

Documentation for available keywords is in the doc directory (generated by libdoc)

Installation
------------

1.  Download latest tar.gz from dist directory
1.  Unzip to your Robot Framework library directory
1.  Add "IPAddrLibrary" to your test suite's Settings table, e.g::
   
   *** Settings ***
   | Library | ./IPAddrLibrary/ |
   
1.  Start using the keywords in your user keywords and test cases.

Issues
------
No doubt there are bugs and missing functionality in this library.  If you encounter any 
problems or have a feature request (i.e. new keywords you'd like to have), please open
an issue on the project's github issue tracker: 
https://github.com/tduskin/robotframework-ipaddrlibrary/issues

License
-------
Copyright 2013 Maldivica (www.maldivica.com)

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.