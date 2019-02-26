
Source :~ <http://compendiumld.open.ac.uk/documentation/readme/ReadMe.html>

---

`This is information about the the most recent prototype of [CompendiumLD](../../index.html),
the Open University's learning design software.`

<a name="top"></a>

# Important Installation Information for CompendiumLD

Table of Contents:

*   [I. Welcome!](#welcome)
*   [II. Install CompendiumLD](#install)  
    - [General](#installgeneral)  
    - [Windows](#windows)  
    - [Mac OS X](#mac)  
    - [Linux](#linux)
*   [III.Known Issues](#issues)  
    - [CompendiumLD](#issueCLD)  
    - [Java](#issueJava)  
    - [General](#issuegeneral)  
    - [Windows](#issuewindows)  

## <a name="welcome"></a> I. Welcome!

### Welcome to CompendiumLD

CompendiumLD is a software tool for designing learning activities using a flexible visual interface.
It provides a set of icons to represent the components of learning activities;
these icons may be dragged and dropped, then connected to form a map representing a learning activity.
CompendiumLD is a specialised version of [Compendium](http://compendium.open.ac.uk/institute/about.htm), the mind mapping or argumentation software that provides a default set of icons for creating maps to visualise the connections between ideas.
All the facilities provided by Compendium are included within CompendiumLD.

This prototype has been released to allow users to explore CompendiumLD and influence and inform its development.
Please provide feedback about the installation process and CompendiumLD itself on the to the [Compendium feature request and bug tracking site](http://compendium.open.ac.uk/bugzilla/enter_bug.cgi?product=CompendiumLD).
If you have any questions about CompendiumLD please contact the lead developer [Andrew Brasher](mailto:a.j.brasher@open.ac.uk).

[Back to top](#top)

## <a name="install"></a> II. Install CompendiumLD

### <a name="installgeneral"></a> General

If you already have the [standard version of Compendium](http://compendium.open.ac.uk/institute/download/download.htm) installed, we recommend that you install this prototype into another directory.

_**CompendiumLD is a Java application, so it requires a Java Runtime Environment (JRE) to be installed**._

_If you have a previous version of CompendiumLD installed we recommend that you copy your previous installation to a new folder_ (e.g. ComendiumLD-backup) before updating the original with this new version.

### <a name="windows"></a>Windows

As stated [above](#installgeneral) CompendiumLD requires the a Java Runtime Environment (JRE) to be installed. If Java is not detected on your system you will be prompted to install the JRE at the end of the CompendiumLD installation process.

The simplest way to install CompendiumLD on either Windows XP, Vista, 7 or 8 is with an account with ADMINISTRATIVE rights. To ensure the installer is run with the necessary privileges in Windows Vista, 7 or 8 you should right-click on the installer and select 'Run as administrator'.

<a name="windowsNonAdmin"></a> If you do not have administrator privileges (administrator rights) you can still install and run CompendiumLD. Just install CompendiumLD in your 'My Documents' or 'Documents' folder, then install the Java Runtime Environment in to the JRE sub-folder within the CompendiumLD folder.

If you are installing onto Windows Vista, 7 or 8 you may get an error message indicating that the Java Runtime Environment has not been installed correctly (e.g. this [javaw message](#issueJava)). If this occurs you will need to install the Java Runtime Environment separately. To do so, download the latest release of the Java Runtime Environment from the Java site and follow the installation instructions provided

### <a name="mac"></a> Mac OS X

CompendiumLD version 1.2 for Mac OS X has been tested on 10.5 (Leopard), 10.6 (Snow Leopard), 10.7 (Lion) and 10.9 (Mavericks). It requires Java J2SE 5.0 Release 4 (aka 1.5.0_4) or later, which will be present if you are running Mac OS 10.6 and below. If you are running Mac OS 10.7 (Lion) or above you will need to install Java: see [Mac OS X Java 7 Information for installing and using Java](http://www.java.com/en/download/faq/java_mac.xml). CompendiumLD should also run on for 10.4 (Tiger) but has not been tested.

Once you have downloaded the relevant .dmg file from the [CompendiumLD web site](http://compendiumld.open.ac.uk/) you need to double click the .dmg file to mount the disk image. This will open a window showing you the CompendiumLD `.mpkg` file. Double click the package file and this will run the installer. Follow the installer instructions.

If you are unsure which version of Java you have installed, open a terminal window (inside Applications/Utilities/Terminal) and type:

```
java -version
```

The output from running that command will look something like:

```
java version "1.5.0_07"  
Java(TM) 2 Runtime Environment, Standard Edition (build 1.5.0_07-164)  
Java HotSpot(TM) Client VM (build 1.5.0_07-87, mixed mode, sharing)
```

The text above shows that Java 1.5.0_07 is installed in this example which is fine as it is greater than the required 1.5.0_04

_NOTE:_ Currently, due to unresolved file permission issues, only the user installing CompendiumLD will be able to run it, unless CompendiumLD subfolders have their permissions changed appropriately.

_USER INTERFACE TIP:_ Depending on your mouse or trackpad settings, you may have to use combinations such as

*   `ctrl+click` to access menus when clicking on nodes or the working area
*   `alt+drag`   to create links between nodes

_TECH TIP:_ You might like to be aware that Compendium sets the Memory allocation for the JRE up to _256mb_ (the default is _64mb_). If you need to change this value for any reason, you will need to open the contents of the Compendium Application file using the 'Show Package Contents' option on the right-click menu, then open the Contents' folder and edit the VMOptions property in the `info.plist` file. Please only attempt this if you are a confident user.

_TECH TIP:_ In order to automatically open external files and links on the Mac, Compendium stores file extension and application associations in a file in

`<Compendium home folder>/System/resources` called `LaunchApplications.properties`.

This file is added to as the user tries to launch various file types for the first time and picks an application to use. We have preloaded this file with three type, `www`, `http` and `https`, and we have associated them with the path `/Applications/Safari`. If you do not have this application or have it in another location, you will need to edit this file appropriately.

### <a name="linux"></a> Linux

Once you have downloaded the relevant `.tar.gz` file from the [CompendiumLD web site](http://compendiumld.open.ac.uk/), simply unpack it.
You can run CompendiumLD by navigating to the CompendiumLD directory and typing:

```
./compendiumLD.sh
```

Compendium is a Java application, so it requires a Java Runtime Environment (1.5+) to be installed before you can run it.

[Back to top](#top)

## <a name="issues"></a> III. Known Issues

### <a name="issueCLD"></a> CompendiumLD

CompendiumLD is under ongoing development and there are some aspects of functionality that we know are missing from this version:

*   The help available via the 'Help' menu is exactly the same as for the standard version of Compendium,
    i.e. it has not been updated to take account of the additional learning design functionality available in CompendiumLD.
*   Although they may be dragged onto the user's design window, the activities in the learning design help pop-up create
    [transclusions](https://en.wikipedia.org/wiki/Transclusion) of existing activities.

There are other aspects of learning design functionality that we plan to add to future prototypes of CompendiumLD.
Further information about these will be available from the [CompendiumLD website](http://compendiumld.open.ac.uk/).

### <a name="issueJava"></a> Java

If, when starting CompendiumLD (e.g. by double clicking the CompendiumLD icon) you get a message like

Windows cannot find `javaw`

you should try reinstalling Java from the Java site ([http://java.com/](http://java.com/)).  

### <a id="issuegeneral" name="issuegeneral"></a> General _(issues concerning standard Compendium functionality)_

When you import a map from QuestMap with Pros and Cons, they come out as Arguments in CompendiumLD (even though they are linked to other nodes).

Exporting to an XML file in an off-line directory can cause the file to be corrupted. (This is a known Windows problem).

### <a name="issuewindows"></a> Windows

There is a general bug with Java running on machines with some versions of NVidia video drivers.
If you have a graphics card which uses these drivers, and experience problems running CompendiumLD,
you should make sure that you have the latest drivers installed.

There is a problem with some Tablet PCs and graphics drivers.
A workaround is to switch off Java 2D graphics. This can be done by editing the `CompendiumLD.bat` file.
The final line in the batch file should resemble:

```
start /b javaw -Dsun.java2d.noddraw=true -Xmx256m -classpath etc.. etc..
```

Best wishes

The [CompendiumLD](../../index.html) Team, [Open University Learning Design Initiative](http://ouldi.open.ac.uk/).

Contact: Andrew Brasher _(lead developer)_, [a.j.brasher@open.ac.uk](mailto:a.j.brasher@open.ac.uk).

<span class="ciparagraph">[Back to top](#top)</span>

---
