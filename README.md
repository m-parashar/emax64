# emax64
Emacs for w64

Clean and optimized build of Emacs for Windows x86-64 systems.
Compiled with support for: jpg/jpeg, gif, png, tiff, xpm and more.
ImageMagick 7 support compiled, binaries, and libraries included.

Get binaries here: https://github.com/m-parashar/emax64/releases

emax64-20180406
---------------

* 64-bit Windows build of Emacs 26.1
* Patched with ImageMagick 7 support. Binaries and libs included.
* PDF-TOOLS (epdfinfo.exe) included.
* Features[1]: "XPM JPEG TIFF GIF PNG RSVG IMAGEMAGICK SOUND NOTIFY ACL GNUTLS LIBXML2 ZLIB TOOLKIT_SCROLL_BARS MODULES THREADS LCMS2"
* Optimized clean build. Options[2]: "--without-compress-install --without-dbus --with-modules 'CFLAGS= -O2 -g3'"
* Built and tested on a clean Windows 10 system.
* addpm modified to not create/update any registry HOME entries. It only creates shortcuts as it should.

* [1] C-h v system-configuration-features
* [2] C-h v system-configuration-options

Installation:
* Unpack the 7z binary archive, preferably in C:\ root directory.
* Since 20180303, directory name has changed from emaxw64 to emax64.
* Double-click the addpm.exe file in emax64\bin to create/update shortcuts.

Recommended:
* Install MSYS2 [64-bit: http://repo.msys2.org/distrib/msys2-x86_64-latest.exe]
* Download and unpack emax.7z into your HOME directory, usually C:\Users\<username>\AppData\Roaming
* emax.7z is an environment to make your Emacs experience a little more tolerable on Windows.
* It includes a barebones dotfile along with BusyBox 64-bit, some MinGW packages, SSH, W3M, Aspell, and other GNU tools to help you start right away.


![emax64 on Windows 10](https://i.imgur.com/4E4OYqo.png)
