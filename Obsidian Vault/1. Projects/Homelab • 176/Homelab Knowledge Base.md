#Homelab #SmartHome #KnowledgeBase
 - - -

## Transmission • Torrenting
### external drive permissions

To download straight to an attached drive, I had to give permissions on the *Host Device.* 
Had to do it per-folder - unless I had messed something else up along the way.
ch
SSH into Homelab & run command:

`sudo chown -R admin:admin /media/devmon/ATTCHED-DRIVE-NAME`

Pulled from this Github forum:
https://github.com/transmission/transmission/discussions/5849


sudo chown -R admin:admin /media/devmon/TORRENT BOX