# Startup instructions

1. Install dependencies:
   `python -m pip install -r requirements.txt`

2. Configure:
   - TELEGRAM_BOT_TOKEN = BotFather token
   - BOT_OWNER_ID = numeric Telegram user ID

3. Optional local Bot API:
   - API_ID
   - API_HASH

4. Start:
   `python run.py`

The bot now fails fast with a clear startup configuration error instead of silently returning.
