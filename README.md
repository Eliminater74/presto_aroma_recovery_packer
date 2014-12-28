#Presto Aroma Recovery Packer
V2.0
By marduk191

###Be sure to change your _*recovery partition*_ location if on a different device.

This is only tested on Linux mint 17, it should work on most systems though.
Bubble notifications may be broken on some systems. If so, revert the commit below
````
https://github.com/marduk191/presto_aroma_recovery_packer/commit/46d80c907a4adce522dabb26a5670ea5fbbd3018
````
##Start the script in your bash shell:

````
./parp
````

###Fill out the form and click "build".

<img src='https://raw.githubusercontent.com/marduk191/wikiart/master/parp.png' width='300px'>

Pico will then open in the console so that you may edit your aroma-config and changelogs.txt. A quick press of the key comination "Ctrl+x" will exit and allow you to save changes



##Get your output file from:

````
output/zip/DeviceName.recoveryName.recovery.recoveryVersion.recoveryRevision.Date-Author.zip
````

###When ready to clean the old files up:

````
./cleanup
````



###Changelogs:
````
https://github.com/marduk191/presto_aroma_recovery_packer/commits/master
````
