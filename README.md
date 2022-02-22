# Pihole Blocklist
### Note: I am only responsible for the websites that are in `custom-whitelist.txt`, `custom-porn-whitelist.txt`, `custom-porn-blocklist.txt`, and `custom-blocklist.txt`. All other ones are grabbed from other lists (see below for details).

Ok, what is it? It's a list of domains/hosts which is involved in showing ads, track, spam, malware etc. Personally, I am using this list in pi-hole(https://pi-hole.net/) which is running on my Raspberry Pi 3 B+.

I made a program which runs every day once on my server. It collects data from a bunch of lists,  made them pi-hole ready(clean domain/host), make them unique & combine them into a single list and commit the list into this repository.

It's a lightweight list. So, it will take fewer resources. As I also block porn websites, a porn website/host list added too. The porn blocklist is updated/checked regularly every night at 1am.

I tried to include popular & effective lists.
The porn list was already pi-hole ready but the domain was non www version. As a result, example.com blocked but www.example.com still accessible. So, I also include a www version of every domain in this list.

### How to use?
Just add the following lists to your pi-hole.

    https://raw.githubusercontent.com/mhhakim/pihole-blocklist/master/list.txt
    https://raw.githubusercontent.com/mhhakim/pihole-blocklist/master/porn.txt
  
### Warning
  I included a few aggressive lists which can impact your regular internet browsing experience. I suggest you check the log query & whitelist the queries which case problem on regular browsing.
  
  
#### The porn.txt includes:
* https://raw.githubusercontent.com/blocklistproject/Lists/master/porn.txt


#### The list.txt includes:
* https://raw.githubusercontent.com/notracking/hosts-blocklists/master/domains.txt
* https://raw.githubusercontent.com/notracking/hosts-blocklists/master/hostnames.txt
* https://raw.githubusercontent.com/StevenBlack/hosts/master/alternates/fakenews-gambling-porn-social/hosts
* https://www.github.developerdan.com/hosts/lists/ads-and-tracking-extended.txt
* https://www.github.developerdan.com/hosts/lists/tracking-aggressive-extended.txt
* http://sysctl.org/cameleon/hosts
* https://justdomains.github.io/blocklists/lists/easylist-justdomains.txt
* https://justdomains.github.io/blocklists/lists/easyprivacy-justdomains.txt
* https://justdomains.github.io/blocklists/lists/adguarddns-justdomains.txt
* https://justdomains.github.io/blocklists/lists/nocoin-justdomains.txt
* https://raw.githubusercontent.com/austinheap/sophos-xg-block-lists/master/yoyo-org.txt
* https://raw.githubusercontent.com/austinheap/sophos-xg-block-lists/master/steven-blacks-unified-list.txt
* https://raw.githubusercontent.com/austinheap/sophos-xg-block-lists/master/adguard.txt
* https://raw.githubusercontent.com/austinheap/sophos-xg-block-lists/master/mitchell-krogs-badd-boyz-hosts.txt
* https://raw.githubusercontent.com/austinheap/sophos-xg-block-lists/master/coinblocker.txt
* https://raw.githubusercontent.com/austinheap/sophos-xg-block-lists/master/easylist.txt
* https://raw.githubusercontent.com/austinheap/sophos-xg-block-lists/master/easyprivacy.txt
* https://raw.githubusercontent.com/austinheap/sophos-xg-block-lists/master/kadhosts.txt
* https://raw.githubusercontent.com/austinheap/sophos-xg-block-lists/master/nocoin.txt
* https://raw.githubusercontent.com/austinheap/sophos-xg-block-lists/master/spotifyads.txt
* https://raw.githubusercontent.com/austinheap/sophos-xg-block-lists/master/steven-blacks-ad-hoc-list.txt
* https://raw.githubusercontent.com/austinheap/sophos-xg-block-lists/master/uncheckyads.txt
* https://raw.githubusercontent.com/austinheap/sophos-xg-block-lists/master/adaway.txt
* https://raw.githubusercontent.com/austinheap/sophos-xg-block-lists/master/add-2o7net.txt
* https://raw.githubusercontent.com/austinheap/sophos-xg-block-lists/master/add-dead.txt
* https://raw.githubusercontent.com/austinheap/sophos-xg-block-lists/master/add-risk.txt
* https://raw.githubusercontent.com/austinheap/sophos-xg-block-lists/master/add-spam.txt
* https://raw.githubusercontent.com/austinheap/sophos-xg-block-lists/master/malware-domain-list.txt
* https://raw.githubusercontent.com/austinheap/sophos-xg-block-lists/master/mvps-hosts-file.txt
* https://raw.githubusercontent.com/austinheap/sophos-xg-block-lists/master/dan-pollock-someonewhocares-org.txt
* https://raw.githubusercontent.com/austinheap/sophos-xg-block-lists/master/tyzbit.txt
* https://s3.amazonaws.com/lists.disconnect.me/simple_tracking.txt
* https://s3.amazonaws.com/lists.disconnect.me/simple_ad.txt
