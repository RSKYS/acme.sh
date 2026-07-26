## acme.sh (Personalized)

#### Init
```
( cd ~
mkdir .acme.sh
cd .acme.sh
wget https://raw.githubusercontent.com/RSKYS/acme.sh/red/acme.sh
chmod +x acme.sh )
```

#### Steps next
```
~/.acme.sh/acme.sh --set-default-ca --server letsencrypt
```

```
~/.acme.sh/acme.sh --register-account -m youremail@exmple.com
```

```
~/.acme.sh/acme.sh --issue -d host.mydomain.com --standalone
```
