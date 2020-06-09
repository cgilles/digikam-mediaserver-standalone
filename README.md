This small program is a stand Alone version of digiKam DNLA/UPNP server
-----------------------------------------------------------------------

To compile this code, you need Cmake under Linux. There is no dependency to digiKam core.

One script is provided to compile under linux (bootstrap-linux.sh).

A target CLI tool is generated and can be used to share folders contents to DLNA/UPNP compatible devices.

$ ./filemediaserver
ERROR: path missing
usage: FileMediaServerTest [-f <friendly_name>] [-p <port>] [-g <guid>] <path>
-f : optional upnp device friendly name
-p : optional http port
<path> : local path to serve

Links:

- Cmake:                 https://cmake.org/
- digiKam:               https://www.digikam.org/
- Related bugzilla file: https://bugs.kde.org/show_bug.cgi?id=386294

Gilles Caulier
