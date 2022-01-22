<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Zabbix for YunoHost

[![Integration level](https://dash.yunohost.org/integration/zabbix.svg)](https://dash.yunohost.org/appci/app/zabbix) ![](https://ci-apps.yunohost.org/ci/badges/zabbix.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/zabbix.maintain.svg)  
[![Install Zabbix with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=zabbix)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Zabbix quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

A monitoring tool for diverse IT components, including networks, servers, VMs and cloud services.

**Shipped version:** 4.4~ynh3



## Screenshots

![](./doc/screenshots/screenshot1.png)

## Disclaimers / important information

#### Known limitations or important informations

* Only x86_64 architecture is supported
* Single sign-on is supported
* Do not change the default admin user password. The user is disabled just after the install but is used to update templates.
* The Zabbix server port is not opened by default for external monitoring (active agent).
* You can add your users in a group in Zabbix (for permissions/rights).
* A YunoHost template is imported and linked to the host "Zabbix-server" (127.0.0.1) for basic monitoring for YunoHost.

## Documentation and resources

* Official app website: https://www.zabbix.com/
* Official admin documentation: https://www.zabbix.com/manuals
* Upstream app code repository: https://github.com/zabbix/zabbix
* YunoHost documentation for this app: https://yunohost.org/app_zabbix
* Report a bug: https://github.com/YunoHost-Apps/zabbix_ynh/issues

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/zabbix_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/zabbix_ynh/tree/testing --debug
or
sudo yunohost app upgrade zabbix -u https://github.com/YunoHost-Apps/zabbix_ynh/tree/testing --debug
```

**More info regarding app packaging:** https://yunohost.org/packaging_apps