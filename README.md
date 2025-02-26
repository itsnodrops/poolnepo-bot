# OpenLoop Bot
Bot to create WebSocket connections to earn Scores on OpenLoop Airdrop.

## OpenLoop Project Overview
OpenLoop Network is a decentralized wireless network aimed at enhancing internet service delivery, making it more efficient, accessible, and rewarding for everyone.

- Official Website: [https://openloop.so/](https://openloop.so/auth/register?ref=ol5a5ae6d1)
- Official Twitter: [@openloop_so](https://x.com/openloop_so)


## **Features**

- **Automatic Registration**
- **Load Existing Tokens**: 
- **Automatic Ping**
- **Supports Multiple Accounts**


## **Requirements**

- **OpenLoop Account**  : Register [here](https://openloop.so/auth/register?ref=ol5a5ae6d1)
- **Python Environment**: Ensure Python is installed.


## Setup

1. Clone this repository:
   ```bash
   git clone https://github.com/itsnodrops/poolnepo-bot.git
   cd poolnepo-bot
   ```
   > Use [GNU screen](https://www.gnu.org/software/screen/) for better experiences. 
2. Create a virtual environment:
   ```bash
   python3 -m venv openloop-venv
   ```
3. Activate the virtual environmentg:
   ```bash
   source openloop-venv/bin/activate
   ```
4. Install all the dependencies:
   ```bash
   pip install --no-cache-dir -r requirements.txt
   ```
5. Add your OpenLoop account credentials to the `accounts.txt` file with the following format:
   >`email1@mail.com,password1` \
   >`email2@mail.com,password2`

   ```bash
   nano accounts.txt
   ```
6. Start the bot:
   ```bash
   python3 main.py
   ```
   > Create a token first by selecting `2. Login to Get Token` \
   > If the token already exists, you can immediately run the bot with the option `1. Start Node` \
   > If the token expires, you can recreate the token by selecting the option `2. Login to Get Token`
7. To stop the bot and exit, you can use the `CTRL+C` combination then exit the virtual environment by running: 
   ```bash
   deactivate
   ```

## Disclaimer

This project is for educational purposes only. Use at your own risk. The authors are not responsible for any consequences resulting from the use of this software.

## References
- [Repository references](github.com/GzGod/openloop)

## Contributing

Need source code? Feel free to DM me.

## Donations

If you want to support the development of this project, you can [click here](https://openloop.so/auth/register?ref=ol5a5ae6d1) or  use this referral code:

```
ol5a5ae6d1
```
> Don't forget to ⭐ this repo 

## License

This project is licensed under the [MIT License](https://github.com/itsnodrops/poolnepo-bot/blob/main/LICENSE).

## Community
[![Telegram](https://upload.wikimedia.org/wikipedia/commons/thumb/8/82/Telegram_logo.svg/12px-Telegram_logo.svg.png)](https://t.me/NoDrops) [NoDrops Telegram Channel](https://t.me/NoDrops) \
[![Telegram](https://upload.wikimedia.org/wikipedia/commons/thumb/8/82/Telegram_logo.svg/12px-Telegram_logo.svg.png)](https://t.me/NoDropsChat) [NoDrops Telegram Group](https://t.me/NoDropsChat)
