---
layout: post
title: Visual Studio Code Sync Settings Release Notes
description : Release notes for visual studio code sync settings
---
Here are the release notes for each of the version released.

**Version - 2.2.3**
* Now you can create public GIST, instead of secret GIST so any one may see your settings.
* [#63](https://github.com/shanalikhan/code-settings-sync/issues/63). Now you can share your public GIST with anyone, they just need to enter your GIST ID in order to get your settings. They wont be able to edit your settings but when you change the GIST or any settings they will get the latest version of all the settings.
* Fixed [#72](https://github.com/shanalikhan/code-settings-sync/issues/72) , [#78](https://github.com/shanalikhan/code-settings-sync/issues/78) , [#79](https://github.com/shanalikhan/code-settings-sync/issues/79) , [#76](https://github.com/shanalikhan/code-settings-sync/issues/76) , [#73](https://github.com/shanalikhan/code-settings-sync/issues/73) ,[#75](https://github.com/shanalikhan/code-settings-sync/issues/75)

**Version - 2.1.0**

* Added Extension Summary Feature [#21](https://github.com/shanalikhan/code-settings-sync/issues/21). The information messages are removed when you initiate the download or upload process, it will show the summary that which files are downloaded/ uploaded alongwith the extensions which are downloaded or deleted (in case of download). Its a better understanding rather then showing information message of which files are uploaded or downloaded.
* Information messages showing in start-up was showing again and again when the download process initiated. To cover this i have made a summary page which tells the status, but you can also disable the summary page and keep a quite process but selecting Toggle Summary Page command. [#76](https://github.com/shanalikhan/code-settings-sync/issues/76).

**Version - 2.0.1**


* Added Automatic Syncing [#31](https://github.com/shanalikhan/code-settings-sync/issues/31). Now you can turn ON the auto download settings from the command and it will just download the latest settings everytime the editor is started. Feel free to report bug or send me a pull request :) if there are any. How to do that? Read Me post is updated, Visit there to get step by step.
* Fixed [#72](https://github.com/shanalikhan/code-settings-sync/issues/72)
* Added more exception handling in different places.

**Version - 1.6.0**

* Fixed [#53](https://github.com/shanalikhan/code-settings-sync/issues/53) with PR [#54](https://github.com/shanalikhan/code-settings-sync/pull/54).
* Added two commands- "Open Settings" and "How to configure"
* Open Settings command will open the JSON file to edit the settings manually.
* How to configure is for new users to open the guide easily.


**Version - 1.5.0**

* Implemented - [#39](https://github.com/shanalikhan/code-settings-sync/issues/39). When you are doing development in both Mac and Windows and you need to sync their key bindings both. Now you can have that! When you download the settings on new computer, it will download the respective OS latest saved key binding file. Have any idea to enhance, feel free to contact! :)


**Version - 1.4.0**


* Added functionality for delete extenions, when the user downloads the new extension file from the gitHub which has some extensions deleted that are in the computer. It will now delete those extenions.


**Version - 1.3.0**


* Merged Pull Request for Proxies Support [#37](https://github.com/shanalikhan/code-settings-sync/pull/37)



**Version - 1.2.3**


* Fixed Issue [#34](https://github.com/shanalikhan/code-settings-sync/issues/34)


**Version - 1.2.2**


* Removed Old Migration Code
* Added Release Notes menu in sync command

**Version - 1.2.0**


* Adding [locale.json](https://code.visualstudio.com/docs/customization/locales) sync support
