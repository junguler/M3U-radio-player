# M3U-radio-player
wrestle with chatgpt for a several hours to create a m3u radio player, this page is not fully featured yet, but here are the things that currently does:

* local and/or online playlist loading support
* automatic checking of stream links and skipping unresponsive ones after 1 second of them not playing
* very basic audio normalization feature, most music should play at the same level of loudness
* basic playlist window that shows currently playing stream and can be clicked to play that spicifc entry
* a basic visualizer, the bar numbers and width dynamically lower and increases based on the playing music
* defualt set 10 of streams that are automatically loaded in by
* add a timeline with elapsed duration at the left and cached time at the right
* make playlist entries always scroll to view
* add a stream info box with optional button copy current stream's info to clipboard
* add a optional [minimal](https://junguler.github.io/M3U-radio-player/minimal.html) version without visualizer

things i want to add, eventually:

* better styling for everything
* actual design of a proper audio player after the functionality is there

if you are on a chromium based web browser (chrome, vivaldi, opera, edge etc …) you are not able to listen to the most of the streams, here is an explanation from [chrome support](https://support.google.com/chrome/thread/29505473?hl=en&msgid=29673696) which tells you why this happens and how to fix it

> Usually this error occurs because the radio station you are trying to listen to is running on an unencrypted port (not 443). This is quite common and it's not technically necessary for radio stations to be encrypted but nowadays web browsers like Chrome have started disallowing unencrypted content to be shown in an otherwise encrypted websites. There is a few solutions for you right now:

*   Open Chrome (or other chromium web browsers), go to the website and then click on the padlock icon to the left of the URL box and then from the drop down menu select the 'Site Settings' option, you can then scroll down to the 'Insecure content' option at the bottom of the page and select 'Allow', this will create an exception for the website and allow you to continue using the player as before.

github pages are static, meaning this code runs on your device, you can just make a local copy of this page if you don't want to always open this page

this repo is made primarily as an auxiliary resource for my [m3u-radio-music-playlists](https://github.com/junguler/m3u-radio-music-playlists) repo and it's going to be linked there as well
