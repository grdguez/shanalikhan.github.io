---
layout: post
title: Code Settings Sync Customizable Sync
description : Add any file or folder inside User folder not to upload / download
---

Extension will create the syncLocalSettings.json insider User folder upon code start and connect with it.

The JSON File will contain :

```
{
    "ignoreUploadFiles": [
        "projects.json",
        "projects_cache_git.json"
    ],
    "ignoreUploadFolders": [
        "workspaceStorage"
    ],
    "replaceCodeSettings": [
        {
            "name":"http.proxy",
            "value":""
        }
    ]
}
```

#### ignoreUploadFiles

All the files inside this key will stop extension to upload the files. You need to only write the file name of file. Any file found with this name inside User folder or subfolders won't be uploaded.

Like in the above example, the projects.json and projects_cache_git.json will not be uploaded to Github Gist.


#### ignoreUploadFolders

All the folder names defined in it will not be uploaded in Gist, Folder can be child of User folder or child of any subfolder.

Like in the above example, workspaceStorage folder files will not be uploaded to Github Gist.


##### replaceCodeSettings

```
{
            "name":"http.proxy",
            "value":""
}
```

It will be used to replace the keys of settings.json with the text in the value after downloading the Gist.

For example, For users who are using proxy in one computer and dont want to set proxy in second one after downloading or need to change the value for proxy.
They need to add value as above

After downloading the settings, extension will check if the value is defined, it will replace the the http.proxy value to defined value in settings.json after downloading.

If the value is not defined as some user dont want to use proxy in Home computer but they have proxy in office computer and they upload from office and it will have proxy in GIST to remove it from Home computer to make it work, the value need to set as empty so extension will delete the http.proxy from the Home computer.


Do you have more suggestion ? Post a comment or Open a Github Issue.