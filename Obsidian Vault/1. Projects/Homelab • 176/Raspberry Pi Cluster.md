#Homelab #Rpi 
- - -
# Raspberry Pi Cluster Build Plan
Firstly the main reason as to why I'm doing this is because having run literally everything off of the single Pi before worked for a while but once issues do arise, it puts out the whole system. With the PLEX media server this is not ideal.

So first of the plans is to plan out the different things needed for the Homelab setup, and with that, which ones can be paired up together.

# Homelab Systems
## PLEX Media Server
- Obviously this one should be left completely on its own, to minimise situations where other systems knock it out.
- But also to remember ~ once you've got the other systems setup (especially the TORRENT BOX) you'll probably want to setup something where you can automate the torrenting system with containers like: *Sonarr, Radarr, Lidarr, Prowlarr, Readarr, Couch Potato & Jacket*
## Homebridge Server | Home Security System
- Definitely need to get the Homebridge Sever back up & running, all of the devices that aren't native to Homekit, are literally useless right now ~ this one also really needs to be separated by itself, I'm pretty sure that I completely messed up the install because of messing around with too many apps / network settings on the previous Pi.
- Apparently Homebridge doesn't use too much resource ~ so can definitely do for a cheaper option for this one
- *Raspberry Pi Zero 2 W, Raspberry Pi 4B 4GB*
## Pi-Hole | NGINX | AdGuard | VPN
- The idea behind Pi-Hole is super dope so ~ having an Ad Blocker thats seperate to everything + the way that it blocks ads (DNS Server) looks like it wouldn't cause issues with platforms trying to force ads.
- One thing to definitely be wary of though is how messing with network settings, especially DNS settings has caused a lot of issues before ~ so much like the others:
  - Have this seperate to the others, and have each device that needs Pi-Hole change its settings specifically
- *Nginx, Cloudflare & VPN Servers* ~ this seems like it's the main way to get Remote Access working for LAN storage drives, etc.
## Docker Container | VM Server | Remote Access Computer
- This one is less of a priority but would be cool to have, plus if there was a way to have the remote PC & the VM's sync my notes with the Macbook as well (probably through Git, & Github).
- Other than that, would be a cool & easier way to get into different Linus Distro's as well as learning more about that.
  - With Virtual Machines, this one might need something a little more powerful unfortunately ~ see if Davo would want to donate his old PC for this / But also figure out wether a donated PC would be better for a HomeNAS.
    - If not Davo's PC then maybe something like an Intel NUC or something similar.
- *Ubuntu Server & Desktop, NixOS* ~ *Intel NUC, Recycled PC, Server / Rack-mounted PC*
## Torrent Box
- Having a space seperate of everything local, especially the MacBook, where most of my work is done ~ is essential.
- This also helps that the torrents can keep downloading even when the MacBook is out the house / network
- *Deluge ~ looks like the #1, Transmission*
## HomeNAS | Remote Storage & Backup
+ Setting this up is going to prove to be the most difficult of the Homelab projects I think.
+ I'll need to research into different ways I can get this done, maybe put easier ones into place as the bigger NAS projects are being worked on
+ As far as I know thus far ~
  1. NextCloud seems to be the eaiest
  2. Then maybe something like a VPN with OMV
  3. TrueNAS seems like the most involved ~ TrueNAS needs a seperate drive on its own just to boot
  4. Will be worth it to look into other options as well ~ PydioCells, check Network Chuck YT Video - he has one using Amazons system
+ *NextCloud, Pydio Cells, TrueNAS, Open Media Vault*

