# lxcing

The lxcing is a tool for creating and starting lxc container.  The created container mounts most part of the host filesystem as own rootfs using bind mount.

## Requirements

* [LXC](https://linuxcontainers.org/lxc/)
* [ruby](https://www.ruby-lang.org/)
* [ruby-lxc](https://github.com/lxc/ruby-lxc)

## Run

For example,

```
sudo ruby lxcing /bin/bash
```
