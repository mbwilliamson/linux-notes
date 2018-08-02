# linux-notes
Notes for setting up my Linux installation after a fresh install.

## Apache Directory Studio
Add the following to ApacheDirectoryStudio.ini to enable OpenJDK v10 compatibility

~~~text
-vmargs
--add-modules=java.se.ee
-Dosgi.requiredJavaVersion=1.8
-Xms256m
-Xmx1024m
~~~

## Visual Studio Code
For whatever reason, the menu animation is laggy in this Electron.js app. Add the --disable-gpu flag to disable hardware acceleration.
