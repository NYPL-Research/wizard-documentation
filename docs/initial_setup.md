---
layout: default
title: Initial Setup
parent: Home
nav_order: 3
---

## 📦 Initial Setup (Internal)

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

### 3. 
