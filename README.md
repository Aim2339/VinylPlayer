# VinylPlayer for Rainmeter

A clean, animated vinyl record music player for Rainmeter. Features smooth physics-based rotation, a fully customizable UI, and seamless integration with web-based and desktop music players.

![Preview](https://github.com/user-attachments/assets/b2d4199a-1bc6-410a-a902-40a0ea12082c)

## Features

* **Animated Vinyl:** The record spins smoothly when music is playing and stops when paused.
* **Settings Menu:** A built-in GUI to change settings without editing code.
* **Customizable Design:**
    * **Theme Color:** Change the accent color of the label and controls using a color picker.
    * **Disc Radius:** Scale the player size up or down to fit your desktop.
    * **Background:** Adjust background color and opacity.
    * **Rotation Direction:** Toggle between Clockwise and Counter-Clockwise spinning.

## Requirements

1.  **Rainmeter:** Version 4.5 or newer.
2.  **WebNowPlaying Plugin:** Required for music integration.
    * **Supported Services:** Works with Spotify, YouTube, SoundCloud, and many others.
        * [View Supported Websites](https://wnp.keifufu.dev/supported-sites)
        * [View Supported Desktop Players](https://wnp.keifufu.dev/desktop-players)
    * **Browser Extension:** You must install the **WebNowPlaying Companion** for your browser:
        * [Chrome / Edge / Brave Extension](https://chromewebstore.google.com/detail/webnowplaying/jfakgfcdgpghbbefmdfjkbdlibjgnbli)
        * [Firefox Extension](https://addons.mozilla.org/en-US/firefox/addon/webnowplaying/)
    * *Note: If using desktop Spotify, [Spicetify](https://spicetify.app/) with the WebNowPlaying app is recommended for best performance.*

## Installation

1.  Download the latest release (`.rmskin`) from the releases page.
2.  Double-click the file to install it to Rainmeter.
3.  Load the skin via the Rainmeter Manage window.

**Manual Installation:**
1.  Clone this repository.
2.  Copy the `VinylPlayer` folder to `Documents\Rainmeter\Skins\`.
3.  Refresh Rainmeter.

## Usage

* **Play/Pause:** Click the Play/Pause button.
* **Next/Prev:** Use the arrow controls.
* **Seek:** Click anywhere on the progress bar.
* **Settings:** Right-click the skin and select **Settings**, or use the Context Menu context title.

## Configuration

All settings are persistent and saved in `@Resources\Variables.inc`. You can modify them via the Settings window or manually edit the file:

```ini
[Variables]
Scale=2.0           ; Global size multiplier
VinylRadius=22      ; Size of the disc
Direction=1         ; 1 = Clockwise, -1 = Counter-Clockwise
```
## Credits

* **Skin Creator:** Aim2339
* **WebNowPlaying Plugin:** [Redux](https://github.com/keifufu/WebNowPlaying-Rainmeter) - Core plugin for browser & Spotify integration.
* **RainRGB4 Addon:** [JSMorley](https://forum.rainmeter.net/viewtopic.php?t=6215) - Color picker utility.
