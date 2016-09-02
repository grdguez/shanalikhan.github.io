layout: post
title: How to share your visual studio code settings and extensions
description : Share your code settings and extensions with other users and let them download each of the settings and extensions you have instantly. 
---

You can now share your visual studio code settings with other users, you will just edit the settings or upload your extensions, it will automatically download in your users computers.




Please make sure you have my extension installed in visual studio code. If you dont have you need to install it and go through the [Readme](http://shanalikhan.github.io/2015/12/15/Visual-Studio-Code-Sync-Settings.html) page to check how to use the extension.

> MARKETPLACE URL : **[Visual Studio Code Settings Sync]("https://marketplace.visualstudio.com/items/Shan.code-settings-sync)**


> To Install : type "ext install code-settings-sync" 


They wont be able to change your settings or extenion information so you can share your settings with your friends and teams. Following are the simple steps to do so: 


### Creating GIST To Share

**Set GIST Generation Mode to Public**

By default extension creates the secret GIST so only you can see it from your github page. So you need to create the public GIST so anyone can see your GIST contents.

> By command : Sync : Advanced Options > Sync : Toggle Public / Private GIST Mode.

It will show information message that public GIST mode is turned on.

**Upload your Settings**

Once you have enabled the public GIST Mode, you need to upload your settings. Once you upload your settings extension will generate new GIST ID and upload your editor settings and extensions there.

> By command : Sync : Update / Upload Settings. 

At the end of upload process , it will show the summary page which contains the **GIST ID** containing all the settings, you need to copy that ID and pass that ID to other users that have extension installed.


### Downloading The Settings From Shared GIST

**Fetch GIST By GIST ID**

Once you have the shared GIST ID, you need to setup in your extension by the command.

> By command : Sync : Advanced Settings > Fetch Other User's Settings

It will start downloading the settings and extensions from the shared GIST.

Your editor is configured !

By default , the auto download is enabled so when you start your editor it will automatically download the settings and extensions from the shared GIST.


> MARKETPLACE URL : **[Visual Studio Code Settings Sync]("https://marketplace.visualstudio.com/items/Shan.code-settings-sync)**


> To Install : type "ext install code-settings-sync" 



