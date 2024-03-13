# DiscordIRCBridge
Ozinger Network Discord-IRC Bridge(Bouncer)

# Main features
* Bounces a message from an IRC channel to a mapped Discord channel. (WebHook)
* PRIVMSG a message from the Discord channel to the mapped IRC channel. (Built-in IRC Client)

# Features
* Support for multiple operating options
* Support for Discord multiple attachment message relay
* A solid implementation of the Discord webhook's lifecycle
* Send operation and monitoring log to Log DB(InfluxDB)
* Implementing a Messaging Bridge

# Installation
1. Input settings `bridge info` and `config.ini`
2. Register the Windows Service “DiscordIRCBridge” using `nssm.exe`.
