# GatherBuddy Reborn · 国服分支

本仓库 fork 自 [Raindeer23/GatherBuddyReborn](https://github.com/Raindeer23/GatherBuddyReborn)，保留原作者、许可证和国服适配。当前发布的 `7.5.0.15` 安装包与该上游版本逐字节一致；本次仅调整仓库和插件列表地址，不改动插件功能。

使用与「键影随行」共用的插件库地址：

```text
https://raw.githubusercontent.com/raindeer21/MyDalamudPlugins/master/pluginmaster.json
```

自动采集需要另外安装并启用 **vnavmesh**。完整上游说明如下。

---

# [![](https://raw.githubusercontent.com/FFXIV-CombatReborn/RebornAssets/main/IconAssets/GBR_Icon.png)](https://github.com/FFXIV-CombatReborn/GatherBuddyReborn)

**GatherBuddyReborn**

![Github Latest Releases](https://img.shields.io/github/downloads/FFXIV-CombatReborn/GatherBuddyReborn/latest/total.svg?style=for-the-badge)
![Github All Releases](https://img.shields.io/github/downloads/FFXIV-CombatReborn/GatherBuddyReborn/total.svg?style=for-the-badge)
![Github License](https://img.shields.io/github/license/FFXIV-CombatReborn/GatherBuddyReborn.svg?label=License&style=for-the-badge)
[![](https://dcbadge.limes.pink/api/server/p54TZMPnC9)](https://discord.gg/p54TZMPnC9)

GatherBuddyReborn is a community-made fork of the original GatherBuddy plugin for Final Fantasy XIV. This tool is designed to enhance your gameplay experience by assisting with all things gathering, now with automated routes via vnavmesh.

## Features

- **AutoGather**: Automated pathing for gathering up to 10 full stacks (999 each) of a resource.
- **Resource Queueing**: Create a list of resources you want and GBR will gather up to 10 stacks of each!
- **Full BTN/MIN Automation**: GBR can find any BTN/MIN item in the world and gather it for you fully automatically, no user input required beyond initial setup

**NOTE**: vnavmesh plugin is *required* for full automation. Please see the links section of this README for more information on vnavmesh.
  
## Installing
- Enter `/xlsettings` in the chat window and go to the Experimental tab in the opening window.
- **Skip below the DevPlugins section to the Custom Plugin Repositories section.**
- Copy and paste the repo.json link into the first free text input field.
```
https://raw.githubusercontent.com/raindeer21/MyDalamudPlugins/master/pluginmaster.json
```
- Click on the + button and make sure the checkmark beside the new field is set afterwards.
- **Click on the Save-icon in the bottom right.**

Following these steps, you should be able to see all contained plugins in the Available Plugins tab in the Dalamud Plugin Installer.
No Plugins will be installed, you have just made them available. You can now select which of these plugins you actually want to install.

## Want to contribute?

- Create a fork
- Make your changes
- Test the changes
- Create a PR and point it to main

## Links

[vnavmesh](https://github.com/awgil/ffxiv_navmesh) Required for automated navigation

## Attribution and Acknowledgements

GatherBuddyReborn and its various functions relies heavily on the original foundations of various individuals whom without their prior works GatherBuddyReborn would not be the utility it is today and in the future. These attributions are NOT implied as endorsements of GatherBuddyReborn. In alphabetical order:

    - All of the contributors to Dalamud and FFXIVLauncher
    - [Artisan](https://github.com/PunishXIV/Artisan): Taurenkey, pksage, Limiana, et al.
    - [GatherBuddy](https://github.com/Ottermandias/GatherBuddy): Ottermandias, et al.
    - [vnavmesh](https://github.com/awgil/ffxiv_navmesh): awgil, xanderscore, et al.