newsbeuter
==========
http://www.newsbeuter.org/

Introduction
------------
Newsbeuter is a RSS feed reader for the text console. It is designed to run
Unix-like operating systems such as Linux. NetBSD is currently not supported,
due to technical limitations.

Downloading
-----------
You can download the latest version of newsbeuter from the following website:
http://www.newsbeuter.org/download.html

Alternatively, you can check out the latest version from the newsbeuter
Git repository (hosted on GitHub):

	git clone git://github.com/akrennmair/newsbeuter.git

Dependencies
------------
Newsbeuter depends on a number of libraries, which need to be installed before
newsbeuter can be compiled.

- [STFL (version 0.21 or newer)](http://www.clifford.at/stfl/)
- [SQLite3 (version 3.5 or newer](http://www.sqlite.org/download.html)
- [libcurl (version 7.18.0 or newer](http://curl.haxx.se/download.html)
- [GNU gettext (on systems that don't provide gettext in the libc)](ftp://ftp.gnu.org/gnu/gettext/)
- [pkg-config](http://pkg-config.freedesktop.org/wiki/)
- [libxml2](http://xmlsoft.org/downloads.html)
- [json-c (version 0.11 or newer)](https://github.com/json-c/json-c/wiki)

Debian unstable comes with ready-to-use packages for these dependencies.

Installation
------------
Compiling and installing newsbeuter is as simple as:

	make
	make install

Usage
-----
Before starting newsbeuter you have to edit `$HOME/.newsbeuter/urls`.
Add feeds urls you want to check with newsbeuter, one by line.
For further information check the man page or visit
http://www.newsbeuter.org/doc/newsbeuter.html

Contact
-------
Andreas Krennmair <ak@newsbeuter.org>

License
-------
Newsbeuter is licensed under the MIT/X Consortium License. See the file LICENSE
for further details.
