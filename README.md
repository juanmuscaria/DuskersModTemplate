# Duskers Mod Template
In this repo you will find a template for modding Duskers using [BepInEx](https://github.com/BepInEx/BepInEx).
Mods created by this template can be used as either standalone DLLs with manual installation of BepInEx or be installed 
using [DuskersModManager](https://github.com/juanmuscaria/DuskersModManager) with the generated zip package.

This template makes use of [DSMF](https://github.com/juanmuscaria/DSMFramework) which provides a basic modding API to be used by mods,
by using this template your mod will require DSMF to run, which can be installed separately.

## Requirements
* [dotNET SDK](https://learn.microsoft.com/en-us/dotnet/core/install/)
* Some C# IDE like [Rider](https://www.jetbrains.com/rider/), [Visual Studio or VS Code](https://visualstudio.microsoft.com/)

# Getting started
Once you have dotnet sdk installed it should come with dotnet CLI for managing dotnet projects.
To get started you need to restore the project to download and install the NuGet dependencies required to build it. 

In your favorite terminal run `dotnet restore` within the project root folder (or let your IDE restore the project automatically).

To build the project you can run `dotnet build` after restoration, once it's build within the ModTemplate/bin should have the release of your mod ready to be installed.


# TODO
Explain what each file does
Explain Duskers Mod Manager packing
Explain DSMF
Make readme easier to understand