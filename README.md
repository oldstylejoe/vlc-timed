vlc-timed

Joe Snider
12/15

This fork of vlc has been modified to record frame display times and audio dts times on windows. Code was changed at the codec level (ffmpeg wrapper and avcodec), so it only works if those codecs are used.

Hacked in logging to directories c:\DataLogs\audio and c:\DataLogs\video.


