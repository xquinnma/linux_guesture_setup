# linux_guesture_setup
setup for linux touchpad guesture (debian based) 

sudo gpasswd -a $USER input

sudo apt-get install wmctrl python3 python3-setuptools xdotool python3-gi libinput-tools

# for libinput-gestures 
sudo make install 

# for gestures app 
sudo python3 setup.py install


libinput-gestures-setup autostart
libinput-gestures-setup start



