# VidBack
Screenshot taker and video uploader via Discord webhook. 

## Requirements
>[!IMPORTANT]
>[7-Zip](https://www.7-zip.org/download.html)

## Upload Instructions

**Step 1:** Download, save and edit line 1 and replace "Discordwebhook" with your webhook and save it. 

>[!NOTE]
>You can change line 2 to anytime that is valid in your videos as long as it looks like "00:00:00". 

**Step 2:** run to get initial files and folders needed. Everything will be installed in "C:\Users\USERNAME\Videos\UClips".

**Step 3:** You can now add video files to the UClips folder.

>[!NOTE]
> These are the video file types currently supported: mp4, .avi, .mkv, .mov, .flv, .wmv, .mpeg

>[!IMPORTANT]
>**Items in UClips folder will be deleted after running!** To save space and keep clean. 

**Step 4:** Run the powershell and let backup happen. 
>[!NOTE]
>If the video file or files are over 24 MB they will be split into as many zip folders as needed and uploaded.
>
>Every video file gets a screenshot taken and uploaded before the zip folders are. 

## Download Instructions

**Step 1:** Download all folders to the same directory. 

**Step 2:** Right click "UClips-Folder.zip.001" and select 7-zip ➜ Open Archive.

**Step 3:** Drag and drop to directory of your liking.

>[!NOTE]
>You can add this powershell to your Stream Deck following the instructions below and removing <>.
>Show Powershell
>Select Plugin ▼System ➜ Open
>In the App/File field, enter:
>powershell <path to your script>\<your power shell script name>.ps1 'param1' 'param3' 'param3'
>
>Hide Powershell
>Select Plugin ▼System ➜ Open
In the App/File field, enter:
>cmd /c start /min "" powershell -WindowStyle Hidden -executionpolicy bypass -noninteractive <path to your powershell script>\<your power shell script name>.ps1 'param1' 'param3' 'param3'

## Legal
Powershells from this repository are provided for educational purposes only. Powershells from dag are intended for authorized auditing and security analysis purposes only where permitted subject to local and international laws where applicable. Users are solely responsible for compliance with all laws of their locality. Dag and affiliates claim no responsibility for unauthorized or unlawful use.

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
