# Gamemode Commands Skript

A simple Skript that adds convenient gamemode commands for Minecraft servers.

## Commands

| Command | Description | Permission |
|---------|-------------|------------|
| `/gmc [player]` | Switch to Creative mode | `skript.gmc` |
| `/gms [player]` | Switch to Survival mode | `skript.gms` |
| `/gma [player]` | Switch to Adventure mode | `skript.gma` |
| `/gmsp [player]` | Switch to Spectator mode | `skript.gmsp` |
| `/gm <mode> [player]` | Switch to any gamemode | `skript.gm` |

## Usage

**Change your own gamemode:**
```
/gmc
/gms
/gma
/gmsp
```

**Change another player's gamemode:**
```
/gmc Notch
/gms Notcoolplayer
/gm creative Coolplayer
```

## Installation

1. Make sure you have [Skript](https://github.com/SkriptLang/Skript) installed on your server
2. Download the `.sk` file
3. Place it in your `plugins/Skript/scripts/` folder
4. Run `/skript reload <filename>` or restart your server

## Permissions

Grant permissions to players or groups using your permissions plugin: 

```
skript.gmc
skript. gms
skript.gma
skript.gmsp
skript.gm
```

## Requirements

- Skript
