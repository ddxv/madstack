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

sudo -E mkdir -p $FOLDER_FOR_DATA/{assets,bazarr,homarr,jellyfin,seerr,lidarr,opensmtpd,prowlarr,qbittorrent,radarr,readarr,sabnzbd,sonarr,tdarr/{server,configs,logs},tdarr_transcode_cache,unpackerr,whisparr}  
sudo -E mkdir -p $FOLDER_FOR_MEDIA/media/{audio,books,movies,music,tv}  
sudo -E mkdir -p $FOLDER_FOR_MEDIA/torrents/{audio,books,complete,console,incomplete,movies,music,prowlarr,software,tv}  
sudo -E mkdir -p $FOLDER_FOR_MEDIA/watch  
sudo -E chmod -R 775 $FOLDER_FOR_MEDIA $FOLDER_FOR_DATA  
sudo -E chown -R $PUID:$PGID $FOLDER_FOR_MEDIA $FOLDER_FOR_DATA  

```
