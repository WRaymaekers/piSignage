#[](https://dl.dropboxusercontent.com/u/166564018/banner%20large.png) PiSignage- Digital Signage For All 
========
###Smartphone controlled Digital Signage
________

###What is PiSignage? 

PiSignage is a HD capable Digital Signage Player based on standard and off-the-shelf 
components. It connects to TV via HDMI port and can even turn on/off your TV! 
PiSignage is powered from any standard USB source. It is based on credit-card sized 
Raspberry Pi computer(Model B/B+/pi2) and completely solid-state. 

PiSignage can be controlled by connecting it directly to your Smartphone, or over a local 
wi-fi network from any Browser or by a Central server. 

Deployment is just a few steps. Upload pictures/videos from your smartphone, sync files 
from the central server, create notices from the available templates or even source content 
from your Social feeds! Control the order of play by simple drag and rearrange and 
optionally configure the duration of each asset. 

PiSignage decides what to play next based on the files present in the player and the playlist 
configuration. Hence it is very versatile to manage! Software can be remotely upgraded 
and has built-in features for resiliency. 

To control large number of players, create groups and assign players. Deploy playlists to 
groups. PiSignage will automatically sync and start playing the new content. You can still 
micro-manage individual players using Smartphone or Browser.

Interested? please drop an email to pisignage@ariemtech.com to know more.

### Benefits of PiSignage 
#### Affordable, Intelligent 
- HD capable Player based on off-the-shelf Raspberry Pi , a credit-card sized computer
- 100% Solid-state, low foot-print, USB powered - Modular Software built upon state-of-the-art mobile, server and sync technologies 
- Resilient Software decides what to play next based on content and playlist settings, auto upgrade, preserves 
state after power recycles 

#### Control from your Smartphone or any Browser 
- Multiple options for connectivity - Direct USB, Ethernet, Wi-Fi or over Internet from Server 
- Upload videos/images, Create notices and Edit Playlists from your mobile or browser 
- Configure and monitor PiSignage at feature level, turn on/off TV 

#### Create Content with ease 
- Upload videos/images from your phone or browser - Create Notices and Messages with the available templates 
- Sync Content from Central Servers, PiSignage seamlessly syncs content across Networks and Locations 
- Create feeds from your Social channels, web resources, Enterprise Servers or even Google Calendars

##Basic Setup (Recommended)

To use pisignage, [download](https://dl.dropboxusercontent.com/u/166564018/pisignagepro.img.zip) the pisignagepro platform image from pisignage.com and boot your pi. Register your player-id on www.pisignage.com.
Start your free trial now! Get in touch with us at pisignage@ariemtech.com, if you need any assistance. 
Here is more detailed [document on Basic setup](https://dl.dropboxusercontent.com/u/166564018/PiSignage_Basic_setup.pdf).

```
$ wget https://dl.dropboxusercontent.com/u/166564018/pisignagepro.img.zip
$ unzip pisignagepro.img.zip
```
###For MAC

Download [Apple pi Baker](http://www.tweaking4all.com/hardware/raspberry-pi/macosx-apple-pi-baker/)

Or use

diskutil list and find out your sd card to be programmed.
```
$ sudo dd bs=1m if=pisignagepro.img of=/dev/rdiskX 
```
###For Windows
Use [Win32DiskImager](http://sourceforge.net/projects/win32diskimager/) utility in administator mode to bake the image to sd card.

### More Info on image Installation refer following link 

[Installing Pi Images](http://www.raspberrypi.org/documentation/installation/installing-images/README.md)

#### If you want prebuilt pisignage image, email us to order an 8GB/16GB micro SD card with low profile adaptor. 
### FAQ
[Refer our WiKi for more information and FAQ](https://github.com/ariemtech/piSignage/wiki) 
### Issues?
Raise your [issues here.](https://github.com/ariemtech/piSignage/issues) 

## Advanced Setup 
We recommend using basic setup. For "advanced" users with raspbian SD card, refer following instructions. In case of difficulty do get in touch with us.  

Use raspi-config and configure username: pi password:pi

Connect keyboard and issue the commands on local terminal, instead of using ssh.
```sh
$ wget http://pisignage.com/releases/pi-image.zip

$ unzip pi-image.zip

$ mv piImage piSignagePro

$ cd ~/piSignagePro/misc

$ . install.sh  >/home/pi/install.log  2>&1
```
#### take a coffee break ...

#### Next steps.
1. Boot your pi-player
2. Signup on www.pisignage.com
3. Register the player id from player screen.
4. Upload assets
5. Create playlist
6. Assign the playlist and Deploy it to groups.
7. To locally manage the pi players using smartphone, download pisingage [android-app](https://play.google.com/store/apps/details?id=com.ariemtech.pisignage) 
8. Pi-Players, can be managed using [chrome-app](https://chrome.google.com/webstore/detail/pisignage-discovery-remot/fngfhanhnojhlclbokgllbejdhnajedo) too


###Backed by Ariem Technologies 

Ariem Technologies incorporated in 2007, conceptualised, developed and marketed connected TV 
products for Education, Banking and Home markets. Ariem is focussed and has expertise in the area 
of Web Technologies, Android/Linux and Connected Devices. We are a small passionate group of 
engineers and love to apply technology to solve real life problems. Please visit www.ariemtech.com 
for more details.


##Get in Touch

# pisignage@ariemtech.com
OR 
Vinay @ +91-9379844799 

