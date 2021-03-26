We at Cubed support and encourage proximity chat usage while playing on our network as proximity chat is usually a huge boost to the gameplay experience factor for yourself and others. It really is fun.

## What is Proximity Chat?
Proximity chat is a feature that mimics how sound travels in real-life. The closer another player gets to you, the louder their voice gets. The opposite is also true, as the further away from the player moves, the softer the sound gets.

## Instructions
### Pre-setup
Before we jump into this guide, we'll assume that you've downloaded and installed [Lunar Client](https://www.lunarclient.com/) onto your system. If you haven't, then please go ahead and do so now. Lunar Client will make it easier for you to connect with the VOIP service we'll use.

If you'd rather install the mod yourself that's used to link yourself to the VOIP service, please click [this link](https://www.minecraftforum.net/forums/mapping-and-modding-java-edition/minecraft-mods/1272675-1-16-5-mumblelink-forge-smp-lan-mumble-ts3) and learn more about MumbleLink and how to configure it.

!!! warning inline end
    If you're a Linux user, the implementation of MumbleLink done by the Lunar Client developers will not work. You may either resort to installing the mod manually or utilizing a virtual machine to get a proper connection to the Mumble VOIP service.
### Setup Mumble
1. Visit [https://mumble.info/downloads/](https://mumble.info/downloads/) and download the right version for your operating system.
2. Run the installer and follow the setup wizard.
    1. "Murmur (server)" is not required. Only "Mumble (client)" is required.
#### Configure Mumble
1. Go to the main Mumble window. [(click to view a screenshot)](https://raw.githubusercontent.com/cubed-mc/cubed-wiki/main/docs/wiki-media/start/proximity-chat/configure-mumble-step1.png)
2. Click "Configure" and complete the audio wizard. Follow each step carefully to get the best possible quality in the long run. [(click to view a screenshot)](https://raw.githubusercontent.com/cubed-mc/cubed-wiki/main/docs/wiki-media/start/proximity-chat/configure-mumble-step2.png)
    1. When you've arrived at [this](https://raw.githubusercontent.com/cubed-mc/cubed-wiki/main/docs/wiki-media/start/proximity-chat/configure-mumble-step2-1.png) step, do **not** check "Use headphones". If checked, it will ruin the realism of the positional audio.
#### Mumble Settings
You can access the Mumble settings by going to the configure tab and clicking "Settings...". [(click to view a screenshot)](https://raw.githubusercontent.com/cubed-mc/cubed-wiki/main/docs/wiki-media/start/proximity-chat/mumble-settings-step1.png)

We suggest you restart Mumble after applying all the settings found below.
##### Audio Input [(visual aid)](https://raw.githubusercontent.com/cubed-mc/cubed-wiki/main/docs/wiki-media/start/proximity-chat/mumble-settings-step1-1.png)
- Set "Echo Cancellation" to "Disabled" if you don't have any echoing in your environment.
- Tweak the colored bar under "Transmission" to make sure your voice is only in the green field when speaking. Any other noises or audio should only be in the reds, not in the yellow field.
- Copy the "Compression" settings to get the best possible audio quality. 
##### Audio Output [(visual aid)](https://raw.githubusercontent.com/cubed-mc/cubed-wiki/main/docs/wiki-media/start/proximity-chat/mumble-settings-step1-2.png)
- Make sure "Positional Audio" is checked.
- Lower "Output Delay" to the lowest possible value without lag/stuttering in other's voices.
- Un-check "while other users talk", "while you talk" and, "Attenuate other users while talking as Priority Speaker"
- Set "Minimum Distance" to the lowest possible value.
- Change your "Maximum Distance" to the max distance you wanna hear people from. (1 meter = 1 in-game block)
- Set "Minimum Volume" to the lowest possible value.
##### Plugins [(visual aid)](https://raw.githubusercontent.com/cubed-mc/cubed-wiki/main/docs/wiki-media/start/proximity-chat/mumble-settings-step1-3.png)
- Make sure "Link to Game and Transmit Position" is enabled.
- Make sure "Link vX.X.X" is enabled in the list of plugins.
#### Add Mumble server to list
1. Click "Server" and then "Connect..."
2. Press "Add New..." and input the following details:
    1. **Address:** play.cubed-mc.com (leave port as default)
    2. **Username:** Preferably your in-game username.
3. Press "OK"
#### Enabling Mumble support in-game
This step will be assuming you are planning to use Lunar Client. Do your own research if you are running a manual install of the MumbleLink mod.

1. Start Minecraft and Mumble and connect to our servers.
2. Press right-shift and select "Settings"
3. Search for "Mumble Link" and make sure you enable it.
4. Wait for "Minecraft linked." in the chat on the left inside of Mumble.
## Troubleshooting
If things aren't working out properly for you, go ahead and try the following things to see if there's a possible fix to your issue.

If none of the things mentioned below ends up working and fixing your issues, please contact the Cubed staff team for further assistance with your issue(s).
### I can hear everyone from anywhere!
- Make sure you enabled the MumbleLink mod and that Mumble did link itself with the game.
- Make sure your audio output has at least 2 channels. (contact for further assistance if unsure)
### I can't hear anyone!
- Make sure your Mumble volume isn't muted.
- Make sure your audio output device is selected to be the proper one.
### Voices are not moving around me
- Make sure "Audio Output: Positional Audio" is enabled
- Make sure you enabled the MumbleLink mod and that Mumble did link itself with the game.
- Make sure your audio output has at least 2 channels. (contact for further assistance if unsure)

We wish you the best of times on the Cubed network, and we hope that this guide was helpful for you.

If you have any suggestions for this guide, feel free to drop them in our Discord. And if you have any questions or issues regarding this guide, please contact our staff team for assistance.