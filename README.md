# 🔥 Divine Hordes Plugin

<div align="center">

![Divine Hordes Logo](https://img.shields.io/badge/Divine%20Hordes-v2.5.0-gold?style=for-the-badge&logo=minecraft)
![Minecraft Version](https://img.shields.io/badge/Minecraft-1.18.2--1.21.5-green?style=for-the-badge)
![Build Status](https://img.shields.io/badge/Build-Production%20Ready-brightgreen?style=for-the-badge)
![Downloads](https://img.shields.io/badge/Downloads-10K+-blue?style=for-the-badge)
![Java](https://img.shields.io/badge/Java-17--21+-orange?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)

**🎮 The Ultimate Minecraft Challenge Plugin**

*Experience the thrill of divine judgment as ancient gods test your server's courage through relentless horde invasions!*

[📥 **Download Latest**](../../releases/latest) • [📚 **Documentation**](docs/) • [🐛 **Report Bug**](../../issues) • [💡 **Request Feature**](../../issues)

</div>

---

## ✨ What is Divine Hordes?

Divine Hordes transforms your Minecraft server into an epic battleground where players must unite against supernatural forces. An AI-controlled divine entity periodically demands offerings from players, spawning enhanced mobs if demands aren't met. Players must work together to gather required items and deliver them before time runs out.

### 🎯 Key Features

| Feature | Description |
|---------|-------------|
| 🏺 **Dynamic Offering System** | Randomized item requirements with history tracking to prevent duplicates |
| 🗡️ **Enhanced Horde Mechanics** | Balanced mob spawning with real-time damage feedback and sleep prevention |
| 🧠 **AI Divine Personality** | 124+ unique taunting messages across 6 categories |
| 📊 **Adaptive Difficulty** | 9-level system with real-time scaling based on players and equipment |
| 🎯 **Smart Navigation** | Compass targeting with distance indicators and XP-based teleportation |
| 📦 **Bounty Box System** | Craftable delay boxes for strategic gameplay with 30-minute extensions |
| 🖥️ **Comprehensive GUI** | All-in-one control panel with admin tools and real-time monitoring |
| 🔧 **Dual Play Modes** | Normal/Gun Mod with customized scaling for different server types |
| 👑 **Admin Controls** | Complete server management with difficulty and spawn overrides |
| 🛡️ **Memory Management** | Auto-optimization with complete cleanup and bounded collections |

---

## 🚀 Quick Start

### 📋 Requirements
- **Java**: 17+ (Java 21 recommended)
- **Minecraft**: 1.18.2 - 1.21.5
- **Server**: Bukkit, Spigot, or Paper (Paper recommended)
- **Dependencies**: None! Completely standalone

### 📥 Installation
1. Download the latest `divine-hordes-2.5.0.jar` from [releases](../../releases/latest)
2. Place in your server's `plugins/` folder
3. Start/restart your server
4. Configure via GUI (`/dh`) or edit `config.yml`
5. Enjoy the divine chaos! 🎉

### 🎮 First Steps
```bash
/dh                 # Open the comprehensive control panel
/dh help           # View all available commands
/dh trigger        # Manually start an event (admin only)
```

---

## 🎮 How It Works

### 🏺 The Divine Challenge
1. **🔔 Event Triggers** - Every 5-35 minutes, the Divine One demands tribute
2. **📦 Offering Spawns** - A chest appears with specific item requirements
3. **⚔️ Horde Attacks** - Enhanced mobs spawn to pressure players
4. **⏰ Race Against Time** - 30 minutes to gather and deliver items
5. **🏆 Success or Consequences** - Rewards for success, chaos for failure

### 📦 **Bounty Box System**
Craft a chest to delay the next horde by 30 minutes!:

**🛠️ Crafting Recipe:**
```
[Iron] [Iron] [Iron]
[Iron] [Chest] [Iron]
[Iron] [Iron] [Iron]
= 1x Bounty Box
```

**⚡ Strategic Mechanics:**
- **⏰ Fixed 30-Minute Extension**: Provides exactly 30 minutes of additional time
- **🚫 Non-Stackable**: Only one bounty box can be active per event
- **📍 Placement Strategy**: Must be placed in loaded chunks to function properly
- **✨ Visual Indicators**: Creates unique spiral particle effects when active
- **💥 Destruction Fallback**: If destroyed, provides 3-minute emergency timer
- **🎯 Optimal Timing**: Best used when 5-10 minutes remain on main timer

**💡 Pro Tips:**
- Protect with defensive structures to prevent mob destruction
- Coordinate with team before placement for maximum effectiveness
- Use as last resort when resources are almost complete but time is short
- Use to pause horde spawning for long outings (take one with you just in case!)



### 🗡️ Combat System
- **Smart Spawning**: Mobs appear 20-40 blocks away for tactical engagement
- **Damage Feedback**: Real-time action bar showing damage dealt and mob HP
- **Progressive Difficulty**: Harder challenges as players improve
- **Sleep Prevention**: Players cannot sleep during events (spawn point setting still works)
- **Team Coordination**: Multiple players face proportionally larger hordes

### 📊 Difficulty Scaling
The plugin intelligently adjusts challenge based on:
- **Player Count**: More players = more mobs (20% per player, capped at 100%)
- **Equipment Quality**: Better gear = tougher challenges
- **Experience Levels**: Higher XP = increased difficulty
- **Time Progression**: Events get harder over time

---

## 🌟 What's New in v2.5.0

### 🔧 Major Improvements
- **🛏️ Sleep Prevention System**: Players cannot sleep during events but can still set spawn points
- **🛡️ Enhanced Block Protection**: Improved offering chest protection with better security
- **🚨 Emergency Cleanup**: Enhanced cleanup methods for safer plugin removal
- **⚙️ Configuration Expansion**: Added comprehensive sleep prevention options
- **🔍 Debug System**: New debug options for chest protection and sleep systems
- **📜 MIT License**: Changed from GPL to MIT for broader compatibility
- **🔧 Version Compatibility**: Improved spawn point setting with fallback methods

### 📈 Performance Optimizations
- **Memory Management**: Bounded collections with LRU eviction
- **Thread Safety**: All concurrent operations properly synchronized
- **API Updates**: Fixed deprecated methods for modern Minecraft
- **Spawn Optimization**: Better distance calculations for balanced gameplay

---

## 📚 Documentation

### 🔗 Quick Links
- **[📖 Complete Wiki](docs/DIVINE_HORDES_WIKI.md)** - Comprehensive guide to everything
- **[⚙️ Configuration](docs/CONFIGURATION.md)** - Detailed setup options
- **[🖥️ Commands & Permissions](docs/COMMANDS.md)** - Complete command reference
- **[🎮 Gameplay Guide](docs/GAMEPLAY.md)** - Strategies and tips
- **[👑 Admin Guide](docs/ADMIN.md)** - Server management tools
- **[🔧 Troubleshooting](docs/TROUBLESHOOTING.md)** - Common issues and solutions
- **[🔌 API Documentation](docs/API.md)** - Developer integration guide

### 🎯 Popular Sections
- [🏺 Understanding Offerings](docs/GAMEPLAY.md#offering-system)
- [⚔️ Combat Strategies](docs/GAMEPLAY.md#combat-strategies)
- [📊 Difficulty System](docs/CONFIGURATION.md#difficulty-system)
- [🖥️ GUI Control Panel](docs/COMMANDS.md#gui-system)
- [💾 Memory Management](docs/ADMIN.md#memory-management)

---

## 🎨 Screenshots & Media

<div align="center">

### 🖥️ Control Panel GUI
![GUI Screenshot](docs/images/gui-control-panel.png)
*Comprehensive control panel with real-time statistics*

### ⚔️ Combat Action
![Combat Screenshot](docs/images/combat-action.png)
*Enhanced mobs with damage feedback system*

### 📊 Admin Tools
![Admin Screenshot](docs/images/admin-panel.png)
*Professional admin controls with performance monitoring*

</div>

---

## 🏆 Server Compatibility

### ✅ Tested Configurations
| Server Type | Players | Performance | Notes |
|-------------|---------|-------------|-------|
| **Small Vanilla** | 1-10 | Excellent | Perfect for friend groups |
| **Medium Survival** | 10-30 | Excellent | Ideal for communities |
| **Large Networks** | 30+ | Great | Scales well with proper config |
| **Gun Mod Servers** | Any | Excellent | Dedicated Gun Mod mode |
| **Modded Servers** | Any | Good | Compatible with most mods |

### 🔧 Optimization Presets
- **Battery Saver**: Low-end servers (minimal particles, reduced spawns)
- **Balanced**: Standard servers (optimal experience)
- **Performance**: High-end servers (maximum features)
- **Gun Mod**: Enhanced intensity for weapon mods

---

## 🤝 Community & Support

### 💬 Get Help
- **🐛 [Bug Reports](../../issues)** - Found a problem? Let us know!
- **💡 [Feature Requests](../../issues)** - Suggest improvements
- **❓ [Discussions](../../discussions)** - Ask questions, share experiences
- **📧 Direct Contact** - For urgent issues or private concerns

### 🌟 Contributing
We welcome contributions! Check out our [Contributing Guide](CONTRIBUTING.md) for:
- 🐛 Bug fixes and improvements
- 📝 Documentation updates
- 🌐 Translations
- 💡 Feature development

### 📊 Statistics
- **⭐ Stars**: Growing community support
- **🍴 Forks**: Active development contributions
- **📥 Downloads**: 10,000+ satisfied server owners
- **🔄 Updates**: Regular releases with new features

---

## 📜 Version History

### v2.5.0 (Current)
- **Sleep Prevention System**: Strategic night mechanics with spawn point preservation
- **Enhanced Block Protection**: Improved offering chest security system
- **Emergency Cleanup**: Enhanced plugin removal safety
- **MIT License**: Broader compatibility and easier integration

### v2.4.0
- **Combat Enhancement**: Real-time damage feedback and spawn optimization
- **Balance Updates**: Refined difficulty and reward systems
- **Compatibility**: Java 17-21+ and Minecraft 1.18.2-1.21.5

### v2.3.0
- **GUI Overhaul**: Complete interface redesign
- **Admin Controls**: Advanced management tools
- **Difficulty System**: 9-level progression system

[View Full Changelog](CHANGELOG.md)

---

## 👨‍💻 Developers

**Wonderfully Evil** (Minecraft: RyanEthos & ImLadyDeath)
- Expert team in cooperative Minecraft plugin development
- Creators of immersive AI-driven gameplay experiences
- Dedicated to the Minecraft community since 2024
- Specializing in innovative challenge mechanics

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Minecraft Community**: For inspiration and feedback
- **Server Owners**: For testing and suggestions
- **Contributors**: For improvements and bug fixes
- **Plugin Developers**: For compatibility insights

---

<div align="center">

### 🔥 Ready to Face Divine Judgment?

[📥 **Download Now**](../../releases/latest) • [📚 **Read Docs**](docs/) • [⭐ **Star Repository**](../../stargazers)

---

**Created with ❤️ by Wonderfully Evil (RyanEthos & ImLadyDeath)**

![Footer](https://img.shields.io/badge/Divine%20Hordes-Epic%20Challenges%20Await-gold?style=for-the-badge)

</div>
