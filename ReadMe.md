# BotStatus
Updates your bot status in the message, every two hours.

**_NOTE:_** This branch needs to be hosted to work. If you prefer to host on GitHub WorkFlows, visit [the other branch](https://github.com/xditya/BotStatus/tree/gh-wf).

# Variables.

- `APP_ID` and `API_HASH` from [my.telegram.org](https://my.telegram.org).
- `BOTS` - TG UserName of your bots separated by space.
- `SESSION` - Telethon SessionString of the User to edit the message.
- `CHANNEL_ID` - ID of your channel.
- `MESSAGE_ID` - ID of the message to edit.

Fill these in a `.env` file, if hosting on a VPS.

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/decentboyy/octave_bot_stats)

# Credits

- [odysseusmax](https://github.com/odysseusmax/bug-free-broccoli)
- [Telethon](https://github.com/LonamiWebs/Telethon)
- [Me](https://xditya.me)
