# OpenBSD Archive Scripts
by Morgan Aldridge <morgant@makkintosshu.com>

## OVERVIEW

A small collection of archive scripts for various services running under OpenBSD, incl.:

* `apache2`
* `nsd` (see [nsd(8)](https://man.openbsd.org/nsd.8))
* `pf` (see [pf(4)](https://man.openbsd.org/pf.4))
* `relayd` (see [relayd(8)](https://man.openbsd.org/relayd.8))
* `smtpd` (see [smtpd(8)](https://man.openbsd.org/smtpd.8))
* `unbound` (see [unbound(8)](https://man.openbsd.org/unbound.8))
* User homefolder

## USAGE

Each archive script accepts an optional destination path as the first parameter.

## INSTALLING

Archive scripts are installed individually, as follows:

```
doas install sbin/pf_archive /usr/local/sbin
```

## LICENSE

Released under the [MIT License](LICENSE).
