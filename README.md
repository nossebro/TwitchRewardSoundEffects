# TwitchRewardSoundEffects

Play sound effects depending on Twitch (Channel Points) Reward IDs. Requires [TwitchPubSubMirror](https://github.com/nossebro/TwitchPubSubMirror) to be installed, and that the subscription of Twitch Channel Points Rewards is enabled in its settings.

## Installation

1. Install the script in SLCB. (Please make sure you have configured the correct [32-bit Python 2.7.13](https://www.python.org/ftp/python/2.7.13/python-2.7.13.msi) Lib-directory).
2. Insert the API_Key.js by right-clicking the script in SLCB.
3. Reload all scripts, so the new API_Key.js file gets picked up.
4. Place mp3 files in the `sounds` subfolder, and name them `<reward-id>.mp3`.
