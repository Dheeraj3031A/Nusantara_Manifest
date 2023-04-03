# Initialize Local Repository #
```bash
repo init -u https://github.com/Dheeraj3031A/Nusantara_Manifest.git -b main
```

# Syncing Repository # 
```bash
repo sync -c --force-sync --optimized-fetch --no-tags --no-clone-bundle --prune -j$(nproc --all)
```

# Lunch Command # 
```bash
mka nad -j
```
