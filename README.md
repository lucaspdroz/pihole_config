# No more Ads in my life... 🚀🎉

Pihole Configuration used at my home server

`git clone --depth 1 https://github.com/pi-hole/pi-hole.git Pi-hole`
`cd "Pi-hole/automated install/"`
`sudo bash basic-install.sh`

### My Issues (fast aproach)

Change admin password
`pihole -a -p [password]`

user blocked (Db block)
`sudo adduser www-data pihole`
`sudo systemctl restart apache2`

DNS and FTL offline
`pihole checkout master`

Other Projetcs I've used:

[spotblock-spotify from vincentkenny01](https://raw.githubusercontent.com/vincentkenny01/spotblock/master/spotify)

[whitelist-domains-whitelist from anudeepND](https://raw.githubusercontent.com/anudeepND/whitelist/master/domains/whitelist.txt)

[fanboy-annoyance from easylist](https://easylist.to/easylist/fanboy-annoyance.txt)
[ultimate-ad-filter from adavoid](https://filters.adavoid.org/ultimate-ad-filter.txt)
