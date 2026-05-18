# Gray Mountain - Mining Rig Setup
* XMRig Mining - Armbian CLI and Termux

## Patreon Sponsor -
* (Patreon / Medium / Substack):

[![Sponsor Binary Kore](https://img.shields.io/github/sponsors/binarykore?label=Sponsor%20Binary%20Kore&logo=github&style=for-the-badge)](https://github.com/sponsors/binarykore?frequency=patreon)


## XMRig Auto Script (Gray Mountain):
* https://redkrakensec.vercel.app
* HTTP Authentication via Short I/O and GitHub API or GitHub Gist -
* ACS / OTA (Over the Air - Updates)

## For Termux (Android Phones) -

## Note:
* It will heat up very quickly -

## Setup: 
* apt-get update -y --fix-missing
* apt-get upgrade
* apt-get install git
* apt-get install wget
* apt-get install proot
* apt-get install build-essential cmake libuv1-dev libssl-dev libmicrohttpd-dev libhwloc-dev -y
* git clone https://github.com/xmrig/xmrig gm
* cd ~/gm
* mkdir build
* cd build
* cmake -DWITH_HWLOC=OFF ..
* make

## For Orange Pi / Raspberry Pi / Banana Pi / Nano Pi / Rock Pi -

## Setup:
* apt-get update -y --fix-missing
* apt-get upgrade
* apt-get install git
* apt-get install wget
* apt-get install build-essential cmake libuv1-dev libssl-dev libmicrohttpd-dev libhwloc-dev -y
* git clone https://github.com/xmrig/xmrig gm
* cd ~/gm
* mkdir build
* cd build
* cmake -DWITH_HWLOC=OFF ..
* make

## Update -
* mkdir build
* cd build
* cmake ..
* make -j$(nproc)

## Auto Start Code:
* Soon (Service Daemon - Systemd) - System Daemon..

### Copyright (2023):

( C ) - [Binary Kore](https://github.com/binarykore), 09225205353
