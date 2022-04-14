<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# mStream for YunoHost

[![Integration level](https://dash.yunohost.org/integration/mstream.svg)](https://dash.yunohost.org/appci/app/mstream) ![](https://ci-apps.yunohost.org/ci/badges/mstream.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/mstream.maintain.svg)  
[![Install mStream with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=mstream)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install mStream quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

mStream is a personal music streaming server. You can use mStream to stream your music from your home computer to any device, anywhere.

### Features

- Cross Platform. Works on Windows, OSX, Linux, & FreeBSD
- Light on memory and CPU
- Tested on multi-terabyte libraries
- Runs on ARM boards like the Raspberry Pi


**Shipped version:** 5.11.4~ynh1

**Demo:** https://demo.mstream.io/?

## Screenshots

![](./doc/screenshots/mstreamv5.png)

## Documentation and resources

* Official app website: https://mstream.io/
* Upstream app code repository: https://github.com/IrosTheBeggar/mStream
* YunoHost documentation for this app: https://yunohost.org/app_mstream
* Report a bug: https://github.com/YunoHost-Apps/mstream_ynh/issues

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/mstream_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/mstream_ynh/tree/testing --debug
or
sudo yunohost app upgrade mstream -u https://github.com/YunoHost-Apps/mstream_ynh/tree/testing --debug
```

**More info regarding app packaging:** https://yunohost.org/packaging_apps