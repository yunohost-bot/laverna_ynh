<!--
Este archivo README esta generado automaticamente<https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
No se debe editar a mano.
-->

# Laverna para Yunohost

[![Nivel de integración](https://dash.yunohost.org/integration/laverna.svg)](https://dash.yunohost.org/appci/app/laverna) ![Estado funcional](https://ci-apps.yunohost.org/ci/badges/laverna.status.svg) ![Estado En Mantención](https://ci-apps.yunohost.org/ci/badges/laverna.maintain.svg)

[![Instalar Laverna con Yunhost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=laverna)

*[Leer este README en otros idiomas.](./ALL_README.md)*

> *Este paquete le permite instalarLaverna rapidamente y simplement en un servidor YunoHost.*  
> *Si no tiene YunoHost, visita [the guide](https://yunohost.org/install) para aprender como instalarla.*

## Descripción general

Laverna is an anonymous system, encrypted and without registration required, it is accessible via a web browser (without software installation).
The data is private because it is stored by default on your machine (InnoDB and localstorage), it is a setting in the settings that will allow you to synchronize it via the cloud on your various devices.


**Versión actual:** 0.7.51~ynh7

**Demo:** <https://laverna.cc/app/>

## Capturas

![Captura de Laverna](./doc/screenshots/laverna.png)

## :red_circle: Características no deseables

- **Upstream not maintained**: This software is not maintained anymore. Expect it to break down over time, be exposed to unfixed security breaches, etc.
- **Package not maintained**: This YunoHost package is not actively maintained and needs adoption. This means that minimal maintenance is made by volunteers who don't use the app, so you should expect the app to lose reliability over time. You can [learn how to package](https://yunohost.org/packaging_apps_intro) if you'd like to adopt it.

## Documentaciones y recursos

- Sitio web oficial: <https://laverna.cc/index.html>
- Documentación administrador oficial: <https://github.com/Laverna/laverna/wiki>
- Repositorio del código fuente oficial de la aplicación : <https://github.com/Laverna/laverna>
- Catálogo YunoHost: <https://apps.yunohost.org/app/laverna>
- Reportar un error: <https://github.com/YunoHost-Apps/laverna_ynh/issues>

## Información para desarrolladores

Por favor enviar sus correcciones a la [`branch testing`](https://github.com/YunoHost-Apps/laverna_ynh/tree/testing

Para probar la rama `testing`, sigue asÍ:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/laverna_ynh/tree/testing --debug
o
sudo yunohost app upgrade laverna -u https://github.com/YunoHost-Apps/laverna_ynh/tree/testing --debug
```

**Mas informaciones sobre el empaquetado de aplicaciones:** <https://yunohost.org/packaging_apps>
