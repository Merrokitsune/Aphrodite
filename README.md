# Aphrodite

<p align="center"><img src="https://raw.githubusercontent.com/Caldera-site-4678/Aphrodite/master/Resources/Textures/Logo/splashlogo.png" width="512px" /></p>

---
Aphrodite is a fork of Floof Station, which, in turn, is a fork of Einstein Engines, which, in turn, is a hard fork of [Space Station 14](https://github.com/space-wizards/space-station-14) built around the ideals and design inspirations of the Baystation family of servers from Space Station 13 with a focus on having modular code that anyone can use to make the RP server of their dreams.

Space Station 14 is inspired heavily by Space Station 13 and runs on [Robust Toolbox](https://github.com/space-wizards/RobustToolbox), a homegrown engine written in C#.

As Einstein Engines is a hard fork, any code sourced from a different upstream cannot ever be merged directly here, and must instead be ported.
All code present in this repository is subject to change as desired by the maintainer team, and the payerbase.

## Links

[Discord](https://discord.gg/bA4xrT9fvh) | [Steam(SSMV Launcher)](https://store.steampowered.com/app/2585480/Space_Station_Multiverse/) | [Steam(WizDen Launcher)](https://store.steampowered.com/app/1255460/Space_Station_14/) | [Standalone](https://spacestationmultiverse.com/downloads/)

## Contributing

We are happy to accept contributions from anybody, come join our Discord if you want to help.
We've got a [list of issues](https://github.com/Simple-Station/Einstein-Engines/issues) that need to be done and anybody can pick them up. Don't be afraid to ask for help in Discord either!

We are currently accepting translations of the game on our main repository.
If you would like to translate the game into another language check the #contributor-general channel in our Discord.

## Building

Refer to [the Space Wizards' guide](https://docs.spacestation14.com/en/general-development/setup/setting-up-a-development-environment.html) on setting up a development environment for general information, but keep in mind that Einstein Engines is not the same and many things may not apply.
We provide some scripts shown below to make the job easier.

### Build dependencies

> - Git
> - .NET SDK 8.0.100


### Windows

> 1. Clone this repository
> 2. Run `git submodule update --init --recursive` in a terminal to download the engine
> 3. Run `Scripts/bat/buildAllDebug.bat` after making any changes to the source
> 4. Run `Scripts/bat/runQuickAll.bat` to launch the client and the server
> 5. Connect to localhost in the client and play

### Linux

> 1. Clone this repository
> 2. Run `git submodule update --init --recursive` in a terminal to download the engine
> 3. Run `Scripts/sh/buildAllDebug.sh` after making any changes to the source
> 4. Run `Scripts/sh/runQuickAll.sh` to launch the client and the server
> 5. Connect to localhost in the client and play

### MacOS

> I don't know anybody using MacOS to test this, but it's probably roughly the same steps as Linux

## License

Please read the [LEGAL.md](./LEGAL.md) file for information on the licenses of the code and assets in this repository.
