# AutoText Mod

**AutoText** is a mod for Minecraft 1.8.9 (Forge) that lets you create text and command macros, assign them to key combinations, and execute them instantly. Perfect for speeding up communication and command usage on servers.

## Features
- 📝 Create macros with text or commands (automatic `/` prefix for commands).
- ⌨️ Assign keys with modifiers: **Ctrl**, **Shift**, **Alt**.
- 🎨 Clean and easy-to-use graphical interface.
- 💾 Automatic JSON saving.
- 🔌 No conflicts with other mods (uses Forge events).

## Screenshots
### Gui Chat Button
![Open Autotext](screenshots/openautotex_principal.png](https://github.com/mananad06-cpu/AutoText-CommandText-Minecraft-1.8.9-Forge-o-Mod/blob/145975fe02ba3ea4f0678ffabd99364a9803844e/openautotex_principal.png)
### Main panel
![Main panel](screenshots/panel_principal.png)

### Macro editor
![Macro editor](screenshots/editor.png)

## Installation
1. Download the `.jar` file from the [Releases](../../releases) section.
2. Place it in the `mods` folder of your Minecraft Forge 1.8.9 client.
3. Enjoy!

## Usage
- Press the key assigned to your macro (with or without modifiers) to send the message or command.
- **Open the configuration panel** by clicking the **"Config AutoText"** button located at the **top‑right corner of the chat screen** (when you press `T` or `/` to open the chat).
- From there, you can create, edit, enable/disable, or delete macros.

## Macro Configuration
Each macro has the following fields:

| Field        | Description |
|--------------|-------------|
| Name         | Macro identifier. |
| Text         | Message or command to send (max 250 characters). |
| Key          | Activation key (e.g., `H`, `C`, `F1`). |
| Modifiers    | Ctrl, Shift, Alt (you can combine multiple). |
| Command      | If enabled, automatically adds `/` at the beginning. |
| Enabled      | Enables or disables the macro without deleting it. |

## Example Default Macros
| Name        | Key | Modifiers | Type    | Text |
|-------------|-----|-----------|---------|------|
| Help        | H   | -         | Command | `/help` |
| Clan Chat   | C   | Ctrl      | Text    | `Hello team!` |
| Gamemode    | G   | Alt       | Command | `/gamemode creative` |

## Compatibility
- ✅ Forge 1.8.9
- ✅ Client and server (client‑side only, no server installation required)
- ✅ Compatible with most mods (OptiFine, JEI, etc.)

## Development
This mod is developed in Java using the Minecraft Forge API. The source code is available under the MIT license.

## Credits
- **Author**: CewlDown
- **Discord**: [Join our community](https://discord.gg/sTFPcZZJFU)

---

⭐ If you like the mod, don't forget to leave a star on GitHub!
