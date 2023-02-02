---
layout: default
title: QA Glossary - Letter L
description: This is just Letter L
---
### Logcat (Android) 
- a command-line tool that dumps a log of system messages, including stack traces when the device throws an error and messages that you have written from your app with the Log class.
- Android Studio > Settings > Tools > Logcat
- https://developer.android.com/studio/debug/logcat

- via terminal (Mac): check the logcat for "Sync success=" string.
```
adb logcat | grep "Sync success="
```

- put the logs in a file with the name languageChange01 as txt (or log)
```
adb logcat -c
adb logcat > languageChange01.txt
```
***
[back](./)