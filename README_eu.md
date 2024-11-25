<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Element-Call YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/element-call.svg)](https://ci-apps.yunohost.org/ci/apps/element-call/) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/element-call.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/element-call.maintain.svg)

[![Instalatu Element-Call YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=element-call)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Element-Call YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

Group calls with WebRTC that leverage Matrix and an open-source WebRTC toolkit from LiveKit.


**Paketatutako bertsioa:** 0.7.0~ynh1

**Demoa:** <https://call.element.io/>

## Pantaila-argazkiak

![Element-Call(r)en pantaila-argazkia](./doc/screenshots/screenshot.jpg)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://call.element.io/>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/vector-im/element-call>
- YunoHost Denda: <https://apps.yunohost.org/app/element-call>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/element-call_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/element-call_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/element-call_ynh/tree/testing --debug
edo
sudo yunohost app upgrade element-call -u https://github.com/YunoHost-Apps/element-call_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
