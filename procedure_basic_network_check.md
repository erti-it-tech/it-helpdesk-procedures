# Procédure : Diagnostic réseau basique

## Étapes
1. Vérifier l’adresse IP :  
ipconfig /all
2. Ping de la passerelle :  
ping 192.168.10.1
3. Ping d’un site externe :  
ping google.com
4. Test DNS :  
nslookup google.com
5. Test du port 443 :  
Test-NetConnection google.com -Port 443

## Problèmes courants
- 169.254.x.x → pas de DHCP  
- DNS incorrect  
- IPv4 mais pas IPv6 (non bloquant)  
- VPN activé  
