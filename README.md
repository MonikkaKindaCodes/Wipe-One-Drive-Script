# Wipe-One-Drive-Script
Bash Script used to close and remove one drive from the Applications folder. 


  
#!/bin/sh

# This Script is used to kill OneDrive and delete it from the applications folder

pkill -a -i "OneDrive"

rm -rf /Applications/Microsoft\ OneDrive.app

echo "OneDrive has been closed and deleted"

echo ""
