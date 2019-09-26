# ICalendar Server

Quick Start

Reference: 
https://github.com/apple/ccs-calendarserver

Creating a directory to contain Calendar and Contacts Server and all its dependencies:
- [ ] mkdir ˜/Documents/GitHub/ICalendar/CalendarServer
- [ ] cd CalendarServer

Next, check out the source code from the GIT repository. To check out the latest code:
- [ ] git clone https://github.com/apple/ccs-calendarserver.git

Install the dependencies over Python
- [ ] sudo python -m ensurepip

Test configuration
- [ ] cd bin/
- [ ] ./run -n
Would you like to copy the test configuration now? [y/n] 
- [ ] y

Copying test cofiguration...
Keychain already unlocked

Starting server...
Reading configuration from file: ˜/Documents/GitHub/ICalendar/CalendarServer/ccs-calendarserver/conf/caldavd-dev.plist
Created directory: ./data/Data
Created directory: ./data/Data/Documents
Created directory: ./data/Logs
Created directory: ./data/Logs/state
The configured TLS Keychain Identity (Keychain: org.calendarserver.test) cannot be used: Unable to use private key for Keychain identity: org.calendarserver.test - The operation couldn’t be completed. (Internal CSSM error error -2147416032 - Internal error #80010820 at SignTransform_block_invoke /BuildRoot/Library/Caches/com.apple.xbs/Sources/Security/Security-58286.270.3.0.1/OSX/libsecurity_transform/lib/SecSignVerifyTransform.c:276)
