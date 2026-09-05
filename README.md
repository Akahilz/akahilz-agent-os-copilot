# 🤖 Akahilz E-Learning Academy: No-Code KOL Media & Execution Engine

An open-source prompt engineering framework and configuration guide designed for Web3 Content Creators, KOLs, and Educators. This setup connects the free Claude Desktop application directly to the official **Binance Agent OS Model Context Protocol (MCP)** server via a secure remote HTTP transport gateway.

This repository fulfills the open-source technical documentation requirement for the **Binance Agent OS Mini Hackathon (Track A)** and the **Binance Creator Challenge #002**.

---

## 💡 The Value Proposition
Web3 community leads and creators waste hours scraping market data manually to write content updates. This framework enables an autonomous AI Co-Pilot that runs completely via natural language to:
1. Fetch live market tickers, 24-hour volume changes, and real-time order book depth directly from Binance infrastructure.
2. Structure high-retention short-form video scripts instantly based on that data.
3. Formulate and route secure spot micro-trades within an isolated, withdrawal-blocked **Agentic virtual sub-account** for automated portfolio rebalancing.

---

## 🛠️ Setup Instructions (100% Code-Free)

### 1. Prerequisite Software
* Download and install the free [Claude Desktop Application](https://claude.ai).

### 2. Connect the Remote Server Manually
Because the official Binance Agent OS uses a remote transport protocol, you do not need to install Node.js locally. Open your system's Claude settings folder to configure the integration:
* **Windows Path:** Press `Win + R`, paste `%APPDATA%\Claude`, and open `claude_desktop_config.json` with Notepad.
* **Mac Path:** Open `~/Library/Application Support/Claude/claude_desktop_config.json`.

Overwrite or append the configuration with this official object block:

```json
{
  "mcpServers": {
    "binance-mcp-server": {
      "command": "curl",
      "args": [
        "-s",
        "https://binance.com"
      ]
    }
  }
}
```

### 3. Authenticate & Grant Scopes
1. Restart your Claude Desktop app.
2. Click the new **plug icon** in the bottom-right corner of the input box or type `/mcp`.
3. Choose **[Authenticate]**. A secure Binance OAuth portal will open in your web browser.
4. Log into your account and authorize the connection for **Market Data**, **Account Read**, and **Spot Trade** scopes. 
5. Fund the newly spawned **Agentic sub-account** with a small testing budget (e.g., $10–$20 USDT) via your Binance dashboard under *Sub-account Management*.

---

## 📊 Deployment Workflow
Once connected, copy the template instructions inside the `prompts.txt` file in this repository and paste them directly into your Claude Desktop chat workspace to run the live media and execution pipeline.
