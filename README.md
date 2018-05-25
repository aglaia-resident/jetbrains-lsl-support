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

Go to the IDE folder of your personal folder.
Where is this folder depends on your OS and how your IDE was installed.
For example, on Linux systems, that will be something like :

```
/home/Alice/.IntelliJIdea2018.1
```

On Windows, it will be something like :

```
c:\Users\Alice\.IntelliJIdea14\
```

Go now in the subfolder config.
Here you may find a folder called "filetypes".
If filetypes folder doesn't exist, create it.
Then put in this folder the LSL.xml file.

The file should now be located at something like (depending on your OS) :

```
/home/Alice/.IntelliJIdea2018.1/config/filetypes/LSL.xml
```

If your IDE is running : restart it.

Your should now have the LSL support for all files with extension .lsl or .LSL !

For any question, please contact me in Second Life. Usename : aglaia
