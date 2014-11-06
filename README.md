Nitrux (icon theme) - Issue tracker repository
============

Hand crafted, infinitely scalable icons. Nitrux is a simple, clean and minimal icon set that has been consistently designed to add the finishing touch to your desktop.

![Nitrux preview](http://fc03.deviantart.net/fs70/f/2013/360/b/7/nitrux_by_deviantn7k1-d4utllr.png "Hand crafted, infinitely scalable icons.")

Icons are licensed under the [Creative Commons Attribution-NonCommercial-NoDerivatives International 4.0 License](https://creativecommons.org/licenses/by-nc-nd/4.0/).

* Check **COPYING** file inside the package for more information.

Download
========

Icons are available to download for GTK based environments (Gnome, Cinnamon, Mate, XFCE, LXDE), KDE (Plasma, Plasma 5 and Android at the [Nitrux Store](http://nitrux.in/store).

Reporting issues
================

When reporting missing icons make sure to follow these steps so we can resolve the issue faster:

### For Linux:

1. Add **screenshots**, images speak louder than words. Add a screenshot of the missing icon, and the instances where it shows (menus, taskbars, panels, notifications, etc.).
2. Add the relevant launcher information, software in Linux DE uses files with the extention *.desktop* as launchers in menus (like Homerun, Mint menu, Gnome Shell overview), these launchers are stored in **/usr/share/applications** (there might be a */kde* folder for KDE apps) for software installed through a package or the package manager. Applications such as Google Chrome extentions install their launchers here: **/home/$USER/.local/share/applications/**. Simply open these files with a text editor and copy their contents in your issue.
3. Add a description of the software, it's very important for us to know what the software does as we are not able to install every software under the sun and to know what it does.
4. Open individual issues for each missing icon.
5. Some software use *hardcoded paths* in their launchers, as such even when we add the icon the system will not load it, you may use [Hardcoded Icon Fixer](https://github.com/Foggalong/hardcode-fixer) to resolve this very problem.

### For Android:

1. If you want to report an Android icon use the following title prefix (without the quotes: "[Android] App_name" - that way we can tag them appropriately.
2. Download [Package Name Viewer](https://play.google.com/store/apps/details?id=com.gijoon.pkgnameviewer) - this application will allow you to see the name of the package that provides any given application your device.
3. Open it and locate the application that's missing the icon. Tap it and select *Copy to Clipboard*.
4. Then depending on your launcher get to the **Activities** list. *(Nova users simply long-press an empty space and then tap *Shortcuts*>*Activities*)*.
5. Locate the app on the activities list and take a screenshot of the activities related to that app. *(Nova users simply locate the app and tap on it, then take the screenshot)*.
6. Upload the and get the direct link to the image.
7. Open an new issue at this repo and add the tag in the title, then paste the package name and the direct link to the screenshot with list of activities.
