locatehost
==========

Obtain geo information about hosts using [ip-api.com](http://ip-api.com).

Usage
-----
```
usage: locatehost [-h] [-c] [-r] [-j] [host ...]

Retrieve geo information for hosts. If no host is specified, geo information
for the current public ip address is obtained.

positional arguments:
  host          FQDN, IPv4 or IPv6 address

optional arguments:
  -h, --help    show this help message and exit
  -c, --coords  only print coords for each host
  -r, --raw     print raw output to stdout
  -j, --json    print json output to stdout
```

Screenshot
----------
![Screenshot](https://raw.githubusercontent.com/martinohmann/locatehost/master/screenshot.png)
