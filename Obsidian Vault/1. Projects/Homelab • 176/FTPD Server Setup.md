#FTPD #Homelab #Networking
- - -

# FTPD / SFTP Server Connection Notes | Journal

>[!date] Sun 22/10/23

Tried to set everything up, and so far there wasn't really any issues. Some things to take note of though:

- - -
* **VSFTPD** 
  - install deleted some FTP modules for Open Media Vault (OMV)
  - checked and OMV doesn't seem to have broken or anything

- - -
* **FTP**
  - Connection seems to have worked ~ see the 'files' folder created, as well as seeing the folders / files when looking in file browser (CasaOS)
  - When trying to transfer files though I get error: *553 Could Not Create File*

- - - 
* **SFTP**
  - Connection seems to have worked just fine ~ though SFTP seems to have connected to the root of the Raspberry Pi volume
  - *devmon* mount points seems to not have anything
  - *mnt* mount points seems to have the top folder ~ though none of the contents seems to have loaded
  
 
