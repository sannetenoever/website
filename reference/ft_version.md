---
title: ft_version
---
```plaintext
 FT_VERSION returns the version of FieldTrip and the path where it is installed

 FieldTrip is not released with version numbers as "2.0", "2.1", etc. Instead, we
 share our development version on http://github.com/fieldtrip/fieldtrip. You can use
 git to make a local clone of the development version. Furthermore, we make
 more-or-less daily releases of the code available on
 https://github.com/fieldtrip/fieldtrip/releases and as zip file on our FTP server.

 If you use git with the development version, the version is labeled with the hash
 of the latest commit like "128c693". You can access the specific version "XXXXXX"
 at https://github.com/fieldtrip/fieldtrip/commit/XXXXXX.

 If you download the daily released version from our FTP server, the version is part
 of the file name "fieldtrip-YYYYMMDD.zip", where YYY, MM and DD correspond to year,
 month and day.

 Use as
   ft_version
 to display the latest revision number on screen, or
   [ftver, ftpath] = ft_version
 to get the version and the installation root directory.

 When using git with the development version, you can also get additional information with
   ft_version revision
   ft_version branch
   ft_version clean

 See also FT_PLATFORM_SUPPORTS, VERSION, VER, VERLESSTHAN
```
