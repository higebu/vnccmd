vnccmd
======

vnccmd is a command line tool to send commands over VNC.
This is a copy of Packer's boot command module.
So this is usefull for testing Packer templates.

Install
-------

```
go get github.com/higebu/vnccmd
```

Usage
-----

```
vnccmd -s 192.168.0.10 -p 5900 -c 'root<enter>'
```
