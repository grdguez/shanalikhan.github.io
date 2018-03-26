---
layout: post
title: Visual Studio Code Settings Synchronization
description : synchronize your visual studio code settings across multiple machines. Whether your editor settings are changed in office you can set synchronize that settings in home editor also.
---

I have developed a small utility in order to synchronize your visual studio code settings across multiple machines. Whether your editor settings are changed in office you can set synchronize that settings in home editor also.

> MARKETPLACE URL : **[Visual Studio Code Settings Sync](https://marketplace.visualstudio.com/items/Shan.code-settings-sync)**


> To Install : type "ext install code-settings-sync"

**Type Sync in command Palette in order to view all commands.**

## Key Features

* Use your GitHub account token and Gist.
* Easy to Upload and Download on one click.
* Show a summary page at the end with details about config and extensions effected.
* Auto Download Latest Settings on Startup.
* Auto upload Settings on file change.
* Share the Gist with other users and let them download your settings.
* Supports GitHub Enterprise


## It Syncs

All the extensions and complete User Folder that Contains

* Settings File
* Keybinding File
* Launch File
* Snippets Folder
* VSCode Extensions Settings
* Workspaces


## Shortcuts

* Upload Key : Shift + Alt + U
* Download Key : Shift + Alt + D

	
### Steps To Get a Personal Access Token from GitHub

This extension requires a Personal Access Token from your GitHub account. You can create one by simply following the steps shown in the pictures below. Make sure you add **Gist** in scope.

#### Go to [Settings](https://github.com/settings) / [Developer settings](https://github.com/settings/tokens) / [Personal access tokens](https://github.com/settings/tokens) / Generate New Token**

![Goto Settings / Personal Access Tokens](http://shanalikhan.github.io/img/github1.PNG)

#### Select Gist From Scopes

![Select Scopes](http://shanalikhan.github.io/img/github2.PNG)

#### Get an Access Token

![Get Unique Key](http://shanalikhan.github.io/img/github3.PNG)

> Save the Token somewhere for future use (i.e. to upload from other machines).

### Upload Your Settings For the first time


#### Type "Sync : Upload" in command

> Shortcut key is : Shift + Alt + u

This will automatically open your GitHub settings page, allowing you to generate a new token for the application, as explained in the previous section. This token will allow the extension to create gists.

Enter the GitHub token in the window and click enter.

![github account access token](http://shanalikhan.github.io/img/upload1.png)

#### Upload your settings automatically and give you GIST ID.

Gist ID is needed to access the data you have uploaded with your token. Copy this Gist ID in order to download the settings to other machines. 

![uploaded automatically](http://shanalikhan.github.io/img/upload2.png)


You can always **verify created gist** on the following url:

> https://gist.github.com/{your_userName}/{gist_id}

Here is the gif of the complete process when you execute the Upload command (Might take some time to load)

![Upload](https://media.giphy.com/media/xT9IglKxSqs2Wdwq2c/source.gif)

### Download your Settings

#### Type "Sync : Download" in command it will ask your GitHub Gist ID

> Shortcut Key : Shift + Alt + d

#### Enter Your GitHub Token

Enter the GitHub token in the window and click enter.

![github account access token](https://shanalikhan.github.io/img/upload1.png)


#### Enter Your GIST ID.

You need to enter your Gist ID in order to download the files you have uploaded with Shift + Alt + U.

![Enter Your Gist ID](https://shanalikhan.github.io/img/download2.png)

#### Settings Downloaded.

You are Done ! All your files are downloaded and it will start downloading your extensions in the background and will let you know to restart the VSCode in order to use the installed extensions.

![Enter Your GIST ID](http://shanalikhan.github.io/img/download3.png)

Here is the gif of the complete process when you execute the Download command (Might take time to load)


![Download](https://media.giphy.com/media/xT9Iglsi3CS9noE8tW/source.gif)


### Reset Token / GIST Settings

> Type ">Sync" In Command Palette and select Reset Token and GIST Settings


### Toggle Auto Download

Auto Download is **disabled by default**. It will sync all the setting by default when the editor starts.
Please make sure you have valid github Token and Gist available to make it work properly.

Select Command **"Sync : Advance Options > Toggle Auto-Download On Startup"** command to Turn ON / OFF the auto download.

### Toggle Force Download

Force Download is **disabled by default**. By default extension wont download the latest settings if you already have latest downloaded version , but sometime when you delete some extension locally and dont upload the settings it will still show you have latest versions by date or time checks, by turning this ON it will always download the cloud settings on startup.

Please make sure you have valid github Token and Gist available to make it work properly.

Select Command **"Sync : Advance Options > Toggle Force Download"** command to Turn ON / OFF the force download.

### Toggle Auto-Upload on change

Auto-upload is **disabled by default**. When the settings are changed and saved this feature will automatic start the upload process and save the settings online.

Please make sure you have valid github Token and Gist available to make it work properly.

Select Command **"Sync : Advance Options > Toggle Auto-Upload on Setting Change"** command to Turn ON / OFF the auto-upload.


### Toggle Summary

Summary is **enabled by default** which shows all the files and extensions that are added or deleted in a single page.
You may turn it off in order to make a upload and download process clean and quiet.  

Select Command **"Sync : Advance Options > Toggle Summary Page On Upload / Download"** command to Turn ON / OFF the auto download.

### Create Public Gist To Share Settings

By default, it creates secret Gist so only you can see it but if you want to share your Gist with other users, you can set it to public.
You can't change the exiting Gist type from secret to public so it will reset the Gist ID so you can create new Gist with all the existing editor settings.

Select Command **"Sync : Advance Options > Share Settings with Public GIST"**

Other users can give your Gist Id to download the Gist, but they cant upload their settings on your Gist.


### Other Posts
For details regarding settings keys, click [here](http://shanalikhan.github.io/2016/07/31/Visual-Studio-code-sync-setting-edit-manually.html)

If you are want to share the settings with your users or team members, see the detailed post [here](http://shanalikhan.github.io/2016/09/02/how-to-Share-visual-studio-code-settings.html)


<a href="https://join.slack.com/t/codesettingssync/shared_invite/enQtMzE3MjY5NTczNDMwLTYwMTIwNGExOGE2MTJkZWU0OTU5MmI3ZTc4N2JkZjhjMzY1OTk5OGExZjkwMDMzMDU4ZTBlYjk5MGQwZmMyNzk">
<img src="https://shanalikhan.github.io/img/slack.PNG" alt="Drawing" style="width: 150px;"/>
</a>


If you enjoy this extension. How about donating, Your donation will help me to keep working and supporting this project.

[<img src="https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif">](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=4W3EWHHBSYMM8&lc=IE&item_name=Code%20Settings%20Sync&item_number=visual%20studio%20code%20settings%20sync&currency_code=USD&bn=PP%2dDonationsBF%3abtn_donate_SM%2egif%3aNonHosted)


> To Install : type "ext install code-settings-sync"

> MARKETPLACE URL : **[Visual Studio Code Settings Sync](https://marketplace.visualstudio.com/items/Shan.code-settings-sync)**
