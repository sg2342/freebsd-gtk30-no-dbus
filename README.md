gtk30-no-dbus
=============

FreeBSD gtk30 port with additional option FAKEATK:

If set, the dependency to at-spi2-atk is replaced with
https://github.com/sg2342/freebsd-atk-bridge-fake .

Since at-spi2-atk depends on dbus, setting FAKEATK enables
dbus-free gtk30.