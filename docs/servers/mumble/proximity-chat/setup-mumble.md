### Install Mumble
1. Visit [https://mumble.info/downloads/](https://mumble.info/downloads/) and download the right installer for your system.
2. Run the installer and proceed with the setup wizard.
#### Configure Mumble
1. Launch Mumble and make sure your screen looks like this.
<img src="https://raw.githubusercontent.com/cubed-mc/cubed-wiki/main/docs/servers/mumble/proximity-chat/media/configure-mumble-step1.png" width="300px" align="right">

2. Click "Configure" and complete the audio wizard. Follow each step carefully to get the best possible quality in the long run. [(click to view a screenshot)](https://raw.githubusercontent.com/cubed-mc/cubed-wiki/main/docs/servers/mumble/proximity-chat/media/configure-mumble-step2.png)
    1. When you've arrived at [this](https://raw.githubusercontent.com/cubed-mc/cubed-wiki/main/docs/servers/mumble/proximity-chat/media/configure-mumble-step2-1.png) step, do **not** check "Use headphones". If checked, it will ruin the realism of the positional audio.
#### Mumble Settings
You can access the Mumble settings by going to the configure tab and clicking "Settings...". [(click to view a screenshot)](https://raw.githubusercontent.com/cubed-mc/cubed-wiki/main/docs/servers/mumble/proximity-chat/media/mumble-settings-step1.png)

We suggest you restart Mumble after applying all the settings found below.
##### Audio Input 
[(Click me for visual aid)](https://raw.githubusercontent.com/cubed-mc/cubed-wiki/main/docs/servers/mumble/proximity-chat/media/mumble-settings-step1-1.png)

- Set "Echo Cancellation" to "Disabled" if you don't have any echoing in your environment.
- Tweak the colored bar under "Transmission" to make sure your voice is only in the green field when speaking. Any other noises or audio should only be in the reds, not in the yellow field.
- Copy the "Compression" settings to get the best possible audio quality. 
##### Audio Output 
[(Click me for visual aid)](https://raw.githubusercontent.com/cubed-mc/cubed-wiki/main/docs/servers/mumble/proximity-chat/media/mumble-settings-step1-2.png)

- Make sure "Positional Audio" is checked.
- Lower "Output Delay" to the lowest possible value without lag/stuttering in other's voices.
- Un-check "while other users talk", "while you talk" and, "Attenuate other users while talking as Priority Speaker"
- Set "Minimum Distance" to the lowest possible value.
- Change your "Maximum Distance" to the max distance you wanna hear people from. (1 meter = 1 in-game block)
- Set "Minimum Volume" to the lowest possible value.
##### Plugins 
[(Click me for visual aid)](https://raw.githubusercontent.com/cubed-mc/cubed-wiki/main/docs/servers/mumble/proximity-chat/media/mumble-settings-step1-3.png)

- Make sure "Link to Game and Transmit Position" is enabled.
- Make sure "Link vX.X.X" is enabled in the list of plugins.
#### Add Mumble server to list
1. Click "Server" and then "Connect..."
2. Press "Add New..." and input the following details:
    1. **Address:** mumble.cubed-mc.com (leave port as default)
    2. **Username:** Preferably your in-game username.
3. Press "OK"