# README

N.b. see [./al-folio.README.md](./al-folio.README.md) for the original forked README from the Jekyll Al-Folio theme.


## Setting up your local
I highly suggest you use docker-compose. See [./al-folio.README.md](./al-folio.README.md) for further instructions. You should end up in a scenario where booting your local requires only that you issue the command

```
docker-compose up
```

Your local will be at http://0.0.0.0:8080; most people (like myself) like to rename this address in the local hosts file. That is, add the following to `/etc/hosts/` on Ubuntu, `/private/etc/hosts/` on mac, or `C:\Windows\System32\drivers\etc\hosts` on Windows.

```
0.0.0.0         clc
```

This makes http://clc:8080 access http://0.0.0.0:8080.


## How to Jekyll
[Read the docs](https://jekyllrb.com/docs/). This [step by step guide](https://jekyllrb.com/docs/step-by-step/01-setup/) has most of what you need to know; read, in particular, the pages on layouts, includes, and collections.

## Contribution

### Editing the homepage

### Editing members

### Editing recent publications

### Editing news / announcements

### Editing everything else
