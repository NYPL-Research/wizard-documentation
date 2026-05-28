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
  - Setup config file destinations for your workflow by replacing the values <example> with real paths and values "example".
  - Config file looks like this:
  
```
{
    "database": {
        "host": "<ip_address>",
        "user": "<username>",
        "name": "<database_name>"
    },
    "network_mounts": {
        "repo": "<volume_mount_path>",
        "ice": "<volume_mount_path>",
        "admin_sync": "<path_to_admin_directory>"
    },
    "ice_paths": {
        "rtg_dest": "<path_to_rtg_folder>",
        "pants_root": "<path_to_Moved_to_RTG_folder>",
        "ice_repo": "<path_to_repo_volume>",
        "ice_deliverables": "<path_to_deliverables_folder>"
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
- Make sure to delete the default Admin user, once your user is set up. 
