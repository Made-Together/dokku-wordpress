# dokku-wordpress

Setup wordpress instances inside dokku


## Requirements

- A Dokku server. Tested on 0.21.4+
- The [dokku-mysql](https://github.com/dokku/dokku-mysql) plugin
- The [dokku-letsencrypt](https://github.com/dokku/dokku-letsencrypt) plugin


## Install

```
sudo dokku plugin:install https://github.com/Made-Together/dokku-wordpress.git wordpress
```

## Quick start

Init new wordpress setup on dokku

```
$ dokku wordpress:init myapp
```


## TODO

[] Missing plugin dependency error notices
[] Fix salt config:set env function
[] Add destroy method
[] Add letsencrypt stuff


## Roadmap

[] dokku wordpress:cli [COMMAND]
[] dokku wordpress:cache [enable/disable]