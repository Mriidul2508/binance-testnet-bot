# Binance Futures Testnet Trading Bot

A simplified Python CLI application designed to place Market and Limit orders on the Binance Futures Testnet (USDT-M). Built with `python-binance` and `argparse`, featuring a modular architecture and clean error handling.

## Project Structure
```text
trading-bot/
├── bot/
│   ├── __init__.py
│   ├── client.py         # Binance client initialization & authentication
│   ├── logging_config.py # Structured logger setup
│   ├── orders.py         # Core order execution logic
│   └── validators.py     # Input validation rules
├── .env                  # API credentials (git-ignored)
├── .gitignore
├── cli.py                # Command-line interface entry point
├── README.md
├── requirements.txt      # Project dependencies
└── trading_bot.log       # Executed order logs (Included per requirements)
