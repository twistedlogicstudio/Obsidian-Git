#CasaOS #Homelab 

# CasaOS Homelab Fix

After trying over and over to re-install CasaOS - keep having issues with install apps inside Casa. Figured out it was a docker / docker-pull / docker connection issue. 

Re-installing over and over didn't work (both Casa & Rpi) 

But have finally figured *more-or-less* that it's a network issue, specifically something to do with the DNS / DHCP settings?

I played around with some of the settings here trying to set a static IP for the Rpi.
Probably fucked something up in the process.

Adjusting some of the settings in:

* dhcpcd.conf file - using:

```sudo nano /etc/dhcpcd.conf 

* adding in:

```nameserver 8.8.8.8
```nameserver 8.8.4.4

Finally got somewhat of a movement going with the app installs - but still ended with an error.

## NOTES
- [ ] I should try and see how a manual install of a docker container / app goes
* 

- - -
## SOME USEFUL RESOURCES

[RPi DNS Settings](https://pimylifeup.com/raspberry-pi-dns-settings/)
[IP Conflicts](https://www.linkedin.com/pulse/ip-address-conflict-docker-kuldeep-ranjan)
[Forums](https://stackoverflow.com/questions/48042184/how-to-solve-i-o-timeout-error-in-docker-pull)
[CasaOS Wiki](https://wiki.casaos.io/en/troubleshooting)
[Github](https://github.com/IceWhaleTech/CasaOS/issues/1299)
[Unread](https://www.simplilearn.com/tutorials/docker-tutorial/raspberry-pi-docker)



