# EternityOS #

Let Eternity Go Beyond....
===

Syncing the source
---

```
# Initialize local repository
repo init -u https://github.com/EternityOS-Plus/manifest -b 12.1

# Sync
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

Building the ROM
---

```
# Set up environment
$ . build/envsetup.sh

# Choose a target
$ lunch aosp_$device-userdebug

# Build the code
$ mka bacon -jX
```

Credits
---
* Pixel Experience
* Void UI
* LineageOS
* HavocOS
* and many others who helped this project...
