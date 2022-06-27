# Description
Systemd configuration file to adapt swtpm as a daemon listen on UNIX domain socket for TPM2 emulation, and tpm2-abrmd to make use of the daemonized swtpm.

# How to build
```
$ cd debian
$ dpkg-buildpackage -b
```
