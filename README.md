# Femboy Flooder

**Femboy Flooder** is a **Layer 7 HTTP flooding script** based on `livex`, supporting both **HTTP 1.0** and **HTTP 2.0**.  
The script is fully configurable and can be run with multiple options.  

---

## Features
- Supports **HTTP 1.0** and **HTTP 2.0**  
- Configurable **User-Agent selection**  
- Supports intervals, random query strings, and cookies  
- Customizable **threads**, **RPS (Requests per Second)**, and **delay**  
- Proxy support for anonymized requests  

---

### Usage

**Run HTTP 1.0 version with default settings:**
node "femboy_flooder - 1.0.js" https://example.com 60 10 64 proxies.txt

**Run HTTP 2.0 version with Windows User-Agent and random query string:**
- node "femboy_flooder - 1.0.js" https://example.com 30 5 32 proxies.txt --delay=100 --cookies=true

---

## Installer
1. Install Node.js: [https://nodejs.org](https://nodejs.org)  
2. Install project dependencies:
3. Install npm install randomstring colors minimist
