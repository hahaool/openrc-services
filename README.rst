OpenRC Services
====================

OpenRC service files for Linux

Contributing
------------

When submitting additional service files please:

+ verify that the service file actually works
+ include a conf file if necessary with sane defaults
+ make sure pid files are created in ``/run`` not ``/var/run``
+ use 4 spaces for indentation
+ make a single commit per service

See ``man runscript (man openrc-run)`` for details on writing service files.
