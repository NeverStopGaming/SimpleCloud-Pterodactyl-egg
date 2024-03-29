# SimpleCloud-Pterodactyl-egg

---

### What is the SimpleCloud-Pterodactyl-egg?

- the SimpleCloud-Pterodactyl-egg is an egg which runs the [SimpleCloud](https://thesimplecloud.eu/) software inside of Pterodactyl.


### How to install the SimpleCloud-Pterodactyl-egg?

1. Download the [egg-SimpleCloud.json](https://raw.githubusercontent.com/NeverStopGaming/SimpleCloud-Pterodactyl-egg/main/egg-SimpleCloud.json) file from the [Github repository](https://github.com/NeverStopGaming/SimpleCloud-Pterodactyl-egg/blob/main/egg-SimpleCloud.json).
2. Go to your Pterodactyl panel and go to the **Nests** page and click **Import Egg** on the top right corner.
3. Select the **egg-SimpleCloud.json** file and chose your **nest**. Then click **Import**.
4. Now you can create a new server with the **SimpleCloud-Pterodactyl-egg**.

Note: You only need to enable one port for the cloud to work but if you want to use the [SimpleCloud-dashboard](http://dashboard-nossl.thesimplecloud.eu/) you need to enable a second port and edit it in `modules/rest/config.json`.

In order to join the server, your proxy port in `groups/proxies/proxy.json` must match the port you have enabled in Pterodactyl Network tab.
