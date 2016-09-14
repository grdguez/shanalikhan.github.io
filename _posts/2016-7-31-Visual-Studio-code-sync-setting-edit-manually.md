---
layout: post
title: Visual Studio Sync Settings Edit Manually
description : Edit the Setting JSON file manually for Visual Studio Code Settings Sync.
---

If the extension is not setup then dont edit this file and read the [Read Me](http://shanalikhan.github.io/2015/12/15/Visual-Studio-Code-Sync-Settings.html)



Now you can easily edit the Settings here if you have all the things.

Settings is in complete JSON format so please make sure you dont break the JSON rules. When you make a edit, make sure you
have a backup JSON file to replace with in case of extension not working.

```javascript
{
    "Token": "xxxxx",
    "Gist": "xxxx",
    "lastUpload": "2016-08-30T21:31:02.462Z",
    "firstTime": true,
    "autoSync": true,
    "lastDownload": "2016-08-31T10:25:31.772Z",
    "ProxyIP": null,
    "ProxyPort": null,
    "Version": 223,
    "showSummary": true,
    "allowUpload": true,
    "publicGist": false,
    "forceDownload":true
}

```





JSON has two parts the **Token** and **GIST** which you need to add correctly to run extension.

**Don't change Version and Dates or it will stop working as expected.**

* **autoSync** : `true` by default. It will start download process automatically when Visual Studio Loads when set to `true` , `false` will not allow extension to auto download the settings upon startup.
*  **showSummary** : `true` by default. It will show the summary page when download or upload process completes displaying the files changed and extensions added or removed. Setting `false` will allow quiet process in the background and only notify via editor statusbar.
* **publicGist** : `false` by default. It tells the extension to either generate the public or secret GIST. `false` will generate secret GIST and `true` will generate public GIST.
* **version** : **Dont Change** , its for helping extension to run the migration process from old settings to new settings for the new versions when released.
* **forceDownload** : `false` by default. If you set it to `true` it will overwrite the existing settings everytime the download process initiated either manually or on start.