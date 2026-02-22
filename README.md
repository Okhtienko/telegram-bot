![Bot](https://github.com/Okhtienko/telegram-bot/actions/workflows/bot.yml/badge.svg)
![Scrapper](https://github.com/Okhtienko/telegram-bot/actions/workflows/scrapper.yml/badge.svg)

# Link Tracker

Application for tracking content updates via links. 
When new events occur, a notification is sent to Telegram.

The project is written in `Java 21`  using `Spring Boot 3`.

The project consists of two applications:
* Bot
* Scrapper

It requires a `PostgreSQL` database. There is an optional dependency on `Kafka`.
