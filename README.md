# nginx config for IP cams on the web
The nginx config I use to expose my IP cams to the internet.<br>
From  https://blog.willmurphy.co.uk/secure_ip_cam_streaming/
---
*default*<br>
The default config, replace the server URL and camera urls with your own. Place in /etc/nginx/sites-available
---
*maintainance*<br>
The config for maintaince mode, redirects to localhost. Place in /etc/nginx/sites-available
---
*setMaintainanceMode*<br>
Bash script to quickly enable/disable maintainance mode
