---
layout: post
title: Visual Studio Code Settings Sync Configurations
description : Edit the Setting JSON file manually for Visual Studio Code Settings Sync.
---

If the extension is not setup then dont edit this file and read the [Read me](http://shanalikhan.github.io/2015/12/15/Visual-Studio-Code-Sync-Settings.html)


In this page i'will be providing details of all the Settings Sync configurations.

There are two type of configurations for Settings Sync in terms of their scope.

* Gist Setting
* Global Settings

Setting Sync Global Settings are the setting which apply on all the Visual Studio Code environment while scope of Gist Settings are only limited to Visual Studio current environment.

For Example : Github Token is a part of Global Settings of two reasons, first its sensitive information for the user that we cannot allow to upload the github token alongwith code settings in Gist. Second its applicable with all Gist, its required to download any Gist.

**Gist Settings**

Gist Settings are stored in Visual Studio code `settings.json` with the `sync` prefixe and may vary with different Gists ( Visual Studio Environemnts) and will be replaced by the new downloaded Settings.

```javascript
{
    "sync.gist": "",
    "sync.lastUpload": "2018-03-04T14:21:39.841Z",
    "sync.autoDownload": false,
    "sync.autoUpload": false,
    "sync.lastDownload": "2018-03-04T14:21:39.841Z",
    "sync.forceDownload": true,
    "sync.host": "",
    "sync.pathPrefix": "",
    "sync.quietSync": false,
    "sync.askGistName": false,
    "sync.removeExtensions": true,
    "sync.syncExtensions": true
}

```

* **gist** : Github Gist ID
* **autoDownload** : `false` by default. If you set it to `true` it will download the settings automatically when code is started.
* **autoUpload** : `false` by default. It will start download process automatically when Visual Studio Loads when set to `true` , `false` will not allow extension to auto download the settings upon startup.
* **quietSync** : `false` by default. It will show the summary page when download or upload process completes displaying the files changed and extensions added or removed. Setting `false` will allow quiet process in the background and only notify via editor statusbar.
* **forceDownload** : `false` by default. If you set it to `true` it will overwrite the existing settings everytime the download process initiated either manually or on start.
* **syncExtensions** : `true` by default. It allows Settings Sync to sync your extensions list in gist so when you download it will automatically install the extensions list in code.
* **removeExtensions** : `true` by default. When `syncExtensions` is `true` and extensions list are downloaded. It allows Setting Sync to remove those extensions which are not a part of downloaded list of extensions. If you want to sync with new extensions and dont want to remove extra extensions keep this config to `false` Settings sync will not delete extensions.
* **host** and **pathPrefix** : `<empty>` by default. It allows Settings Sync to support GitHub Enterprise and perform actions on Company's GitHub Enterprise.
* **askGistName** : `false` by default. When set to `true` allows user to set Gist name while creating new one. Very helpful when you have multiple environments ( e.g Home Settings, Work Settings ) you can name those gist and download them by identifying.


**lastDownload** and **lastUpload** is just to keep record of download and upload status. You can set it to empty to hit manual download process.



 
**Global Settings**

Global Settings are stored in the same `User` folder with the file name `syncLocalSettings.json`. On Windows, this is `%APPDATA%\Code\User\syncLocalSettings.json`. On Mac its `$HOME/Library/Application Support/Code/User/syncLocalSettings.json` while on Linux its, `~/.config/Code/User/syncLocalSettings.json`.


```javascript
{
    "ignoreUploadFiles": [
        "projects.json",
        "projects_cache_vscode.json",
        "projects_cache_git.json",
        "projects_cache_svn.json",
        "gpm_projects.json",
        "gpm-recentItems.json"
    ],
    "ignoreUploadFolders": [
        "workspaceStorage"
    ],
    "replaceCodeSettings": {
        "http.proxy" :"",
        "files.autoSave" :"off"
    },
    "gistDescription": "Visual Studio Code Settings Sync Gist",
    "version": 290,
    "token": "",
    "downloadPublicGist": false,
    "supportedFileExtensions": [
        "json",
        "code-snippets"
    ]
}
```

**ignoreUploadFiles**  : All the files inside this key will stop extension to upload the files. You need to only write the file name of file. Any file found with this name inside User folder or subfolders won’t be uploaded.

Like in the above example, the projects.json and projects_cache_git.json will not be uploaded to Github Gist.

**ignoreUploadFolders** : All the folder names defined in it will not be uploaded in Gist, Folder can be child of User folder or child of any subfolder.

Like in the above example, workspaceStorage folder files will not be uploaded to Github Gist.

**gistDescription** : This is the name of gist you are going to create. Very helpful when you have multiple environments ( e.g Home Settings, Work Settings ) you can name those gist and download them by identifying.

**token**: The GitHub User secret identifier in order to allow Settings Sync upload and download the gist.

**supportedFileExtensions** : It allows Settings Sync to upload only the files in gist which extension are defined. Like it will only upload the of type `json` and `code-snippets`.

**downloadPublicGist** : If you are looking forward to make Setting Sync only download mode. For example, team member looking forward to the team environment. Set it to `true` and Settings Sync will only download the Gist and will never ask for token in order to download.

**replaceCodeSettings** :

```javascript
{
        "http.proxy" :"",
        "files.autoSave" :"off"
            
}
```

It will be used to replace the keys of settings.json with the text in the value after downloading the Gist.

For example, For users who are using proxy in one computer and dont want to set proxy in second one after downloading or need to change the value for proxy. They need to add value as above

After downloading the settings, extension will check if the value is defined, it will replace the the http.proxy value to defined value in settings.json after downloading.

If the value is not defined as some user dont want to use proxy in Home computer but they have proxy in office computer and they upload from office and it will have proxy in GIST to remove it from Home computer to make it work, the value need to set as empty so extension will delete the http.proxy from the Home computer.


Feel free to join Slack Community to discuss new ideas and scenarios and fix your problems if you have any.

<a href="https://join.slack.com/t/codesettingssync/shared_invite/enQtMzE3MjY5NTczNDMwLTYwMTIwNGExOGE2MTJkZWU0OTU5MmI3ZTc4N2JkZjhjMzY1OTk5OGExZjkwMDMzMDU4ZTBlYjk5MGQwZmMyNzk">
<img src="https://shanalikhan.github.io/img/slack.PNG" alt="Drawing" style="width: 150px;"/>
</a>

