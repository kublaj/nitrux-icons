Nitrux (icon theme) - Issue tracker repository
============

Hand crafted, infinitely scalable icons. Nitrux is a simple, clean and minimal icon set that has been consistently designed to add the finishing touch to your desktop.

![Nitrux preview](http://fc03.deviantart.net/fs70/f/2013/360/b/7/nitrux_by_deviantn7k1-d4utllr.png "Hand crafted, infinitely scalable icons.")

Icons are licensed under the [Creative Commons Attribution-NonCommercial-NoDerivatives International 4.0 License](https://creativecommons.org/licenses/by-nc-nd/4.0/).

* Check **COPYING** file inside the package for more information.

Download
========

Icons are available to download for GTK based environments (Gnome, Cinnamon, Mate, XFCE, LXDE), KDE (Plasma, Plasma 5) and Android at the [Nitrux Store](http://nitrux.in/store).

Reporting missing icons
=======================

When reporting missing icons make sure to follow these steps so we can resolve it faster:

### For Linux:

1. Add **screenshots**, images speak louder than words. Add a screenshot of the missing icon and the instances where it's displayed  ` (menus, taskbars, panels, notifications, etc.).
2. Use the following title prefix (without the quotes): "[Linux] App_name Desktop_environment" - that way we can tag them appropriately.
3. Add the relevant launcher information, software in Linux DE uses files with the extension *.desktop* as launchers in menus (like Homerun, Mint menu, Gnome Shell overview, Unity, etc.), these launchers are stored in **/usr/share/applications** (there might be a */kde* folder for KDE apps) for software installed through a package or the package manager. Applications such as Google Chrome apps install their launchers here: **/home/$USER/.local/share/applications/**. Simply open these files with a text editor and copy their contents into your issue.
4. Add a description of the software, it's very important for us to know what the software does as we are not able to install every software under the sun and test them.

Some software uses *hardcoded paths* in their launchers, as such even when we add the icon the system will not load it, you may use [Hardcoded Icon Fixer](https://github.com/Foggalong/hardcode-fixer) to resolve this problem.

### For Android:

1. If you want to report an Android icon use the following title prefix (without the quotes): "[Android] App_name" - that way we can tag them appropriately.
2. Download [Package Name Viewer](https://play.google.com/store/apps/details?id=com.gijoon.pkgnameviewer) - this application will allow you to see the name of the package that provides any given application in your device.
3. Open it and locate the application that's missing the icon. Tap it and select *Copy to Clipboard*.
4. Then depending on your launcher get to the **activities** list. *(Nova users simply long-press an empty space and then tap *Shortcuts*>*Activities*)*.
5. Locate the app on the activities list and take a screenshot of the activities related to that app. *(Nova users simply locate the app and tap on it, then take the screenshot)*.
6. Upload it and get the direct link to the image.
7. Open an new issue at this repo and add the prefix in the title, then paste the package name and the direct link to the screenshot with the list of activities.


Disclaimer
==========

* New issues (starting from November 6th 2014) that do not meet the criteria above will not be fixed.
* Issues with paid Nitrux bundles will not be discussed here, you can contact us at our mail.
* You are allowed to open issues about licensing the icons for inclusion in your distribution (if your intention is to include them in a commercial end-product) or including them in your distribution repositories and/or porting them to a non-supported platform.
* Issues that are missing information and are requested for it and see no activity within 24 hours will be labeled as *expiring* and closed 1 week after the request is done.
