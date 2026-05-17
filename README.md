# Gray Mountain - Mining Rig Setup
* XMRig Mining - Orange Pi CLI and Termux

## Patreon Sponsor -
* (Patreon / Medium / Substack):

[![Sponsor Gray Mountain](https://img.shields.io/github/sponsors/binarykore?label=Sponsor%20Binary%20Kore&logo=github&style=for-the-badge)](https://github.com/sponsors/binarykore?frequency=patreon)


## XMRig Auto Script (Gray Mountain):
* https://redkrakensec.vercel.app

## For Termux (Android Phones) -

## Note:
* It will heat up very quickly -

## Setup: 
* apt-get update -y --fix-missing
* apt-get upgrade
* apt-get install git
* apt-get install wget
* apt-get install proot
* apt-get install build-essential cmake libuv1-dev libmicrohttpd-dev libssl-dev libhwloc-dev -y
* git clone https://github.com/xmrig/xmrig
* cd xmrig
* mkdir build
* cd bulid
* cmake -DWITH_HWLOC=OFF ..
* make

## For Orange / Raspberry / Banana Pi -

## Setup:
* apt-get update -y --fix-missing
* apt-get upgrade
* apt-get install git
* apt-get install wget
* apt-get install build-essential cmake libuv1-dev libmicrohttpd-dev libssl-dev libhwloc-dev -y
* git clone https://github.com/xmrig/xmrig
* cd xmrig
* mkdir build
* cd bulid
* cmake -DWITH_HWLOC=OFF ..
* make

## Auto Start Code:
* Soon (Service Daemon - Systemd)..

### Copyright (2023):

( C ) - [Binary Kore](https://github.com/binarykore), 09225205353
