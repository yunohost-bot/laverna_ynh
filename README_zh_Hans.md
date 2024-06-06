<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 Laverna

[![集成程度](https://dash.yunohost.org/integration/laverna.svg)](https://dash.yunohost.org/appci/app/laverna) ![工作状态](https://ci-apps.yunohost.org/ci/badges/laverna.status.svg) ![维护状态](https://ci-apps.yunohost.org/ci/badges/laverna.maintain.svg)

[![使用 YunoHost 安装 Laverna](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=laverna)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 Laverna。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

Laverna is an anonymous system, encrypted and without registration required, it is accessible via a web browser (without software installation).
The data is private because it is stored by default on your machine (InnoDB and localstorage), it is a setting in the settings that will allow you to synchronize it via the cloud on your various devices.


**分发版本：** 0.7.51~ynh6

**演示：** <https://laverna.cc/app/>

## 截图

![Laverna 的截图](./doc/screenshots/laverna.png)

## :red_circle: 负面特征

- **Upstream not maintained**: This software is not maintained anymore. Expect it to break down over time, be exposed to unfixed security breaches, etc.
- **Package not maintained**: This YunoHost package is not actively maintained and needs adoption. This means that minimal maintenance is made by volunteers who don't use the app, so you should expect the app to lose reliability over time. You can [learn how to package](https://yunohost.org/packaging_apps_intro) if you'd like to adopt it.

## 文档与资源

- 官方应用网站： <https://laverna.cc/index.html>
- 官方管理文档： <https://github.com/Laverna/laverna/wiki>
- 上游应用代码库： <https://github.com/Laverna/laverna>
- YunoHost 商店： <https://apps.yunohost.org/app/laverna>
- 报告 bug： <https://github.com/YunoHost-Apps/laverna_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/laverna_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/laverna_ynh/tree/testing --debug
或
sudo yunohost app upgrade laverna -u https://github.com/YunoHost-Apps/laverna_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
