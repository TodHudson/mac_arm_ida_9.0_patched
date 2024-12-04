# mac_arm_ida_9.0_patched
Patching IDA 9.0 Pro for Mac arm M1/M2

# Usage
Step 1: Go to /Applications/IDA Professional 9.0.app/Contents/MacOS/
Step 2: Change 2 file libida.dylib and libida64.dylib into .bak
Step 3: Copy 2 files *.dylib here to replace them
Step 4: run python file generate.py to make ida.hexlic
Step 5: Start IDA
Step 6: Browser to your file ida.hexlic and enjoy !

# Error
If you encounter the error like: Oops! internal error 30016 occurred.
- Go to /Applications/IDA Professional 9.0.app/Contents/MacOS/plugins/
- Backup file arm_mac_user64.dylib and replace with file from github
