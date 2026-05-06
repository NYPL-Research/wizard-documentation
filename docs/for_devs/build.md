---
layout: default
title: Build
parent: For Devs
nav_order: 9
---

# Build
Wizard uses a custom build script, `build.sh` to build the app bundle. This is in order to bypass the macOS security that prevents unknown/unverified/not-on-app-store apps from running. 

Since Wizard is meant to be strictly in-house, there is no need to get an Apple Developer's License to sign the app build the normal way.

To build the app bundle, run these in the CLI:
```
cd ~/YourPathTo/Wizard 
venv/bin/activate
./build_wizard.sh
```