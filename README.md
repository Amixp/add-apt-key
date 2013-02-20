# Simple add-apt-key

Simple adding apt keys in deb-based systems.

Trying with:

*[keyserver.ubuntu.com](http://keyserver.ubuntu.com/)
*[keys.gnupg.net](http://keys.gnupg.net/)
*[keyring.debian.org](http://keyring.debian.org/)

## Installation

```bash
wget https://raw.github.com/gleero/add-apt-key/master/add-apt-key -O /usr/sbin/add-apt-key && chmod +x /usr/sbin/add-apt-key
```

## Usage

```bash
add-apt-key <key>
```
