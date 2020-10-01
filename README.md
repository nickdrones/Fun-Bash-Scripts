# Windows and Linux Bash
This is a small collection of bash program's I've either written on my own or followed a tutorial. Some of these are recent and written for a specific purpose, others were made when I was a kid and I was just messing around.

## cropcommand
This is a short bash script I made for my Raspberry Pi to use ffmpeg to perform the same crop on all mp4 files in a given folder. I downloaded Season 1 of Storm Chasers from the Discovery Channel website and noticed that only format they had was the 16:9 video slapped into a 4:3 frame, so I made this script to go through and crop the black bars off the top and bottom of the frame on the whole season.

## flac2mp3
Self-explanatory title. This script, also made for my Raspberry Pi, takes a directory full of .flac audio files and converts them all to .mp3 files

## locker.bat
If my memory is right, I made this script back in 2015 from a tutorial. When run, this script creates a folder called "Private". Then after putting files into that folder, you run the script again and the folder disappears. If you run the script again, it prompts you for a hard-coded password to unlock and reveal the "Private" folder again. All it does is simply changes the folder to be a hidden system file, effectively hiding it from view and not revealing it in searches.

## opener.vbs
Also made a while ago, this script simply loops every 5 seconds and calls the command to eject a user's primary optical disk drive tray. Not really used much anymore since optical drives are uncommon