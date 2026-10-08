# Test Users Telegram Bot

A learning project: a Telegram bot that generates fake test users for QA purposes. Built with Python during a QA training course (2024).

## What it does

Send the bot `/start`, pick how many users you need (1, 2, 5, or 10), and it replies with generated profiles: a Russian name, phone number, and a random password — handy when a test needs realistic-looking user data.

## Tech stack

- Python 3.x
- [pyTelegramBotAPI](https://github.com/eternnoir/pyTelegramBotAPI) — Telegram Bot API wrapper
- [Faker](https://faker.readthedocs.io/) (`ru_RU` locale) — fake data generation

## How to run

```bash
pip install pyTelegramBotAPI Faker
```

1. Create a bot with [@BotFather](https://t.me/BotFather) and copy its token.
2. Paste the token into the `TOKEN` variable at the top of the `bot` file.
3. Run it:

```bash
python bot
```

## Status

Course project (2024). The committed `bot` file uses a placeholder token — it will not run until you insert your own.
