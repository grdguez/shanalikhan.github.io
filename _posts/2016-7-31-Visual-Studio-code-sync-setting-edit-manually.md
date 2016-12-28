---
layout: post
title: Visual Studio Code Settings Sync Configurations
description : Edit the Setting JSON file manually for Visual Studio Code Settings Sync.
---

If the extension is not setup then dont edit this file and read the [Read me](http://shanalikhan.github.io/2015/12/15/Visual-Studio-Code-Sync-Settings.html)
Prior to Settings Sync 2.4. The extension was configured through its own configuration file that was in User folder.

After the version 2.4, the extension configuration settings has been changed. Users can configure the setting sync extension just by using the code own configuration settings.
Open the Visual Studio Code User Settings and update the information for the following keys.

**Note** : Github token is sensitive information for the user that we cannot allow to upload the github token alongwith code settings in Gist, so the only way to insert token is to add while starting the download and upload command process.


```javascript
{
    "sync.gist": "testID",
    "sync.version": 240,
    "sync.lastUpload": "2016-12-28T11:29:14.619Z",
    "sync.autoDownload": false,
    "sync.autoUpload": false,
    "sync.lastDownload": "2016-12-28T11:22:59.178Z",
    "sync.showSummary": true,
    "sync.forceDownload": true
}

```

* **gist** : Github Gist ID
* **autoUpload** : `false` by default. It will start download process automatically when Visual Studio Loads when set to `true` , `false` will not allow extension to auto download the settings upon startup.
* **showSummary** : `true` by default. It will show the summary page when download or upload process completes displaying the files changed and extensions added or removed. Setting `false` will allow quiet process in the background and only notify via editor statusbar.
* **publicGist** : `false` by default. It tells the extension to either generate the public or secret GIST. `false` will generate secret GIST and `true` will generate public GIST.
* **version** : **Dont Change** , its for helping extension to run the migration process from old settings to new settings for the new versions when released.
* **forceDownload** : `false` by default. If you set it to `true` it will overwrite the existing settings everytime the download process initiated either manually or on start.
* **autoDownload** : `false` by default. If you set it to `true` it will download the settings automatically when code is started.

**lastDownload** and **lastUpload** is just to keep record of download and upload status. You can set it to empty to hit manual download process.

