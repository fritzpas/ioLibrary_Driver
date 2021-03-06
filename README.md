#ioLibrary Driver
The ioLibrary means “Internet Offload Library” for WIZnet chip. It includes drivers and application protocols. 
The driver (ioLibrary) can be used for the application design of WIZnet TCP/IP chips as [W5500](http://wizwiki.net/wiki/doku.php?id=products:w5500:start), W5200, W5100 and etc.

##ioLibrary
This driver provides the Berkeley Socket type APIs.
- Directory Structure
<!-- ioLibrary pic -->
![ioLibrary](http://wizwiki.net/wiki/lib/exe/fetch.php?media=products:w5500:iolibrary_bsd.jpg "ioLibrary")

- Ethernet : SOCKET APIs like BSD & WIZCHIP([W5500](http://wizwiki.net/wiki/doku.php?id=products:w5500:start), W5200 and etc) Driver
- Internet :
  - DHCP client
  - DNS client
  - Others will be added.

## How to add an ioLibrary in project through github site.
  - Example, refer to https://www.youtube.com/watch?v=mt815RBGdsA
  - [ioLibrary Doxygen doument](https://github.com/Wiznet/ioLibrary_Driver/blob/master/Ethernet/SOCKET_APIs_V2.0.chm) : Refer to **TODO** in this document
    - Define what chip is used in **wizchip_conf.h**
    - Define what Host I/F mode is used in **wizchip_conf.h**

## Revision History
  * Type casting error Fixed : 09, April. 2015
    In socket.c, send() : Refer to M20150409
  * ioLibrary V2.0 released : April. 2015
    * Added to W5100, W5200
    * Correct to some typing error
    * Fixed the warning of type casting.
  
  * Last release : Nov. 2014

