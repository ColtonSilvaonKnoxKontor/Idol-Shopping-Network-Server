# Idol Shopping Network's Server

Idol Shopping Network was the e-commerce platform launched in 2021 by TV personality and current senator Raffy Tulfo, featuring online marketplace for local businesses. It is now defunct and their domain address https://www.idolshoppingnetwork.com/ is now for sale. Because the ISN server went offline, this server emulator is written from scratch to implement the same function as the original ISN server.

<img width="447" height="447" alt="images" src="https://github.com/user-attachments/assets/089cee10-b2e0-4287-9fe5-0e2e142d838c" />

# Available server

Currently my server for Idol Shopping Network is active: https://isn.silvasystems.online, whereas my main website related for tarpits and honeypots is: https://silvasystems.online.

# Requirements:

You need to change the URL from it's client apk to point to your server as it requires experience in APK modding, unless you hijack the dns so that the url will redirect to your server which you don't have to modify the apk. Luckily you may download the ISN modified version which the URL points to my server.

**FOR HARDWARE:** Anything you like, from SBCs, PC, WorkStations or an actual server machines.

I prefer debian-based Linux distribution to serve the backend for ISN.

Must have domain name, as most of the domain registrar offers cheap .online, .asia. or others with less than $2 for 1 year offer. And you may install cloudflared tunnel if you want to serve it using your own computer and if you are behind ISP's CGNAT. If you don't want to purchase domain name and don't want to expose the server to internet, you can use local IP address.

NGINX/Apache cookers (config your own).

# Feature for now:

- A webmaster can add product and category list.

# To-do

- Add buyer and seller login system
- Direct customer support chat system to silvasystems server

# Issues

As this is under development, the apk can crash if you select a product, as I'm trying to figure out some things in a decompiled code, so as to tune up the backend server to properly sync with the client.
