*******************
/usr/local/etc/mrh/
*******************
/usr/local/etc/mrh/ contains configuration files used by either MRH Core 
or multiple MRH platform components.

MRH_Core.conf
-------------
MRH_Core.conf is the MRH Core configuration, read for information like event 
exchange timings and the home package to use.

MRH_Locale.conf
---------------
This file contains the active locale used by the MRH platform.

MRH_PackageList.conf
--------------------
The package list configuration file contains the full path to all packages 
known and usable by the MRH platform.

MRH_ProtectedEventList.conf
---------------------------
The protected event list contains all events for which MRH Core requires a 
password verification by a user application before being usable.

MRH_UserEventRoute.conf
-----------------------
The user event route configuration assings events into event route groups.

MRH_PlatformServiceList.conf
----------------------------
MRH_PlatformServiceList.conf contains all platform services to load by MRH Core 
and how those services should be treated. This file also defines which events 
a service receives by using event routes.

MRH_UserServiceList.conf
------------------------
The user service list acts as a whitelist and defines which user application 
services should be started by MRH Core.