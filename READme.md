# Discord XP and Moderation Bot

## Description

This Discord bot is a versatile tool designed to enhance server engagement and moderation. It features an XP system, level progression, user warnings, and various administrative commands. The bot is built using the discord.py library and offers functionalities such as:

- XP and leveling system
- User warnings and management
- Leaderboard for top users
- XP multiplier customization
- Level management (reset, set levels)
- Customizable command prefixes
- Word blacklisting

## Features

1. **XP System**: Users earn XP for each message, with customizable multipliers.
2. **Leveling**: Automatic level-up notifications and special rewards at milestone levels.
3. **Warnings**: Admins can warn users and manage these warnings.
4. **Leaderboard**: View top users based on XP and levels.
5. **Admin Commands**: Reset levels, set individual levels, manage XP multipliers.
6. **Prefix Management**: Add or remove custom command prefixes.
7. **Word Blacklisting**: Automatically delete messages containing blacklisted words and warn users.

## Setup

1. Clone this repository.
2.Install Dependencies


## Commands

- `#stats [user]`: View XP and level stats for a user.
- `#top`: Display the server's top 10 users.
- `#warn <user> [reason]`: Warn a user.
- `#warnings [user]`: View a user's warnings.
- `#remove_warn <number> [user]`: Remove a specific warning.
- `#set_multiplier <multiplier> [user]`: Set XP multiplier for a user.
- `#reset_levels`: Reset all users' levels and XP.
- `#reset_level <user>`: Reset a specific user's level and XP.
- `#set_level <level> [user]`: Set a user's level.
- `#prefix <new_prefix>`: Add a new command prefix.
- `#remove_prefix <prefix>`: Remove a command prefix.
- `#blacklist <word>`: Add a word to the blacklist.

Note: Some commands require administrator permissions.

## Contributing

Contributions, issues, and feature requests are welcome. 

