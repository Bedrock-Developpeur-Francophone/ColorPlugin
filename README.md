# 🎨 ColorPlugin

[![License](https://img.shields.io/badge/License-GPL--2.0-blue.svg)](LICENSE)
![Version](https://img.shields.io/badge/version-0.0.3-green.svg)

> ✨ **Personalize your Minecraft experience with custom player name colors!**

A powerful Minecraft Bedrock Edition plugin for Endstone servers that lets players customize the color of other players' nicknames. All color changes are client-side and only visible to you - create your own unique visual experience! 🌈

---

## 📖 Description

ColorPlugin brings a whole new level of personalization to your Minecraft server! Give each player their own signature color in your view, making it easier to spot friends, teammates, or rivals at a glance. Whether you want to organize your team by color or just make your favorite players stand out, ColorPlugin makes it simple and fun! 🎯

## ✨ Features

- 🎨 **Personal Color Configuration**: Assign custom colors to any player's name
- 👁️ **Client-Side Only**: Your color choices are visible only to you
- 🌈 **7 Vibrant Colors**: Choose from a beautiful palette of colors
- 🔄 **Easy Reset**: One-click return to default colors
- 📋 **Color Management**: Track and manage all your colored players
- ⚡ **Real-Time Updates**: See changes instantly without reconnecting
- 🚀 **High Performance**: Optimized packet handling for smooth gameplay

---

## 🎨 Available Colors

| Color | Code | Description | Visual |
|-------|------|-------------|--------|
| **Reset** | Default | Standard white color | ⚪ |
| **Red** | `§c` | Bold red shade | 🔴 |
| **Yellow** | `§e` | Golden yellow | 🟡 |
| **Green** | `§a` | Vibrant green | 🟢 |
| **Pink** | `§d` | Bright magenta | 🩷 |
| **Blue** | `§b` | Cyan blue | 🔵 |
| **Purple** | `§u` | Deep purple | 🟣 |

---

## 🎮 Commands

### 🎨 `/color [player]`
Open an interactive color selection menu for a specific player.

```
/color Steve
```
📝 Opens a beautiful form with all available color options

### 📋 `/listcolor`
Display your complete list of colored players.

```
/listcolor
```
📊 Shows all players you've customized with their current colors

---

## 📦 Installation

### Quick Start

1. 📥 **Download** the latest release from the releases page
2. 📂 **Place** the plugin file in your Endstone server's `plugins` directory
3. 🔄 **Reload** your server or restart it
4. ✅ **Done!** The plugin is ready to use

## 🚀 How to Use

### Step-by-Step Guide

1. 🎯 **Target a Player**: Type `/color <playername>` to select who you want to colorize
2. 🎨 **Choose Your Color**: A beautiful menu appears with all available colors
3. ✨ **Instant Effect**: The player's name immediately appears in your chosen color
4. 📋 **Manage Colors**: Use `/listcolor` to see all your customizations
5. 🔄 **Reset Anytime**: Select "Reset" from the color menu to return to default

### 💡 Pro Tips

- 🎯 Use different colors for different teams or groups
- 🌟 Make your friends stand out with their favorite colors
- 🚫 Reset colors if the server gets too colorful
- 📊 Regular use of `/listcolor` helps you remember your color scheme

---

## ⚙️ Technical Details

| Property | Value |
|----------|-------|
| 🔧 API Version | 0.10 |
| 🎮 Server Type | Minecraft Bedrock Edition (Endstone) |
| 🐍 Python Version | 3.9+ |
| 📦 Package Name | endstone-color-plugin |
| 🔖 Current Version | 0.0.2 |

### 📚 Dependencies

- **endstone**: Core server framework
- **bedrock-protocol**: Minecraft Bedrock protocol handling
- **bstream**: Binary stream manipulation

---

## 📝 Notes & Tips

- 💾 **Persistence**: Color settings are saved throughout your play session
- 🔒 **Privacy**: Each player has their own completely independent color configuration
- ⚡ **Performance**: Colors update in real-time with optimized packet handling
- 🎯 **No Conflicts**: Your color choices never interfere with other players
- 🌐 **Client-Side Magic**: All processing happens on your client - zero server impact

---

## 🤝 Contributing

Found a bug? 🐛 Have a feature request? 💡 Want to contribute? 🚀

Feel free to open an issue or submit a pull request on our [GitHub repository](https://github.com/thedrewen/ColorPlugin)!

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 👨‍💻 Author

Created with ❤️ by **thedrewen**

---

<div align="center">

### ⭐ If you like this plugin, don't forget to star the repository! ⭐

**Made with 💜 for the Minecraft community**

</div>
