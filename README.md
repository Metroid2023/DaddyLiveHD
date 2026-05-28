To use the playlist-2 files, you need to use "m3u-playlist-proxy"
1. Next, download M3U Playlist Proxy and follow the directions on the read me. 
2. On the "m3u-playlist-proxy" page, fill in the info for playlist.m3u and add the required headers.

### Standard Playlist Information

**Playlist.m3u8**  
This is a standard M3U playlist. To use it, ensure your IPTV application supports custom headers, specifically `Referer`, `Origin`, and `User-Agent`. These headers are required to access the streams, and omitting them will result in a 403 error.

- **playlist.m3u8:** `https://tinyurl.com/yc3b4cbn`

#### Required Headers for playlist-2.m3u8
- **Referer:** `https://donis.jimpenopisonline.online/`
- **Origin:** `https://donis.jimpenopisonline.online`
- **User-Agent:** `Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/146.0.0.0 Safari/537.36`
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
#### dlhd.m3u8 playlist
- To use dlhd.m3u8 playlist, you need EasyProxy to make it work! https://github.com/realbestia1/EasyProxy
- 1. Install EasyProxy to docker in cmd: docker run -d --name EasyProxy --cap-add=NET_ADMIN --device /dev/net/tun -e ENABLE_WARP=true -p 7860:7860 ghcr.io/realbestia1/easyproxy:latest
  2. After installing EasyProxy, go to http://localhost:7860
  3. On that page, go to Playlist Builder.
  4. Insert this url to Playlist URL: https://raw.githubusercontent.com/Metroid2023/DaddyLiveHD/refs/heads/main/dlhd.m3u8 and press +
  5. Once the playlist have been Generated, copy the link from the Generated Link and use it on any player you have.
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
#### Note about playlist-2.m3u8
Only m3u-playlist-proxy works for playlist-2.m3u8 at the moment. I need to figure out how to extract the full playlist from DaddyLiveHD: https://dlhd.pk/24-7-channels.php
to make it work with m3u-playlist-proxy.

Playlist-2.m3u8 doesn't work anymore with m3u-playlist-proxy because now it uses token at the end of the m3u8 url.
