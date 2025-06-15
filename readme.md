## huggingface
1. Sign up to [https://huggingface.co/](https://huggingface.co/).
2. In the top‑right corner, click the ➕ icon → **New Space**.
3. **Name**: enter `dproxy` (or any name you prefer).
4. **SDK**: choose **Docker**
5. **Visibility**: select **Public**
6. Click **Create Space**.
7. In the Files section, upload the Dockerfile from this repo (or create a file in huggingface named Dockerfile and paste the contents of the Dockerfile of this repo), commit then wait for it to build, start and run.
8. Click **Embed this Space**. It will show you the url of the space. Visit that url. If you see a ":)" then you are good to go.
9. Channels playlist is accessible via: **https://username-dproxy.hf.space/playlist/channels**. (Refresh playlist from your iptv player to update)</br>
   Events playlist is accessible via: **https://username-dproxy.hf.space/playlist/events**. (Refresh playlist from your iptv player to update)
10. Enjoy! </br>
Note: To update the proxy for new changes, click on **Settings** then click on **Factory rebuild**.

## docker-compose
1. Clone the repository
   ```bash
   git clone https://github.com/Metroid2023/DaddyLiveHD
   cd daddylive
   ```
2. Launch the service:
   ```bash
   docker-compose up -d --build
   ```
3. Visit the proxy at:
   ```text
   http://localhost:7860  
4. Channels playlist is accessible via: **http://localhost:50030/playlist/channels**. (Refresh playlist from your iptv player to update)</br>
   Events playlist is accessible via: **http://localhost:50030/playlist/events**. (Refresh playlist from your iptv player to update)
5. Enjoy! (For arm cpus, visit https://github.com/pigzillaaaaa/daddylive/issues/10)



## tip

<p align="left">
  <a href="https://ko-fi.com/pigzillaaaaa" target="_blank">
    <img src="https://cdn.ko-fi.com/cdn/kofi5.png" alt="Buy Me a Coffee" style="height:50px;" />
  </a>
</p>
Join our discord: https://discord.gg/aVuhm62hFU (#iptv)
