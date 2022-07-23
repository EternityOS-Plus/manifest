# EternityOS #
===============
Let Eternity Go Beyond....
---------------------------

### Sync ###

```bash

# Initialize local repository
repo init -u https://github.com/EternityOS/manifest -b 12.1

# Sync
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

### Build ###

```bash

# Set up environment
$ . build/envsetup.sh

# Choose a target
$ lunch aosp_$device-userdebug

# Build the code
$ mka bacon -jX
```

===============
Credits
===============
• Pixel Experience
• Void UI
• LineageOS
• HavocOS
 & other who helped to achieve project successfully..
