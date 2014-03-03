#Installing ZPanel

#Before installing ZPanel...

...you NEED to ensure the following requirements are all OK:

NOTICE: We only support default installs of ZPanel (the way it is installed by the official installers). The main reason for this is that when we roll out the next update, everything will go smoothly. If you customize your install, the chances of your ZPanel failing are increased because you have changed things.

NOTICE: Currently you can NOT re-install ZPanel over an existing installation to try and fix errors! You can only update. (Although, we are working on new installers that will be able to install, update and repair ZPanel.)

NOTICE: ZPanel DOES NOT use or work with Nginx! You can try if you want, but we do not support it!

Fresh install of the OS with minimal options. The following modules MUST NOT be installed on your server:

    MySql
    Apache
    Bind
     
    Dovecot (Ubuntu, CentOS)
    Postfix (Ubuntu, CentOS)
    proFTPd (Ubuntu, CentOS)
     
    hMail Server (Windows)
    FileZilla Server (Windows)
    IIS (Windows)

#Officially Supported OSes

#Officially supported installers are available for Ubuntu 12.04 LTS, CentOS 6.4 and Windows in our ZPanelX Guides & How-To forum section.
Other Unsupported OSes

#Ubuntu 12.04 LTS based 
(server version) (desktop version please dot not use network-manager use networking)

These OSes are unsupported (which means that they can't be labeled as "official" but still work with ZPanel)

    Lubuntu 12.04 LTS
    Xubuntu 12.04 LTS
    Mythbuntu 12.04 LTS
    Zorin OS Core 6
    Anything based on Ubuntu 12.04 LTS

#CentOS 6.4 Based

These OSes are unsupported (which means that they can't be labeled as "official" but still work with ZPanel)

    Scientific Linux
    Anything that uses the CentOS 6.X repositories.
    RedHat 6.X (with a lot of reconfiguration)
    
#Will be added very soon

#Fédora 17
#Fédora 18
#Fédora 19
#Fédora 20
#Debian 7
#Mac OSX 10.5 (if I can find a mac lol or vm on mac "50 euros by mount")
 

Pen Have you found an OS that's not listed here and would like to get it added to this list? Then click on the pen below and please let us know.

 
#Detailed pre-installation check:

Fully read this BEFORE attempting to install Zpanel!

If you don't follow the install instructions and fully follow the pre-install checklist, then your install is considered 'custom' and your support from our staff will be very limited until you properly install ZPanel.
ZPanel is designed and developed to be as simple as possible to be installed and set-up provided you pay attention to the installation details!
We suggest you read everything twice! Both in this brief pre-install guide AND during the actual installation.
ZPanel installation checklist: (ALL items must be completed in order to even THINK about trying to installing ZPanel!)

    You MUST have a CLEAN, FRESH install of Windows (any version XP and above) or a Linux/FreeBSD (Ubuntu, CentOS, etc) installed on your server computer.
    NO OTHER WEB HOSTING RELATED SERVICES CAN BE INSTALLED ON THE SERVER AT ALL! (Examples: IIS, Nginx, MySQL, Apache, PHP, FTP Server, Mail Server, etc.) They MUST BE REMOVED or use the 'minimal install' before installing ZPanel!
     
    You MUST have a domain name registered and pointing to your server computer IP. (Just using an IP will not work properly and you will have to start from scratch!) (You can get a free domain or purchase a domain from sites like GoDaddy.com).
    A reduced functions set can be tested without domainname, see How to check server without DNS
     
    ZPanel should be installed and setup on a SUB-DOMAIN of your main domain: During installation you will be asked to enter an FQDN. This is the sub-domain zpanel is to be installed on. Examples: zpanel.domain.com, cp.domain.com, panel.domain.com, etc.
     
    You MUST have opened and forwared the requireds ports in your modem or router, and on the server firewall. See the list of required ports here.

Once the above are ALL completed, you may begin to install ZPanel on your server.

NOTE: There are IMPORTANT questions during the install process! Please read them carefully as they are crucial to the proper installation and operation of ZPanel One of them being the setup of the ZPanel sub domain! See also About Installer questions for axplanations about them

If you don't follow the install instructions and fully follow the pre-install checklist, then your install is considered 'custom' and your support from our staff will be very limited until you properly install ZPanel.

If you do not understand any of the terms or steps mentioned above, we suggest you do some reading and studying of web servers and web hosting BEFORE attempting to install ZPanel.

We will help you as long as you help us by following the install instructions.
#ADDITIONAL REQUIRED READING/UPDATES:

YOU MUST INSTALL EMERGENCY PATCHES. Read Security updates and patches doc page
