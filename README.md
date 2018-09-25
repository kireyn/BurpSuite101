# BurpSuite101

Set up your own BurpSuite for fun and profit.

# What we need:

BurpSuite Community Edition or OWASP_Zed_Attack_Proxy_Project

https://portswigger.net/burp/communitydownload

https://github.com/zaproxy/zaproxy/wiki/Downloads

Mozilla Firefox or Google Chrome

https://www.mozilla.org/en-US/firefox/new/ 

https://www.google.com/chrome/

Use special Browser Profile for testing, this preventing you from leaking your creds. 

Useful extensions:

Wappalyzer  

https://www.wappalyzer.com/

FoxyProxy or TunnelSwitch

https://getfoxyproxy.org/

https://chrome.google.com/webstore/detail/tunnelswitch/nfpphleklkamlblagdkbkomjmaedanoh

Cookie Editor or EditThisCookie

https://add0n.com/cookie-editor.html

https://chrome.google.com/webstore/detail/editthiscookie/fngmhnnpilhplaeedifhccceomclgfbg?hl=ru

User-Agent Switcher or User-Agent Switcher for Chrome

https://addons.mozilla.org/en-US/firefox/addon/uaswitcher/

https://chrome.google.com/webstore/detail/user-agent-switcher-for-c/djflhoibgkdhkhhcedjiklpkjnoahfmg?hl=ru

 # What we are going to play with:

Hacker101 and OWASP_Juice_Shop_Project

https://www.hacker101.com/

You need test Gmail account for Hacker101  

https://www.owasp.org/index.php/OWASP_Juice_Shop_Project

How to setup your own playground on Ubuntu VM:

Download Ubuntu Server 18.04.1 LTS

https://www.ubuntu.com/download/server

In terminal:

sudo -i

apt update

apt upgrade

ifconfig

apt install curl

curl -sL https://deb.nodesource.com/setup_10.x | sudo bash -

sudo apt install -y nodejs

mkdir JuiceShop

cd JuiceShop/

wget https://github.com/bkimminich/juice-shop/releases/download/v7.5.1/juice-shop-7.5.1_node10_linux_x64.tgz

tar -zxvf juice-shop-7.5.1_node10_linux_x64.tgz

cd juice-shop-7.5.1/

nmp start

Look at http://IP_from_ipconfig:3000/

# Let's play: 

Launching Burp Suite in more effective way

java -Djsse.enableSNIExtension=false -jar -Xmx1G /path/to/burp.jar

1G = 1024m = RAM

Or set up BurpSuitePro.vmoptions file in Burp home directory

Burp Setup

Generate Certificate

http://burp

Target Tab 

Focus on specific sites

Focus  on specific functions

Visualize attack  surface

Set "Scope" to filter or other tools

Proxy Tab 

Trap/Modify live traffic

View all traffic

Set wild scale configuration for the traffic flowing through Burp

Spider 

Spidering will find you all the linked content: Pages,scripts and images, ...

Content discovery is finding unlinked content by either guesing or brute force  

Scanner

Automatically scan and  fuzz all traffic for common vulnerabilities  

Burp Intruder

Set up robust, automated/scripted testing easily

"Fuzz" parameters, paths, etc, etc

Bruteforce Passwords

Content discovery with lists

Iterating ID's, etc, etc

++

Burp Reapeter

Replay requests quickly and  from any tool inside of Burp

Perform manual testing

Sequencer

Decoder

Comparer

Project Options

User Options

Alerts

Extender

Useful Burp Suite Extensions

Active Scan ++

Additionalr Scanner Checks

Backslash Powered Scanners

Param Miner

Site Map Extractor

Soft vulnerability Scanner

Retire.JS

JSON Beatifier

Authmatrix

Useful lists:

https://github.com/danielmiessler/SecLists

https://github.com/fuzzdb-project/fuzzdb

https://github.com/Bo0oM/fuzz.txt

# What you are going to read after:

https://leanpub.com/ltr101-breaking-into-infosec

https://leanpub.com/web-hacking-101

https://www.amazon.co.uk/Web-Application-Hackers-Handbook-Exploiting/dp/1118026470/

https://www.owasp.org/images/1/19/OTGv4.pdf

https://www.amazon.co.uk/Mastering-Modern-Web-Penetration-Testing/dp/1785284584/



