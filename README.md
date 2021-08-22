LSL support for IntelliJ and other JetBrains IDEs
=================================================

This file will allow the LSL (Linden Script Language) support in all IDE of the JetBrains range.

Supported IDEs
--------------

* IntelliJ
* PyCharn
* WebStorm
* PhpStorm
* ReSharper
* ReSharper C++
* Rider
* CLion
* RubyMine
* AppCode
* GoLand

What does it provide ?
----------------------

Once enabled, the LSL support will be applied to all files with extension .lsl or .LSL that you 
will open in your IDE. It will give you :


* Syntax highligh
* Keywords and function autocomplete

Installation
------------

Following process describes the installation for the IntelliJ IDE.
You have to adapt it, replacing "IntelliJ" by the name of your IDE.

Download LSL.xml

Go to the Configuration directory of your IDE. This directory depends of your system.
This will tell you where is this folder on your computer: https://www.jetbrains.com/help/pycharm/directories-used-by-the-ide-to-store-settings-caches-plugins-and-logs.html#config-directory

For example, on Linux systems, that will be something like :

```
~/.config/JetBrains/IntelliJIdea2021.2
```

On Windows, it will be something like :

```
C:\Users\JohnS\AppData\Roaming\JetBrains\IntelliJIdea2021.2
```

On Mac, something like:

```
~/Library/Application Support/JetBrains/PyCharm2021.2
```

In this folder, you may find a folder called "filetypes".
If the filetypes folder doesn't exist, create it.
Then put the LSL.xml file in this folder.

The file should now be located at something like (depending on your OS) :

```
~/.config/JetBrains/IntelliJIdea2021.2/filetypes/LSL.xml
```

If your IDE is running : restart it.

Your should now have the LSL support for all files with extension .lsl or .LSL !

For any question, please contact me in Second Life. Usename : aglaia
