# Installation

```
sudo sh install.sh
```


# Modules

## Apps

QT application to monitor device log events:

```
app/android-dev-watcher-qt/
```

## udev

Scripts for udev resides in 'udev' directory.

## Logger

Scripts to handle udev events. Installed by install.sh.

## inotify

Scripts and application for inotify reside in 'inotify' directory.

Build inotify native application:

```
sh inotify/c-api/compile.sh
```

## USB

Scripts for USB resides in 'usb' directory.

## ADB

Scripts for Android ADB resides in 'adb' directory.

# Miscellaneous

Monitor udev registered events:

Less detail:
```
    udevadm monitor
```

More detail:
```
    udevadm monitor --property
```

