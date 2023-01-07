# selfhosted-among-us

## On Server

```bash
sudo openssl pkcs12 -in /etc/letsencrypt/live/selfmade4u.de/cert.pem -inkey /etc/letsencrypt/live/selfmade4u.de/privkey.pem -export -clcerts -out privkey.der -passout pass:
mkdir plugins
curl -L https://github.com/Impostor/Impostor.Http/releases/download/v0.4.0/Impostor.Http.dll --output plugins/Impostor.Http.dll
```

Install ASP.NET Core Runtime 7 (https://dotnet.microsoft.com/en-us/download/dotnet/7.0)

```bash
docker compose up -d
```

## On Client

```bash
cp ./regionInfo.json '~/.var/app/com.valvesoftware.Steam/.local/share/Steam/steamapps/compatdata/945360/pfx/drive_c/users/steamuser/AppData/LocalLow/Innersloth/Among Us/regionInfo.json'

```
