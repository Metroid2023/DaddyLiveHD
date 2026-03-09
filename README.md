Only playlist-headers.m3u8 works but you can't use it to record. You need a proxy to make it work to record.

To use the playlist files, you need to use "m3u-playlist-proxy"
1. Next, download M3U Playlist Proxy and follow the directions on the read me. 
2. On the "m3u-playlist-proxy" page, fill in the info for playlist.m3u and add the required headers.

### Standard Playlist Information

**Playlist.m3u8**  
This is a standard M3U playlist. To use it, ensure your IPTV application supports custom headers, specifically `Referer`, `Origin`, and `User-Agent`. These headers are required to access the streams, and omitting them will result in a 403 error.

- **Test:** `https://tinyurl.com/r6bsd7t2`

#### Required Headers
- **Referer:** `https://adffdafdsafds.sbs/`
- **Origin:** `https://adffdafdsafds.sbs`
- **User-Agent:** `Mozilla/5.0 (iPhone; CPU iPhone OS 17_7 like Mac OS X) AppleWebKit/605.1.15 (KHTML, like Gecko) Version/18.0 Mobile/15E148 Safari/604.1`
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
- **dlstreams:** `https://tinyurl.com/4ka32474`
- To use dlstreams playlist, you need EasyProxy to make it work: https://github.com/stremio-manager/EasyProxy
