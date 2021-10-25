# WorldEdit: Bedrock Edition
[![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=XXXJ5ETNT5PSN)

This is a Minecraft Bedrock addon port of the famous WorldEdit mod for Minecraft: Java Edition. The addon comes with custom commands to make building easier, and more fun! Not only are there commands, but also items to make it easier for anyone on any device to use this.
__Please note that this addon is currently in its beta stage, and requires experimental features. To be on the safe side, make a backup of your world.__

## Installation
### Locally
First you must download the mcaddon file. You can find one in the release section. After which, you open it with Minecraft and it will be imported into your game. Once there, choose a world you want to apply this addon to, and add the behaviour pack and resource pack together. The following experimental features must also be enabled.
![GameTest Framework and Holiday Creator Features](docs/Experimental_Features.jpg)
And that's it! Your world is ready for WorldEdit.

### Aternos server
To properly add this addon to the server, you first need to upload an already existing world with the required experimental features enabled. You must then install the addon separately in the server's `packs` folder. Read more about how aternos handles addons and experimental features [here](https://support.aternos.org/hc/en-us/articles/360042095232-Installing-Addons-Minecraft-Bedrock-Edition-) and [here](https://support.aternos.org/hc/en-us/articles/4407553257873-Enabling-experimental-gameplay-Minecraft-Bedrock-Edition-).

## Usage
The game will come with instructions on how to use WorldEdit in the How to Play section in settings while you're in the world.
![How to Play](docs/How_to_Play.jpg)

## Features
![Clipboard](docs/Clipboard.jpg)![Generation](docs/Generation.jpg)
WorldEdit currently has the following features.
- Clipboard manipulation (Cut, Copy, Paste)
- Masking blocks from certain actions
- Making cuboid region selections
- Navigation commands and the Navigation Wand
- Generating shapes
- Multiblock patterns
- Undo and Redo
- Filling selections

## Planned
These features will be added in the near future.
- Brushes
- More tools and items
- More selection shapes
- More selection operations
- More sophisticated patterns and masks
- No limit to selection size

## Contribution
### Bug Report
If you've encountered a bug with the addon, please do the following.
1. Check the [issues page](https://github.com/SIsilicon/WorldEdit-BE/issues) to see if your bug was already reported. If not continue with the steps.
2. In Minecraft, enable content log file and gui in `Settings > Creator`.
3. Reproduce the bug and go to `Setting > Creator > Content Log History` and copy the logs, if applicable.
4. Open a new [issue](https://github.com/SIsilicon/WorldEdit-BE/issues/new), state the bug, list the steps to reproduce and if you've got logs, paste them here too.
5. Submit! 

### Feature Request
The aim of this project is to replicate as many of the original WorldEdit features as possible, so if there's a feature you want that's in the original mod, it will likely be implemented anyway if possible.
However, you can still propose features that _aren't_ in the original mod, so long as you can make a case for how useful it can be. Then the proposal will be considered.

You submit proposals [here](https://github.com/SIsilicon/WorldEdit-BE/issues). Make sure that a similar proposal has not been made already.

## License
This addon is under the [GPLv3 license](LICENSE.txt). This means that you:
- CAN modify, copy and distribute this addon.
- CAN use it privately or for commercial use.
- CAN'T change the license of your modified version.
- CAN'T make the modified source code closed.
- HAVE TO indicate any changes in the modified version.

You also dont HAVE to credit me, but it would be great if you did! 😁

## Special Thanks
The backbone of this addon's code is notbeer's [GameTest API Wrapper](https://github.com/notbeer/Gametest-API-Wrapper).

And thanks to the original creator of the WorldEdit mod "sk89q" and [EngineHub](https://enginehub.org/) as a whole. They developed and excellent mod, and I'm just simply making a version of it work on bedrock. They're the real heroes. :) 

## Support
I kmow you already saw the badge at the top, but it took time and effort to make this addon, so if you can, please support me by donating via [PayPal](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=XXXJ5ETNT5PSN)!