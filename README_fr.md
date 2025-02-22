<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# AdGuard Home pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/adguardhome.svg)](https://dash.yunohost.org/appci/app/adguardhome) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/adguardhome.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/adguardhome.maintain.svg)

[![Installer AdGuard Home avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=adguardhome)

*[Read this readme in english.](./README.md)*

> *Ce package vous permet d’installer AdGuard Home rapidement et simplement sur un serveur YunoHost.
Si vous n’avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

AdGuard Home est un logiciel à l'échelle du réseau pour bloquer les publicités et le pistage. Après l'avoir configuré, il couvrira TOUS vos appareils domestiques et vous n'avez besoin d'aucun logiciel côté client pour cela.

Il fonctionne comme un serveur DNS qui redirige les domaines de pistage vers un "trou noir", empêchant ainsi vos appareils de se connecter à ces serveurs. Il est basé sur un logiciel que nous utilisons pour nos serveurs DNS publics AdGuard - les deux partagent beaucoup de code commun. 


**Version incluse :** 0.107.23~ynh1

## Captures d’écran

![Capture d’écran de AdGuard Home](./doc/screenshots/68747470733a2f2f63646e2e616467756172642e636f6d2f7075626c69632f416467756172642f436f6d6d6f6e2f616467756172645f686f6d652e676966.gif)

## Documentations et ressources

* Site officiel de l’app : <https://adguard.com/adguard-home.html>
* Documentation officielle utilisateur : <https://kb.adguard.com/en>
* Documentation officielle de l’admin : <https://github.com/AdguardTeam/AdGuardHome/wiki>
* Dépôt de code officiel de l’app : <https://github.com/AdguardTeam/AdGuardHome>
* Documentation YunoHost pour cette app : <https://yunohost.org/app_adguardhome>
* Signaler un bug : <https://github.com/YunoHost-Apps/adguardhome_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/adguardhome_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/adguardhome_ynh/tree/testing --debug
ou
sudo yunohost app upgrade adguardhome -u https://github.com/YunoHost-Apps/adguardhome_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>