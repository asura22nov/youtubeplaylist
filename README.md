# youtubeplaylist
youtube playlist using youtube-dl , jq and Sed all in windows

windows CMD command to create Youtube Playlist using youtube-dl, jq and sed windows executables in Windows OS 10.

```bash
youtube-dl -j --flat-playlist "<your youtube playlist web url>" | jq-win64.exe -r ".id" | sed.exe "s/^/https\:\/\/www\.youtube\.com\//" > full_playlist.log
```
