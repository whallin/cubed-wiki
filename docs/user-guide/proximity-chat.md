The process of enabling proximity chat is quite easy, and it takes no more than a few minutes to get a proper proximity chat up-and-running. So, let's get started on getting you up-and-running with your own proximity chat setup.

To lower the amount of wordiness and steps part of this guide, we'll be assuming you have already installed [Lunar Client](https://www.lunarclient.com/download/) solely for the ease of use.

**Note:** Lunar Client's implementation of "[Mumble Link](https://www.curseforge.com/minecraft/mc-mods/mumblelink)" will *not* work properly on systems running Linux distros. Please research into manually installing the mod for yourself in that case.

We apologize in advance if the screenshots in Swedish turns out to be confusing, the steps will be the same no matter language.

## Guide
1. Download [Mumble](https://www.mumble.info/downloads/) for your operating system.
2. Launch the installer and follow the on-screen wizard.
3. Once setup is done, add a new server to your list with the following connection details:
    1. **Address:** ``cubed.williamhallin.com`` (leave port as default)
    2. **Username:** Preferably your in-game username.
4. Press "OK" and then "Cancel"
5. Press "Configure" at the very top of the Mumble window, then "Settings..." [(View a screenshot)](https://cdn.discordapp.com/attachments/503829891566010368/823964516789387294/unknown.png)
6. Click "Audio Input" and copy the settings seen in [this screenshot.](https://cdn.discordapp.com/attachments/503829891566010368/823964626446188604/unknown.png) 
    1. Modify "Maximum Distance"/"Högsta avstånd" to your preferred value. This is the amount in blocks you'll be able to hear people from in-game.
    2. Do **not** change "Output Delay"/"Utgångsfördröjning", "Volume"/"Volym", or "Minimum Distance"/"Lägsta avstånd".
7. Press "Apply" and go to "Plugins"/"Insticksmoduler" and enable the marked setting seen [here.](https://cdn.discordapp.com/attachments/503829891566010368/823964920160190534/unknown.png)
8. Press "Apply" yet again, but this time restart your Mumble after you're done.
9. Connect to the server and press right-shift to open [this](https://cdn.discordapp.com/attachments/503829891566010368/823964002437824522/2021-03-23_17.57.42.png) menu.
10. Press "Settings" and search for "Mumble Link". You should now see [this mod](https://cdn.discordapp.com/attachments/503829891566010368/823964000655114240/2021-03-23_17.57.55.png), and make sure you enable it.

Now, you've officially turned on Mumble Link/proximity chat. Verify that it works in-game by just entering a conversation or trying it out together with a friend of yours.

If, for whatever reason, something is off and not working properly, please contact someone from the Cubed staff team for assistance on the issue. 

## Troubleshooting
### Can't hear players close to me
- Make sure your "Minimum Distance"/"Lägsta avstånd" in "Audio Output" in your Mumble settings is set to "1.0 m"
### No audio at all
- Make sure you have Mumble Link properly enabled in-game.
- Make sure you've turned on the setting at the very top located at "Plugins"/"Insticksmoduler".
- Make sure your audio output device is the correct one.
