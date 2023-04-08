## New Version of HTTP Browser

This is a new version of the HTTP browser script that can be used to bypass DDoS protections

### Installation

Before you can use the script, you'll need to install Node.js on your system

```shell
curl -sL https://deb.nodesource.com/setup_16.x | sudo bash -
sudo apt -y install nodejs
npm install puppeteer-extra puppeteer-extra-plugin-recaptcha puppeteer-extra-plugin-stealth
apt install chromium-browser -y
```

### Usage

node golang_engine.js https://website.com proxy.txt 1200 20 GET 64

The `proxy.txt` file should contain a list of HTTP proxies to use in the attack

Note that you'll also need to change the 2captcha key in the `golang_engine.js` file to your own API key.

### Disclaimer

This script was created by Ch2k1t3 for StresserUS
