# ampere-2-gamemanager
private Minecraft world manager

features to have
- Whitelist allowed for all people already on the server to submit a request to whitelist someone/give perms to insta whitelist someone
- Reworked join message/leave message
- Auto server pausing? (unload the actual world while creating a limbo server, use world creator…)
- Basic anticheat (?)
- Anti xray
- Import plugins on demand
- Delete plugin on demand
- Web interface for public stats, etc.
- Who is online
- Log checker web interface / server stats

when enabling firewall now
add ingress rules
enable UFW 25565
sudo iptables -I INPUT -p tcp --dport 25565 -j ACCEPT
