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

## 🎮 Commands

### NameSystem Commands

#### Display Server Information
**Aliases:** `/serverinfo`, `/si`  
**Description:** Displays server information including name, IP, version, and more  
**Permission:** None required

---

### LuckPerms Setup Commands

#### Create Groups
Create Owner group
/lp creategroup owner
/lp group owner meta setweight 1000
/lp group owner

Create Admin group
/lp creategroup admin
/lp group admin meta setweight 900
/lp group ad

Create Moderator group
/lp creategroup moderator
/lp group moderator meta setweight 800
/lp group

Create VIP group
/lp creategroup vip
/lp group vip meta setweight 500
/lp gr

Create Default group
/lp creategroup default
/lp group default meta setweight 0
/lp

#### Assign Players to Groups
Set player's primary group
/lp user <player> parent set <group>

Add secondary group
/lp user <player> parent add <group>

Remove group from player
/lp user <player> parent remove <group>


#### View Information
View player information
/lp user <player> info

View group information
/lp group <group> info

View all groups
/lp listgroups

Open web editor (recommended for advanced configuration)
/lp editor
