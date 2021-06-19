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

[https://raw.githubusercontent.com/vincentkenny01/spotblock/master/spotify](https://raw.githubusercontent.com/vincentkenny01/spotblock/master/spotify)

[https://raw.githubusercontent.com/anudeepND/whitelist/master/domains/whitelist.txt](https://raw.githubusercontent.com/anudeepND/whitelist/master/domains/whitelist.txt)

[https://gist.githubusercontent.com/anudeepND/adac7982307fec6ee23605e281a57f1a/raw/5b8582b906a9497624c3f3187a49ebc23a9cf2fb/Test.txt](https://gist.githubusercontent.com/anudeepND/adac7982307fec6ee23605e281a57f1a/raw/5b8582b906a9497624c3f3187a49ebc23a9cf2fb/Test.txt)