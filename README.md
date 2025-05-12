<div align="center">
  
# Discord.js Handler Template

**A simple and modular Discord bot handler template built using Discord.js v16**

---

### [Join the Support Server](https://discord.gg/YOUR_INVITE_LINK) | [Visit Website](https://yourwebsite.com)

</div>

---

## 📦 Installation Guide

### 1. Requirements
- **Node.js v16.6.0 or higher**

### 2. Setup
- Open `./botconfig/config.json` and update your **Bot Token** and **Prefix**
- Open `./botconfig/settings.json` to configure **default messages** and **bot settings**
- Open `./botconfig/embed.json` to customize **embed appearance**

### 3. Install Dependencies
```bash
npm install```

### 4. Start The Bot
```bash
node index.js
```

### 5. ⚔️ Slash Commands Guide

- To create a subcommand, add a folder inside ./slashCommands
- Be sure to register it in ./botconfig/config.json
- Only one folder level is supported (no nested folders)
- For regular slash commands, create .js files directly inside ./slashCommands

### 6. 💡 Credits

- If you use this handler or template, please credit the original creator.

> Made with love by Kɛn ᡣ𐭩.
