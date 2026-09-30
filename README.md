# madstack
personal media server

mostly based on [mediastack]('https://github.com/geekau/mediastack')

create

create folders
```
export FOLDER_FOR_MEDIA=/mediastack  
export FOLDER_FOR_DATA=/mediastackdata  

export PUID=1000  
export PGID=1000  

sudo -E mkdir -p $FOLDER_FOR_DATA/{authelia/assets,bazarr,ddns-updater,gluetun,heimdall,homepage,jellyfin,jellyseerr,lidarr,mylar3,opensmtpd,plex,portainer,prowlarr,qbittorrent,radarr,readarr,sabnzbd,sonarr,swag,tdarr/{server,configs,logs},tdarr_transcode_cache,unpackerr,whisparr}  
sudo -E mkdir -p $FOLDER_FOR_MEDIA/media/{anime,audio,books,comics,movies,music,photos,tv,xxx}  
sudo -E mkdir -p $FOLDER_FOR_MEDIA/usenet/{anime,audio,books,comics,complete,console,incomplete,movies,music,prowlarr,software,tv,xxx}  
sudo -E mkdir -p $FOLDER_FOR_MEDIA/torrents/{anime,audio,books,comics,complete,console,incomplete,movies,music,prowlarr,software,tv,xxx}  
sudo -E mkdir -p $FOLDER_FOR_MEDIA/watch  
sudo -E chmod -R 775 $FOLDER_FOR_MEDIA $FOLDER_FOR_DATA  
sudo -E chown -R $PUID:$PGID $FOLDER_FOR_MEDIA $FOLDER_FOR_DATA  
```
