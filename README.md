[<img src="https://img.shields.io/badge/Telegram-%40Me-orange">](https://t.me/hhhscvx)


## Functionality
| Functional                                                     | Supported |
|----------------------------------------------------------------|:---------:|
| Multithreading                                                 |     ✅     |
| Binding a proxy to a session                                   |     ✅     |
| Auto-activate Energy Boost                                     |     ✅     |
| Random sleep time between clicks                               |     ✅     |
| Random number of clicks per request                            |     ✅     |

## [Change Settings](https://github.com/hhhscvx/1WinBot/blob/master/bot/config/config.py)
| Настройка                | Описание                                                                               |
|--------------------------|----------------------------------------------------------------------------------------|
| **API_ID / API_HASH**    | Platform data from which to launch a Telegram session (stock - Android)                |

## Installation
You can download [**Repository**](https://github.com/hhhscvx/1WinBot) by cloning it to your system and installing the necessary dependencies:
```shell
~ >>> git clone https://github.com/hhhscvx/1WinBot.git
~ >>> cd 1WinBot

#Linux
~/1WinBot >>> python3 -m venv venv
~/1WinBot >>> source venv/bin/activate
~/1WinBot >>> pip3 install -r requirements.txt
~/1WinBot >>> cp .env-example .env
~/1WinBot >>> nano .env # Here you must specify your API_ID and API_HASH , the rest is taken by default
~/1WinBot >>> python3 main.py

#Windows
~/1WinBot >>> python -m venv venv
~/1WinBot >>> venv\Scripts\activate
~/1WinBot >>> pip install -r requirements.txt
~/1WinBot >>> copy .env-example .env
~/1WinBot >>> # Specify your API_ID and API_HASH, the rest is taken by default
~/1WinBot >>> python main.py
```