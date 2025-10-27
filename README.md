<div align="center">

# 🏷️ NameSystem

### Advanced TabList, Chat & Nametag Plugin with LuckPerms Integration
### Fortgeschrittenes TabList, Chat & Nametag Plugin mit LuckPerms Integration

[![Minecraft Version](https://img.shields.io/badge/Minecraft-1.21+-green.svg)](https://www.spigotmc.org/)
[![License](https://img.shields.io/badge/License-GPL--3.0-blue.svg)](LICENSE)
[![Java](https://img.shields.io/badge/Java-17+-orange.svg)](https://www.java.com/)
[![LuckPerms](https://img.shields.io/badge/Requires-LuckPerms-purple.svg)](https://luckperms.net/)

**[🇬🇧 English](#-english)** | **[🇩🇪 Deutsch](#-deutsch)**

</div>

---

# 🇬🇧 English

## 📋 Overview

**NameSystem** is a powerful and lightweight Minecraft plugin that seamlessly integrates with LuckPerms to provide beautiful rank displays in chat, tablist, and above player heads. It also includes a customizable server information command.

### ✨ Key Features

- 🔗 **Full LuckPerms Integration** - Automatic synchronization with LuckPerms ranks
- 💬 **Custom Chat Format** - Fully customizable chat messages with prefixes and suffixes
- 📊 **TabList Display** - Show ranks in the TAB menu with automatic sorting
- 🏷️ **Nametag System** - Display ranks above player heads
- ⚡ **Real-time Updates** - Instant rank changes without server reload
- 🎨 **Color Support** - Full support for Minecraft color codes
- ℹ️ **Server Info Command** - Display server information with `/sinfo`

---

## 🚀 Features

### 🎯 LuckPerms Integration

The plugin automatically reads prefixes, suffixes, and group weights from LuckPerms. No manual configuration needed!

**Example LuckPerms commands:**
Create a new group
/lp creategroup admin

Set a prefix for the group
/lp group admin meta setprefix "&c[ADMIN] &c"

Set a suffix for the group (optional)
/lp group admin meta setsuffix " &7★"

Set group weight (for sorting in TabList - higher = top)
/lp group admin meta setweight 100

Give permissions to the group
/lp group admin permission set minecraft.command.gamemode

Assign a player to a group
/lp user PlayerName parent set admin

Add a secondary group to a player
/lp user PlayerName parent add vip

Remove a player from a group
/lp user PlayerName parent remove admin

View a player's groups
/lp user PlayerName info
