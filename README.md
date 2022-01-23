# python-calculator-with-Kivy-

# Packaging Your App for Android

In shell, run;
$ pip install buildozer

Then run;
$ buildozer init 

This will create a buildozer.spec file that you’ll use to configure your build 

Once you are satisfiewd with your spe file above , proceed to run;

$ buildozer -v android debug

Buildozer will download whatever Android SDK pieces it needs during the build process. If everything goes according to plan, then you’ll have a file named something like kvcalc-0.1-debug.apk in your bin folder.
