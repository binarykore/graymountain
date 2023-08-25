# Gray Mountain - Mining RIG Setup
* XMRig Mining - Orange Pi CLI and Termux

## XMRig Auto Script (Gray Mountain):
* https://redkrakensec.vercel.app

## For Termux (Android Phones)

## Note:
* It will heat up very quickly:

## Setup: 
* apt-get update -y --fix-missing
* apt-get upgrade
* apt-get install git
* apt-get install wget
* apt-get install proot
* apt-get install git build-essential cmake libuv1-dev libmicrohttpd-dev libssl-dev -y
* git clone https://github.com/xmrig/xmrig
* cd xmrig
* mkdir build
* cd bulid
* cmake -DWITH_HWLOC=OFF ..
* make

## For Orange Pi One:

## Setup:
* apt-get update -y --fix-missing
* apt-get upgrade
* apt-get install git
* apt-get install wget
* apt-get install git build-essential cmake libuv1-dev libmicrohttpd-dev libssl-dev -y
* git clone https://github.com/xmrig/xmrig
* cd xmrig
* mkdir build
* cd bulid
* cmake -DWITH_HWLOC=OFF ..
* make

## Auto Start Code
* Soon..
