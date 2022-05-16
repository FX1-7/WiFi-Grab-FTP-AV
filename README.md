-----------------------------------------------------
# Rubber Ducky WiFI Grab and Upload via FTP (UAC & Windows Defender deactivation included)


REM Title:         UAC, Windows Defender and WiFi Grab via FTP

REM Description    Disable UAC and download py script to disable Realtime and tamper protection, after this the ducky will grab alll wifi passwords the device has and upload them to an ftp server defined in the payload.

REM Author:        FX17

REM Version:       3.0

REM Target:        Windows 7/8/10/11

REM Attackmodes:   HID

—————————————————————————————————————————————————

Be sure to edit the .txt file lines 96, 99 and 102.

For example the script should look like:

96: `STRING 192.168.0.69 21`

99: `STRING FX17`

102: `STRING SecurePassword123!`


After these changes encode the script and upload to your ducky!

If you have any issues running this script, please contact me via discord: @Keiran1712

-----------------------------------------------------
