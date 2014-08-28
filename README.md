##DO NOT USE THIS ON ANY OTHER DEVICE.
THIS IS FOR THE PANTECH PRESTO (BURST/P9070).
YOUR RECOVERY PARTITIONS WILL BE DIFFERENT.

Copy your recovery to

````
output/zip
````
and make sure it is named 
````
recovery.img
````

Open the build script and adjust your variables.

````
###Set your variables

#Device name
device=presto

#Recovery name
recoveryname=cwm

#Recovery version
vernumber=6.0.5.0

#Insert date
NOW=$(date +"%m%d%y")

#File revision
revision=r2

#Author of the file
author=marduk191
````

Edit your changelog

````
gedit ./changelogs.txt
````

Run the build script

````
./build
````

Get your output file from

````
output/zip/presto.cwm.recovery.6.0.5.0.r2.082714-marduk191.zip
````

When ready to clean the old files up (including the one you just made)

````
./cleanup
````