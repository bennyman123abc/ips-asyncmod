ips-asyncmod v1.0
===========
A Python 3 module and a CLI program to apply and create IPS patches.
Forked from ips.py by fbeaudet

__Usage__

__NOTE: CLI Functionality is and will remain untested officially.__
As a CLI program :
```bash
   ips apply path/to/original/file path/to/patch path/to/new/file
   ips create path/to/original/file path/to/modified path/to/new/patch
   ips help
```
* patch files can be .ips or .gzip


As a Python module :
```bash
   import ips
   import asyncio

   await ips.applyPatch(original, patch, newFile)
   await ips.createPatch(original, modified, newPatch)
```

__What's an IPS patch ?__

A popular format for retro game ROM hacks
* http://zerosoft.zophar.net/ips.php
* http://www.romhacking.net/translations/

__Tests__

The tests have been removed in this version of ips-asyncmod
