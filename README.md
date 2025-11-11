# ColorPlugin

A Minecraft Bedrock Edition plugin for Endstone servers that allows players to customize the color of other players' nicknames. The color changes are client-side and only visible to the player who configured them.

## Description

ColorPlugin provides a simple yet powerful way for players to personalize their gaming experience by applying custom colors to other players' names. Each player can configure their own color scheme independently, creating a unique visual environment without affecting other players' views.

## Features

- **Personal Color Configuration**: Each player can set custom colors for other players' names
- **Client-Side Only**: Color changes are visible only to the player who configured them
- **Multiple Color Options**: Choose from 7 different colors including red, yellow, green, pink, blue, and purple
- **Easy Reset**: Quickly reset any player's name back to default color
- **Color Management**: List all players with custom colors you've configured

## Available Colors

- **Reset**: Remove color formatting (default white)
- **Red** (§c): Bright red color
- **Yellow** (§e): Golden yellow color  
- **Green** (§a): Bright green color
- **Pink** (§d): Magenta/pink color
- **Blue** (§b): Cyan/light blue color
- **Purple** (§u): Purple/dark blue color

## Commands

### `/color [player]`
Configure the color of a specific player's name.

**Usage**: `/color <playername>`
**Example**: `/color Steve` - Opens a color selection form for player "Steve"

### `/listcolor`
Display a list of all players whose names you have colored.

**Usage**: `/listcolor`

## Installation

1. Download the plugin files
2. Place the plugin in your Endstone server's plugins directory
3. Reload the server
4. The plugin will be automatically enabled

## How It Works

1. Use `/color <playername>` to open a color selection form
2. Choose your desired color from the available options
3. The selected player's name will appear in the chosen color (only for you)
4. Use `/listcolor` to see all your color configurations
5. Use the "Reset" option to remove color formatting from a player's name

## Notes

- Color changes are persistent during the session
- Each player maintains their own independent color configuration
- Colors are applied in real-time and update continuously
- The plugin uses custom packet handling for optimal performance
