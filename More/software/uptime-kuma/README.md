# Uptime Kuma

## Author & Contributers
| Name        | Github Profile  | Buy me a Coffee |
| ------------- |-------------|-------------|
|   gOOvER   | https://github.com/gOOvER | [![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/B0B351D0Q) |

## Description
Uptime Kuma is an easy-to-use self-hosted monitoring tool 
Egg is based on parkers generic nodejs egg

## Links
Github: https://github.com/louislam/uptime-kuma

## Admin & login
After installation and successful start, browse to your <ip>:<port> and setup the Admin.

## Server Ports

Uptime Kuma requires 1 port. You can choose any port you want

| Port    | default       |
|---------|---------------|
| default |     3000      |

## Cloudflared, Apprise & Chromium

The latest image provides support for Cloudflared and Apprise.

### Cloudflared
With Cloudflared it is possible to create a proxy over Cloudflare without having to use an nginx proxy. More info here:
https://github.com/louislam/uptime-kuma/wiki/Reverse-Proxy-with-Cloudflare-Tunnel

### Apprise
Apprise provides notifications for all kinds of services. Uptime Kuma has a built-in support for Apprise.
More info's here:
https://github.com/caronc/apprise#supported-notifications

### Monitor HTTP(s) - Browser Engine (Chromium) 
The image supports the monitor "HTTP(s) - Browser Engine". 
To use this monitor, enter the following path in the settings under "General -> Chrome/Chromium Executable" (at the bottom):

/usr/bin/chromium-browser