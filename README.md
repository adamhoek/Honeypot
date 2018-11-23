# Honeypot
Modern Honey Network (MHN)

Deployed Dionaea over HTTP honeypot. 

Challenge 1: I was concerned about the following error message:
 - The resource 'projects/ubuntu-os-cloud/global/images/ubuntu-1404-trusty-v20171010' is deprecated. A suggested replacement is 'projects/ubuntu-os-cloud/global/images/ubuntu-1404-trusty-v20181114'.
Correcting the trusty-version in the installer removes the error, and produces a threat map, but no admin console.

Challenge 2: I can create the Session.JASON, but can't download it.

<img src="https://github.com/adamhoek/Honeypot/blob/master/Session.JSON.gif" width="800">

Note the inital attacks from Mexico City (189.146.243.244).  That's me.  As you can see, I was quickly joined by friends from around the world.

<img src="https://github.com/adamhoek/Honeypot/blob/master/Week%209%20Honeypot.gif" width="800">

The majority of initial attacks are Packet Capture (PCAP)

Checking back later.  There are a couple of public IP addresses in Moldova that have been very busy.

<img src="https://github.com/adamhoek/Honeypot/blob/master/Week%209%20Threat%20Map.gif" width="800">
