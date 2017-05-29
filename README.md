[![Travis](https://shields.beevelop.com/travis/beevelop/docker-watchmen.svg?style=flat-square)](https://travis-ci.org/beevelop/docker-watchmen)
[![Pulls](https://shields.beevelop.com/docker/pulls/beevelop/watchmen.svg?style=flat-square)](https://links.beevelop.com/d-watchmen)
[![Layers](https://shields.beevelop.com/docker/image/layers/beevelop/watchmen/latest.svg?style=flat-square)](https://links.beevelop.com/d-watchmen)
[![Size](https://shields.beevelop.com/docker/image/size/beevelop/watchmen/latest.svg?style=flat-square)](https://links.beevelop.com/d-watchmen)
[![GitHub release](https://shields.beevelop.com/github/release/beevelop/docker-watchmen.svg?style=flat-square)](https://github.com/beevelop/docker-watchmen/releases)
![Badges](https://shields.beevelop.com/badge/badges-7-brightgreen.svg?style=flat-square)
[![Beevelop](https://links.beevelop.com/honey-badge)](https://beevelop.com)

# Latest watchmen
### based on [beevelop/nodejs](https://github.com/beevelop/docker-nodejs)

> watchmen is developer-friendly health-monitor (outages, uptime, response time warnings, avg. response time, etc) for your services and is easily extensible through pluggable ping types (http head, http contains, smtp,…) and custom action plugins (console output, email notifications,…).

This Docker image is an unofficial adaption to provide an easy-to-run and preconfigured version with a bunch of ping types and custom action plugins.

----
### Pull from Docker Hub
```
docker pull beevelop/watchmen:latest
```

### Or build from GitHub
```
docker build -t beevelop/watchmen github.com/beevelop/docker-java
```

### Run image
```
docker run -it beevelop/watchmen bash
```

### Or use as base image
```Dockerfile
FROM beevelop/watchmen:latest
```

----

![One does not simply use latest](https://i.imgflip.com/1fgwxr.jpg)
