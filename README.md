# 🛡️ BSoftware Bans - Premium Moderation Management Plugin

**Keep your Minecraft server safe with professional ban, IP-ban, mute, and kick management.**

---

## What is BSoftware Bans?

BSoftware Bans is a modern, feature-rich moderation management plugin for Minecraft servers and networks. Whether you're running a small community server or a large network, our plugin provides the tools you need to maintain a safe and welcoming environment.

With support for permanent and temporary bans, IP-bans, mutes, and kicks, plus integrated network-wide synchronization via a central REST API, managing player conduct has never been easier.

---

## 🎯 Key Features

✨ **Permanent & Temp Bans** - Keep troublemakers off your server with detailed reasons  
🚫 **IP-Ban System** - Block entire IP addresses to prevent ban evasion  
🤐 **Mute System** - Silence abusive players temporarily or permanently  
👢 **Kick Command** - Instantly remove players from the server  
🌐 **Network-Wide Synchronization** - Sync bans and IP-bans across your server network via REST API  
⚡ **Lightning Fast** - Asynchronous database and API operations ensure zero server lag  
🎨 **Fully Customizable** - Personalize all messages and settings via simple configuration  
🔒 **Secure & Reliable** - SQLite database ensures data integrity and high-speed local access  
🧹 **Auto-Cleanup** - Automatically removes expired temporary bans and mutes  

---

## 🚀 Quick Start

### Installation
1. Download the latest release JAR file.
2. Place it in your server's `plugins/` folder.
3. Start your server.
4. **Configure API (Optional):**
    - Set your `api_url` and `api_key` in `plugins/BSoftware_Bans/config.yml`.
    - This enables network-wide synchronization for bans and IP-bans.
5. Customize your messages in the `config.yml`.
6. Restart your server to apply the changes.

### Essential Commands
```
/ban <player> <reason>              Ban a player permanently
/tempban <player> <duration> <reason> Ban a player temporarily
/ipban <ip> <reason>                Ban a specific IP address
/mute <player> <duration|perm> <reason> Mute a player
/kick <player> <reason>             Kick a player from the server
/unban <player>                     Unban a player
/unmute <player>                    Unmute a player
```

---

## ⏱️ Duration Examples

Support for simple time formats (s, m, h, d) or `perm`:

```
/tempban Cheater 24h Hacking
/mute ToxicUser 30m Toxicity
/mute BadPlayer perm Repeated Violations
/tempban Griefer 7d Major Griefing
```

---

## 🌟 Why Choose BSoftware Bans?

| Feature | BSoftware Bans |
|---------|-----------------|
| Permanent & Temp Bans | ✅ |
| IP-Ban System | ✅ |
| Mute System (Temp/Perm) | ✅ |
| Kick Command | ✅ |
| Network API Synchronization | ✅ |
| Customizable Messages | ✅ |
| Asynchronous Operations | ✅ |
| Reliable SQLite Database | ✅ |
| Automatic Expiration | ✅ |
| Zero Server Lag | ✅ |

---

## 🔧 Configuration

The plugin creates a comprehensive `config.yml` on the first run. Customize everything:

- **Moderation Messages:** Set your own styles with color codes and placeholders.
- **Server Identification:** Name your server for network tracking.
- **API Settings:** Connect to your central REST API.
- **Cleanup Settings:** Automatically manage expired data.

---

## 📱 Player Experience

Players receive clear, professional messages when moderation actions are taken:

**Banned Player Join:**
```
§4You are GLOBALLY banned from the network!
§7Reason: Automatic Global Ban
```

**Muted Player Chat:**
```
§cYou are muted!
§7Reason: Spam
§7Expires in: 45m 20s
```

---

## 📖 Documentation & Support

For more details:
- **README.md** - Complete technical documentation and installation guide.
- **RELEASE.md** - Version changelog and feature details.
- **Website:** https://bsoftware.xyz

---

## 📜 License

Released under the **MIT License** - free and open source!

---

*Made with ❤️ by the BSoftware Team*

**v0.1.3** - Stable Release  
March 23, 2026
