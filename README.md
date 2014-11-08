Theme Viewer
============
This is a tool for Sublime Text theme and syntax developpers.  
This tool shows the standard Textmate scopes used by Sublime Text.  
It's composed of a syntax definition and a text sample.  
The YAML syntax definition is also given, for easy tweaks with _AAAPackageDev_

Installation
===
Prefer the use of the _Package Control_.  
Else, you can put the files inside **\<package-dir\>/User/**

Use
===
Simply open the **theme-viewer.theme-viewer** file inside the package : the file will be automaticaly colored. 
(There is a menu entry to open it easily : Tools/Theme Viewer/Open Sample)  
By changing your theme, you can see its coloration for each of the Textmate standard scopes.  
The syntax definition is easily tweakable to add custom scope. You can do that by directly modifying the **theme-viewer.tmLanguage**, or better, the **theme-viewer.YAML-tmLanguage** file with the _AAAPackageDev_.
