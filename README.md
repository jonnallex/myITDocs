## Info
https://letsencrypt.org/
https://www.digitalocean.com/community/tutorials/how-to-secure-nginx-with-let-s-encrypt-on-ubuntu-20-04

## Set
```sudo ufw allow 80```
```sudo ufw allow 443```
``` sudo ufw status``` check status
```sudo apt install certbot python3-certbot-nginx```
```sudo certbot --nginx -d jonnallex.space -d jonnallex.space```
