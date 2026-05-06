---
layout: default
title: Initial Setup
parent: Home
nav_order: 3
---

## 📦 Initial Setup

### 1. You will be prompted to enter credentials to initialize setup
  - Enter default password `W1z@rd` for setup user `Admin`
### 2. Config File
  - Setup config file destinations for your workflow
  - Config file looks like this:
  
```
{
    "database": {
        "host": "xx.xxx.xxx.xxx",
        "user": "xxx",
        "name": "xxx"
    },
    "network_mounts": {
        "repo": "volumeMountPath",
        "ice": "volumeMountPath",
        "admin_sync": "pathToWizardAdminDirectory"
    },
    "ice_paths": {
        "rtg_dest": "/Volumes/xxx/rtg",
        "pants_root": "/Volumes/xxx/xxx/Moved_to_RTG",
        "ice_repo": "/Volumes/xxxx",
        "ice_deliverables": "/Volumes/xxx/Deliverables"
    }
}
```

### 3. New Admin User Setup
- Once you are in the app and you have confirmed your config file is in the correct location on your local machine, and that your admin_sync is pointed to the correct directory on the server, you can create a new user.
- Enter admin mode by clicking the user badge at the top left of Wizard.
    - Enter the default credentials `Admin` and `W1z@rd`
- Navigate to the bottom of Wizard and find User Admin
    - Enter password again
- Click Add Staff and then fill out the table, making sure to select Admin in the Role dropdown.
    - Make sure your email is correct, as this will be key in recovering your password if you forget it.
