<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 Epicyon

[![集成程度](https://dash.yunohost.org/integration/epicyon.svg)](https://dash.yunohost.org/appci/app/epicyon) ![工作状态](https://ci-apps.yunohost.org/ci/badges/epicyon.status.svg) ![维护状态](https://ci-apps.yunohost.org/ci/badges/epicyon.maintain.svg)

[![使用 YunoHost 安装 Epicyon](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=epicyon)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 Epicyon。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

ActivityPub server implementing S2S and C2S protocols, suitable for single board computers. Includes features such as moderation tools, post expiry, content warnings, and image descriptions


**分发版本：** 2024.05.22~ynh1

## 截图

![Epicyon 的截图](./doc/screenshots/screenshot_starlight.jpg)

## 文档与资源

- 官方应用网站： <https://epicyon.net>
- 上游应用代码库： <https://gitlab.com/bashrc2/epicyon/>
- YunoHost 商店： <https://apps.yunohost.org/app/epicyon>
- 报告 bug： <https://github.com/YunoHost-Apps/epicyon_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/epicyon_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/epicyon_ynh/tree/testing --debug
或
sudo yunohost app upgrade epicyon -u https://github.com/YunoHost-Apps/epicyon_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
