# SafeSocPi
A collection of scripts and chef cookbooks to initialise a Raspberry Pi as a Social Hub for your family that is able to filter content and runs chat bots to police chatrooms without parents having to spy on them.

Currently working features:
-...;)

The plan is to have the following features:

1) Implement a Mattermost chat server
2) Implement a social network that can be networked with other parents devices (possibly diaspora)
3) Implement a Proxy server to filter innapropriate content from kids, this needs to be affective in and out of the home on all mediums, phone, laptop, etc.
4) Implement bots to monitor the usage and report on it in a non intrusive way, preferably helping the children to learn safe online habits and helping them learn how to not put themselves or others at risk.
5) Have a management interface web page to configure the device and navigate to the various functions on it.
6) Schedule automatic pulls from git and updates (should be configurable through the management interface website).
7) Configure a VPN to allow access to the internet though your home network.
8) An installer that allows for the installation of some or all of the features.
9) A way secondary Pis under a master Pi providing automatic port forwarding to features hosted on other Pis and having the management interface forward to other Pis too.

As you might imagine, at some point I might find that my 2015 Raspberry Pi might fail to perform well under this load so as I develop these I will make notes on performance with all of the features running and whether I have to get a second Pi.  I'll also suggest mimimum system requirements, I'm expecting the need for an external hard disk for instance.
