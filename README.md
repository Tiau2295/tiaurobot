# tiaurobot – Grok Bot Terminal

Multi-agent Solana memecoin desk (Scanner → Rug Check → Sizer → Executor → Logger).

⚠️ **Paper trading by default.** Extremely high risk. Educational only.

## Quick start
```bash
pip install requests python-dotenv
cp .env.example .env
python grok_bot_terminal.pySee the script for full configuration.text**2. `.env.example`**
```env
PAPER_MODE=true
POSITION_SIZE_PCT=0.25
MAX_SLIPPAGE_BPS=200
MIN_LIQUIDITY_USD=15000
MAX_TOP10_HOLDERS_PCT=25
MAX_RISK_SCORE=400
START_BALANCE=100
# RPC_URL=
# PRIVATE_KEY=
# HELIUS_API_KEY=3. .gitignoretext.env
__pycache__/
*.pyc
night.log
venv/
.venv/Method 2: Using Git (if you prefer terminal)Bashgit clone https://github.com/Tiau2295/tiaurobot.git
cd tiaurobot

# Create the files
# (paste the script into grok_bot_terminal.py, etc.)

git add .
git commit -m "Initial commit: Grok Bot Terminal"
git pushWould you like me to give you the complete ready-to-paste content for all four files (grok_bot_terminal.py + README.md + .env.example + .gitignore) in one go so you can just copy-paste them one by one?
