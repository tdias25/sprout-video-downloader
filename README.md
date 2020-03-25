# sprout-video-downloader
generate a decoded m3u8 from an embeded sprout video url 

Usage:

this script uses puppeteer and it also needs to have flash enabled, so it's better to install google chrome on your machine and then edit the chrome executable location at 
"executablePath" in line 14.

after this it's pretty simple.
just call node downloader.js VIDEO_URL

in the VIDEO_URL it has to be the embed video page.

eg: 

https://videos.sproutvideo.com/embed/a09adbb51a1fe1c428/2e9125edb81231ce?signature=iWwb5PgXjilc08GrGpDwu%2Fj%2FUM4%3D&expires=1584907207&type=hd  

the script will generate a decoded m3u8 file, with this file you can download the video with any software that is able to read m3u8 files such as VLC, FFMPEG....
