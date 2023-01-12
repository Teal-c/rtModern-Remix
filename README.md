# rtModern - ruTorrent themes

Do the themes work with your installation?  
In order to fill the table, give me your configurations in the [issues](https://github.com/Teal-c/rtModern-Remix/issues). 😘


 . | ruTorrent | version
:---: | :---: | :---
:heavy_check_mark: | [Novik/ruTorrent](https://github.com/Novik/ruTorrent) | v3.10, v4.0-beta.1
:heavy_check_mark: | [crazy-max/docker-rtorrent-rutorrent](https://github.com/crazy-max/docker-rtorrent-rutorrent) | 3.10-0.9.8-0.13.8-r17 => 4.0-0.9.8-0.13.8
:heavy_check_mark: | [mondedie/rutorrent](https://github.com/mondediefr/docker-rutorrent) | 2022.06
:heavy_check_mark: | [exrat/rutorrent-bonobox](https://github.com/exrat/rutorrent-bonobox) | 2022/01/19


## rtModern-Remix

![alt text](https://raw.githubusercontent.com/Teal-c/rtModern-Remix/main/captures/capture-remix.png "demo")

```
cd /var/www/rutorrent/plugins/theme/themes
```

```
git clone https://github.com/Teal-c/rtModern-Remix.git rtModern-Remix
```

```
chown -R www-data:www-data rtModern-Remix
```

## rtModern-Plex

![alt text](https://github.com/Teal-c/rtModern-Remix/blob/main/captures/capure-plex.png "demo")

```
cd /var/www/rutorrent/plugins/theme/themes
```

```
git clone https://github.com/Teal-c/rtModern-Remix.git rtModern-Plex-v2
```
```
rm rtModern-Plex-v2/custom.css
cp rtModern-Plex-v2/themes/plex.css rtModern-Plex-v2/custom.css
```

```
chown -R www-data:www-data rtModern-Plex-v2
```

## rtModern-Jellyfin

![alt text](https://github.com/Teal-c/rtModern-Remix/blob/main/captures/capture-jellyfin.png "demo")

```
cd /var/www/rutorrent/plugins/theme/themes
```

```
git clone https://github.com/Teal-c/rtModern-Remix.git rtModern-Jellyfin-v2
```
```
rm rtModern-Jellyfin-v2/custom.css
cp rtModern-Jellyfin-v2/themes/jellyfin.css rtModern-Jellyfin-v2/custom.css
```

```
chown -R www-data:www-data rtModern-Jellyfin-v2
```

## rtModern-Jellyfin-bg

![alt text](https://github.com/Teal-c/rtModern-Remix/blob/main/captures/capture-jellyfin-bg.jpg "demo")

```
cd /var/www/rutorrent/plugins/theme/themes
```

```
git clone https://github.com/Teal-c/rtModern-Remix.git rtModern-Jellyfin-v2-bg
```
```
rm rtModern-Jellyfin-v2-bg/custom.css
cp rtModern-Jellyfin-v2-bg/themes/jellyfin-bg.css rtModern-Jellyfin-v2-bg/custom.css
```

```
chown -R www-data:www-data rtModern-Jellyfin-v2-bg
```

## rtModern-LightPink

![alt text](https://raw.githubusercontent.com/Teal-c/rtModern-Remix/main/captures/captures-light.png "demo")

```
cd /var/www/rutorrent/plugins/theme/themes
```

```
git clone https://github.com/Teal-c/rtModern-Remix.git rtModern-LightPink
```
```
rm rtModern-LightPink/custom.css
cp rtModern-LightPink/themes/light-pink.css rtModern-LightPink/custom.css
```

```
chown -R www-data:www-data rtModern-LightPink
```

### Customize the colors

All the color code is in custom.css, with examples in the "themes" folder.


---

### ruTorrent on mondedie/rutorrent docker image 

https://hub.docker.com/r/mondedie/rutorrent

https://mondedie.fr/d/11214-tuto-installer-limage-docker-rutorrent-de-mondediefr

### Installation on crazymax/docker-rtorrent-rutorrent docker image 

https://hub.docker.com/r/crazymax/rtorrent-rutorrent

https://www.forum-nas.fr/threads/tuto-installation-de-openvpn-jackett-prowlarr-rutorrent-qbittorrent-sonarr-radarr.16625/

### Install ruTorrent on Debian 11 (nginx and php-fpm) 

https://mondedie.fr/d/11708-tuto-installer-rutorrent-sur-debian-11-nginx-php-fpm
