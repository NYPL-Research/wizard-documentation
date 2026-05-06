---
layout: default
title: Uploader
parent: Actions for Devs
nav_order: 1
---

# Uploader
This tool does the following in order:
1. Creates a local MD5 file of hashes for all files in the folder
2. Runs JHOVE on all files in the folder
3. Runs BDCP Checker on all files in the folder (Bit Depth & Color Profile Checker)
4. Creates a QC folder and populates it with JPG derivatives at 3500px on the long side
5. Mirrors the input folder to the selected destination folder
6. Creates a server MD5 file of hashes for all files that were uploaded
7. Crosschecks the two MD5 files to verify if the file was uploaded without corruption
8. Creates a manifest that is served locally on Chrome for user to verify


## Use
### Server Upload:
- This tool is primarily used to upload files to the server for the QC process
- The MD5 files can also optionally be used by [Repo Depot](https://minasystemsnypl.github.io/wizard-documentation/docs/actions/repo_depot.html) to verify if files downloaded from the Repository are the exact same as those that were uploaded to the server
    - Simply drop the empty shell folder that was moved to `Moved_to_RTG`, and the action will find the MD5s and verify
