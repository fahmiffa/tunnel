# Config Tunnel Remote

CLient Windows 
<br>
https://developers.cloudflare.com/warp-client/get-started/windows/
<br>
https://downloads.cloudflareclient.com/v1/download/windows/ga

# SSH
Host "url" User root ProxyCommand cloudflared access ssh --hostname %h IdentitiesOnly yes

# URL 
- domain host url

# Remote SQL 
- ssh -o ServerAliveInterval=60 -L 3307:127.0.0.1:3306 host

