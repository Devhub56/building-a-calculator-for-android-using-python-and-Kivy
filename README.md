# python-calculator-with-Kivy from https://realpython.com/mobile-app-kivy-python/#creating-a-kivy-application

# Packaging Your App for Android

In shell, run;
$ pip install buildozer

Then run;
$ buildozer init 

This will create a buildozer.spec file that you’ll use to configure your build 

Once you are satisfiewd with your buildozer spec file above , proceed to run;

$ buildozer -v android debug

Buildozer will download whatever Android SDK pieces it needs during the build process. If everything goes according to plan, then you’ll have a file named something like appname-versionnumber-debug.apk in your bin folder.
