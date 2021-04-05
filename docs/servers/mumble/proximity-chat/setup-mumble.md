### Install Mumble
1. Visit [https://mumble.info/downloads/](https://mumble.info/downloads/) and download the right installer for your system.
2. Run the installer and proceed with the setup wizard.
### Configure Mumble
1. Launch Mumble and make sure your screen looks like [this](https://raw.githubusercontent.com/cubed-mc/cubed-wiki/main/docs/servers/mumble/proximity-chat/media/configure-mumble-step1.png).
2. Click ["Configure"](https://raw.githubusercontent.com/cubed-mc/cubed-wiki/main/docs/servers/mumble/proximity-chat/media/configure-mumble-step2.png) and proceed with the audio wizard. Read each step carefully to get the best possible audio quality.
    1. When you reach [this step](https://raw.githubusercontent.com/cubed-mc/cubed-wiki/main/docs/servers/mumble/proximity-chat/media/configure-mumble-step2-1.png), do **not** check "Use headphones"—it will ruin the realism of the positional audio.
### Mumble Settings
You can access the Mumble settings by going to the configure tab and clicking ["Settings..."](https://raw.githubusercontent.com/cubed-mc/cubed-wiki/main/docs/servers/mumble/proximity-chat/media/mumble-settings-step1.png)). We suggest you restart Mumble after applying all the settings found below.
#### Audio Input 
<figure>
  <img src="https://raw.githubusercontent.com/cubed-mc/cubed-wiki/main/docs/servers/mumble/proximity-chat/media/mumble-settings-step1-1.png" width="300" />
  <figcaption>Example of what "Audio Input" should look like</figcaption>
</figure>

- Set "Echo Cancellation" to "Disabled" if you don't have any echo in your room.
- Tweak the colored bar under "Transmission" to make sure your voice is **only** in the green field when speaking. Any other background noise or audio should be in the reds.
- Copy the "Compression" settings from the image above to get the best possible audio quality. 
#### Audio Output 
<figure>
  <img src="https://raw.githubusercontent.com/cubed-mc/cubed-wiki/main/docs/servers/mumble/proximity-chat/media/mumble-settings-step1-2.png" width="300" />
  <figcaption>Example of what "Audio Output" should look like</figcaption>
</figure>

- Make sure "Positional Audio" is enabled.
- Lower "Output Delay" to the lowest possible value without lag in other's voices.
- Uncheck "while other users talk", "while you talk" and, "Attenuate other users while talking as Priority Speaker"
- Set "Minimum Distance" to the lowest possible value.
- Change your "Maximum Distance" to the max distance you wanna hear people from. (1m = 1 in-game block)
- Set "Minimum Volume" to the lowest possible value.
#### Plugins
<figure>
  <img src="https://raw.githubusercontent.com/cubed-mc/cubed-wiki/main/docs/servers/mumble/proximity-chat/media/mumble-settings-step1-3.png" width="300" />
  <figcaption>Example of what "Plugins" should look like</figcaption>
</figure>

- Make sure "Link to Game and Transmit Position" is enabled.
- Make sure "Link vX.X.X" is enabled in the list of plugins.
### Add Mumble server to list
1. Click "Server" and then "Connect..."
2. Press "Add New..." and enter the following details:
    1. **Address:** mumble.cubed-mc.com
    2. **Username:** Preferably your in-game username.
3. Press "OK"