#General information

This README file describes the process for upgrading all the tablet computers of Síragon trademark to new android operating system for mobile devices.
For assistance or questions relating this process please contact Síragon Social Hub Support at [0500-SIRAGON][7] (7472466) or email at [desarrollo03@siragon.com.ve][6]. 
Hours of operation: 5 days, from Monday to Friday, 8:30 AM – 6:00 PM.

##Software Enhancement

###Android™ Operating System upgrade###

	Cupcake operating system
	Donut operating system
	Éclair operating system
	Froyo operating system
	Gingerbread operating system
	Honeycomb operating system
	Ice Cream Sandwich operating system
	Jelly Bean operating system
	Key Lime Pie operating system

#Equipment Requirement

* Síragon AOSU, version 1.0.0.0 or later.
* Data Link Cable, for example: APCBU10BBE.
* PC with standard USB port and the following system requirements.
	
##System Requirement

###Windows

####Operating Systems

    Windows 2000
    Windows XP
    Windows Server 2003
    Windows Vista
    Windows 7
    Windows 8

####Recommended Hardware

    Pentium 4 or newer processor that supports SSE2
    512MB of RAM
    200MB of hard drive space

###Mac

####Operating Systems

    Mac OS X 10.5
    Mac OS X 10.6
    Mac OS X 10.7

####Recommended Hardware

    Macintosh computer with an Intel x86 processor
    512 MB of RAM
    200 MB hard drive space

###Canaima GNU/Linux and others GNU Operating Systems

####Software Requirements
Please note that Linux distributors may provide packages for your distribution which have different requirements.

    Síragon AOSU will not run at all without the following libraries or packages:
        GTK+ 2.10 or higher
        GLib 2.12 or higher
        Pango 1.14 or higher
        X.Org 1.0 or higher (1.7 or higher is recommended)
        libstdc++ 4.3 or higher
    For optimal functionality, we recommend the following libraries or packages:
        NetworkManager 0.7 or higher
        DBus 1.0 or higher
        HAL 0.5.8 or higher
        GNOME 2.16 or higher


##Getting Síragon AOSU

To get the latest version of Síragon AOSU, visit the [www.siragon.com/ve/siragon_aosu][1] and download AOSU to a folder on your PC desktop, .

##Installing Síragon AOSU

1. Verify that no previous version of Síragon AOSU is installed on PC. If a previous version of Síragon AOSU is installed, please remove before proceeding with AOSU installation. *All Programs > Síragon > AOSU > Uninstall AOSU* wait for AOSU program to be removed.
2. Open Síragon AOSU folder on PC desktop and double click AOSU icon to install program.

##Firmware Upgrade Procedure

	1. Run Síragon AOSU program.
	2. Connect data cable to PC USB port.
	3. Power on device and connect to data cable.
	4. Wait for Síragon AOSU to recognize the device.
	5. Síragon AOSU will display pop-up window to alert if there is a software update available. Click to begin software upgrade process.
	6. Click [I have read all of the above information]
	7. Select information saving option.
	8. Click [Start Update]
	9. Firmware upgrade in process. Do not disconnect the cable from the PC.
	10. Firmware upgrade complete. Click [X]

##L10N

Translation workflow and crowdsourcing for technical teams and smart translators.

[Transifex][5] is the localization platform for Síragon AOSU. 

[**Main-Program-Entities**][3] Mozilla DTD files

A DTD file contains a list of entities that need to be localized. The entities defined in these files are then used inside the user interface XUL files.

#####Associated file extensions:
    .dtd
	
#####i18n type:
    DTD
	
#####Encoding:
    UTF-8

**Sample data**
```xml
<!ENTITY foo.var1 "Hello">
<!-- This is a comment -->
<!ENTITY foo.var2 "How are you?">
```


![image](https://www.transifex.com/projects/p/siragon-aosu/resource/main-program-entities/chart/image_png)

[**Main-Program**][4] Mozilla Property Files

You can also translate Mozilla property files with Transifex. These files must be escaped Unicode encoded. In these files contain a number of javaScript properties are assigned with a string value. String resources in Mozilla property files appear in the following form:

The translations downloaded from Transifex will use the source strings for any empty translation strings and will have the relevant entries commented-out.

```INI
	property_name = This is a value text
```

#####Associated file extensions:
    .properties
#####i18n type:
    MOZILLAPROPERTIES
#####Notes:
    The files to be uploaded must be escaped Unicode encoded. 


![image](https://www.transifex.com/projects/p/siragon-aosu/resource/main-program-properties/chart/image_png)

##Trademark Notices

Microsoft®, Windows®, and Windows Vista® are either registered trademarks or trademarks of Microsoft Corporation in the United States and/or other countries.  <br /> 
Mac OS® is a registered trademark of Apple Inc. <br /> 
Android® is a registered trademark of Google Inc. <br /> 
Síragon® is a registered trademark.

The proper names of the Windows operating systems are as follows: <br /> 
 - The product names of Windows® 2000 are as follows: <br /> 
        Microsoft® Windows® 2000 professional <br /> 
 - The product names of Windows® XP are as follows: <br /> 
        Microsoft® Windows® XP Home Edition <br /> 
        Microsoft® Windows® XP Professional <br /> 
 - The product names of Windows Vista® are as follows: <br /> 
        Microsoft® Windows Vista® Home Basic <br /> 
        Microsoft® Windows Vista® Home Premium <br /> 
        Microsoft® Windows Vista® Ultimate <br /> 
        Microsoft® Windows Vista® Business <br /> 
        Microsoft® Windows Vista® Enterprise <br /> 
 - The product names of Windows 7 are as follows: <br /> 
        Microsoft® Windows 7 Starter <br /> 
        Microsoft® Windows 7 Home Basic <br /> 
        Microsoft® Windows 7 Home Premium <br /> 
        Microsoft® Windows 7 Professional <br /> 
        Microsoft® Windows 7 Enterprise <br /> 
        Microsoft® Windows 7 Ultimate <br /> 
 - The product names of Windows 8 are as follows: <br /> 
        Microsoft® Windows 8 Consumer Preview <br /> 
        Microsoft® Windows 8 Release Preview <br /> 
        Microsoft® Windows 8 Pro <br /> 
        Microsoft® Windows 8 Enterprise <br /> 
        Microsoft® Windows 8 RT
		
Other product names used herein are for identification purposes only and might be trademarks of their respective companies. We disclaim any and all rights to those marks. 

##License

Síragon AOSU is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

Síragon AOSU is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with Síragon AOSU. If not, see [<http://www.gnu.org/licenses/>][2]. 


  [1]: http://www.siragon.com
  [2]: http://www.gnu.org/licenses/
  [3]: https://www.transifex.com/projects/p/siragon-aosu/resource/main-program-entities/
  [4]: https://www.transifex.com/projects/p/siragon-aosu/resource/main-program-properties/
  [5]: http://www.transifex.com
  [6]: mailto:desarrollo03@siragon.com.ve
  [7]: tel:05007472466
