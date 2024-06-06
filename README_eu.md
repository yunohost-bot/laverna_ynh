<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Laverna YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/laverna.svg)](https://dash.yunohost.org/appci/app/laverna) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/laverna.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/laverna.maintain.svg)

[![Instalatu Laverna YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=laverna)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Laverna YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

Laverna is an anonymous system, encrypted and without registration required, it is accessible via a web browser (without software installation).
The data is private because it is stored by default on your machine (InnoDB and localstorage), it is a setting in the settings that will allow you to synchronize it via the cloud on your various devices.


**Paketatutako bertsioa:** 0.7.51~ynh6

**Demoa:** <https://laverna.cc/app/>

## Pantaila-argazkiak

![Laverna(r)en pantaila-argazkia](./doc/screenshots/laverna.png)

## :red_circle: Ezaugarri zalantzagarriak

- **Jatorrizko garapena utzita**: Software honek ez du arduradunik. Denborak aurrera egin ahala funtzionatzeari utziko dio, konpondu gabeko segurtasun arazoak izango ditu, etab.
- **Mantendu gabeko paketea**: YunoHost pakete honek ez du mantenduko duenik, bere gain hartuko duen norbaiten beharra dauka. Honek esan nahi duena da mantentze-lanak minimoak izango direla eta aplikazioa erabiltzen ez duten boluntarioek egingo dituztela lanok; denborak aurrera egin ahala fidagarri izateari utziko dio. [Aplikazioak nola paketatu](https://yunohost.org/packaging_apps_intro) ikas dezakezu, zure gain hartu nahi baduzu.

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://laverna.cc/index.html>
- Administratzaileen dokumentazio ofiziala: <https://github.com/Laverna/laverna/wiki>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/Laverna/laverna>
- YunoHost Denda: <https://apps.yunohost.org/app/laverna>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/laverna_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/laverna_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/laverna_ynh/tree/testing --debug
edo
sudo yunohost app upgrade laverna -u https://github.com/YunoHost-Apps/laverna_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
