# Preview in development

## Important improvement
Rewrite startup code to speed up startup  
Same as global server, no need to start multiple processes  
Use unified path and configuration  

## Changes
Add Reset default settings  
~~Optimize the use of shadowsocks plugin~~  
Remove the sh script used in update and modify the UI usage  
Remove Easylist China from adblock and add NEO DEV HOST  
Adjust the parameters used by wget to ensure compatibility  
Add Trojan-go support  
Add vless share link import  
Optimize update return value  
V2ray_Plugin is off by default  
Improve Trojan-Go support  

## Fixes
Fix the issue of starting twice after apply in the server node list  
Fix the problem that dnsmasq fails to start when the access control list contains wrong entries  
Replace expired gfwlist update URLs  
Fix shadowsocks startup bug  
Fix process daemon bug  