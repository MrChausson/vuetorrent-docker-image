## vuetorrent-docker-image
*qBittorrentVPN Docker image with pre-installed VueTorrent webUI*

# Getting started #
1.  **docker-compose.yml**
    * Set VPN_USERNAME and VPN_PASSWORD
    * Set LAN_NETWORK to your subnet
    * Then Bind your "downloads" volume to wherever you want on the host (for example to /home/myuser/Downloads)
2.  **config/openvpn**
    * Place your .ovpn configuration file in that folder
###
# Finaly run **sudo docker build && sudo docker-compose up -d** to start the container #
