# Genshin Windsong Lyre Midi Player ![GitHub release (latest by date)](https://img.shields.io/github/v/release/sabihoshi/GenshinLyreMidiPlayer) ![GitHub all releases](https://img.shields.io/github/downloads/sabihoshi/GenshinLyreMidiPlayer/total)

A MIDI to key player for Genshin Impact's Windsong Lyre made using C# and WPF using Windows Fluent design.

![2021-04-05_08-31-16](https://user-images.githubusercontent.com/25006819/113526431-989a4680-95ec-11eb-9896-47154c86b333.png)

## How to install

1. Download the latest version found here. [Download](https://github.com/sabihoshi/GenshinLyreMidiPlayer/releases/latest)
2. Run the program, no installation is required.
3. Open a .mid file by pressing the open file button at the top left.
4. Enable the tracks that you want to be played back.
5. Press play.

## Features
![GenshinLyreMidiPlayer_2021-04-07_13-50-29](https://user-images.githubusercontent.com/25006819/113817035-40a83f00-97a8-11eb-901e-0752fd28aebe.png)
* The ability to change the key. By default, it is keyed to C major.
* You can play multiple tracks of a MIDI file at the same time.
* You can enable transposing of notes, otherwise it will skip the notes entirely.
* Written in C# WPF with modern fluent design.
* Change the keyboard layout (QWERTZ, AZERTY, DVORAK, etc.)

### Play using your own MIDI Input Device
If you have your own MIDI instrument, this will let you play directly to the Genshin Lyre. This lets you play directly without using a MIDI file.

### [![](https://img.shields.io/badge/v1.5.0-New!-yellow)](https://github.com/sabihoshi/GenshinLyreMidiPlayer/releases/tag/v1.5.0) Hold notes & Merge nearby notes
  - You can set the player to hold sustained notes (does not really make a difference. Off by default.)
  - Some songs sound better when nearby notes are merged see [#4](https://github.com/sabihoshi/GenshinLyreMidiPlayer/issues/4) for an example

### Light Mode
You can set the player to light mode/dark mode (uses your system's theme by default.)
![GenshinLyreMidiPlayer_2021-04-05_08-58-35](https://user-images.githubusercontent.com/25006819/113526575-237b4100-95ed-11eb-813c-1e9c661624cf.png)

### Mini Mode
You can resize the player as small as you want and it should close the panels accordingly.
![GenshinLyreMidiPlayer_2021-04-05_08-55-34](https://user-images.githubusercontent.com/25006819/113526479-c67f8b00-95ec-11eb-9da4-bdf087488f5b.png)


## Upcoming
* Output into a "Piano Sheet" in a text file.
* History of opened MIDI files.

## About

### What are MIDI files?
MIDI files (.mid) is a set of instructions that play various instruments on what are called tracks. You can enable specific tracks that you want it to play. It converts the notes on the track into the keyboard inputs in Genshin Impact. Currently it is tuned to C major.

### Can this get me banned?
The short answer is that it's uncertain. I have used this in development with my own account for a week now and so far, I have not gotten banned. But use it at your own risk. Do not play songs that will spam the keyboard, listen to the MIDI file first and make sure to play only one instrument so that the tool doesn't spam keyboard inputs. [Here is miHoYo's response](https://genshin.mihoyo.com/en/news/detail/5763) to using 3rd party tools.

## Special Thanks
* Credits to [ShawzinBot](https://github.com/ianespana/ShawzinBot) by [ianespana](ianespana) where most of the inspiration comes from.
* Lantua for explaining to me music theory; what octaves, transposition, keys, and scales are.

## License
* This project is under the [MIT](LICENSE.md) license.
* © All rights reserved by miHoYo Co., Ltd. This project is not affiliated nor endorsed by miHoYo. Genshin Impact™ and other properties belong to their respective owners.
