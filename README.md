# M3U-radio-player
wrestle with artifical dumbness (chat gpt 4o) for a few hours to create a m3u radio player, this page is not fully featured yet, but here are the things that currently does:

* local and/or online playlist loading support
* automatic checking of stream links and skipping unresponsive ones after 1 second of them not playing
* very basic audio normalization feature, most music should play at the same level of loudness
* basic playlist window that shows currently playing stream and can be clicked to play that spicifc entry
* add a basic visualizer, the bar numbers and width dynamically lower and increases based on the playing music

things i want to add, eventually:

* better styling for everything
* defualt set of streams that are loaded in automatically
* actual design of a proper audio player after the functionality is there

if you are on a chromium based web browser (chrome, vivaldi, opera, edge etc …) you are not able to listen to the most of the streams, here is an explanation from [chrome support](https://support.google.com/chrome/thread/29505473?hl=en&msgid=29673696) which tells you why this happens and how to fix it

> Usually this error occurs because the radio station you are trying to listen to is running on an unencrypted port (not 443). This is quite common and it's not technically necessary for radio stations to be encrypted but nowadays web browsers like Chrome have started disallowing unencrypted content to be shown in an otherwise encrypted websites. There is a few solutions for you right now:

*   Open Chrome (or other chromium web browsers), go to the website and then click on the padlock icon to the left of the URL box and then from the drop down menu select the 'Site Settings' option, you can then scroll down to the 'Insecure content' option at the bottom of the page and select 'Allow', this will create an exception for the website and allow you to continue using the player as before.

github pages are static, meaning this code runs on your device, you can just make a local copy of this page if you don't want to always open this page