# SafeSocPi/Family Internet/Family Protect/Family Haven
A collection of scripts and chef cookbooks to initialise a Raspberry Pi as a Social Hub for your family that is able to filter content and runs chat bots to police chatrooms without parents having to spy on them.

PLEASE NOTE: The plan has evolved to use an old Android phone as the Mattermost server, this should provide a fairly power efficient server, and I can run the database off the Pi.  Therefore the web server and network related items will probably be run off the Android device also.

Currently working features:
-...;)

The plan is to have the following features:

1. 'ANDROID -' Implement a Mattermost chat server (Cannot be implemented on a 32bit arcitecture).
2. 'PI      -' Implement the Mattermost database server.

3. 'ANDROID -' Implement a social network that can be networked with other parents devices (possibly diaspora)
4. 'ANDROID -' Implement a Proxy server to filter innapropriate content from kids, this needs to be affective in and out of the home on all mediums, phone, laptop, etc.
5. 'EITHER  -' Implement bots to monitor the usage and report on it in a non intrusive way, preferably helping the children to learn safe online habits and helping them learn how to not put themselves or others at risk.
6. 'ANDROID -' Have a management interface web page to configure the device and navigate to the various functions on it.
7. 'ANDROID -' Schedule automatic pulls from git and updates (should be configurable through the management interface website).
8. 'ANDROID -' Configure a VPN to allow access to the internet though your home network.
9. 'BOTH    -' An installer that allows for the installation of some or all of the features `- CHEF roles and cookbooks`
10. 'ANDROID-' A way secondary Pis under a master Pi providing automatic port forwarding to features hosted on other Pis and having the management interface forward to other Pis too `- NGINX reverse proxy?`
11. 'PI     -' SSH reachable desktop machine.

As you might imagine, at some point I might find that my 2015 Raspberry Pi might fail to perform well under this load so as I develop these I will make notes on performance with all of the features running and whether I have to get a second Pi.  I'll also suggest mimimum system requirements, I'm expecting the need for an external hard disk for instance.

#Installation Instructions
1. Run `sudo apt-get install chef`
2. Create a Chef Manage organisation here https://manage.chef.io/ and download the starter kit.
3. From a terminal window run `unzip chef-starter.zip`
4. Run `mv chef-repo/.chef ~;mv chef-repo/cookbooks ~`
