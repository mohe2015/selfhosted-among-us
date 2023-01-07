# selfhosted-among-us

```bash
sudo openssl pkcs12 -in /etc/letsencrypt/live/selfmade4u.de/cert.pem -inkey /etc/letsencrypt/live/selfmade4u.de/privkey.pem -export -clcerts -out privkey.der -passout pass:
