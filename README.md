# OctoryConfigMaker

Hopefully some day this script will write a script that can configure Octory.

This is a test

```bash
rebootList="/Users/plannc/Desktop/scripts/Paperspace/vmsToStart.txt"

while read VMName
do
	paperspace machines start --machineId "$VMName"
	echo "Starting VM "$VMName""
done < "$rebootList"
```
