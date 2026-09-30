Omarchy VPN

Simple OpenConnect VPN script for Omarchy/Linux.

Installation

Copy the script to:

~/.local/bin/

Make it executable:

chmod +x ~/.local/bin/vpn

Edit the configuration:

nano ~/.local/bin/vpn

Set these values:

SERVER=""
USERNAME=""
PASSWORD=""

The script requires:

sudo pacman -S openconnect

Connect:

vpn

or:

vpn start
vpn connect

Disconnect:

vpn stop
vpn disconnect

Restart:

vpn restart

Check status:

vpn status

The script runs OpenConnect in the background, checks for the tun0 interface, and restarts NetworkManager after a successful connection.
