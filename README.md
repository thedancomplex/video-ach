video-ach
=========

Sending video over Ach

Ideas: http://stackoverflow.com/questions/18080588/how-to-setup-a-webcam-server-using-python

Send over ffmpg: 
ffmpeg -loglevel quiet -f v4l2 -i /dev/video1 -f h264 -preset ultrafast udp://hostip:port
ffmpeg -loglevel quiet -f video4linux2 -i /dev/video0 -f h264 -preset ultrafast udp://192.168.0.10:11000

ffmpeg.org config file: 
http://ffmpeg.org/sample.html

for video streaming: https://code.google.com/p/slyseal/
