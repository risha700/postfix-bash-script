### |=========> Postfix the easy way <======|

## The Motive :
Automation script that deploys a secured POSTFIX mail server instance "On digital ocean for now" 
in matter of minutes

## Postfix mail server including
- Dovecot "IMAP POP"
- SPF
- DKIM
- Spamassasin

# how to use?
```
# git clone or download tar ball
wget https://github.com/risha700/postfix-bash-script/tarball/master | tar xf

./run 
 
# it will prompt you for some neccessary inputs or it can take config file as first argument like:
 
./run my.config

```

## What you need ?
Linux Ubuntu 20.04LTS
Public accessible IP from a provider that allows outbound port for SMTP 25 

## TODO
mysql admin
postgress user db aliases
quota plugin
PAM auth and SASL

### Disclaimar: This script is exclusively automate the process on DigitalOcean instance
---
Author: risha700 

Licensce: MIT