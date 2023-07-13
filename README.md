# Creator Studio for Webtoon - Extension

## How to Manually Setup the Extension

### 1. Set up the Manifest
You will need to set up the `manifest.json` so that its `key` is set to a value that will allow the extension to maintain its id.

1. Download `.env` file from the appropriate location (i.e. check pinned post in the discord \#general).
2. Save it under the `ws-extension` folder (**NOT the `ws-extension/bin` folder**)
3. Run the `setup.sh` file. This will create `build/bin` folder.
4. The `build/bin/manifest.json` file now has its `key` value set up.

**IMPORTANT: DO NOT COMMIT OR PUSH `manifest.json`!!**
*Revert to the backup manifest json file before committing if manifest needs its value changed*

### 2. Sideload the Extension
<details open>
<summary><b>Google Chrome</b></summary>

1. Select **Settings and more (...)** > **More tools** > **Extensions**
2. Or enter `chrome://extensions` on the address bar.

![chrome-01](/images/howto_chrome_01.gif)


1. Turn on the **Developer mode** toggle.
2. Click **Load unpacked** button.
3. Select the `../ws-extension/build/bin` on the dialog.

**PLEASE NOTE THAT THE GIF BELOW SHOWS THE WRONG PATH TO THE BIN FOLDER**\
**USE THE `../ws-extension/build/bin` FOLDER FOR THE EXTENSION**

![chrome-03](/images/howto_chrome_02.gif)
</details>

<details>
<summary><b>Microsoft Edge</b></summary>

1. Select **Settings and more (...)** > **Extensions**
2. Click **Manage extensions**. Or enter `edge://extensions` on the address bar.

![edge-01](/images/howto_edge_01.gif)

3. Turn on the **Developer mode** toggle.
4. Click **Load unpacked** button.
5. Select the `../ws-extension/build/bin` on the dialog.

**PLEASE NOTE THAT THE GIF BELOW SHOWS THE WRONG PATH TO THE BIN FOLDER**\
**USE THE `../ws-extension/build/bin` FOLDER FOR THE EXTENSION**

![edge-02](/images/howto_edge_02.gif)
</details>
