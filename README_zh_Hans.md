<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 mStream

[![集成程度](https://dash.yunohost.org/integration/mstream.svg)](https://ci-apps.yunohost.org/ci/apps/mstream/) ![工作状态](https://ci-apps.yunohost.org/ci/badges/mstream.status.svg) ![维护状态](https://ci-apps.yunohost.org/ci/badges/mstream.maintain.svg)

[![使用 YunoHost 安装 mStream](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=mstream)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 mStream。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

mStream is a personal music streaming server. You can use mStream to stream your music from your home computer to any device, anywhere.

### Features

- Light on memory and CPU
- Tested on multi-terabyte libraries
- Runs on ARM boards like the Raspberry Pi


**分发版本：** 5.12.2~ynh2

**演示：** <https://demo.mstream.io/>

## 截图

![mStream 的截图](./doc/screenshots/mstreamv5.png)

## 文档与资源

- 官方应用网站： <https://mstream.io/>
- 上游应用代码库： <https://github.com/IrosTheBeggar/mStream>
- YunoHost 商店： <https://apps.yunohost.org/app/mstream>
- 报告 bug： <https://github.com/YunoHost-Apps/mstream_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/mstream_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/mstream_ynh/tree/testing --debug
或
sudo yunohost app upgrade mstream -u https://github.com/YunoHost-Apps/mstream_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
