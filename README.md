![screenshot_002](https://github.com/keree21/dwm/assets/102629278/767b364e-925a-4f88-be3d-306b92ba849f)

# dwm

My fork for suckless dwm, feel free to use it for your distribution.

Firstly, you will need to install xorg-server xorg-xinit libxft libxinerama kitty picom nitrogen unclutter xautolock xorg-xrandr unclutter.

Secondly, you will need to to git clone this repository:

cd /usr/local && git clone https://github.com/unikeree/dwm && cd dwm

From here you will need to go in each directory and apply sudo make clean install

After, you need to copy .xinitrc , Xresources to your /home/name/

Also, you will have to put your path in .xinitrc for dwm-bar 

move .xinitrc and .Xresources to /home/user/

Then you can enter your environment by using:

startx

Thats's it!
