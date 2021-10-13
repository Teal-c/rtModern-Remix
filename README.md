# rtModern-Remix - Thème ruTorrent

## Installation du thème : Remix

![alt text](https://raw.githubusercontent.com/Teal-c/rtModern-Remix/main/captures/capture-default.png "demo")

```
cd /var/www/rutorrent/plugins/theme/themes
```

```
git clone git://github.com/Teal-c/rtModern-Remix.git rtModern-Remix
```

```
chown -R www-data:www-data /var/www/rutorrent/plugins/theme/themes/rtModern-Remix
```

## Installation du thème : Plex

![alt text](https://github.com/Teal-c/rtModern-Remix/blob/main/captures/capure-plex.png "demo")

```
cd /var/www/rutorrent/plugins/theme/themes
```

```
git clone git://github.com/Teal-c/rtModern-Remix.git rtModern-Plex-v2

```
```
rm rtModern-Plex-v2/custom.css
cp rtModern-Plex-v2/themes/plex.css rtModern-Plex-v2/custom.css
```

```
chown -R www-data:www-data /var/www/rutorrent/plugins/theme/themes/rtModern-Plex-v2
```

## Installation du thème : Jellyfin

![alt text](https://github.com/Teal-c/rtModern-Jellyfin/blob/main/captures/capure-jellyfin.png "demo")

```
cd /var/www/rutorrent/plugins/theme/themes
```

```
git clone git://github.com/Teal-c/rtModern-Remix.git rtModern-Jellyfin

```
```
rm rtModern-Jellyfin/custom.css
cp rtModern-Jellyfin/themes/jellyfin.css rtModern-Jellyfin/custom.css
```

```
chown -R www-data:www-data /var/www/rutorrent/plugins/theme/themes/rtModern-Jellyfin
```

## Installation du thème : Light-Pink

![alt text](https://raw.githubusercontent.com/Teal-c/rtModern-Remix/main/captures/captures-light.png "demo")

```
cd /var/www/rutorrent/plugins/theme/themes
```

```
git clone git://github.com/Teal-c/rtModern-Remix.git rtModern-LightPink
```
```
rm rtModern-LightPink/custom.css
cp rtModern-LightPink/themes/light-pink.css rtModern-LightPink/custom.css
```

```
chown -R www-data:www-data /var/www/rutorrent/plugins/theme/themes/rtModern-LightPink
```

### Personnaliser les couleurs

Tout est dans le fichier custom.css, avec des exemples dans le dossier "themes".


### Les autres thèmes

URL : https://github.com/Teal-c/rtModern

---

### Script d'installation ruTorrent Bonobox

https://github.com/exrat/rutorrent-bonobox  

https://mondedie.fr/d/5399-script-installation-automatique-rutorrent-nginx  
