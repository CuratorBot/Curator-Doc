# message

#### Command Examples:

```fix
/message join %user% join the VC!
/message leave %user% left the VC!
/message reset (join/leave/both)
/message toggle
```

#### Arguments:

- **join** - Changes the join message for the text channel.
- **leave** - Changes the leave message for the text channel.
- **reset** - Resets either the join or leave message of the text channel.
- **toggle** - Toggles sending the join/leave message in the text channel.

#### Placeholders:

- **%user%** - The user who entered/left the voice channel.
- **%user_mention** - Same as `%user%` but Curator would mention them instead.
- **%channelName%** - The name of the channel the user joined.

#### Description:

Changes the join/leave message for the text channel. It has 4 arguments, naming `join`, `leave`, `reset`, and `toggle`. Changing the join message changes what Curator would send when a user joins the voice channel. Same goes when you change the leave message. You can also opt to not make Curator send any join /leave messages by adding the `toggle` argument.
