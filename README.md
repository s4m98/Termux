# Termux

#------- HOW TO INSTALL KALI LINUX IN TERMUX WITHOUT ROOTED DEVICE -------#

First of all Install Install Termux Application on Play Store OR F-DROID Website
Website link Here:  

https://search.f-droid.org/?q=termux&lang=en

Now Chnage your termux repo by follwing command

$ termux-change-repo

You can see pop-us appear click OK

Select any Mirrors Repo  then --> OK 

Congres.....
your repo change successfully ....

#---- How To Install Kali-Linux in Termux ----#

First of all install wget in your termux by follow command:

$ pkg install wget

Now Copy this commands:

$ pkg install wget openssl-tool proot -y && hash -r

$  wget https://raw.githubusercontent.com/EXALAB/AnLinux-Resources/master/Scripts/Installer/Kali/Kali.sh

$  bash  kali.sh

Note: this should install Debian on your system, you can then run ./start-kali.sh to run the command line.
Remember: you will need to run ./start-kali.sh to run the command line.

$  ./start-kali.sh

BOOM.....



