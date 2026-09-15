# boying
A fully automated trading bot with multiple strategies, risk management, and production monitoring.
# UltraBeast EA for MetaTrader 5
## Prerequisites
- Python 3.8+
- MetaTrader 5 (installed and running)
- Windows, Linux, or macOS

## Installation

### Windows
- Run `deploy.bat`

### Linux/macOS
- Run `chmod +x deploy.sh && ./deploy.sh`

## Configuration
Edit `config/config.json` to adjust symbol, timeframe, risk, and demo mode.

## Running the EA
- Activate virtual environment:
  - Windows: `venv\Scripts\activate`
  - Linux/macOS: `source venv/bin/activate`
- Run: `python src/ultrabeast_ea.py`

## Logs
Trading logs are written to `logs/ultrabeast_debug.log` (rotated).

## Safety
- **Always test in DEMO mode** before live trading.
- The EA includes maximum open trades, daily loss limits (configurable via code), and trailing stops.
