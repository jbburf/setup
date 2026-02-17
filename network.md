# Network
I run a pi-hole on my network to block ads and trackers. I run it on a Raspberry Pi setup as the DNS server and DHCP server. Here are the steps to setup the pi-hole on the Raspberry Pi as well as details about my network.
* I setup a Raspberry Pi 3B Plus following [this guide](https://www.raspberrypi.com/tutorials/running-pi-hole-on-a-raspberry-pi/). I connect my Raspberry Pi directly to the router with an ethernet cable.
* For my main network I use [Asus Zenwifi](https://www.blacktubi.com/review/asus-zenwifi-ax-xt8/) with 4 mesh nodes. Assigning a static IP to my Raspberry Pi, setting a custom DNS address and disabling the DHCP server is fairly straightforward.
* I also run a second network that is not behind my pi-hole from a Netgear [Nighthawk R9000](https://www.smallnetbuilder.com/wireless/wireless-reviews/netgear-r9000-nighthawk-x10-smart-wifi-router-reviewed/).
