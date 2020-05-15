    Ads              Advertisements, Banners, Widgets & Push Notifications  
    Adult            Porn / 18+ Content  
    Apple            Bloat / Push Notifications  
    Bitcoin          Bitcoin Miner & Related Sites  
    Bloat            Fonts, Domains not required for software to function  
    Chat             Live / Bot Chat Dialog Boxes  
    Dating           Dating Sites  
    Dynamic          Dynamic DNS:  DNS --> IP  
    Free             Free/Cheap Hosting & Blogs  
    Junk             Surveys, Junk, Personally Untrusted Antivirus, ISPs (Spam/Botnets), etc  
    Malware          Malicious Sites, PUPs, Malware, Brower Hijackers, Phishing Sites  
    Marketing        Web Marketing / Ebay Listing Tools  
    Marketing-Email  Email Based Marketing  
    Microsoft        Apps, Bing, Bloat, Tiles, Unknown  
    Pirate           Torrent / Magnet Sites, Torrent Trackers, Warez  
    Remote           Domains used to remotely control your stuff  
    Scam             Fake / Misleading Sites - Not malware  
    Shock            Gore, Gross, Torture, Race/Gender Superiority  
    Suspicious       Domains I am uncertain of. Contains a mixture of possible Ads, Trackers, Malware  
    Top_Level        Top Level Domains: Will block most non-traditional domains  
    Tracking         Analytics, Diagnostics, Location, Metrics, Puplic IP  
    Tunnels          VPNs & Proxies
    Typo             Typosquatting / Misspelling of websites.  
    Unknown          Similar to Suspicious, but is more organized.  
  
    Filter           Used by my parse script to show me what has not been blocked
    Whitelist        Reasons for some allowed domains  
  
Domains are sorted by category. Some domains are used for both ads and tracking.  
  
These lists are all verified by me, either by going to the domain or by using automated tools that I have written. These domains are a mix of domains I have found, and other users have compiled. I try to keep dead, parked, and sinkholed domains out of these lists.  
  
I remove _www<span></span>._ _mobile._ _m._  prefixes. They are added in the script below. This keeps the original list shorter, and ensures the domain is fully blocked.  
  
_Free_, _Junk_, _Marketing*_, _Suspicious_, and _Unknown_ may break some websites.
  
**Create Block List**  
  while read -r Line || [[ -n "$Line" ]]; do  
  echo "0.0.0.0 $Line www<span></span>.$Line mobile.$Line m.$Line" >> OUTPUT_LIST
  done < INPUT_LIST
  
**Useful Links**  
[Norton Safeweb](https://safeweb.norton.com/)  
[Sucuri Site Check](https://sitecheck.sucuri.net/)  
[VirusTotal](https://www.virustotal.com/gui/home/url)  
  
[SSL Labs](https://www.ssllabs.com/ssltest/)  
[Whois](https://www.whois.com/whois/)  
  
[Spamhaus Statistics](https://www.spamhaus.org/statistics/countries/)  

[Typo Generator](http://domaincheckplugin.com/typo)
