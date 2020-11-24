# Dolby Atmos ZTE A2019 Pro Magisk Module

## Descriptions
- An EQ ported from ZTE A2019 Pro (P845A02)
- No dynamic partitions

## Tested on
- Redmi 4A (rolex) CRDroid Lineage based ROM Android 10 arm64-v8a

## Requirements
- Android 9, 10, or 11
- 64 bit
- Magisk installed

## Installation Guide
- Remove another Dolby module
- Reboot
- Install via Magisk Manager only
- Reboot

## Optional
- If using multiple audio mods, use one of these, don't use both:
  - AML 4.0 supported
  - ACDB supported (Android 10 and bellow only for now)
- You can rename dax-default extension to use more bass enhancer boost. See /data/adb/modules_update/DolbyAtmos/system/vendor/etc/dolby/. 

## Troubleshooting
- If SE policy patch doesn't work for your device, send logcats to dev, then try using force permissive method.
  Run at Terminal Emulator before flash:
  - `su`
  - `setprop dolby.force.permissive 1`
- If Dolby force close, just reinstall again
- Make sure manifest.xml is patched correctly
- Use Audio Compatibility Patch if you encounter processing problem

## Attention!
- Reporting without sending full logcats and magisk install logs is ignored! https://play.google.com/store/apps/details?id=com.dp.logcatapp

## Credits
- All people that helped and tested my modules
- dolby_dax.jar recompiled by @aip_x

## Groups discussion
- https://t.me/joinchat/E-On6U9cxckhIlAnoPIYpw
- https://t.me/@modsandco

## Donate
- https://www.paypal.me/reiryuki




           - Enjoy the Atmos 🎧 -
