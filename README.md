LSL support for IntelliJ and other JetBrains IDEs
=================================================

This file will allow the LSL (Linden Script Language) support in all IDE of the JetBrains range: IntelliJ, PhpStorm, PyCharm, and all other Jetbrains IDEs.

What does it provide ?
----------------------

* Syntax highligh
* Keywords and function autocomplete

Installation
------------

Following process describes the installation for the IntelliJ IDE.
You have to adapt it, replacing "IntelliJ" by the name of your IDE.

Download LSL.xml

Go to the Configuration directory of your IDE. This directory depends of your system.
This will tell you where is this folder on your computer: https://www.jetbrains.com/help/pycharm/directories-used-by-the-ide-to-store-settings-caches-plugins-and-logs.html#config-directory

For example on Windows, it will be something like :

```
C:\Users\JohnS\AppData\Roaming\JetBrains\IntelliJIdea2021.2
```

In this folder, you may find a folder called "filetypes".
If the filetypes folder doesn't exist, create it.
Then put the LSL.xml file in this folder.


If your IDE is running : restart it.

Now go to File > Settings > Editor > Files types. You should see "Linden Script Language" in the left colum. On the right side, under "File Name Patterns", click the + icon and add "*.lsl". This will associate .lsl extension to the Linden Script Language content type.

Your should now have the LSL support for all files with extension .lsl!

For any question, please contact me in Second Life. Usename : aglaia
