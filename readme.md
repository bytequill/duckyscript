[![wakatime](https://wakatime.com/badge/user/018d4fc2-0fac-485b-aeae-4960f02ed0a6/project/018da435-6f7e-40a4-af7f-f98cc55a0d18.svg)](https://wakatime.com/badge/user/018d4fc2-0fac-485b-aeae-4960f02ed0a6/project/018da435-6f7e-40a4-af7f-f98cc55a0d18)
# DuckyScript 3.0 collection
A collection of personally written scripts for the DuckyScript framework.
For personal learning and utility

## Install browser extension - Windows
- Description: Install a browser extension of your choice in Chrome/Edge/Firefox.
- Target: Windows Chrome/Edge/Firefox
- Usage:  
For each `[browser]_ENABLED` set to `TRUE` or `FALSE`  
Then set `[browser]_EXT_URL` to the URL of the adequate webstore. eg: `addons.mozilla.org/en-US/firefox/addon/ublock-origin/` for `Ublock origin` on `Firefox`

# Loot
## Wlan storage exfil
- Description: Exfil wlan SSID:password pairs and MacAddress
- Target: Windows Powershell
- Usage:  
Set `#DRIVENAME` to your ducky partition label. By default set to `DUCKY`.
- Exfil format:  
`[HOSTNAME]` (filename)
```
01-23-45-67-89-AB
SSID:password
WiFiWithNoPassword:
```