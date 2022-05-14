NppLogcat
=========

A Notepad++ User Defined Language (UDL) for Android logcat logs, for the default and Solarized Dark colour theme.

A custom language for use with [Notepad++](https://notepad-plus-plus.org), to add color to Android Logcat logs that were saved to a text file, similar to the color highlighting used in Eclipse and Android Studio. This version is based on [TronicZomB's original NppLogCat](https://github.com/TronicZomB/NppLogCat) with some improvements for the default color theme, along with a variation for the [Solarized Dark color theme](http://ethanschoonover.com/solarized) by Ethan Schoonover.

This user-defined language file can be imported into Notepad++ to get colored lines for your Logcat files. Verbose is grey, info is green, debug is blue, warning is orange, and error is red. This file is compatible with Eclipse's log file export and copy-paste, as well as the command-line `adb logcat` formats (at least the default, `-v thread` and `-v threadtime`).

Prerequisite: Notepad++ Theme
-----------------------------

For this user-defined language to look as intended, you must be using the correct theme in Notepad++. It is built into recent versions of Notepad++. To change to it:

1. Go to the **Settings** menu > **Style Configurator...**.
2. In the dropdown labeled **Select theme**, choose the style, depending on the Logcat UDL you want to use:
  * For the default style (`logcat.npp.xml`), choose **Default (stylers.xml)**.
  * For the Solarized Dark style (`logcat.solarized-dark.npp.xml`), choose **Solarized**.
3. Click **Save & Close**.

Installation
------------

1. Open Notepad++.
2. Go to the **Languages** menu > **Define your language...**. A dialog will appear.
3. Click on the **Import...** button at the top.
4. Find and select the appropriate XML file from this repository (`logcat.npp.xml` or `logcat.solarized-dark.npp.xml`). Click OK.
5. Restart Notepad++. The language "Logcat" (for `logcat.npp.xml`) or "Logcat (Solarized Dark)" (for `locat.solarized-dark.npp.xml`) will appear at the bottom of the **Languages** menu, below the **Define your languages...** item.

Usage
-----

1. Open a logcat file or paste a logcat into Notepad++.
2. If the file extension is .logcat, the log will be automatically colorized.
3. Otherwise, go to the **Languages** menu > **Logcat** or **Logcat (Solarized Dark)**. The log then will be colorized.
