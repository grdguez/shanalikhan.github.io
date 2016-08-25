---
layout: post
title: Visual Studio Code Settings Synchronization
description : synchronize your visual studio code settings across multiple machines. Whether your editor settings are changed in office you can set synchronize that settings in home editor also.
---

I have developed a small utility in order to synchronize your visual studio code settings across multiple machines. Whether your editor settings are changed in office you can set synchronize that settings in home editor also.

<blackquote>
<p>
<strong>MARKETPLACE URL : 
<a href="https://marketplace.visualstudio.com/items/Shan.code-settings-sync">Visual Studio Code Settings Sync</a></strong>
</p>
</blackquote>

> To Install : type "ext install code-settings-sync"

<strong> Type Sync in command to get all the commands </strong>


### Key Features


* Use your github account token.
* Easy to Upload and Download on one click.
* Saves all settings and snippets files.
* Upload Key : Shift + Alt + u
* Download Key : Shift + Alt + d
* Auto Download the settings when Visual Studio Code Starts.



### It Syncs

* Settings File
* Keybinding File
* Launch File
* Snippets Folder
* VSCode Extensions

	
## Steps To Get the Github Key.

This extension required your GitHub Account Personal Access Token. You can create one simple by looking into the following pictures.

#### Goto Settings / Personal Access Tokens / Generate New Token

![Goto Settings / Personal Access Tokens](/img/github1.PNG)

#### Select Scopes

![Select Scopes](/img/github2.PNG)

#### Get Unique Key

![Get Unique Key](/img/github3.PNG)

> You need to save this key for this extension for future use, and dont share this key with anyone as it will get your data without needing to logg in.

## Upload Your Settings For the first time


#### Type "Sync : Upload" in command

> Shortcut key is : Shift + Alt + u

It will open github account page. Enter the github account in the window and click enter.

![github account access token](/img/upload1.png)

#### Upload your settings automatically and give you GIST ID.

Copy this Gist ID in order to download the settings in other machines.

![uploaded automatically](/img/upload2.png)


## Download your Settings

#### Type "Sync : Download" in command

> Shortcut Key : Shift + Alt + d

Enter the github account in the window and click enter.

![github account access token](/img/upload1.png)

#### Enter Your GIST ID.

you need to enter your Gist ID in order to get the all files

![Enter Your GIST ID](/img/download2.png)

#### Settings Downloaded.

You are Done ! All your files are downloaded and it will start downloading your extensions in the background and will let you know to restart the VSCode in order to use the installed extensions.

![Enter Your GIST ID](/img/download3.png)


## Reset Token / GIST Settings

> Type ">Sync" In Command Palette and select Reset Token and GIST Settings

## Enable Auto Download
When token and GIST is filled up correctly, you can enable auto download the latest settings on the editor startup. This will save you to download all the settings from the cloud again and again in different systems. To enable :

**Select Command "Toggle Auto Download" command to Turn ON / OFF the auto download.**


> To Install : type "ext install code-settings-sync"


<blackquote>
<p>
<strong>MARKETPLACE URL :
<a href="https://marketplace.visualstudio.com/items/Shan.code-settings-sync">Visual Studio Code Settings Sync</a></strong>
</p>
</blackquote>
