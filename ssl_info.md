## Info
https://letsencrypt.org/
https://www.digitalocean.com/community/tutorials/how-to-secure-nginx-with-let-s-encrypt-on-ubuntu-20-04

## Set
1. ```sudo ufw allow 80```
2. ```sudo ufw allow 443```
3. ```sudo ufw status``` check status
4. ```sudo apt install certbot python3-certbot-nginx```
5. ```sudo certbot --nginx -d jonnallex.space -d jonnallex.space```
