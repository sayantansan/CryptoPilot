Crypto Pilot is an automated cryptocurrency trading bot that trades on Binance. It leverages the observation that cryptocurrencies often follow Bitcoin's lead and oscillate relative to each other. The bot trades between coins using USDT as a bridge to maximize holdings by switching from stronger to weaker coins, anticipating a reversal.

Setup Overview:
Binance Setup: Create an account, enable 2FA, generate API keys, and get cryptocurrency.

Tool Setup: Install dependencies, configure user.cfg with API keys and preferences.

Key Features:
Trades based on ratio differences.

Avoids returning to a coin unless profitable.

Supports margin and multiple trading strategies.

Provides Docker support and backtesting.

Commands:
pip install -r requirements.txt – Install dependencies.

python -m crypto_pilot – Run the bot.

docker-compose up – Run via Docker.

python backtest.py – Run backtesting.

Disclaimer: For informational purposes only. Conduct your own research before trading.
