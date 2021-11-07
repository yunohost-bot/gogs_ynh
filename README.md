<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Gogs for YunoHost

[![Integration level](https://dash.yunohost.org/integration/gogs.svg)](https://dash.yunohost.org/appci/app/gogs) ![](https://ci-apps.yunohost.org/ci/badges/gogs.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/gogs.maintain.svg)  
[![Install Gogs with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=gogs)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Gogs quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Gogs (Go Git Service) is a git-based multiplatform forge written in Go. Its particularity is that it is light and can run on an ARM card, which makes it suitable for self-hosting. Gogs has a web interface similar to that of GitHub. 

**Shipped version:** 0.12.3~ynh1

**Demo:** https://try.gogs.io/user/login

## Screenshots

![](./doc/screenshots/screenshot.png)

## Documentation and resources

* Official app website: http://gogs.io
* Official admin documentation: https://gogs.io/docs
* Upstream app code repository: https://github.com/gogs/gogs
* YunoHost documentation for this app: https://yunohost.org/app_gogs
* Report a bug: https://github.com/YunoHost-Apps/gogs_ynh/issues

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/gogs_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/gogs_ynh/tree/testing --debug
or
sudo yunohost app upgrade gogs -u https://github.com/YunoHost-Apps/gogs_ynh/tree/testing --debug
```

**More info regarding app packaging:** https://yunohost.org/packaging_apps