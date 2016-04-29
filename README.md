# ProgrammingPi

This repo is to place docs and code for raspberry pi programming

## Setup

1. class 10 tf card is a must-have or else you may encounter lots of iowait..
1. Following instructions on [pi official website](https://www.raspberrypi.org/help/noobs-setup/) to install OS
1. Having installed OS, install Chinese fonts and IME: `sudo apt-get install -y fcitx fcitx-googlepinyin fcitx-module-cloudpinyin ttf-wqy-microhei ttf-wqy-zenhei xfonts-wqy`
1. In case of keyboard laytout issue (I got one for '|'), following [this page](https://thepihut.com/blogs/raspberry-pi-tutorials/25556740-changing-the-raspberry-pi-keyboard-layout) to resolve
1. Install gvm: `sudo apt-get install -y bison &&  bash <<(curl -s -S -L https://raw.githubusercontent.com/moovweb/gvm/master/binscripts/gvm-installer)`
2. Instatall Golang: re-login to enable gvm then `gvm install  go1.4.3 && gvm use go1.4.3 && gvm install  go1.6.2`
