# RitoSkin

Custom skins have become an integral part of the League of Legends community, allowing players to personalize their gaming experience.

- Custom skins and skin hacks are prevalent in the community.
- While custom skins are permitted by Riot Games, skin hacks are strictly prohibited.
- Unfortunately, some individuals exploit this by charging for custom skins or selling unauthorized skin hacks on the black market.
- Riot Games should either allow free access to official skins or take stronger measures to prevent unauthorized use.
- Custom artist-made skins can cost up to $300, while official chroma skins may be priced around $200, raising questions of fairness and accessibility.

RitoSkin aims to address these issues by providing an open-source solution for creating and managing custom skins. Our goal is to make skin customization accessible to all players.

> We hold that gaming culture should be inclusive and accessible, not just a privilege for those who can afford it.

## Features

RitoSkin offers a comprehensive set of tools for skin customization. At its core, the project utilizes advanced methods to retrieve skin data from the game files. This data can then be modified, allowing users to create unique skins or alter existing ones.

A key feature of RitoSkin is its ability to convert these custom skins into a format compatible with the default game skins, ensuring seamless integration. To make the process user-friendly, we've developed a graphical interface that simplifies skin management tasks.

Additionally, RitoSkin includes an automated skin processing system. This feature organizes champion skins into a structured folder system, streamlining the management and application of skin modifications.

## Installation

To get started with RitoSkin, follow these steps:

1. Download the latest release from our [Releases](https://github.com/nylish/ritoskin/releases) page.
2. Extract the contents to a directory of your choice.
3. Ensure you have the necessary dependencies installed.

> [!IMPORTANT]
> RitoSkin requires `cslol-dll.dll` to function correctly. Please obtain this file in accordance with LeagueToolkit's licensing terms and place it in the `resources\cslol` folder of your RitoSkin installation.

### Why isn't `cslol-dll.dll` included in the resources folder?

The `cslol-dll.dll` is part of the cslol-patcher project, which is owned by LeagueToolkit. We do not have the rights to redistribute it or provide direct download links. You must acquire it yourself while complying with their license terms.

## Updating Hashes

- [Update-ritobin-hashes](https://youtu.be/-zzso5CYZMY)

RitoSkin relies on up-to-date hash lists to function optimally. To keep these hashes current, we recommend using the CommunityDragon Toolbox. Here's how to use it:

## Usage

Using RitoSkin involves few steps:

### Updating hashes and preparing the files
1. Download `RitoBin` and update the hashes.
2. Use a .wad reader to extract the champion files you wish to modify. We recommend [Obsidian](https://github.com/Crauzer/Obsidian).
3. Next, enter the folder that you've just scraped and go to `data/characters/`
4. Copy all of its contents to process_champions/ folder inside `src/ritoskin_extractor/`

### Processing

After preparing the files, execute `ritoskin.exe`.
> Using RitoBin, this program goes inside each skin, convert it to `.py`, apply the necessary changes, convert it to `.bin` again and store inside `skins_extracted` inside of the champion folder.
That's it. You'll have all fles needed inside of each skin folder. If you want to change the IDs to the skin name and compress to .fantome, you can run `index_output_names.py`. All
compressed files will be available inside the `output/` folder

> [!NOTE]
> To ensure smooth execution of the Python script, you may need to install some external libraries using `pip install <requirement name>`

Finally, use a custom skin loader to apply your newly created or modified skin in-game.

> [!WARNING]
> Always ensure you're using the latest hash lists to avoid compatibility issues with recent game updates !!

People who are interested in contributing to the project can find more information in the `CONTRIBUTING.md` file.

## Resources

For those interested in diving deeper into League of Legends modding, we recommend exploring these related projects:

- [Update-ritobin-hashes](https://youtu.be/-zzso5CYZMY)
- [Fix-Missing-Assets](https://youtu.be/DuEa4I8vLGk)
- [Obsidian](https://github.com/Crauzer/Obsidian)
- [cslol-manager](https://github.com/LeagueToolkit/cslol-manager)
- [ritobin](https://github.com/moonshadow565/ritobin)
- [CommunityDragon Toolbox](https://github.com/CommunityDragon/CDTB)

These resources have been invaluable in the development of RitoSkin and offer powerful tools for League of Legends modding.

## Contact

If you have questions, suggestions, or concerns about RitoSkin, we're here to help.

You can reach out to us on Discord: `nylish.me`

Show me some ❤️ by 🌟 this repository!

Good luck on the Rift!

---

**Disclaimer**: RitoSkin is an unofficial tool and is not endorsed by Riot Games. Use it responsibly and always respect the terms of service of League of Legends.
