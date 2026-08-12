OrangeFox Recovery  Unofficial Build for a52sxq

Version: R12.0_1
Device: a52sxq (Samsung Galaxy A52s 5G)

CREDITS
-------
- OrangeFox Recovery Project  original core source
  https://gitlab.com/OrangeFox

  (Note: this device is currently unmaintained by the original team)

WHAT WAS CHANGED
-----------------
The original device tree used a deprecated `FOX_VERSION` variable that 
is no longer supported by the latest OrangeFox core, causing build 
failures. This build patches `vendorsetup.sh` to use 
`FOX_MAINTAINER_PATCH_VERSION` instead, allowing successful compilation 
against the current OrangeFox source.

No other changes were made to the original device tree.

TESTED / WORKING
-----------------
- Boots successfully ✅
- Can read files on internal storage ✅
- MTP ✅
- ADB ✅
- Reboot menu ✅
- Backup ✅


STATUS / DISCLAIMER
--------------------
This is an UNOFFICIAL, community-patched build — not endorsed or 
tested by the OrangeFox Team. It has been personally tested and 
confirmed working as listed above, but is provided as-is with no 
warranty. Use at your own risk. Always back up your EFS/IMEI 
partition before flashing.

Patched by: ICECAT
Patch source: https://gitlab.com/icecatm7-lab/a52sxq (branch: fox_12.1)
