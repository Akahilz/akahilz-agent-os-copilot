# 🤖 Akahilz E-Learning Academy – BinaKOL aka the K-Agent (KOL Content & Execution Co-Pilot)

A simple, 100% no-code AI agent built with the official **Binance Agent OS**.

This agent helps Web3 creators and educators:
- Pull live market data (order books + 24h metrics) from Binance
- Automatically write short-form video scripts
- Prepare and execute small secure spot trades inside an isolated Agentic sub-account

Built for the **Binance Agent OS Mini Hackathon (Track A)** and **Binance Creator Challenge #002**.

---

## ✨ What This KOL Agent Does

1. Shows your current USDT balance in the Agentic sub-account  
2. Scans live order book depth and 24-hour data for BNB, BTC, and ETH  
3. Turns that data into a punchy 60-second video script for @akahilz  
4. Prepares a $10 BNB micro-trade and waits for your approval before executing

---

## 🛠️ How to Set It Up (Completely Free & No Code)

You can run BinaKOL on **Claude** or **ChatGPT**. Both methods are shown below.

### Option 1: Claude (Recommended for free users)

1. Open free Claude (claude.ai in browser or Claude Desktop app) and log in.
2. Go to **Settings** → **Connectors** → **Add custom connector**
   - Name: `Binance Agent OS`
   - URL: `https://agent.binance.com/mcp/agentic`
3. Click Add and authenticate with your Binance account.
4. Enable these permissions only:
   - Market Data
   - Account (Read)
   - Spot Trade
5. Fund your Agentic sub-account with $10–$20 USDT.

### Option 2: ChatGPT

1. Open ChatGPT (ChatGPT Plus recommended for best experience).
2. Turn on **Developer Mode** (Settings → Apps & Connectors / Developer features).
3. Add the Binance MCP / plugin using the official endpoint:  
   `https://agent.binance.com/mcp/agentic`
4. Authenticate with your Binance account and approve the same permissions (Market Data, Account Read, Spot Trade).
5. Fund your Agentic sub-account with $10–$20 USDT.

---

## 🚀 How to Run the KOL Agent

1. Copy the Master Prompt from the `prompts.txt` file in this repository.
2. Paste it into Claude or ChatGPT.
3. The agent will:
   - Show your balance
   - Fetch live market data
   - Write a video script
   - Prepare the $10 BNB trade for your approval

---

## 📁 Files in this Repository

- `README.md` → This guide
- `prompts.txt` → The exact Master Prompt used in the live demonstration
- `50-FAQs.md` → 50 frequently asked questions
- `50-Prompts-to-Try.md` → 50 extra prompts you can experiment with

---

## 🎥 Live Demo

- X: https://x.com/Akahilz2/status/2097262746685395327  
- Also available on YouTube and TikTok (links in the video comments)

Built by Kelvin Anamali (Akahilz) – Akahilz E-Learning Academy
