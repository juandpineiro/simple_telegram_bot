# Simple Telegram Bot

Simple Telegram Bot using the [HTTP Telegram Bot API](https://core.telegram.org/bots), 
Python 3.5 and the `requests` module. From the tutorial in [Djangostars - How to Create
and Deploy a Telegram Bot](https://djangostars.com/blog/how-to-create-and-deploy-a-telegram-bot/).

Replies to the user once a day with a greetings depending on the time of day.

To run:

* Make sure you have system-wide Python 3.5 or virtual environment.
* Install dependencies (`pip install requests`)
* Set `TELEGRAM_API_KEY` environment variable with your API token.
* Run using `./bot.py`