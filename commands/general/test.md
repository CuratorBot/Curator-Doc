# test

#### Command Example/s:

```fix

```

#### Arguments:

#### Description:

Probably a test command for something, idk...

```ts
sync run(bot, interaction) {
        await interaction.deleteReply();
        const hasVoted = (await bot.topggAPI.hasVoted(interaction.user.id))
            ? "User has voted!"
            : "User has not voted";

        bot.consola.log(hasVoted);
    },
```
