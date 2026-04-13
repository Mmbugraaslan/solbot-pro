# ⚡ SolBot Pro — Solana AI Trading Bot

> Automated Solana token trading with real-time signal analysis, slippage protection, and Phantom wallet integration.

**Built by [@Mmbugraaslan](https://github.com/Mmbugraaslan)**

---

## 🚀 Live Demo

👉 **[https://Mmbugraaslan.github.io/solbot-pro](https://Mmbugraaslan.github.io/solbot-pro)**

> Open on mobile Chrome → tap ⋮ → **"Add to Home Screen"** to install as an app.

---

## ✨ Features

| Feature | Description |
|---|---|
| 🤖 Auto Trading | Fully automated buy/sell based on AI signal scoring |
| 🛡️ Slippage Protection | Calculates DEX fees + slippage before every trade |
| 👻 Phantom Wallet | Direct integration with Phantom wallet (Solana) |
| 📊 Live Signals | Real-time RSI + momentum analysis across 6 tokens |
| 📱 Mobile PWA | Installable on Android as a native-like app |
| ⚙️ Configurable | Adjust score threshold, TP%, SL%, trade size |
| 🧪 Paper Mode | Test without real money before going live |

---

## 📱 Mobile Installation (Android)

1. Open **Chrome** on your Android phone
2. Visit the live demo link above
3. Tap the **⋮ menu** (top right)
4. Select **"Add to Home Screen"**
5. App installs — opens fullscreen like a native app

---

## 🧠 How the Bot Works

```
Market Data → RSI + Momentum Score (0-100)
                        ↓
              Score ≥ 80? → Cost Check (slippage + fees)
                        ↓
           Expected profit > cost × 1.5? → ENTER TRADE
                        ↓
              Take Profit 25% OR Stop Loss 12% → EXIT
```

The bot **skips trades** where fees and slippage eat the profit — protecting your capital on small amounts.

---

## 🪙 Supported Tokens

`BONK` · `WIF` · `POPCAT` · `MYRO` · `BOME` · `MEW`

---

## ⚙️ Bot Settings

| Setting | Default | Description |
|---|---|---|
| Min Score | 80 | Minimum signal score to enter |
| Max Per Trade | 20% | Max % of budget per trade |
| Take Profit | 25% | Auto-exit at this gain |
| Stop Loss | 12% | Auto-exit to limit loss |
| Slippage | 1% | Jupiter aggregator slippage |

---

## 🖥️ Desktop (Python Bot)

For running the full bot on your PC with real Phantom key:

```bash
# Clone & install
git clone https://github.com/Mmbugraaslan/solbot-pro
cd solbot-pro
pip install -r requirements.txt

# Configure
cp .env.template .env
# Add your Phantom private key to .env

# Run simulation first
python bot.py --mode paper

# Go live when ready
python bot.py --mode live
```

---

## ⚠️ Risk Disclaimer

> This software is for **educational and experimental purposes only**.
> Cryptocurrency trading involves significant financial risk.
> Never invest more than you can afford to lose.
> The author is not responsible for any financial losses.
> Always test in **paper mode** before using real funds.

---

## 📄 License

This project is licensed under the **MIT License** — see [LICENSE](LICENSE) for details.

© 2026 **Mmbugraaslan** — Free to use with attribution.

---

## 🌐 Connect

- GitHub: [@Mmbugraaslan](https://github.com/Mmbugraaslan)
- Project: [solbot-pro](https://github.com/Mmbugraaslan/solbot-pro)

---

<div align="center">
  <sub>Built with ❤️ on Solana · Powered by Jupiter Aggregator</sub>
</div>
