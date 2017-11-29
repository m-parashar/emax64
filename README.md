# emax64
Emacs for w64

The first w64 version of ntemacs has been renamed emax64.

Clean and optimized build of Emacs for Windows x86-64 systems.
Compiled with support for: jpg/jpeg, gif, png, tiff, xpm and more.

Get binaries here: https://github.com/m-parashar/emax64/releases

emax64-20171129
---------------

* 64-bit Windows build of Emacs 26.0.90. DLLs included.
* Built and tested on a clean Windows 10 system.
* Patched with ImageMagick 7 support. Binaries and libs included.
* PDF-TOOLS (epdfinfo.exe) included.
* Features: XPM JPEG TIFF GIF PNG RSVG IMAGEMAGICK SOUND DBUS NOTIFY ACL GNUTLS LIBXML2 ZLIB TOOLKIT_SCROLL_BARS MODULES LCMS2
* Optimized clean build. Options: "--without-compress-install --with-dbus --with-modules 'CFLAGS= -O3 -pipe -s -g0 -march=native' 'LDFLAGS= -s '"

Installation:

* Unpack the 7z binary archive, preferably in C:\ root directory.
* Run emacs\bin\addpm.exe to add registry entries.
* Double-click the runemacs.exe file in emacs\bin and hack away!
