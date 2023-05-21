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

### Vps

To deploy on a VPS, follow these steps

1. Update and upgrade your system packages:
```
sudo apt-get update && sudo apt-get upgrade -y
```

2. Clone the repository and navigate to the project directory:
```
git clone https://github.com/decentboyy/octave_bot_stats
```

3. Install the required packages:
```
pip3 install -U -r requirements.txt
```
4. Create .env using example.env
```
cp example.env .env
```
5. Now open the .env file using **vi .env**
6. Edit the vars, by pressing **I**  on the keyboard
7. After editing save the file using **ctrl + c** then **:wq**
8. Run the script using Python 3:
```
python3 main.py
```
