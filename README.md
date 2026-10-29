# Sync a twrp minimal manifest, patch it for building OrangeFox, and sync the OrangeFox sources

## To fetch the manifest for the first time, follow these steps: ##
------------------------------------

### 1. Fetch these sync tools ###
```
mkdir ~/OrangeFoxSync
```

```
cd ~/OrangeFoxSync
```

```
git clone https://github.com/xiaomi-klee-devs/android_sync.git manifest
```

### 2. Do the syncing (this can take up to 1-2 hours, and can use up to 40GB-80GB of disk space) - below is an example, for 14.1 (amend as required for other branches) ##
```
cd ~/OrangeFoxSync/manifest
```

```
./orangefox_sync.sh --branch 14.1 --path ~/fox_14.1
```

Notes:
- You *MUST* supply an *ABSOLUTE* path name for the "--path" switch
- If the sync process gets stuck, you might need to terminate it with Ctrl-C and then run the script again
- If you want to use ssh for cloning the OrangeFox sources and vendor tree, export "USE_SSH=1" before starting, or supply "--ssh 1" on the command line
- After the initial sync process, you must then clone your device trees, before you can build for your device
