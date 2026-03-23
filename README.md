# 🛡️ BSoftware Bans - Premium Ban Management Plugin

**Keep your Minecraft server safe with professional ban management.**

---

## What is BSoftware Bans?

BSoftware Bans is a modern, feature-rich ban management plugin for Minecraft servers. Whether you're running a small community server or a large network, our plugin provides the tools you need to maintain a safe and welcoming environment.

With support for both permanent and temporary bans, integrated server-wide ban checking, and an intuitive command interface, managing player conduct has never been easier.

---

## 🎯 Key Features

✨ **Permanent Bans** - Keep trouble-makers off your server permanently  
⏱️ **Temporary Bans** - Issue time-based bans with flexible durations (hours, days, minutes)  
🌐 **Network-Wide Ban Checking** - Optionally sync bans across your server network  
⚡ **Lightning Fast** - Asynchronous database operations ensure zero server lag  
🎨 **Fully Customizable** - Personalize all messages and settings via simple configuration  
🔒 **Secure & Reliable** - SQLite database ensures data integrity and quick access  

---

## 🚀 Quick Start

### Installation
1. Download the latest release
2. Place the JAR file in your server's `plugins/` folder
3. Start your server
4. **[Optional] Get your API Key:**
   - Visit https://api.bsoftware.xyz/
   - Create a new API key for your server
   - This enables network-wide ban synchronization
5. Configure the plugin in `plugins/BSoftware_Bans/config.yml` and add your API key (optional)
6. Restart your server

### First Commands
```
/ban <player> <reason>              Ban a player permanently
/tempban <player> <duration> <reason> Ban a player temporarily
/unban <player>                     Remove a player from the ban list
```

---

## ⏱️ Temporary Ban Examples

Ban for different durations with simple time formats:

```
/tempban Cheater 24h Hacking
/tempban SpamBot 1h Spam
/tempban Troll 3d Harassment
/tempban Griefer 30m Warning
/tempban BadBehavior 1d2h30m Multiple violations
```

Time formats supported: `d` (days), `h` (hours), `m` (minutes), `s` (seconds)

---

## 📊 Perfect For

- 🎮 Community Servers
- 👥 Roleplay Servers
- 🏆 Competitive Servers
- 🌍 Server Networks
- 🔧 Network Administrators

---

## ✅ Requirements

- **Minecraft Server:** 1.21+ (Spigot/Paper)
- **Java:** 21 or higher

---

## 🎮 Use Cases

**Quick Response to Violations**
> Issue time-based bans for minor infractions and give players a second chance.

**Permanent Ban Archive**
> Keep detailed records of permanently banned players with reasons and ban dates.

**Cross-Server Protection**
> Optionally integrate with a central ban system to sync bans across multiple servers.

**Custom Messages**
> Set personalized ban messages that reflect your community's values and rules.

---

## 🔧 Configuration

The plugin creates a `config.yml` file on first run. All features can be customized:

- Ban messages (with player-specific placeholders)
- Server name identification
- Central API integration (requires API key from https://api.bsoftware.xyz/)
- Database settings

A well-commented default configuration is generated automatically.

### Setting Up API Integration (Optional)
To enable network-wide ban synchronization:
1. Go to https://api.bsoftware.xyz/
2. Create a new API key for your server
3. Add the key to your `config.yml` under `database.central.api_key`
4. Restart your server

Without an API key, the plugin works perfectly fine for local bans only.

---

## 📱 Player Experience

When a banned player tries to join, they see a clear message:
```
§cYou are temporarily banned from this server!
§7Reason: Spam
§7Expires in: 2h 15m
```

After the ban expires, the player can rejoin automatically.

---

## 🌟 Why Choose BSoftware Bans?

| Feature | BSoftware Bans |
|---------|-----------------|
| Permanent Bans | ✅ |
| Temporary Bans | ✅ |
| Duration Auto-Expire | ✅ |
| Network Integration | ✅ |
| Customizable Messages | ✅ |
| Asynchronous Operations | ✅ |
| Reliable SQLite Database | ✅ |
| Zero Configuration Needed | ✅ |
| Active Support | ✅ |

---

## 📖 Documentation

For detailed installation, configuration, and troubleshooting, see:
- **README.md** - Complete technical documentation
- **RELEASE.md** - Feature changelog and version information

---

## 🛠️ Support

Have questions or need help?
- Visit our website: https://bsoftware.xyz
- Check the documentation included with the plugin
- Review the configuration examples

---

## 📜 License

This plugin is released under the **MIT License** - see LICENSE file for details.

---

## 💡 Tips for Server Administrators

1. **Backup your database** - Regularly backup `bans.db` to prevent data loss
2. **Test bans first** - Try banning and unbanning a test account to familiarize yourself
3. **Customize messages** - Make ban messages unique to your community
4. **Document reasons** - Always provide clear ban reasons for transparency
5. **Review regularly** - Periodically review and adjust your ban policies

---

## 🎉 Get Started Today!

Download BSoftware Bans and give your server the professional ban management it deserves.

**v0.1.0** - Stable Release  
March 23, 2026

---

*Made with ❤️ by the BSoftware Team*

**Website:** https://bsoftware.xyz

