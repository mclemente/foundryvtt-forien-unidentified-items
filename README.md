# FoundryVTT - Forien's Unidentified Items
![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/mclemente/foundryvtt-forien-unidentified-items?style=for-the-badge) 
![GitHub Releases](https://img.shields.io/github/downloads/mclemente/foundryvtt-forien-unidentified-items/latest/total?style=for-the-badge) 
![GitHub All Releases](https://img.shields.io/github/downloads/mclemente/foundryvtt-forien-unidentified-items/total?style=for-the-badge&label=Downloads+total)  

This module aims to provides system agnostic solution to handle unidentified items and their identification for games via Foundry Virtual Tabletop.

## Usage

**Please refer to Wiki for full information on [Usage](https://github.com/Forien/foundryvtt-forien-unidentified-items/wiki#usage)**  

Right click on items in sidebar, or use buttons on Item Sheet's header to Mystify an item. It will create new apparently blank item.

Mystified item can be fully edited and works just as a normal item in that system. However, GM can at any point peek at what the original item is (currently it's not possible to edit original data).

GM can also click on "Identify" button, which transforms entire Item into original, using embedded data.  
Data used during identification is decided upon at the time of mystification.

## Screenshots 

<img src="https://i.gyazo.com/1c440fd3a3d4867d3c96fcd3bd2cb585.png" alt="Mystify As - Transmogrify" width=400/><img src="https://i.gyazo.com/ee294dbe6fb2eeefe25c51ac9825b58f.png" alt="Advanced mystification" width=400/><br/><img src="https://i.gyazo.com/f862aa34e373c4c7f1e47adfb27e5bf6.png" alt="Mystified Acid Vial" width=400/><img src="https://i.gyazo.com/9a8e32db257136af9fa728c57e05201b.png" alt="Context Menu" width=200/><img src="https://i.gyazo.com/c8d75fc3c6f205655f3eb14e59f661bb.png" alt="Context Menu" width=200/>

## System Integration
One of main principles of this module is being [**System Agnostic**](https://github.com/Forien/foundryvtt-forien-unidentified-items/wiki#1-completely-system-agnostic). There is however, way of integrating systems.

Basic settings initialization (like setting default persisting properties for dnd5e) I will allow to be built-in this module. These can, however, be defined from the System's side.

#### What about logic? Skill Checks for Identification?

According to this module's Primary Principle, there will never be any system-specific logic in module. Feel free to integrate logic into your System or your Module, using API and Hooks

### How to integrate?

If you are **System** or **Module** developer, please read the [Developers Wiki](https://github.com/Forien/foundryvtt-forien-unidentified-items/wiki/Developers) for API and Hooks references.

## Translations

If you are interested in translating my module, simply make a new Pull Request with your changes, or contact me on Discord.

## Acknowledgments

* Icons were created by transforming assets made by Lorc and Willdabeast from [game-icons.net](https://game-icons.net/)
* Thanks to unsoluble for the idea for this Module!
* Thanks to KLO for providing Korean translation
* Thanks to rinnocenti for providing Portuguese (Brazil) translation
* Thanks to freyrrabbit for help with defining default properties for PF2e system
* Thanks to SalieriC for help with defining default properties for Swade system

## License

Forien's Unidentified Items is a module for Foundry VTT by Forien and is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).

This work is licensed under Foundry Virtual Tabletop [EULA - Limited License Agreement for module development from May 29, 2020](https://foundryvtt.com/article/license/).
