# My Caddy Server config files
## The files
### Caddyfile Root
This file functions as your main caddyfile that imports all caddyfiles located in /var/www/

### Caddyfile Hugo
This caddyfile will download a hugo site repository and deploy it.

### Caddyfile Login with Google
More coming soon...

### The Notes
**Refresh Caddy Config**
sudo pkill -USR1 caddy

**Get Caddy Status**
sudo systemctl status caddy

**Restart Caddy**
sudo systemctl status caddy

**Get Caddy Service Logs**
sudo journalctl -u caddy