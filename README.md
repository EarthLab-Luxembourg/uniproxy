uniproxy
========

The Universal Proxy is an application with the purpose of providing maritime authorities (and anyone else) 
with a simple application that will provide a secure and reliable transparent TCP/P socket connection between two entities over the Internet.

The project is partly sponsored by the Mona Lisa project funded by the European Union.

The documentation ie. the requirement specification is available but will not be put on github.



Log:
========

1/10-2013 PBondo
----------------
Has been running successfully deployed for more than a year now.

Added support for the provider proxy configuration.

Changed build type for Windows to 64 bit.

Installer included for Windows

Switched to Visual Studio 2012.


6/8-2012 PBondo
---------------
Preparing for initial push of the source for uniproxy.


Building instructions:
======================

Linux (Ubuntu)
--------------
Dependencies:

Python (www.python.org)
cmake (www.cmake.org)
openssl (www.openssl.org)
boost (www.boost.org)
# sudo apt-get install cmake libssl-dev libboost-all-dev
cppcms (cppcms.com)
# Must be installed and compiled manually.

mkdir build
cd build
cmake ..
make

The codelite project files should be correct.


Windows (Windows 7)
-------------------
Dependencies:

Python (www.python.org)
cmake (www.cmake.org)
openssl (www.openssl.org)
boost (www.boost.org)
cppcms (cppcms.com)

mkdir build
cd build
cmake -G "Visual Studio 11 Win64" ..
make


Contributers:
-------------
Poul Bondo (GateHouse) Founder and current Maintainer

