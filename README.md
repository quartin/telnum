telnum commandline utility
==========================

Analyse telephone numbers from the commandline using daviddrysdale's Python
port of Google's libphonenumber

Requirements
------------

* [`python-phonenumbers`](https://github.com/daviddrysdale/python-phonenumbers): `pip install phonenumbers`

Usage
-----

Specify one or multiple phone numbers as commandline arguments, or input them
on stdin.

Phone numbers have to be internationally unique, i.e. "+447444123456" instead
of "07444123456".

Example
-------

```
$ ./telnum +447444123456 +442083661177 +1800VANITY 08002462468      
```
