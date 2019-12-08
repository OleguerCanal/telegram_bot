# telegram_bot
Python Telegram bot wrapper

## Usage:

Clone the repo into your scripts folder:

`git clone git@github.com:OleguerCanal/telegram_bot.git`

Include this line into your script:

```python
from telegram_bot.telegram_bot import TelegramBot
```

```python
telegram_bot = TelegramBot()
answer = telegram_bot.send("your string")
handle_answer(answer)
```
