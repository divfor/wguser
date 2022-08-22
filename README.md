# wguser
script to create, delete, and list wg users for a server role.

INIT:
1. put all scripts on /usr/local/bin/ and make them executable;
2. edit /usr/local/bin/wguser's top lines to meet your enviorment;
3. first executing 'wguser add <username>' will be initilizing a directory of /etc/wireguard.

USAGE:
wguser add <username>
wguser del <username>
wguser list
wguser list | grep <peer_ip>
wguser list | grep <username>

enjoy.
