# PinToMind / Infoskjermen Windows Player – releases

This repo only holds sideload releases of the Windows player. CI publishes them from the private source repo, and there is no code here.

The player is also available in the Microsoft Store, which is the easiest option when the device has Store access.

## Install (sideloading)

Download from the [latest release](https://github.com/favo/windows-player-releases/releases/latest):

1. **Trust the certificate (once per device).** Download [`PinToMindPlayer.cer`](https://github.com/favo/windows-player-releases/releases/latest/download/PinToMindPlayer.cer), open it, choose **Install Certificate → Local Machine**, and place it in **Trusted People**.
2. **Install the app.** Download and open [`PinToMindPlayer.appinstaller`](https://github.com/favo/windows-player-releases/releases/latest/download/PinToMindPlayer.appinstaller). The app checks this file at launch and updates itself when a new release is published.

**Offline / scripted install:** download [`PinToMindPlayer-offline.zip`](https://github.com/favo/windows-player-releases/releases/latest/download/PinToMindPlayer-offline.zip), unzip it and run `Install.ps1` in PowerShell.

## Stable links

These always point to the newest release:

```
https://github.com/favo/windows-player-releases/releases/latest/download/PinToMindPlayer.appinstaller
https://github.com/favo/windows-player-releases/releases/latest/download/PinToMindPlayer.msixbundle
https://github.com/favo/windows-player-releases/releases/latest/download/PinToMindPlayer.cer
https://github.com/favo/windows-player-releases/releases/latest/download/PinToMindPlayer-offline.zip
```
