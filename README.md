# wguser
script to create, delete, and list wg users for a server role.

*init*
1. put all scripts on /usr/local/bin/ and make them executable;
2. edit /usr/local/bin/wguser's top lines to meet your enviorment;
3. first executing 'wguser add username' will be initilizing a directory of /etc/wireguard.

*usage*
1. wguser add username
2. wguser del username
3. wguser list
4. wguser list | grep peer_ip
5. wguser list | grep username

enjoy.
