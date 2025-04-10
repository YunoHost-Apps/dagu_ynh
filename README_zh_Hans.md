<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 Dagu

[![集成程度](https://apps.yunohost.org/badge/integration/dagu)](https://ci-apps.yunohost.org/ci/apps/dagu/)
![工作状态](https://apps.yunohost.org/badge/state/dagu)
![维护状态](https://apps.yunohost.org/badge/maintained/dagu)

[![使用 YunoHost 安装 Dagu](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=dagu)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 Dagu。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

Dagu is a powerful Cron alternative that comes with a Web UI. It allows you to define dependencies between commands as a Directed Acyclic Graph (DAG) in a declarative YAML format. Dagu simplifies the management and execution of complex workflows. It natively supports running Docker containers, making HTTP requests, and executing commands over SSH.


**分发版本：** 1.16.7~ynh1

## 截图

![Dagu 的截图](./doc/screenshots/screenshot.png)

## 文档与资源

- 官方管理文档： <https://dagu.readthedocs.io/en/latest/>
- 上游应用代码库： <https://github.com/dagu-org/dagu>
- YunoHost 商店： <https://apps.yunohost.org/app/dagu>
- 报告 bug： <https://github.com/YunoHost-Apps/dagu_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/dagu_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/dagu_ynh/tree/testing --debug
或
sudo yunohost app upgrade dagu -u https://github.com/YunoHost-Apps/dagu_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
