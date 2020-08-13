# tenda-ac10-firmware

Extracted from `US_AC10V1.0RTL_V15.03.06.23_multi_TD01.bin`

This is the latest Tenda AC10 firmware.

Main Issues:
* Does not support IPv6 (even with ip6 libs and executables bundled with)
* Udp transport issues
* A lot of suspicious ports opened.

Ports:
````
PORT      STATE    SERVICE
0/tcp     filtered unknown
80/tcp    open     http
5500/tcp  open     hotline
9000/tcp  open     cslistener
10004/tcp open     emcrmirccd

Suspicious Binaries found so far:
```
 lib/libucapi.so
 lib/libtpi.so
 bin/tendaupload
 bin/tendauploadcfe
```
