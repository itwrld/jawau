# JAWAU

Just Another Warcraft Addon Updater

![alt text](https://raw.githubusercontent.com/itwrld/jawau/master/showcase/JAWAU.png)


## Getting Started

If you run the program for the first time, you&rsquo;ll notice that My Addons and Search buttons are disabled. In order to actually be able to use this program, you need to go to Settings and select the World of Warcraft installation folder using the Browse button.

After choosing your WoW folder you can start using the program. Important to know that JAWAU can't find already installed addons. That's why, you need to reinstall them using this program. That way, they'll be added to an internal database for easy future management.

## Using the program

If you want to install an addon to the database, you press the Search button and type the desired addon's name in there, after that, press Enter key or the Search button. The program will then search the addon you've just typed on <a href="https://www.curseforge.com/wow/addons" target="_blank" rel="noopener">CurseForge</a>. Sometimes it's better to use keywords when you search for addons (ie: sexy instead of sexymap), it will be more accurate.

If you found the addon you were searching for, you need to press the Install button to install it. If the addon is already present on your database, you won't be able to install it, you will need to remove it from My Addons first.

If you click on My Addons section, you will see your installed addons, that you can update or remove if needed. When you remove an addon, it will disappear from your installed addons. If you remove addons, all the folders and files in your World of Warcraft addon folder that belongs to the addon will be removed also.

If you want to check for updates, just click on the same My Addons section or the Refresh button and the program will automatically check for new updates. That easy! :)

In Settings section you also have three useful options: Backup, Restore and Reset. They are really useful if you like to backup/restore or reset your current configuration.

### Prerequisites

To run this software you need to be on Windows 7/8.1/10 64bit OS.

To install this software you only need some ZIP unpacking tool like,

```
WinRAR from https://www.rarlab.com/
```

### Installing

The installing procedure is quite simple. Here's what you need to do:

Download the binary

```
Go to https://github.com/itwrld/jawau/releases and download the latest version.
```

Unpack the contents

```
Open jawau.zip from your computer with your unpacking tool (WinRAR for example) and extract the contents to a folder named JAWAU.
```

That's it, now you're ready to use JAWAU!


## Built With

* [Qt](https://www.qt.io/download) - The cross-platform SDK used
* [QuaZIP](http://quazip.sourceforge.net) - Qt/C++ wrapper for ZIP/UNZIP package
* [zlib](http://www.zlib.net) - A massively spiffy yet delicately unobtrusive compression library
* [OpenSSL](https://www.openssl.org/) - a robust, commercial-grade, and full-featured toolkit for the Transport Layer Security (TLS) and Secure Sockets Layer (SSL) protocols


## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/itwrld/jawau/tags). 

## Authors

* **Ionut Trandafir** - trandafir.ionut[at]itwrld.com


## License

This project is licensed under the  GNU Version 3 - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Marian Calin (icon graphics)
* Serge Terryn (parts of the html parsing code)
* Alex Turkin (busy indicator code)

## Support for the project

If you like JAWAU and found it useful, and you think i deserve a cookie, use the donate button ->
[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://paypal.me/JohnnyUSA?locale.x=en_US)
