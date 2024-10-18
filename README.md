# CopyBid

## Setup & Run
### Setup (onetime)
```bash
cp sample_config.py config.py
$EDITOR config.py
```
Add CodeBid's id in `FORWARD_FROM` list as integer.

Edit `CHAT_ID` with the id of chat/channel where the forwarded messages will go (integer).

Replace `BOT_TOKEN` with bot token from [@botFather](https://t.me/BotFather) (string)
### Run
```zsh
pip3 install python-telegram-bot
python3 bot.py
```
