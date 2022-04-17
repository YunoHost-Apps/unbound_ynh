<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Unbound for YunoHost

[![Integration level](https://dash.yunohost.org/integration/unbound.svg)](https://dash.yunohost.org/appci/app/unbound) ![](https://ci-apps.yunohost.org/ci/badges/unbound.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/unbound.maintain.svg)  
[![Install Unbound with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=unbound)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Unbound quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Unbound is a validating, recursive, caching DNS resolver. It is designed to be fast and lean and incorporates modern features based on open standards.
To help increase online privacy, Unbound supports DNS-over-TLS and DNS-over-HTTPS which allows clients to encrypt their communication. In addition, it supports various modern standards that limit the amount of data exchanged with authoritative servers. These standards do not only improve privacy but also help making the DNS more robust. The most important are Query Name Minimisation, the Aggressive Use of DNSSEC-Validated Cache and support for authority zones, which can be used to load a copy of the root zone.

**Shipped version:** 1.13.1~ynh1



## Documentation and resources

* Official app website: https://nlnetlabs.nl/projects/unbound/about/
* Official admin documentation: https://nlnetlabs.nl/documentation/unbound/
* Upstream app code repository: https://github.com/NLnetLabs/unbound
* YunoHost documentation for this app: https://yunohost.org/app_unbound
* Report a bug: https://github.com/YunoHost-Apps/unbound_ynh/issues

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/unbound_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/unbound_ynh/tree/testing --debug
or
sudo yunohost app upgrade unbound -u https://github.com/YunoHost-Apps/unbound_ynh/tree/testing --debug
```

**More info regarding app packaging:** https://yunohost.org/packaging_apps