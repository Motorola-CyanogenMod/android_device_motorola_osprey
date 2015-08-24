#Paranoid tree for Moto G (2015)
* Based off https://github.com/MotoG3/android_device_motorola_osprey

##Dependencies:
````
sudo apt-get install bison build-essential curl flex git gnupg gperf libesd0-dev liblz4-tool libncurses5-dev libsdl1.2-dev libwxgtk2.8-dev libxml2 libxml2-utils lzop openjdk-6-jdk openjdk-6-jre pngcrush schedtool squashfs-tools xsltproc zip zlib1g-dev
sudo apt-get install g++-multilib gcc-multilib lib32ncurses5-dev lib32readline-gplv2-dev lib32z1-dev schedtool libc6-i386 lib32stdc++6 lib32gcc1 lib32ncurses5 zlib1g lib32z1 lib32bz2-1.0
````
You also need the repo tool for cloning Android source trees.

Copy pa_config/pa_osprey.mk to vendor/pa/products/

then run ./rom_build.sh osprey

