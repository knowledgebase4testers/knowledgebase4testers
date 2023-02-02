---
layout: default
title: QA Glossary - Letter A
description: This is just Letter A
---

### Acceptance testing: 
- Formal testing conducted to enable a user, customer, or other authorized entity to determine whether to accept a system or component. [IEEE], user acceptance testing 

### Accessibility testing 
- [gDoc]

### Actual outcome: 
- The behaviour actually produced when the object is tested under specified conditions.

### adb (Android Debug Bridge) 
-  is a command-line tool that lets you communicate with a device.
```
adb install path_to_apk
```

- Check the device ID (command to get the list of emulators or devices connected to the machine)
```
adb devices
./adb devices
```

- Ceck Device serial number

    Option A
```
On phone or tablet navigating to “Settings > About Phone > Status”.
```
    Option B
```
adb get-serialno
```

- Install/Uninstall Apps
```
adb install "path/to/file.apk"
adb uninstall <package-name>
```

- pull logcat (parameter -c will clear the current logs on the device.)
```
adb logcat -c  
```
- Save the logcat output to a file on the local system.
```
adb logcat -d > [path_to_file] 
```

- dump the whole device information like dumpstate, dumpsys and logcat output.
```
adb bugreport > [path_to_file] 
```

- Start or Stop ADB Server
```
adb start-server
adb kill-server
```

- Flashing a device with the following cmds
```
adb devices
adb root && adb remount &&
#adb wait-for-device &&
aae flash 2s 7639102
#aae flash --yes birdy-img-7639102.zip 2s
```

- Take a screenshot on the device and place the file on your computer
```
adb shell screencap /sdcard/screenshot.png
```

### ad hoc testing: 
- it is a form of a black box or behavioural testing performed without any formal process in place. 						
- Mainly done with the aim of trying to uncover defects which cannot be captured through traditional or formal processes followed during the testing cycle. 		
Testing carried out using no recognised test case design technique.
In real life you get request from the PM or developer to check how bad a bug is or how good the fix.

    **Weakness**
        - not being able to recreate defects in the subsequent attempts if asked for information.

    **effort accountability**
        - Since this is not planned/ structured, there is no way to account for the time and effort invested in this kind of testing.
has to only be performed by a very knowledgeable and skilled tester in the team as it demands being proactive and intuition in terms foreseeing potential defect ridden areas.

### Agile
- software development methodologies based on iterative development, where requirements and solutions evolve through collaboration between self-organizing cross-functional teams. Agile is a time-boxed, iterative approach to software delivery that builds software incrementally from the start of the project, instead of trying to deliver it all at once near the end. It works by breaking projects down into little bits of user functionality called user stories, prioritizing them, and then continuously delivering them in short two-week cycles.

### Alpha testing: 

- Simulated or actual operational testing at an in-house site not otherwise involved with the software developers.

### ANR (Application Not Responding): 
- An ANR error is triggered, when the UI thread of an Android app is blocked for too long. 

### API (Application Programming Interface)
- A software intermediary that allows two applications to talk to each other

### API testing  
Types:
1. ‍Unit testing (automatically run with every build of the application.)
2. Integration Testing.  
3. Performance testing. 
4. Load testing. 
5. Runtime error detection. 
6. Security testing. 

### Appium 
- Selenium's mobile analogue, 
- Used for mobile UI automation.

### Assurance: 
- Grounds for justified confidence that a claim has been or will be achieved.

[back](./)
