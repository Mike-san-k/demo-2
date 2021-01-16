Command's parameters enclosed between [] are optional, you may or may not provide them.

| command | parameters | description |
|---------|------------|-------------|
| `help` | None | Tells you about various commands of this bot. |
| `ban` | member, [duration] | Bans a member from the server for the provided duration else indefinitely. |
| `unban` | member_id | Unbans a member from the server. |
| `kick` | member | Kicks out a member from the server. |
| `mute` | member, [duration] | Mutes the member for the given duration else indefinitely. |
| `unmute` | member | Unmutes a member. |
| `take_role` | member, role | Removes the given role from the given member. |
| `give_role` | member, role | Adds the given role to the given member. |
| `configure` | None | This command configures the bot for the server. |
| `java` | keyword_name | Gives the definition and syntax of the given java keyword. |
| `set_default_role` | role | Sets a default role which is given to anyone who joins the server. |
| `create_role` | role name | Creates a role in the server. |
| `del_role` | role | Deletes the given role in the server. |
| `rules` | None | Gives you rules of the server. |
| `zen` | None | Prints the Zen of Python. |
| `user` | [member] | Gives info about the given user. If member not provided, gives user about the command user. |
| `ping` | None | Gives the latency of the bot. |
| `nick` | member, new name | Changes the nick name of the given user to the given name. |
| `elem` | [element name] | Gives info about the provided element name. If element name not provided, gives info about the periodic table.|
| `remind` | text to be reminded, date, time, ping, channel | Adds a reminder to the bot. Bot will ping the specified role at specified channel. |
| `server` | None | Gives info about the server. |
| `clear` | [Number] | clears the provided number of messages. If number is not provided, 5 is taken as default.|
| `py` | Code block | It runs the block of python code which is provided after the command. |
| `js` | Code block | It runs the block of javascript code which is provided after the command |
| `guess_game` | [mode] | Starts a guessing game of numbers. It takes 1 argument. guess_game <easy/medium/hard> |
