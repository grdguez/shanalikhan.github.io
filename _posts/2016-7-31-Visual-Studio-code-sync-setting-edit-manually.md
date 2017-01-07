---
layout: post
title: Visual Studio Code Settings Sync Configurations
description : Edit the Setting JSON file manually for Visual Studio Code Settings Sync.
---

If the extension is not setup then dont edit this file and read the [Read me](http://shanalikhan.github.io/2015/12/15/Visual-Studio-Code-Sync-Settings.html)

**Note** : Github token is sensitive information for the user that we cannot allow to upload the github token alongwith code settings in Gist, so the only way to insert token is to add while starting the download and upload command process.


```javascript
{
    "sync.gist": "",
    "sync.version": 242,
    "sync.lastUpload": "2016-12-27T16:34:19.308Z",
    "sync.autoDownload": false,
    "sync.autoUpload": true,
    "sync.lastDownload": "2016-12-27T15:58:35.760Z",
    "sync.showSummary": true,
    "sync.forceDownload": true,
    "sync.workspaceSync": false,
    "sync.anonymousGist": false
}

```

* **gist** : Github Gist ID
* **version** : **Dont Change** , its for helping extension to run the migration process from old settings to new settings for the new versions when released.
* **autoDownload** : `false` by default. If you set it to `true` it will download the settings automatically when code is started.
* **autoUpload** : `false` by default. It will start download process automatically when Visual Studio Loads when set to `true` , `false` will not allow extension to auto download the settings upon startup.
* **showSummary** : `true` by default. It will show the summary page when download or upload process completes displaying the files changed and extensions added or removed. Setting `false` will allow quiet process in the background and only notify via editor statusbar.
* **forceDownload** : `false` by default. If you set it to `true` it will overwrite the existing settings everytime the download process initiated either manually or on start.
* **workspaceSync** : `false` by default. If you set it to `true` it will sync the workspaceStorage folder also. Only sync the `.json` files inside your workspaceStorage folder.
* **anonymousGist** : `false` by default. It you set it to `true` it will not ask for Github token upon uploading and downloading the Anonymous gist. It will always create Anonymous Gist for uploading as Github doesnt allow Anonymous Gist to update once created.

**lastDownload** and **lastUpload** is just to keep record of download and upload status. You can set it to empty to hit manual download process.

