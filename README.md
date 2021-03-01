

# Epicyon app for YunoHost

[![Integration level](https://dash.yunohost.org/integration/epicyon.svg)](https://dash.yunohost.org/appci/app/epicyon) ![](https://ci-apps.yunohost.org/ci/badges/epicyon.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/epicyon.maintain.svg)

[![Install Epicyon with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=epicyon)

> *This package allows you to install Epicyon quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview
ActivityPub server implementing S2S and C2S protocols, suitable for single board computers. Includes features such as moderation tools, post expiry, content warnings, and image descriptions

**Shipped version:** 01.03.2021

## Screenshots

![](https://user-content.gitlab-static.net/930ea132a7a3a86dbc20782644a54e80a646d5f3/68747470733a2f2f65706963796f6e2e6e65742f696d672f73637265656e73686f745f6c696768742e6a7067)

![](https://user-content.gitlab-static.net/3e7464f70018b45c4664ec28a98f3b39ea2258f8/68747470733a2f2f65706963796f6e2e6e65742f696d672f73637265656e73686f745f737461726c696768742e6a7067)

![](https://user-content.gitlab-static.net/3a2f50083b88e221883ae2d70ddf86a4d79ef466/68747470733a2f2f65706963796f6e2e6e65742f696d672f73637265656e73686f745f6c6f67696e2e6a7067)


## YunoHost specific features

#### Multi-user support

Are LDAP and HTTP auth supported? NO
Can the app be used by multiple users? Yes

#### Supported architectures

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/epicyon%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/epicyon/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/epicyon%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/epicyon/)


**More info on the documentation page:**
https://yunohost.org/packaging_apps

## Links

 * Report a bug: https://github.com/YunoHost-Apps/epicyon/issues
 * App website: https://epicyon.net/
 * Upstream app repository: https://gitlab.com/bashrc2/epicyon/
 * YunoHost website: https://yunohost.org/

---

## Developer info

**Only if you want to use a testing branch for coding, instead of merging directly into master.**
Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/epicyon/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/epicyon/tree/testing --debug
or
sudo yunohost app upgrade epicyon -u https://github.com/YunoHost-Apps/epicyon/tree/testing --debug
```
