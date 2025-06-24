# BLACKWALL
Simple ASN scraper for mass blocks of low-rep/low-regret ASNs.  Mostly VPS and assorted bulletproof hosting/crimeware stuff.
![image](https://github.com/user-attachments/assets/cc7fcd59-be40-4c5f-b291-9814604261e1)

This repository maintains an up-to-date collection of IP address blocks associated with a curated list of Autonomous System Numbers (ASNs) known for low reputation or suspicious activity.  It is refreshed daily.  If you would like to add an ASN to this list, please reach out to https://bsky.app/profile/mattysplo.it 

The intent is to keep it to only known-bad ASNs that most orgs can get away with blocking outright.  If you are not sure if that is you, do not use this.
It is essentially a more aggressive version of [Spamhaus' "Don't Route or Peer" (DROP) Lists](https://www.spamhaus.org/blocklists/do-not-route-or-peer/).  This includes that dataset and layers on a few more manually curated.  Use Spamhaus for higher trust and fidelity.
I'm also just some guy on the internet, why are you trusting me with your blocklists?

## Files
### THEBLACKWALL.txt
A consolidated list of IP address ranges associated with the monitored ASNs. This file is regularly updated to reflect changes in network allocations.

### asn_list.txt
A reference list of the ASNs included in this blocklist, along with their registered organization names. This helps identify the entities behind the IP blocks.

The purpose of this repository is to provide a reliable, automatically refreshed source of network blocks for use in security monitoring, network filtering, or threat intelligence workflows.
