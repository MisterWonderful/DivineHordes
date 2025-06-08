# 🔥 Divine Hordes Plugin

<div align="center">

![Divine Hordes Logo](https://img.shields.io/badge/Divine%20Hordes-v2.4.0-gold?style=for-the-badge&logo=minecraft)
![Minecraft Version](https://img.shields.io/badge/Minecraft-1.18.2--1.21.5-green?style=for-the-badge)
![Build Status](https://img.shields.io/badge/Build-Production%20Ready-brightgreen?style=for-the-badge)
![Downloads](https://img.shields.io/badge/Downloads-10K+-blue?style=for-the-badge)
![Java](https://img.shields.io/badge/Java-17--21+-orange?style=for-the-badge)

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
| 🏺 **Dynamic Offering System** | Randomized item requirements with history tracking |
| 🗡️ **Enhanced Horde Mechanics** | Balanced mob spawning with real-time damage feedback |
| 🧠 **AI Divine Personality** | 124+ unique taunting messages across 6 categories |
| 📊 **Adaptive Difficulty** | 9-level system with real-time scaling |
| 🎯 **Smart Navigation** | Compass targeting with distance indicators |
| 📦 **Bounty Box System** | Craftable delay boxes for strategic gameplay |
| 🖥️ **Comprehensive GUI** | All-in-one control panel with admin tools |
| 🔧 **Dual Play Modes** | Normal/Gun Mod with customized scaling |
| 👑 **Admin Controls** | Complete server management tools |
| 🛡️ **Memory Management** | Auto-optimization with complete cleanup |

---

## 🚀 Quick Start

### 📋 Requirements
- **Java**: 17+ (Java 21 recommended)
- **Minecraft**: 1.18.2 - 1.21.5
- **Server**: Bukkit, Spigot, or Paper (Paper recommended)
- **Dependencies**: None! Completely standalone

### 📥 Installation
1. Download the latest `divine-hordes-2.4.0.jar` from [releases](../../releases/latest)
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

### 🗡️ Combat System
- **Smart Spawning**: Mobs appear 20-40 blocks away for tactical engagement
- **Damage Feedback**: Real-time action bar showing damage dealt and mob HP
- **Progressive Difficulty**: Harder challenges as players improve
- **Team Coordination**: Multiple players face proportionally larger hordes

### 📊 Difficulty Scaling
The plugin intelligently adjusts challenge based on:
- **Player Count**: More players = more mobs (20% per player)
- **Equipment Quality**: Better gear = tougher challenges
- **Experience Levels**: Higher XP = increased difficulty
- **Time Progression**: Events get harder over time

---

## 🌟 What's New in v2.4.0

### 🔧 Major Improvements
- **🚀 Production Ready**: Complete memory management and thread safety
- **⚔️ Combat Enhancement**: Optimized spawn distances and damage feedback
- **🎯 Balance Updates**: Reduced rewards, improved progression
- **🔄 History System**: No duplicate offerings between events
- **🛡️ Baby Zombie Protection**: Converted to adults until Hard difficulty
- **☕ Java 17-21+ Support**: Forward compatibility
- **🗑️ ZMenu Removal**: No external dependencies

### 📈 Performance Optimizations
- **Memory Management**: Bounded collections with LRU eviction
- **Thread Safety**: All concurrent operations properly synchronized
- **API Updates**: Fixed deprecated methods for modern Minecraft
- **Spawn Optimization**: Better distance calculations for balanced gameplay

---

## 📚 Documentation

### 🔗 Quick Links
- **[📖 Complete Wiki](docs/WIKI.md)** - Comprehensive guide to everything
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

*Comprehensive control panel with real-time statistics*

### ⚔️ Combat Action

*Enhanced mobs with damage feedback system*

### 📊 Admin Tools

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

### v2.4.0 (Current)
- **Production Ready**: Complete memory management and optimization
- **Combat Enhancement**: Real-time damage feedback and spawn optimization
- **Balance Updates**: Refined difficulty and reward systems
- **Compatibility**: Java 17-21+ and Minecraft 1.18.2-1.21.5

### v2.3.0
- **GUI Overhaul**: Complete interface redesign
- **Admin Controls**: Advanced management tools
- **Difficulty System**: 9-level progression system

[View Full Changelog](CHANGELOG.md)

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

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

**Made with ❤️ for the Minecraft community**

![Footer](https://img.shields.io/badge/Divine%20Hordes-Epic%20Challenges%20Await-gold?style=for-the-badge)

</div>
