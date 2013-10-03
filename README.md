video-ach
=========

Sending video over Ach

Ideas: http://stackoverflow.com/questions/18080588/how-to-setup-a-webcam-server-using-python

Send over ffmpg: 
ffmpeg -loglevel quiet -f v4l2 -i /dev/video1 -f h264 -preset ultrafast udp://hostip:port
