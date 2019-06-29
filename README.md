# telegram-bot-startkit

Here you have the basic boilerplate to start developing right away your [telegram bot](https://core.telegram.org/bots) with [Python 3](https://www.python.org/downloads/) and [python-telegram-bot](https://python-telegram-bot.org).

## Instructions
First, clone this repository somewhere and access it:
```
git clone https://github.com/jahosp/telegram-bot-startkit

cd telegram-bot-startkit/
```
Install the python wrapper for the bot API using [pip](https://pypi.org/project/pip/):
```
pip3 install -r requirements.txt 
```
Now you should add your <b>bot token</b> into the config.py file, if you don't have it, go and talk with the [BotFather](https://telegram.me/botfather).

Finally, you can start the bot by executing:
```
python3 bot.py
```

## Notes

<b>Be careful about making commits with your token inside config.py</b>, you should add that file to the .gitignore file.