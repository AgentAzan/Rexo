Rexo Dashboard
A powerful, all-in-one Discord bot built with discord.js and a focus on modularity, security, and a future web-based dashboard for easy configuration.

Features
Based on the provided code, Rexo Dashboard includes a wide range of administrative and fun features:

Anti-Nuke & Security
Anti-Nuke Protection: Automatically detects and counters malicious activity like mass channel deletions or role purges.

Auto-Moderation: Automated moderation actions for spam, mentions, and other defined behaviors.

Server Locks: Ability to lock down the server during a raid or other security incident.

⚙️ Server Administration
User Management: Commands for kicking, banning, and temporary banning users.

Channel & Role Management: Commands to create, delete, and modify channels and roles.

Configuration: A system to persist and manage per-guild configurations, which will be the basis for the web dashboard.

Fun & Utility
Leveling System: A user leveling system with XP gain.

Custom Commands: The ability to create and manage custom bot commands.

Utility Commands: Useful commands like ping, stats, and help.

Getting Started
To get Rexo Dashboard up and running, follow these steps.

Prerequisites
Node.js (version 18 or higher recommended)

Git

Add Rexo to your Server
Bot Invite Link: Click here to add Rexo to your server!

Support Server: Join the Rexo Support Server

Configuration
Your bot requires a Discord bot token and other sensitive information. These must be stored in a .env file for security.

Create a file named .env in the root of your project. Do not share this file with anyone! It contains your secret keys and tokens.

Add the following variables to the .env file, replacing the placeholder values with your actual credentials from the Discord Developer Portal:

TOKEN=YOUR_BOT_TOKEN_HERE
CLIENT_ID=YOUR_APPLICATION_CLIENT_ID
GUILD_ID=YOUR_DEVELOPMENT_SERVER_ID


The GUILD_ID is for instantly registering slash commands to a single server for testing purposes.

Running the Bot
Once everything is configured, you can start your bot:

node index.js


📝 License
This project is licensed under the MIT License.
