Fully tested on Debian stable 2024.
requires yt-dlp and total size.

yt-dlp: git clone https://github.com/yt-dlp/yt-dlp.git
totalsize: git clone https://github.com/theychx/totalsize.git

This script allows you to download video and audio from 
Youtube and 100's of other known sites and unknown sites.

        - For a complete list, see the yt-dlp docs

This script allows you to download media from your YouTube
channel using cookies from your browser (default is Firefox)

        - You MIGHT need a browser extension such as 
          "cookies.txt" to make your cookies accessible.

The current download options are "video file", "audio file", 
"video playlist", and "audio playlist".

Playlists are numbered in order.
Playlists skip over already existing downloaded files.

Two other options are to check download size and and update.

        - Checking download size uses the Python script 
          "totalsize" which could be unstable, and only gets 
          the size of videos and playlists (not audio).

        - The update function calls yt-dlp to update, if 
          that fails, it updates the local yt-dlp git 
          repo (adjust the file path to fit your system)
