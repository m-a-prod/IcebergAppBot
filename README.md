# IcebergAppBot Clicker
clicker for https://t.me/IcebergAppBot

Additional soft information: https://t.me/ApeCryptorSoft/83

## Functionality
| Functional                                                     | Supported |
|----------------------------------------------------------------|:---------:|
| Multithreading                                                 |     ✅     |
| Binding a proxy to a session                                   |     ✅     |
| Auto-complete tasks; claim points every 6 hours, start mine    |     ✅     |
| Random sleep time between accounts, claim                      |     ✅     |
| Support pyrogram .session                                      |     ✅     |
| Get statistics for all accounts                                |     ✅     |

## Settings data/config.py
| Setting                      | Description                                                                                    |
|------------------------------|------------------------------------------------------------------------------------------------|
| **API_ID / API_HASH**        | Platform data from which to launch a Telegram session _(stock - Android)_                      |
| **DELAYS-ACCOUNT**           | Delay between connections to accounts (the more accounts, the longer the delay) _(eg [5, 15])_ |
| **DELAYS-BEFORE_CLAIM**      | delay before claim points _(eg [5, 15])_                                                       |
| **DELAYS-CHANGE_STATUS_TASK**| CHANGE_STATUS_TASK _(eg [10, 12])_                                                             |
| **PROXY_TYPE**               | Proxy type for telegram session _(eg 'socks5')_                                                |
| **WORKDIR**                  | directory with session _(eg "sessions/")_                                                      |

## Requirements
- Python 3.9 (you can install it [here](https://www.python.org/downloads/release/python-390/)) 
- Telegram API_ID and API_HASH (you can get them [here](https://my.telegram.org/auth))

1. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
   
## Usage
1. Run the bot:
   ```bash
   python main.py
   ```
