#Presto Aroma Recovery Packer
V2.0
By marduk191

###THIS IS FOR THE PANTECH PRESTO (BURST/P9070).
Be sure to change your recovery partition location if on a different device.

This is only tested on Linux mint 17, it should work on most systems though.
Bubble notifications may be broken on some systems. If so, revert the commit below
````
https://github.com/marduk191/presto_aroma_recovery_packer/commit/46d80c907a4adce522dabb26a5670ea5fbbd3018
````
If you would like to use the yad interface:

````
./parp
````
Fill out the form and click "build".
Pico will then open in the console so that you may edit your aroma-config and changelogs.txt. A quick press of the key comination "Ctrl+x" will exit and allow you to save changes

<img src='https://raw.githubusercontent.com/marduk191/wikiart/master/parp.png' width='300px'>

Get your output file from:

````
output/zip/DeviceName.recoveryName.recovery.recoveryVersion.recoveryRevision.Date-Author.zip
````

When ready to clean the old files up (including the one you just made)

````
./cleanup
````



Changelogs:
````
https://github.com/marduk191/presto_aroma_recovery_packer/commits/master
````
