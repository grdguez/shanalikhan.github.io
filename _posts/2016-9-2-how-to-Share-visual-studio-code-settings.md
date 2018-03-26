---

layout: post

title: How to share your visual studio code settings and extensions

description : Share your code settings and extensions with other users and let them download each of the settings and extensions you have instantly. 

---

You can now share your visual studio code settings with your users or team members, you will just edit the settings or upload your extensions, it will automatically download in your users computers.


Make sure you have Github Access Token. You need to [Configure](http://shanalikhan.github.io/2015/12/15/Visual-Studio-Code-Sync-Settings.html) it if its not setup.


### Creating GIST To Share

By default extension creates the secret GIST so only you can see it from your github page. So you need to create the public GIST so anyone can see your GIST contents.

> By command : Sync : Advance Options > Share Settings with Public GIST

It will remove your current Gist and create new public Gist and upload the settings. You can share your GIST ID with other users so they can download those settings using your gitHub Gist.


### Downloading The Settings From Shared GIST

Settings Sync, by default ask for Github Token to download the settings, but if you are download from Public Gist the token isnt required. You need to turn on the public Gist download mode as:

> By command : Sync : Advance Options > Download Settings from public Gist.

Now when you download the settings, it will download from the Public Gist that is avaiable in Code Settings file.

Extension dont allow users to edit or change the Gist of other Users.


Feel free to join our channel for discussion or comment below.
<a href="https://join.slack.com/t/codesettingssync/shared_invite/enQtMzE3MjY5NTczNDMwLTYwMTIwNGExOGE2MTJkZWU0OTU5MmI3ZTc4N2JkZjhjMzY1OTk5OGExZjkwMDMzMDU4ZTBlYjk5MGQwZmMyNzk">
<img src="https://shanalikhan.github.io/img/slack.PNG" alt="Drawing" style="width: 150px;"/>
</a>
