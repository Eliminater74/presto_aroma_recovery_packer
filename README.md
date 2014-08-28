##DO NOT USE THIS ON ANY OTHER DEVICE.
THIS IS FOR THE PANTECH PRESTO (BURST/P9070).
YOUR RECOVERY PARTITIONS WILL BE DIFFERENT.

1. copy your recovery to

````
output/zip
````
and make sure it is named 
````
recovery.zip
````

2. Open the build script and adjust your variables.

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

3. Edit your changelog

````
gedit ./changelogs.txt
````

4. Run the build script

````
./build
````

5. Get your output file from

````
output/zip/presto.cwm.recovery.6.0.5.0.r2.082714-marduk191.zip
````

6. When ready to clean the old files up (including the one you just made)

````
./cleanup
````