# Idol Shopping Network's Server

Idol Shopping Network was the e-commerce platform launched in 2021 by TV personality and current senator Raffy Tulfo, featuring online marketplace for local businesses. It is now defunct and their domain address https://www.idolshoppingnetwork.com/ is now for sale. Because the ISN server went offline, this server emulator is written from scratch to implement the same function as the original ISN server.

<img width="447" height="447" alt="images" src="https://github.com/user-attachments/assets/089cee10-b2e0-4287-9fe5-0e2e142d838c" />

# Available server

Currently my server for Idol Shopping Network is active: https://isn.silvasystems.online, whereas my main website related for tarpits and honeypots is: https://silvasystems.online.

# Screenshots:

<img width="720" height="1600" alt="Screenshot_20260828-222600" src="https://github.com/user-attachments/assets/ca071d01-6650-4a62-9a5f-394041c160f4" />
<img width="720" height="1600" alt="Screenshot_20260828-222553" src="https://github.com/user-attachments/assets/8bac6874-abf0-4e32-8048-67fafaf0cb41" />


# Requirements:

You need to change the URL from it's client apk to point to your server as it requires experience in APK modding, unless you hijack the dns so that the url will redirect to your server which you don't have to modify the apk. Luckily you may download the ISN modified version which the URL points to my server.

**FOR HARDWARE:** Anything you like, from SBCs, PC, WorkStations or an actual server machines.

I prefer debian-based Linux distribution to serve the backend for ISN.

Must have domain name, as most of the domain registrar offers cheap .online, .asia. or others with less than $2 for 1 year offer. And you may install cloudflared tunnel if you want to serve it using your own computer and if you are behind ISP's CGNAT. If you don't want to purchase domain name and don't want to expose the server to internet, you can use local IP address.

NGINX/Apache cookers (config your own).

# Language used:

The only backend that runs the server emulator is PHP and SQLite for database, as it is lightweight and fast.

# Feature for now:

- A webmaster can add product and category list.
- Add buyer and seller login system
- Direct customer support chat system to silvasystems server

# Todo

- Mock ordering, payment and delivery system
- Seller account system and have ability for seller to add their product.

# Issues

As this is under development, the apk can crash if you select a product, as I'm trying to figure out some things in a decompiled code, so as to tune up the backend server to properly sync with the client.

# Where is the source code?

For now, only category and product list is available into the codebase. The login system, add to cart and purchasing system is under development.

# Disclaimer and Legal Notice

Refer at [this page](/DISCLAIMER.md).

================================================================================

MANDATORY NOTICE: PLEASE READ BEFORE DOWNLOADING, CLONING, OR RUNNING THIS CODE

By accessing, downloading, cloning, or using any part of this repository (including
the server emulator source code, database schemas, and modified APK binaries), you
expressly acknowledge and agree to the following terms:

1. STRICTLY FOR RESEARCH & PRESERVATION ONLY:
   This project is an independent educational and historical software preservation
   sandbox. It is NOT for commercial use and has NO connection to the original
   trademark holders.

2. ZERO REAL MONETARY VALUE:
   All wallet balances, orders, products, COD transactions, and phone numbers are
   100% simulated dummy data with ZERO cash value.

3. STRICT PROHIBITION AGAINST ILLEGAL USE:
   You are strictly forbidden from deploying or modifying this project for:
   - Scams, phishing, identity theft, or deceptive commercial schemes.
   - Any activity violating Republic Act No. 10175 (Cybercrime Prevention Act),
     RA 12010 (Anti-Financial Account Scamming Act), or applicable local laws.

4. USER RESPONSIBILITY & DISCLAIMER:
   The author assumes zero liability for any third-party misuse of this code. If you
   deploy this server, you do so entirely at your own risk and responsibility.

-> You MUST read the full legal terms and compliance notes in DISCLAIMER.md before
   installing or running this server. If you do not agree, you are not authorized
   to use this project.
================================================================================
