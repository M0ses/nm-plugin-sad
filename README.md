nm-plugin-sad
=============

'''A plugin/dispatcher script for NetworkManager for siproxd and dnsmasq'''

This tool is a "plugin" for NetworkManager in form of a dispatcher 
script (located under /etc/NetworkManager/dispatcher.d) which starts 
siproxy and/or dnsmasq depending on your configurtion.

in my case i use it to:

1. get a splitting DNS server running on my laptop to keep name resolution for 
   my local network and being able to resolve dns names from the DNS server in
   my companies network
2. start siproxd to connet my local VOIP phone in my home network connection to
   the VOIP server in my companies network


