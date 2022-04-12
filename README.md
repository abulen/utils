# utils
Collection of useful bash scripts

## sync
Syncs source directory to destination directory/share while monitory source directory
and kills sync process if source directory disconnected

Requires: 
- rclone configured for sync process
<br />

    sync /mnt/cifs/source/share/ remote:destination/path

## convertFolder
Converts video files in current directory to web optimized MP4

Video: H264<br />
Audio: 2 Channel AAC<br />
Metadata: Title = filename


Requires:
- ffmpeg
- mediainfo 
<br />

    cd /path/to/video/files  
    convertFolder
