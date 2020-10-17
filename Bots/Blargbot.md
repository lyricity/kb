# [◆](/) ❱ [Bots](/Bots) ❱ Blargbot

![Prefix /](https://img.shields.io/badge/Prefix-/-black?style=flat-square)

Blargbot handles all the moderation commands within the server for the moderators and community managers.

**`<user>` can be a @mention or the UserID for Blarg commands.**

## Delta commands

_All Betas and higher roles have access to these commands as well._

`Mute <user> -t 00h00m00s -r <reason>` mutes a designated users for the amount of time given. **If no time is specified then the user will be permanently muted**

_Example: `/mute @Discord#0001 -t 5h -r Example message`_

`Unmute <user> -r <reason>` unmutes the user.

`Timers` show active timers running on the bot. These can be the timers set for mutes/bans and allows you to see how much longer the timer will run for.

`Iso <user>` isolates a user from the server.

`bd <user>` adds the birthday role to a user for 24 hours

`rmbd <user>` removes the birthday role from a user if the role is stuck or role needs to be removed before its timer finishes.

## Beta commands

`Ban <user> -t 00h00m00s`

`Hackban <userid>`

`Kick <user>`

`Logs <number> [Flags]` pulls up chat logs for whatever chat the command is used in if not specified.

`Reason <caseid> <new reason>` changes the reason in the embed for a case e.g. ban/kick/mute/warning

### [Flags for Logs]:

- `-t CREATE, UPDATE, DELETE` specifies what type of message you are trying to find. Messages that were either created, updated, or deleted
- `-c <channel name>`specifies the channel to grab logs of.
- `-u <user>` specifies a user to pull only his/her messages
- `-C` pulls only created messages
- `-U` pulls only updated messages
- `-D` pulls only deleted messages
- `-json` exports the logs to a file instead of a link to a website. Useful for longterm shortage of logs.

`Tidy <amount> [Flags]` bulk message deletion

### [Flags for Tidy]:

- `-u <user>` specifies user to delete messages of.
- `-b`specifies only delete messages from Bots
- `-l`specifies only delete links
- `-y`bypasses the confirmation message normally received when you send the command without this flag. **Highly recommended to not use this flag and confirm the deletion so you do not accidentally over-delete the chat.**

`Pardon <user> -r <reason>` removes a warning from the user.

`Warn <user> -r <reason>` used to log warnings for users in #blarg-modlog.

## Blarg-Modlogs

These store all the actions of the previous commands listed. **CaseIDs** can be found in this channel by looking at the embed for the Ban/Kick/Mute/Warning

<!-- TAGS --> <!-- Mute Ban Reason Timers Isolation birthday hackban kick logs tidy pardon warn caseid blarg-modlog -->