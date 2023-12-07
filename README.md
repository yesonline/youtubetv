
<h1 align="center"> YouTubeTV </h1>

[![M3U generator for YouTube](https://github.com/yesonline/youtubetv/actions/workflows/m3u_Generator.yml/badge.svg)](https://github.com/yesonline/youtubetv/actions/workflows/m3u_Generator.yml)

`https://raw.githubusercontent.com/yesonline/youtubetv/main/youtube.m3u`

Updated m3u links of YouTube live channels, **auto-updated every 3 hours**.

### Usage
Paste this URL: `https://raw.githubusercontent.com/yesonline/youtubetv/main/youtube.m3u` to any player which supports M3U playlists

### Run the tool on your local machine
``` bash
git clone https://github.com/yesonline/youtubetv.git
cd YouTube_to_m3u
chmod +x autorun.sh
./autorun.sh
```
Do not forget to add a cron job set for every 4 hours(or 5) if you plan to run the script locally.
