# volume-notification-dunst
This script enables dunst (or any other notification daemon) to send traditional volume notifications (screenshots below).
Inspired by https://gist.github.com/sebastiencs/5d7227f388d93374cebdf72e783fbd6a

This differs from the one linked because it uses pulseaudio and doesn't require dunstify, thus making this useable with any notification daemon.

# installation
The script requires the faba icon pack to be installed (otherwise icons won't be displayed) and relies 
on this script (https://github.com/vlevit/notify-send.sh/blob/master/notify-send.sh), it has to be placed in the
same directory as volume.sh. This patched notify-send.sh is necessary because by default notify-send doesn't allow replacing existing notifications. To use the script place volume.sh and notify-send.sh in the same folder and either type in a terminal 

/path/to/volume.sh up            to increase the volume

/path/to/volume.sh down          to decrease the volume

/path/to/volume.sh mute          to mute the volume

Or bind the desired functionality to your key combination of choice.
# screenshots
<a href="http://i.imgur.com/IKpZvez.png">
  <img src="http://imgur.com/IKpZvezl.png" />
</a>

<a href="http://i.imgur.com/JrsExYe.png">
  <img src="http://imgur.com/JrsExYel.png" />
</a>
