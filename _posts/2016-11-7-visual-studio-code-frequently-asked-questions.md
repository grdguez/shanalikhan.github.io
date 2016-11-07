---
layout: post
title: Visual Studio Settings Sync Frequently Asked Questions
description : Frequenlty asked questions about the extensions.
---

Before Opening issues in the repository please check your exception here so you can solve your issue quickly.

### Exception Message 'Not Found'

```
{"message":"Not Found",
        "documentation_url":"https://developer.github.com/v3"}
```


This is due to **invalid Token**

Either dont have selected **GIST option** in scope while creating new token or not pasted the correct token.

Please reset the settings by sync reset settings command and then again try to download.

Check the Token exists in github with Gist Scope

Reference : [GitHub](https://developer.github.com/v3/#authentication)

![Goto Settings / Personal Access Tokens](http://shanalikhan.github.io/img/github2.PNG)