# Magisk-iOS-Emoji
Systemlessly replaces emoji font with iOS Emoji 

## Changelog
v16.4
- Added 16.4 Emojis
- Fixed Typo

v15.4.6
- Added Android 12 Support
- Fixed typo on extraction 
- Added Android 13 Support

v15.4.5
- Removed method to replace Google Keyboard emoji as it was conflicting with other apps settings.

v15.4.4
- Forgot to add the xml file to the module
- Fixed typo

15.4.3
- Merged the normal module and the Samsung module into one
- Fixed a directory path that was wrong on the install file
- Added compatibility for other devices like LG and HTC

15.4.2 
- Added method to potentially completely replace Google Keyboard Emojis
- Testing updater.json directly from the Magisk Manager

15.4.1
- Added updater json for the ability to update directly from the Magisk Manager
- Cleaned code a bit

15.4
- Added 15.4 Emojis

14.6
- Added 14.6 Emojis
- Added method to replace Facebook and Facebook Messenger App's Emojis

14.2
- Added 14.2 Emojis
- Fixed a naming error on Samsung Devices

## Changelog for emojis
[16.4 new emojis](https://blog.emojipedia.org/ios-16-4-emoji-changelog/)

[15.4 new emojis](https://blog.emojipedia.org/ios-15-4-emoji-changelog/)

[14.6 new emojis](https://blog.emojipedia.org/ios-14-6-emoji-changelog/)

[14.2 new emojis](https://blog.emojipedia.org/ios-14-2-emoji-changelog/)

## Tested on
- OnesPlus 8T (A13)
- OnePlus 6
- Reported working by user tkj94 on OnePlus 11 (OxygenOS - CPH2449 - A.09)
- Reported working by user clickkz on OnePlus 10 Pro (Oxygen OS 13.1)
- Reported working by user mrjshzk on Redmi Note 10 Pro (A13/AOSP)
- Reported working by user phlexian on S22Ultra (OneUI 5.0 - S908B)

## Troubleshooting 
If it doesn't work delete all files under /data/font/files/(Random folder name)