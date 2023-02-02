# bashscripts
- A respository of miscellaneous bash scripts that others might find useful


## energysavings
 - Mainly beneficial from the perspective of being able to compare energy usage *without* a battery backup, and _with_ a battery backup, charging the battery up overnight on Economy7, and then using it throughout the day. This original version doesn't take into account annual solar energy input, so if you _are_ going to use it as-is, then make sure when you enter the annual usage value, you subtract off the Solar PV contribution from your total


## installnetmaker
### Adapted from (*definitely* read these before diving in & watching at least the first video listed below!):
 - https://wiki.opensourceisawesome.com/books/netmaker-for-remote-network-access-via-wireguard/page/setting-up-a-remote-access-wireguard-vpn-with-netmaker
 - https://docs.netmaker.org/quick-start.html

### FFI, watch these tutorials (especially the first):
 - https://youtu.be/CGw4Kc424VE & 
 - https://youtu.be/X-BYDYoM_3w

### INSTRUCTIONS
 - Create two files, one called:
 - serveremail => put your desired Netmaker email address in a single line in this file
 - serverdomain => put your Netmaker domain in a single line in this file (can be a TLD or subdomain)
  - Then run this script via bash installnetmaker (or chmod +x installnetmaker && ./installnetmaker)
