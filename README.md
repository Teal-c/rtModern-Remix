# rtModern - ruTorrent themes

 . | ruTorrent | version
:---: | :---: | :---
:heavy_check_mark: | [Novik/ruTorrent](https://github.com/Novik/ruTorrent) | v3.10, v4.0-beta.1
:heavy_check_mark: | [exrat/rutorrent-bonobox](https://github.com/exrat/rutorrent-bonobox) | 2022/01/19
:heavy_check_mark: | [crazy-max/docker-rtorrent-rutorrent](https://github.com/crazy-max/docker-rtorrent-rutorrent) | 3.10-0.9.8-0.13.8-r17


## rtModern-Remix

![alt text](https://raw.githubusercontent.com/Teal-c/rtModern-Remix/main/captures/capture-remix.png "demo")

```
cd /var/www/rutorrent/plugins/theme/themes
```

```
git clone git://github.com/Teal-c/rtModern-Remix.git rtModern-Remix
```

```
chown -R www-data:www-data /var/www/rutorrent/plugins/theme/themes/rtModern-Remix
```

## rtModern-Plex

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

## rtModern-Jellyfin

![alt text](https://github.com/Teal-c/rtModern-Remix/blob/main/captures/capture-jellyfin.png "demo")

```
cd /var/www/rutorrent/plugins/theme/themes
```

```
git clone git://github.com/Teal-c/rtModern-Remix.git rtModern-Jellyfin-v2
```
```
rm rtModern-Jellyfin-v2/custom.css
cp rtModern-Jellyfin-v2/themes/jellyfin.css rtModern-Jellyfin-v2/custom.css
```

```
chown -R www-data:www-data /var/www/rutorrent/plugins/theme/themes/rtModern-Jellyfin-v2
```

## rtModern-LightPink

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

### Customize the colors

All the color code is in custom.css, with examples in the "themes" folder.


---

### ruTorrent Bonobox installation script

https://github.com/exrat/rutorrent-bonobox  

https://mondedie.fr/d/5399-script-installation-automatique-rutorrent-nginx  

### Installation on crazymax/docker-rtorrent-rutorrent docker image 

https://www.forum-nas.fr/threads/tuto-changer-le-th%C3%A8me-de-rutorrent.16968/

### Install ruTorrent on Debian 11 (nginx and php-fpm) 
https://mondedie.fr/d/11708-tuto-installer-rutorrent-sur-debian-11-nginx-php-fpm
