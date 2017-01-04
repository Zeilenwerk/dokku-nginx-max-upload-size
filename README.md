# Dokku Nginx Max Upload Size

Dokku plugin for setting the NGINX client_max_body_size directive

## Installation

```shell
# on 0.4.x+
sudo dokku plugin:install https://github.com/Zeilenwerk/dokku-nginx-max-upload-size.git
```

## Usage

```shell
# To set a max body size, set the MAX_UPLOAD_SIZE env var
# If you unset the variable, a default of 2M will be used
dokku config:set MAX_UPLOAD_SIZE=20M
```
