---
layout: post
title: Visual Studio Code Sync Settings Release Notes
description : Release notes for Visual Studio Code Sync Settings
---
Here are the release notes for each of the version released.

**v3.2.9** - April 18,2019

* Bug : Fixed Code that kills Extension Host for MacOS [#827](https://github.com/shanalikhan/code-settings-sync/issues/827) - Thanks for PR [#834](https://github.com/shanalikhan/code-settings-sync/pull/834) by [@arnohovhannisyan](https://github.com/arnohovhannisyan)
* Bug : Download From Public Gist not working [#816](https://github.com/shanalikhan/code-settings-sync/issues/816)
* Bug : Auto Upload Fix [#832](https://github.com/shanalikhan/code-settings-sync/issues/832) - Thanks for PR [#835](https://github.com/shanalikhan/code-settings-sync/pull/835) by [@arnohovhannisyan](https://github.com/arnohovhannisyan)
* Improvement - Inserts some empty lines in the beginning of `settings.json` [#819](https://github.com/shanalikhan/code-settings-sync/issues/819) - Thanks for PR [#828](https://github.com/shanalikhan/code-settings-sync/pull/828) by [@arnohovhannisyan](https://github.com/arnohovhannisyan)
* Wiki : Update Documentation - Thanks for PR [#828](https://github.com/shanalikhan/code-settings-sync/pull/845) by [@colinaaa](https://github.com/colinaaa)



**v3.2.8** - April 04,2019

* Bug : auto upload doesn't work when make change on settings [#801](https://github.com/shanalikhan/code-settings-sync/issues/801) -  Thanks for PR [#807](https://github.com/shanalikhan/code-settings-sync/pull/807) by [@arnohovhannisyan](https://github.com/arnohovhannisyan)
* Bug : Auto Upload / Download : Disable change detection for workspace storage folder [#708](https://github.com/shanalikhan/code-settings-sync/issues/708) -  Thanks for PR [#811](https://github.com/shanalikhan/code-settings-sync/pull/811) by [@knyhle](https://github.com/knyhle)
* Pretiffy Custom Settings JSON -  Thanks for PR [#812](https://github.com/shanalikhan/code-settings-sync/pull/812) by [@knyhle](https://github.com/knyhle)
* Improvement - Remove manual visx package installation in favour of extension download by CLI [#820](https://github.com/shanalikhan/code-settings-sync/issues/820)
* Improvement - Remove replaceCodeSettings from Settings Sync configurations [#805](https://github.com/shanalikhan/code-settings-sync/issues/805)

**v3.2.7** - March 06,2019

* Bug : Fixing Extensions Sync on Windows [#789](https://github.com/shanalikhan/code-settings-sync/issues/789) -  Thanks for PR [#791](https://github.com/shanalikhan/code-settings-sync/pull/791) by [@LuisUrrutia](https://github.com/LuisUrrutia)

**v3.2.6** - March 05,2019

* Bug : Syncing of extensions not working in portable mode [#756](https://github.com/shanalikhan/code-settings-sync/issues/756) -  Thanks for PR [#782](https://github.com/shanalikhan/code-settings-sync/pull/782) by [@LuisUrrutia](https://github.com/LuisUrrutia)
* Bug : Fixing NODE_TLS_REJECT_UNAUTHORIZED [#776](https://github.com/shanalikhan/code-settings-sync/issues/776) -  Thanks for PR [#779](https://github.com/shanalikhan/code-settings-sync/pull/779) by [@MattMorgis](https://github.com/MattMorgis)
* Documentation Updated
* Packages Updated


**v3.2.5** - Feb 15,2019

* Bug : Not working with VSCode 1.31 [#762](https://github.com/shanalikhan/code-settings-sync/issues/762) -  Thanks for PR [#763](https://github.com/shanalikhan/code-settings-sync/pull/763) by [@nekonenene](https://github.com/nekonenene)
* Bug : Multi-line settings aren't ignored properly using sync pragma [#701](https://github.com/shanalikhan/code-settings-sync/issues/701) -  Thanks for PR [#750](https://github.com/shanalikhan/code-settings-sync/pull/750) by [@ioprotium](https://github.com/ioprotium)
* Packages updated, small improvements


**Version - 3.2.3** - 11 Dec, 2018

* Startup : Long startup activation time on the first start [#656](https://github.com/shanalikhan/code-settings-sync/issues/656) -  Thanks for PR [#717](https://github.com/shanalikhan/code-settings-sync/pull/717) by [@thejewdude](https://github.com/thejewdude)
* Feature : Adding coder.com support [#714](https://github.com/shanalikhan/code-settings-sync/issues/714) - Thanks for PR [#720](https://github.com/shanalikhan/code-settings-sync/pull/720) by [@deansheather](https://github.com/deansheather)

**Version - 3.2.2** - 26 Nov, 2018

* Sync Advance Setting Menu doesnt open when JSON not Valid [#683](https://github.com/shanalikhan/code-settings-sync/issues/683)


**Version - 3.2.1** - 26 Nov, 2018

* Bug : Only install missing extensions in Portable Vs Code [#687](https://github.com/shanalikhan/code-settings-sync/issues/687)
* Bug : Error: Cannot read property 'token' of undefined [#685](https://github.com/shanalikhan/code-settings-sync/issues/685)
* Bug : sync-ignore isn't ignoring my local value, it deletes it [#686](https://github.com/shanalikhan/code-settings-sync/issues/686)
* Bug : Download of extension packages failed [#642](https://github.com/shanalikhan/code-settings-sync/issues/642) - Thanks for PR [#705](https://github.com/shanalikhan/code-settings-sync/pull/705) by [@emptyother](https://github.com/emptyother)




**Version - 3.2.0** - 17 Oct, 2018

* Prompt to reload VSCode after installing extensions [#629](https://github.com/shanalikhan/code-settings-sync/issues/629)
* Keep output of CLI installation command [#628](https://github.com/shanalikhan/code-settings-sync/issues/628)
* Dont write default settings sync config to code settings.json [#513](https://github.com/shanalikhan/code-settings-sync/issues/513)
* vscodium download settings fails [#650](https://github.com/shanalikhan/code-settings-sync/issues/650) - Thanks for PR [#651](https://github.com/shanalikhan/code-settings-sync/pull/651) by [@stripedpajamas](https://github.com/stripedpajamas)
* Does not work with Portable Visual Studio Code [#331](https://github.com/shanalikhan/code-settings-sync/issues/331)
* Flatpak Support for Settings Sync [#621](https://github.com/shanalikhan/code-settings-sync/issues/621) - Thanks for PR [#657](https://github.com/shanalikhan/code-settings-sync/pull/657) by [@laloch](https://github.com/laloch)
* Per-platform / per-hostname inline settings [#640](https://github.com/shanalikhan/code-settings-sync/issues/640) - Thanks for PR [#667](https://github.com/shanalikhan/code-settings-sync/pull/667) by [@ioprotium](https://github.com/ioprotium)
* Idea/Suggestion: Adds support to sync custom files [#258](https://github.com/shanalikhan/code-settings-sync/issues/258) - Thanks for PR [#258](https://github.com/shanalikhan/code-settings-sync/pull/258) by [@tkrtmy](https://github.com/tkrtmy)




**Version - 3.1.2**
* Extension CLI Download Improvements.

**Version - 3.1.1**
* Fixed : Extension Download fails for Code Insiders and mac Users [#618](https://github.com/shanalikhan/code-settings-sync/issues/618)
* Fixed : Upload issues for mac [#622](https://github.com/shanalikhan/code-settings-sync/issues/622)

**Version - 3.1.0**
* Option to Install Extensions Using CLI [#434](https://github.com/shanalikhan/code-settings-sync/issues/434)
    - Code Team hasn't provided API to install extension, but as CLI is available Settings Sync will start using code cli to download extensions. Live Status will be displayed while downloading.
    - Note : This feature wont work in Mac as I cant test on Mac. You will be facing problems, for this I need Mac users to help and fix it.
    - Fixes : [#337](https://github.com/shanalikhan/code-settings-sync/issues/337), [#566](https://github.com/shanalikhan/code-settings-sync/issues/566) and [#577](https://github.com/shanalikhan/code-settings-sync/issues/577)
* Unify the code style by using tslint and prettier - Thanks for PR [#595](https://github.com/shanalikhan/code-settings-sync/pull/595) by [@axetroy](https://github.com/axetroy)
    - Fixes : [#578](https://github.com/shanalikhan/code-settings-sync/issues/578), [#597](https://github.com/shanalikhan/code-settings-sync/issues/597), [#486](https://github.com/shanalikhan/code-settings-sync/issues/486) by upgrading all the packages like Github Api.
* Don't introduce "sync.*" settings which is equal to default behavior after DL/UL - [#513](https://github.com/shanalikhan/code-settings-sync/issues/513)
    - Settings Sync configuration has been changed, Readme is updated.
* Added German localization - Thanks for PR [#588](https://github.com/shanalikhan/code-settings-sync/pull/588) by [@ljosberinn](https://github.com/ljosberinn)
* Missing partial i18n translation - Thanks for PR [#593](https://github.com/shanalikhan/code-settings-sync/pull/593) by [@axetroy](https://github.com/axetroy)
* Documentation Improvement - Thanks for PR [#603](https://github.com/shanalikhan/code-settings-sync/pull/603) by [@MastaCoder](https://github.com/MastaCoder)
* Fix slack img in README and Update tutorial message - Thanks for PR [#607](https://github.com/shanalikhan/code-settings-sync/pull/607) and [#608](https://github.com/shanalikhan/code-settings-sync/pull/608) by [@fr3fou](https://github.com/fr3fou)
* Ignored extensions can be accidentally deleted if removeExtensions is enabled. - Thanks for PR [#604](https://github.com/shanalikhan/code-settings-sync/pull/604) by [@leepowellcouk](https://github.com/leepowellcouk)
* Error Translation - Thanks for PR [#616](https://github.com/shanalikhan/code-settings-sync/pull/616) by [@Xiongqi-XQ](https://github.com/Xiongqi-XQ)

**Version - 3.0.0**

* Bug Fix for OSS Variant  [#549](https://github.com/shanalikhan/code-settings-sync/issues/549) - Thanks for PR [@rudfoss](https://github.com/rudfoss)
* Support i18n for extension - Currently Supports English and Chinese [#581](https://github.com/shanalikhan/code-settings-sync/issues/581) - Thanks for PR [@axetroy](https://github.com/axetroy)
* Added Functionality to ignore extension in settings sync [#523](https://github.com/shanalikhan/code-settings-sync/pull/523) - Thanks for PR [@leepowellcouk](https://github.com/leepowellcouk)
* Setting to disable opening of github page [#576](https://github.com/shanalikhan/code-settings-sync/pull/576)
* Update adm-zip to the latest version [#551](https://github.com/shanalikhan/code-settings-sync/pull/551)



**Version - 2.9.1**

* Bug Fix for OSS Variant  [#510](https://github.com/shanalikhan/code-settings-sync/issues/510) - Thanks for PR [@JacobHenner](https://github.com/JacobHenner)
* Readme Typo Fix [#531](https://github.com/shanalikhan/code-settings-sync/issues/531) - Thanks for PR [@x4m3](https://github.com/x4m3)
* syncLocalSettings does not support replacing setting with "False" value [#516](https://github.com/shanalikhan/code-settings-sync/issues/516) - Thanks for PR [@leepowellcouk](https://github.com/leepowellcouk)
* add support for xdg environment paths [#532](https://github.com/shanalikhan/code-settings-sync/pull/532) - Thanks for PR [@Dennor](https://github.com/Dennor)



**Version - 2.9.0**

*Important* : Github is going to [disable anonymous Gist](https://blog.github.com/2018-02-18-deprecation-notice-removing-anonymous-gist-creation/) from March 19, 2018. Anonymous Gist support has been removed from Settings Sync.

* Settings Sync now support OSS Variant  [#77](https://github.com/shanalikhan/code-settings-sync/issues/77) - By @LC43
* Settings Sync now support "code-snippets" files and other snippets extensions [#340](https://github.com/shanalikhan/code-settings-sync/issues/340)
* Now you can configure settings sync not to delete extensions on download [#373](https://github.com/shanalikhan/code-settings-sync/issues/373)
* Now you can exclude extensions list while uploading [#389](https://github.com/shanalikhan/code-settings-sync/issues/389)
* If you are looking to use Settings Sync to download settings only. (e.g Fetch Team Environment) - Bug has been fixed [#487](https://github.com/shanalikhan/code-settings-sync/issues/487)


**Version - 2.8.7**

* Token dialog will appear when you hit download command [#461](https://github.com/shanalikhan/code-settings-sync/issues/461)
* Documentation Improved [#467](https://github.com/shanalikhan/code-settings-sync/pull/467) - By @Modelmat



**Version - 2.8.6**

* Bug Fix : [#444](https://github.com/shanalikhan/code-settings-sync/issues/444) - Added support for Latest VS Code.
* Documentation Improved [#448](https://github.com/shanalikhan/code-settings-sync/pull/448) (By : @textortexxel)


**Version - 2.8.5**

* Bug Fix : [#440](https://github.com/shanalikhan/code-settings-sync/issues/440)
* Summary will be displayed on Code Output Window [#137](https://github.com/shanalikhan/code-settings-sync/issues/137) (By : @ThisIsManta)
* Extension installation message improved [#359](https://github.com/shanalikhan/code-settings-sync/issues/359)


**Version - 2.8.4**

* Fixing extension after API Changes [#428](https://github.com/shanalikhan/code-settings-sync/issues/428) (By : @sonhanguyen)
* Added GIF for Upload and Download for readme (By : @mmakarios)
* Documentation Improved (By : @VictorioBerra , @eliasmeire )
* Typo Fix ( By : @guiconti )


**Version - 2.8.3**

* Allow to set multiple gist Description [#319](https://github.com/shanalikhan/code-settings-sync/issues/319). gist you create will have custom name, for example : Home Settings , Office Settings. It will allow you to switch between multiple Gist in single Click, in future updates.
* Fixing [#374](https://github.com/shanalikhan/code-settings-sync/issues/374)
* Fixing [#363](https://github.com/shanalikhan/code-settings-sync/issues/363)
* Fixing [#352](https://github.com/shanalikhan/code-settings-sync/issues/352)
* Sometimes on downloading, User enter GitHub token instead of GIST causing extension failing. Documentation is updated to verify the created Gist. [#343](https://github.com/shanalikhan/code-settings-sync/issues/343)


**Version - 2.8.2**

* Improved code for [#343](https://github.com/shanalikhan/code-settings-sync/issues/343) as GitHub API shows "Not Found" Exception on connection. Alot of users are reporting this over time so  I have decided to add new [option](https://github.com/shanalikhan/code-settings-sync/issues/343) to store settings in local drive so you guys can set path of local one drive to export settings there and let one drive do the upload and import from the file location.
* Fixing [#342](https://github.com/shanalikhan/code-settings-sync/issues/342)
* If you have MacOS and looking forward to do some work on [#343](https://github.com/shanalikhan/code-settings-sync/issues/343) let me know, i will assist you as i dont have Mac environment.


**Version - 2.8.0**

* Fixing [#322](https://github.com/shanalikhan/code-settings-sync/issues/322)
* Fixing [#289](https://github.com/shanalikhan/code-settings-sync/issues/289)
* Fixing [#320](https://github.com/shanalikhan/code-settings-sync/issues/320)
* Fixing [#310](https://github.com/shanalikhan/code-settings-sync/issues/310) : Now you can set github token manually from the sync local settings.


**Version - 2.7.0**


* Fixing [#296](https://github.com/shanalikhan/code-settings-sync/issues/296) : Now you can easily setup your Gist description while creating new gist.
* Fixing [#295](https://github.com/shanalikhan/code-settings-sync/issues/295) : If user try to change other users gist, extension will show logs displaying the current user and the gist owner user.
* Fixing [#232](https://github.com/shanalikhan/code-settings-sync/issues/232) : Now you can decide which settings you want to upload.


**Version - 2.6.2**

* Fixing [#263](https://github.com/shanalikhan/code-settings-sync/issues/263)
* Fixing [#192](https://github.com/shanalikhan/code-settings-sync/issues/192)


**Version - 2.6.1**

* Added Support for Github Enterprise

**Version - 2.5.1**

* Local Settings Layout Change - New Layout [here](http://shanalikhan.github.io/2017/02/19/Option-to-ignore-settings-folders-code-settings-sync.html)



**Version - 2.5.0**

* Fixing Bugs [#225](https://github.com/shanalikhan/code-settings-sync/issues/225)
* Fixing Bugs [#229](https://github.com/shanalikhan/code-settings-sync/issues/229)
* Fixing Bugs [#233](https://github.com/shanalikhan/code-settings-sync/issues/233)


**Version - 2.4.4**

* Added Feature [#100](https://github.com/shanalikhan/code-settings-sync/issues/100) - Detailed post on [here](http://shanalikhan.github.io/2017/02/19/Option-to-ignore-settings-folders-code-settings-sync.html)
* Extension Enhanced [#203](https://github.com/shanalikhan/code-settings-sync/issues/203)
* Fixing Bugs [#206](https://github.com/shanalikhan/code-settings-sync/issues/206)
* Fixing Bugs [#213](https://github.com/shanalikhan/code-settings-sync/issues/213)



**Version - 2.4.3**

* Fixing Bugs [#190](https://github.com/shanalikhan/code-settings-sync/issues/190)
* Fixing Bugs [#194](https://github.com/shanalikhan/code-settings-sync/issues/194)
* Gist Uploaded will contains extension version information for future work.


**Version - 2.4.2**

* workspaces is configurable default as false
* Fixing Bug [#161](https://github.com/shanalikhan/code-settings-sync/issues/161)
* Supporting Anonymous Gists [#180](https://github.com/shanalikhan/code-settings-sync/issues/180)

**Version - 2.4.0**

* This version is currently released for Code version 1.9 users that are currently insiders. Once I make sure that its working fine, i will publish 2.4.1 in next week for normal build users.
* [#167](https://github.com/shanalikhan/code-settings-sync/issues/167) Changed the name from Visual Studio Code Settings Sync to Settings Sync for better understanding.
* [#168](https://github.com/shanalikhan/code-settings-sync/issues/168) Added workspaces sync feature - User can now sync all the workspaces alongwith the settings across multiple machines that will include tasks.json and other files.
* [#111](https://github.com/shanalikhan/code-settings-sync/issues/111) Previously the extension was configured by its own settings file. But now it will be configured using Code's own configuration settings.
* [#144](https://github.com/shanalikhan/code-settings-sync/issues/144) Sharing settings are more easier it will remove the existing Gist and create new public Gist and upload the settings. Users can download the other users Gist but cannot make changes to other User Gist.
* Bugs Resolved [#161](https://github.com/shanalikhan/code-settings-sync/issues/161)


**Version - 2.3.4**

* Proxy Support Added [#60](https://github.com/shanalikhan/code-settings-sync/issues/60). It will now support http.proxy settings from code settings.json file.
* Auto upload settings on extension remove and install will be done in 2.4 version as there is limitation in vscode, i have already opened an [issue](https://github.com/Microsoft/vscode/issues/14444) in code repository. 


**Version - 2.3.3**


* Improvements with auto upload.
* Fixed [#117](https://github.com/shanalikhan/code-settings-sync/issues/117) , [#97](https://github.com/shanalikhan/code-settings-sync/issues/97)


**Version - 2.3.1**

* Added auto-upload feature , disable by default. It will start uploading process when any of the setting is changed automatically.
* Exception handling Added
* Reverted [#97](https://github.com/shanalikhan/code-settings-sync/issues/97) and fixed [#106](https://github.com/shanalikhan/code-settings-sync/issues/106)

**Version -2.2.7**

* Fixed [#105](https://github.com/shanalikhan/code-settings-sync/issues/105) , [#101](https://github.com/shanalikhan/code-settings-sync/issues/101) , [#95](https://github.com/shanalikhan/code-settings-sync/issues/98) , [#96](https://github.com/shanalikhan/code-settings-sync/issues/96) , [#93](https://github.com/shanalikhan/code-settings-sync/issues/93) and [#90](https://github.com/shanalikhan/code-settings-sync/issues/90)



**Version - 2.2.4**

* Added Toggle Force Download options to initiate download process even you have the latest settings.
* Open URL when settings are opened and other small tweaks.


**Version - 2.2.3**

* Now you can create public GIST, instead of secret GIST so any one may see your settings.
* [#63](https://github.com/shanalikhan/code-settings-sync/issues/63). Now you can share your public GIST with anyone, they just need to enter your GIST ID in order to get your settings. They wont be able to edit your settings but when you change the GIST or any settings they will get the latest version of all the settings.
* Fixed [#78](https://github.com/shanalikhan/code-settings-sync/issues/78) , [#79](https://github.com/shanalikhan/code-settings-sync/issues/79) , [#73](https://github.com/shanalikhan/code-settings-sync/issues/73) ,[#75](https://github.com/shanalikhan/code-settings-sync/issues/75)


**Version - 2.1.0**

* Added Extension Summary Feature [#21](https://github.com/shanalikhan/code-settings-sync/issues/21). The information messages are removed when you initiate the download or upload process, it will show the summary that which files are downloaded/ uploaded alongwith the extensions which are downloaded or deleted (in case of download). Its a better understanding rather then showing information message of which files are uploaded or downloaded.
* Information messages showing in start-up was showing again and again when the download process initiated. To cover this i have made a summary page which tells the status, but you can also disable the summary page and keep a quite process but selecting Toggle Summary Page command. [#76](https://github.com/shanalikhan/code-settings-sync/issues/76).

**Version - 2.0.1**


* Added Automatic Syncing [#31](https://github.com/shanalikhan/code-settings-sync/issues/31). Now you can turn ON the auto download settings from the command and it will just download the latest settings everytime the editor is started. Feel free to report bug or send me a pull request :) if there are any. How to do that? Read Me post is updated, Visit there to get step by step.
* Fixed [#72](https://github.com/shanalikhan/code-settings-sync/issues/72)
* Added more exception handling in different places.



_Previous Build from v2 notes are removed_
