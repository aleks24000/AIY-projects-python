# Fork of AIY Projects

## Features

When pushing button (long) choose a language

When pushing button (short), speak french, speach translate to chosen language

When pushing one more time, speak chosen language, speach translate to french

## Make it work

sudo vi /etc/profile

 - add at the end

sh /home/pi/speach_google/launcher.sh >/home/pi/logs/cronlog 2>&1 &

 - put token file : 

/home/pi/cloud_speech.json

## Run in thonny

 - kill pulseaudio process
 - error at startup is non blocking
