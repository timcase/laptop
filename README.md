Laptop
======

Laptop is a script to set up a Mac OS X or Linux laptop for Rails
development. 

**NOTE: This is a fork from thoughtbot has been modified for
my (Tim Case) own particular tastes, you would be better off using the
original project from thoughtbot, check the fork link above.**


Requirements
------------

### Mac OS X

Install a C compiler:

For Snow Leopard (10.6): use [OS X GCC
Installer](https://github.com/kennethreitz/osx-gcc-installer/).

For Lion (10.7) or Mountain Lion (10.8): use [Command Line Tools for
XCode](https://developer.apple.com/downloads/index.action).

For Mavericks (10.9): run `sudo xcodebuild -license` and follow the instructions
to accept the XCode agreement.  Then run `xcode-select --install` in your
terminal and then click "Install".

### Linux

We support:

* [13.10: Saucy Salamander](https://wiki.ubuntu.com/SaucySalamander/ReleaseNotes),
* [13.04: Raring Ringtail](https://wiki.ubuntu.com/RaringRingtail/ReleaseNotes),
* [12.10: Quantal Quetzal](https://wiki.ubuntu.com/QuantalQuetzal/ReleaseNotes), and
* [12.04 LTS: Precise Pangolin](https://wiki.ubuntu.com/PrecisePangolin/ReleaseNotes),
* Debian stable (currently [wheezy](http://www.debian.org/releases/stable/)).
* Debian testing (currently [jessie](http://www.debian.org/releases/testing/)).

Install
-------

### Mac OS X

Read, then run the script:

    bash <(curl -s https://raw.github.com/timcase/laptop/master/mac)

### Linux

Read, then run the script:

    bash <(wget -qO- https://raw.github.com/timcase/laptop/master/linux)

Credits
-------
This was originally forked from thoughtbot

![thoughtbot](http://thoughtbot.com/assets/tm/logo.png)

