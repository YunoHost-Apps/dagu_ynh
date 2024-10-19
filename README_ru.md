<!--
Важно: этот README был автоматически сгенерирован <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Он НЕ ДОЛЖЕН редактироваться вручную.
-->

# Dagu для YunoHost

[![Уровень интеграции](https://dash.yunohost.org/integration/dagu.svg)](https://ci-apps.yunohost.org/ci/apps/dagu/) ![Состояние работы](https://ci-apps.yunohost.org/ci/badges/dagu.status.svg) ![Состояние сопровождения](https://ci-apps.yunohost.org/ci/badges/dagu.maintain.svg)

[![Установите Dagu с YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=dagu)

*[Прочтите этот README на других языках.](./ALL_README.md)*

> *Этот пакет позволяет Вам установить Dagu быстро и просто на YunoHost-сервер.*  
> *Если у Вас нет YunoHost, пожалуйста, посмотрите [инструкцию](https://yunohost.org/install), чтобы узнать, как установить его.*

## Обзор

Dagu is a powerful Cron alternative that comes with a Web UI. It allows you to define dependencies between commands as a Directed Acyclic Graph (DAG) in a declarative YAML format. Dagu simplifies the management and execution of complex workflows. It natively supports running Docker containers, making HTTP requests, and executing commands over SSH.


**Поставляемая версия:** 1.14.5~ynh1

## Снимки экрана

![Снимок экрана Dagu](./doc/screenshots/screenshot.png)

## Документация и ресурсы

- Официальная документация администратора: <https://dagu.readthedocs.io/en/latest/>
- Репозиторий кода главной ветки приложения: <https://github.com/dagu-org/dagu>
- Магазин YunoHost: <https://apps.yunohost.org/app/dagu>
- Сообщите об ошибке: <https://github.com/YunoHost-Apps/dagu_ynh/issues>

## Информация для разработчиков

Пришлите Ваш запрос на слияние в [ветку `testing`](https://github.com/YunoHost-Apps/dagu_ynh/tree/testing).

Чтобы попробовать ветку `testing`, пожалуйста, сделайте что-то вроде этого:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/dagu_ynh/tree/testing --debug
или
sudo yunohost app upgrade dagu -u https://github.com/YunoHost-Apps/dagu_ynh/tree/testing --debug
```

**Больше информации о пакетировании приложений:** <https://yunohost.org/packaging_apps>
