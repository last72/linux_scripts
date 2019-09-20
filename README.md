# linux_scripts


	1. torrentbox

    It install and configure samba and qbittorrent.

    Type

    ```
    curl -s https://raw.githubusercontent.com/last72/linux_scripts/master/torrentbox | sudo bash
    ```
    in to the terminal (require superuser account).


After install, the torrent needs to be downloaded under /torrent/Downloaded or /torrent

Connect the the server by typing smbclient //<serverIP>/tbox -U tbox

1.1 Sources

- Samba turorial
https://tutorials.ubuntu.com/tutorial/install-and-configure-samba#3

- Samba tutorial
https://www.digitalocean.com/community/tutorials/how-to-set-up-a-samba-share-for-a-small-organization-on-ubuntu-16-04

- Append to the file
https://stackoverflow.com/questions/6207573/how-to-append-output-to-the-end-of-a-text-file

- 5 torrent options
https://itsfoss.com/best-torrent-ubuntu/

- Install transmission
https://help.ubuntu.com/community/TransmissionHowTo

- Install qbittorrent
https://www.linuxbabe.com/ubuntu/install-qbittorrent-ubuntu-18-04-desktop-server

- Install qbittorrent
https://github.com/qbittorrent/qBittorrent/wiki/Setting-up-qBittorrent-on-Ubuntu-server-as-daemon-with-Web-interface-(15.04-and-newer)