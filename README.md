![unipi logo](https://github.com/UniPiTechnology/evok-web-jq/raw/main/www/css/images/unipi-logo-short-cmyk.svg?sanitize=true "Unipi logo")

# EVOK WEB jQ

Evok web is simple web application based on jQuery Mobile for [Evok].
Web presents the Evok REST API and Websocket.

To publish website on server, you need to configure and run a http server like [Nginx] or [Apache]


## Installation

Evok web can be installed by apt.
You must have Evok installed before. 
See [Evok installation instructions](https://github.com/UniPiTechnology/evok/docs/installation.md).

Install/Upgrade:
```bash
sudo su
apt-get update
apt-get install -y evok-web
```


[Nginx]:https://nginx.org/
[Apache]:https://httpd.apache.org/
[Evok]:https://github.com/UniPiTechnology/evok
