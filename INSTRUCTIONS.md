# Desktop SSH Config

This is to store the config to setup my linux desktop as an SSH server.

## Install

```
sudo apt install openssh-server
```

## Generate Key

Public key authentication is the way to go here. Always use a pasphrase, then we've got the "something you have, something you know" security in place.

```
ssh-keygen -o -b 4096 -t rsa
[passphrase]: *********

```

## Status

Never got key auth to work. Password auth is currently working.