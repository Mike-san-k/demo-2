Command's parameters enclosed between [] are optional, you may or may not provide them.

| command | parameters | Usage example | description |
|---------|------------|---------------|-------------|
`help`  | None  | .help  | Tells you about various commands of this bot. |
`ban`  | member, [duration]  | .ban @person 2d 4h | Bans a member from the server for the provided duration else indefinitely. |
`unban`  | member_id  | .unban 032479823795  | Unbans a member from the server. |
`kick`  | member  | .kick @person | Kicks out a member from the server. |
`mute`  | member, [duration]  | .mute @person 10min | Mutes the member for the given duration else indefinitely. |
`unmute`  | member  | .unmute @person | Unmutes a member. |
`take_role`  | member, role  | .take_role @person @role | Removes the given role from the given member. |
`give_role`  | member, role  | .give_role @person @role | Adds the given role to the given member. |
`configure`  | None  | .configure | This command configures the bot for the server. |
`java`  | keyword_name  | .java public | Gives the definition and syntax of the given java keyword. |
`set_default_role`  | role  | .set_default_role @role | Sets a default role which is given to everyone who joins the server. |
`create_role`  | role name  | .create_role new_role  | Creates a role in the server. |
`del_role`  | role  |  .del_role @new_role | Deletes the given role in the server. |
`rules`  | None  | .rules | Gives you rules of the server. |
`zen`  | None  | .zen  | Prints the Zen of Python. |
`user`  | [member]  | .user @person  | Gives info about the given user. If member not provided, gives user about the command user. |
`ping`  | None  | .ping | Gives the latency of the bot. |
`nick`  | member, new name  | .nick @person new name  | Changes the nick name of the given user to the given name. |
`elem`  | [element name]  | .elem radon | Gives info about the provided element name. If element name not provided, gives info about the periodic table.|
`remind`  | text to be reminded, date, time, ping, channel  | .remind "This is the text to be reminded" "20/5/2021" "17:00:00" @moderators #mod-chat | Adds a reminder to the bot. Bot will ping the specified role at specified channel. |
`server`  | None  | .server | Gives info about the server. |
`clear`  | [Number]  | .clear 10 | clears the provided number of messages. If number is not provided, 5 is taken as default.|
`py`  | Code block  |   | It runs the block of python code which is provided after the command. |
`js`  | Code block  |  | It runs the block of javascript code which is provided after the command |
`guess_game`  | [mode]  | .guess_game hard | Starts a guessing game of numbers. It takes 1 argument. guess_game <easy/medium/hard> |
