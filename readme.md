# Discord Text-To-Speech

A discord bot with voice chat text-to-speech.

Type in any text channel `(prefix)say (language) (text)` for bot to appear in your current voice chat.

# Installing

**Requirements:** You need ffmpeg to use audio in discord.js module and a Discord bot.

Clone repository locally. Create **.env** file with your bot token and prefered prefix values like this:
```env
TOKEN=INSERT_YOUR_TOKEN_HERE
PREFIX=+
```

Then run these:

`npm install` to install all dependencies<br>
`npm build` to build all typescript files<br>
`npm start` to start the bot