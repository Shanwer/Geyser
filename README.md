### 下载须知:
这是Geyser的非官方版本，旨在恢复了不安全的mojang账号登录功能以提供Authlib-injector支持，该Repo使用GitHub Action与Upstream每日定时同步以保证源代码最新，但由于Action的限制，不能做到同步代码后自动构建，需要更新可以自行clone编译或者踢我一下来开一个Action的手动构建。我自己也是服主，所以一般基岩协议版本更新的时候我都会在那构建一下。  
pr build是否可用？

This is the unofficial version of Geyser. It aims to revert the insecure function of mojang account login which gives you access to inject authlib. This repo uses GitHub Action to keep up-todate with the upstream everyday, however, due to the action's limit, it cannot automatically build after syncing the source code. If you need update, you can clone it and build by yourself or inform me to launch a workflow dispatch. Me myself am a server owner and whenever the bedrock protocol updates I will build it on action.

<img src="https://geysermc.org/img/geyser-1760-860.png" alt="Geyser" width="600"/>

[![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Discord](https://img.shields.io/discord/613163671870242838.svg?color=%237289da&label=discord)](https://discord.gg/geysermc)
[![Crowdin](https://badges.crowdin.net/geyser/localized.svg)](https://translate.geysermc.org/)

Geyser is a bridge between Minecraft: Bedrock Edition and Minecraft: Java Edition, closing the gap from those wanting to play true cross-platform.

Geyser is an open collaboration project by [CubeCraft Games](https://cubecraft.net).

## What is Geyser?
Geyser is a proxy, bridging the gap between Minecraft: Bedrock Edition and Minecraft: Java Edition servers.
The ultimate goal of this project is to allow Minecraft: Bedrock Edition users to join Minecraft: Java Edition servers as seamlessly as possible. However, due to the nature of Geyser translating packets over the network of two different games, *do not expect everything to work perfectly!*

Special thanks to the DragonProxy project for being a trailblazer in protocol translation and for all the team members who have joined us here!

### Currently supporting Minecraft Bedrock 1.20.40 - 1.20.61 and Minecraft Java 1.20.4

## Setting Up
Take a look [here](https://wiki.geysermc.org/geyser/setup/) for how to set up Geyser.

[![YouTube Video](https://img.youtube.com/vi/U7dZZ8w7Gi4/0.jpg)](https://www.youtube.com/watch?v=U7dZZ8w7Gi4)

## Links:
- Website: https://geysermc.org
- Docs: https://wiki.geysermc.org/geyser/
- Download: https://geysermc.org/download
- Discord: https://discord.gg/geysermc
- Donate: https://opencollective.com/geysermc
- Test Server: `test.geysermc.org` port `25565` for Java and `19132` for Bedrock

## What's Left to be Added/Fixed
- Near-perfect movement (to the point where anticheat on large servers is unlikely to ban you)
- Some Entity Flags
- Structure block UI

## What can't be fixed
There are a few things Geyser is unable to support due to various differences between Minecraft Bedrock and Java. For a list of these limitations, see the [Current Limitations](https://wiki.geysermc.org/geyser/current-limitations/) page.

## Compiling
1. Clone the repo to your computer
2. Navigate to the Geyser root directory and run `git submodule update --init --recursive`. This command downloads all the needed submodules for Geyser and is a crucial step in this process.
3. Run `gradlew build` and locate to `bootstrap/build` folder.

## Contributing
Any contributions are appreciated. Please feel free to reach out to us on [Discord](http://discord.geysermc.org/) if
you're interested in helping out with Geyser.

## Libraries Used:
- [Adventure Text Library](https://github.com/KyoriPowered/adventure)
- [NukkitX Bedrock Protocol Library](https://github.com/NukkitX/Protocol)
- [Steveice10's Java Protocol Library](https://github.com/Steveice10/MCProtocolLib)
- [TerminalConsoleAppender](https://github.com/Minecrell/TerminalConsoleAppender)
- [Simple Logging Facade for Java (slf4j)](https://github.com/qos-ch/slf4j)
