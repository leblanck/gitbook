---
description: What domains do we have and what are they for?
---

# 🌐 Domain Management

<table><thead><tr><th>Domain Name</th><th>Purpose</th><th width="200">Name Server</th><th>Registrar</th></tr></thead><tbody><tr><td>leblanc.sh</td><td>Personal Website</td><td>Netlify</td><td>Hover</td></tr><tr><td>fleet.leblanc.sh</td><td>FleetDM</td><td>Netlify</td><td>Hover</td></tr><tr><td>blog.leblanc.sh</td><td>Hosting The Workbench Blog</td><td>Netlify</td><td>N/A</td></tr><tr><td>photo.leblanc.sh</td><td>Photography Website</td><td>Netlify</td><td>N/A</td></tr><tr><td>docs.leblanc.sh</td><td>Documentation on GitBook</td><td>Netlify</td><td>N/A</td></tr><tr><td>home.leblanc.sh</td><td>Custom Browser Homepage</td><td>Netlify</td><td>N/A</td></tr><tr><td>creative.leblanc.sh</td><td>Creative Department</td><td>Netlify</td><td>N/A</td></tr><tr><td>leblancracing.com</td><td>LeBlanc Racing Home</td><td>Netlify</td><td>Hover</td></tr><tr><td>pinkrhino.studio</td><td>PinkRhino Blog</td><td>Netlify</td><td>Hover</td></tr><tr><td>kyleblanc.com</td><td>n/a</td><td>Hover</td><td>Hover</td></tr><tr><td>kyleblanc.dev</td><td>Freelance Dev Website</td><td>Hover</td><td>Hover</td></tr><tr><td>leblanc.wtf</td><td>Cloudflare Tunnel</td><td>Cloudflare</td><td>Hover</td></tr><tr><td>root.leblanc.sh</td><td>Root URL</td><td>Netlify</td><td>N/A</td></tr></tbody></table>

### NGINX Proxy Manager

| URL                   | MAPS TO                                                    | APP                                   |
| --------------------- | ---------------------------------------------------------- | ------------------------------------- |
| casa.leblanc.wtf      | [http://192.168.40.105:88](http://192.168.40.105:88)       | CasaOS                                |
| uptime.leblanc.wtf    | http://159.65.191.48:3001                                  | Uptime Kuma (Hosted on Digital Ocean) |
| jelly.leblanc.wtf     | [http://192.168.40.105:8096](http://192.168.40.105:8096)   | Jellyfin                              |
| portainer.leblanc.wtf | [https://192.168.40.105:9443](https://192.168.40.105:9443) | Portainer                             |
| books.leblanc.wtf     | [http://192.168.40.105:8083](http://192.168.40.105:8083)   | Calibre-Web                           |
| grafana.leblanc.wtf   | [http://192.168.40.105:3000](http://192.168.40.105:3000)   | Grafana                               |
| wazuh.leblanc.wtf     | [https://192.168.40.105:443](https://192.168.40.105)       | Wazuh                                 |

AdGuard Home

Custom Local DNS Mappings

\*.leblanc.wtf -> 192.168.40.166 (NGINX)
