# IRCurd
IRCurd is designed for privacy-conscious users. Ensures complete anonymity and employs military-grade encryption to secure all communications.

## Features

### Multi-Server Connectivity
- Simultaneous connections to multiple IRC servers.
- Server-specific channel management.
- Customizable connection settings for each server.
- Effortless server switching.

### Channel Management
- Join multiple channels on different servers.
- User list displays operator and voice status.
- Channel admin tools (kick, ban, grant/revoke op/voice).
- Manage channel modes and topics.
- Batch updates for user lists.

### Private Messaging
- Separate windows for direct conversations.
- Support for CTCP actions (/me commands).
- Messaging between users across servers.

### Advanced IRC Functionalities
- Complete IRC command support.
- WHOIS command for user details.
- Channel listing with search filters.
- Support for NickServ and ChanServ services.
- Manage away status and nickname authentication.

### User-Friendly Interface
- Modern tabbed layout for organized browsing.
- Network tree for simplified navigation.
- Customizable themes to suit preferences.
- Status window for server messages.
- Context menus for quick actions.
- Intuitive dialog windows for user interaction.

### Theme Customization
- Preloaded themes: Default, Dark, Light, Matrix.
- Adjustable message type colors.
- Instantly switch themes.
- Persistent theme preferences.

### Additional Features
- Auto-reconnect to servers.
- Comprehensive error handling.
- UTF-8 encoding support.
- Log conversations and events.
- Track user modes in real time.
- Support for action messages.

## Installation

### Clone the repository:

git clone https://github.com/rotterdamdaddyy/IRCurd.git

### Install dependencies

pip3 install -r requirements.txt

# Usage

python3 IRCurd.py

### User Menu

Left click on a user in the channel window to access the user menu.

![User Menu](user_menu.png)

### Channel Window Management

Click on a channel in the network tree to toggle its visibility.
---

### Basic Commands
- `/server <server> [port] [nickname]` - Connect to an IRC server
- `/join #channel` - Join a channel
- `/msg <user> <message>` - Send a direct fully encrypted message to a user.
- `/me <action>` - Send an action command
- `/quit [message]` - Disconnect from the server

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments
- Inspired by classic IRC clients while embracing modern design principles

---
Built by Mahmood Dzay



