# Stream Deck Profiles

Stream Deck profiles by Matt Shields, sold on the Elgato Marketplace. This repo is the public place to report bugs and request changes.

## Profiles

| Profile | Platforms | Devices |
| --- | --- | --- |
| Stream Deck Tools for SolidCraft | macOS, Windows | Stream Deck XL, Stream Deck, Stream Deck MK.2, Stream Deck +, Stream Deck Neo, Stream Deck Mini |

More details: https://shields.tv/streamdeck/

## Reporting a bug

[Open an issue](https://github.com/mattboston/streamdeck-profiles/issues/new) and include:

- **Profile and version**, for example `SolidCraft Tools 1.0.0`. The version is in the profile name in the Stream Deck app.
- **Device**, for example Stream Deck XL.
- **OS and version**, for example macOS 26.1 or Windows 11.
- **App versions:** the Stream Deck app and the app the profile controls, for example SolidCraft 0.48.1.
- **Which key:** the page path and key label, for example Model › Sketch › Dimension › Driven dim.
- **What happened** and **what you expected**.

Before you report a key that does nothing:

- Make sure the app the profile controls is the active window.
- Re-import the shortcut file that came with the profile. Each profile version has its own shortcut file, and keys stop working if the two don't match.
- Check whether another app or a system shortcut uses the same key combination. The `button-map` file in the download lists the combination each key sends.

## Requesting a change

Open an issue for a missing command, a layout change, a new device or support for another app. Say which profile and device it's for.

## Notes

- Issues are public. Don't post order numbers, receipts or personal details.
- The profiles are independent community projects. They aren't made, endorsed or supported by the makers of the apps they control. Report bugs in those apps to their developers.
