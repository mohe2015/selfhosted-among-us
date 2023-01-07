# selfhosted-among-us

```bash
sudo openssl pkcs12 -in /etc/letsencrypt/live/selfmade4u.de/cert.pem -inkey /etc/letsencrypt/live/selfmade4u.de/privkey.pem -export -clcerts -out privkey.der -passout pass:
mkdir plugins
curl -L https://github.com/Impostor/Impostor.Http/releases/download/v0.4.0/Impostor.Http.dll --output plugins/Impostor.Http.dll
```

Install ASP.NET Core Runtime 7 (https://dotnet.microsoft.com/en-us/download/dotnet/7.0)
