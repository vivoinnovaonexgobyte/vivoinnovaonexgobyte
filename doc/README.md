Vivoinnovaonexgobyte Core 0.12.1
=====================

This is the official reference wallet for Vivoinnovaonexgobyte digital currency and comprises the backbone of the Vivoinnovaonexgobyte peer-to-peer network. You can [download Vivoinnovaonexgobyte Core](https://www.vivoinnovaonexgobyte.org/downloads/) or [build it yourself](#building) using the guides below.

Running
---------------------
The following are some helpful notes on how to run Vivoinnovaonexgobyte on your native platform.

### Unix

You need the Qt4 run-time libraries to run Vivoinnovaonexgobyte-Qt. On Debian or Ubuntu:

	sudo apt-get install libqtgui4

Unpack the files into a directory and run:

- bin/32/vivoinnovaonexgobyte-qt (GUI, 32-bit) or bin/32/vivoinnovaonexgobyted (headless, 32-bit)
- bin/64/vivoinnovaonexgobyte-qt (GUI, 64-bit) or bin/64/vivoinnovaonexgobyted (headless, 64-bit)



### Windows

Unpack the files into a directory, and then run vivoinnovaonexgobyte-qt.exe.

### OS X

Drag Vivoinnovaonexgobyte-Core to your applications folder, and then run Vivoinnovaonexgobyte-Core.

### Need Help?

* See the [Vivoinnovaonexgobyte documentation](https://vivoinnovaonexgobytepay.atlassian.net/wiki/display/DOC)
for help and more information.
* Ask for help on [#vivoinnovaonexgobytepay](http://webchat.freenode.net?channels=vivoinnovaonexgobytepay) on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net?channels=vivoinnovaonexgobytepay).
* Ask for help on the [VivoinnovaonexgobyteTalk](https://vivoinnovaonexgobytetalk.org/) forums.

Building
---------------------
The following are developer notes on how to build Vivoinnovaonexgobyte on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [OS X Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)
- [Windows Build Notes](build-windows.md)
- [OpenBSD Build Notes](build-openbsd.md)
- [Gitian Building Guide](gitian-building.md)

Development
---------------------
The Vivoinnovaonexgobyte repo's [root README](/README.md) contains relevant information on the development process and automated testing.

- [Developer Notes](developer-notes.md)
- [Multiwallet Qt Development](multiwallet-qt.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)
- Source Code Documentation ***TODO***
- [Translation Process](translation_process.md)
- [Translation Strings Policy](translation_strings_policy.md)
- [Unit Tests](unit-tests.md)
- [Unauthenticated REST Interface](REST-interface.md)
- [Shared Libraries](shared-libraries.md)
- [BIPS](bips.md)
- [Dnsseed Policy](dnsseed-policy.md)

### Resources
* Discuss on the [VivoinnovaonexgobyteTalk](https://vivoinnovaonexgobytetalk.org/) forums, in the Development & Technical Discussion board.
* Discuss on [#vivoinnovaonexgobytepay](http://webchat.freenode.net/?channels=vivoinnovaonexgobytepay) on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net/?channels=vivoinnovaonexgobytepay).

### Miscellaneous
- [Assets Attribution](assets-attribution.md)
- [Files](files.md)
- [Tor Support](tor.md)
- [Init Scripts (systemd/upstart/openrc)](init.md)

License
---------------------
Distributed under the [MIT software license](http://www.opensource.org/licenses/mit-license.php).
This product includes software developed by the OpenSSL Project for use in the [OpenSSL Toolkit](https://www.openssl.org/). This product includes
cryptographic software written by Eric Young ([eay@cryptsoft.com](mailto:eay@cryptsoft.com)), and UPnP software written by Thomas Bernard.
