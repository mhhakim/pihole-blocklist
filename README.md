# Pihole Blocklist
<p>Ok, what is it? It's a list of domains/hosts which is involved in showing ads, track, spam, malware etc. Personally, I am using this list in pi-hole(https://pi-hole.net/) which is running on my Raspberry Pi 3 B+.</p>
<p>I made a program which runs every day once on my server. It collects data from a bunch of lists,  made them pi-hole ready(clean domain/host), make them unique & combine them into a single list and commit the list into this repository.</p>
<p>It's a lightweight list. So, it will take fewer resources. As I also block porn websites, a porn website/host list added too.</p>

<p>I tried to include popular & effective lists.</p>
<p>The porn list was already pi-hole ready but the domain was non www version. As a result, example.com blocked but www.example.com still accessible. So, I also include a www version of every domain in this list.</p>

### How to use?
  Just add the following list to your pi-hole.

  <code> https://raw.githubusercontent.com/mhhakim/pihole-blocklist/master/list.txt </code>
  
  <code> https://raw.githubusercontent.com/mhhakim/pihole-blocklist/master/porn.txt </code>
  
### Warning
  I included a few aggressive lists which can impact your regular internet browsing experience. I suggest you check the log query & whitelist the queries which case problem on regular browsing.
  
  
#### The porn.txt includes:
* https://raw.githubusercontent.com/chadmayfield/pihole-blocklists/master/lists/pi_blocklist_porn_top1m.list


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
* https://mirror1.malwaredomains.com/files/justdomains
* https://zeustracker.abuse.ch/blocklist.php?download=domainblocklist
* https://s3.amazonaws.com/lists.disconnect.me/simple_tracking.txt
* https://s3.amazonaws.com/lists.disconnect.me/simple_ad.txt
