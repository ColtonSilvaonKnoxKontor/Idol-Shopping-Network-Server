# Idol Shopping Network's Server

Idol Shopping Network was the e-commerce platform launched in 2021 by TV personality and current senator Raffy Tulfo, featuring online marketplace for local businesses. It is now defunct and their domain address https://www.idolshoppingnetwork.com/ is now for sale.

<img width="447" height="447" alt="images" src="https://github.com/user-attachments/assets/089cee10-b2e0-4287-9fe5-0e2e142d838c" />


# Available server

Currently my server for Idol Shopping Network is active: https://isn.silvasystems.online, whereas my main website related for tarpits and honeypots is: https://silvasystems.online.

# Requirements:

You need to change the URL from it's client apk to point to your server as it requires experience in APK modding, unless you hijack the dns so that the url will redirect to your server which you don't have to modify the apk. Luckily you may download the ISN modified version which the URL points to my server.

I prefer debian-based Linux distribution to serve the backend for ISN

Must have domain name, cloudflared tunnel if you want to serve it locally and if you are behind ISP's CGNAT.

# Issues

As this is under development, the apk can crash if you select a product, as I'm trying to figure out some things in a decompiled code, so as to tune up the backend server to properly sync with the client.
