qpslog
======

Display the queries per second of a log file

I wanted to track the requests/sec of my web server. Since one line in the
logfile is one request why not just count the number of lines?

Why not use the value given by status_mod? because this value is calculated over
the lifetime of the server.

Prerequisites
-------------

* bash, bc, sed

Usage
-----

qpslog <logfile>

Where "logfile" is the log file

Examples
--------
    qpslog /var/log/apache/access.log

Author
------

Samuel Krieg <my_first_name dot my_last_name at gmail dot com>

