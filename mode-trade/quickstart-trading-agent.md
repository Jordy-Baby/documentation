---
description: >-
  This guide shows how to quickly set up and launch a Mode Trade AI trading
  agent.
---

# 🦾 AI Trading Agent

## 1. Introduction

### What Are Mode Trade AI Agents?

Mode Trade AI Agents are automated trading assistants that help you trade more consistently. They handle execution, risk management, and trade monitoring so you don't have to make decisions in the heat of the moment.

Instead of constantly watching the markets or second-guessing your plan, an agent executes according to the rules you set. It helps you avoid emotional trading, manage entries/exits, and stay consistent over time.

### What They Are _Not_

* Agents do **not** guarantee profits.
* Agents are **not** a replacement for learning basic trading principles.
* Agents are **not** immune to market risk — losses are possible and should be expected.

### Why Use Them

* Reduce emotional decisions when trading.
* Maintain consistent execution of your strategy.
* Save time — agents run even when you're offline.
* Learn in a controlled environment with built-in risk limits.

***

## 2. Getting Started

### Step 1 — Create a Sub-Account

Each agent must run in its own sub-account.

* Only **one agent per sub-account**.
* The sub-account must be funded before you launch an agent.

**Example:**\
If you want to test an agent with $50, create a sub-account named "Test Agent," transfer $50, then launch the agent there.

<div align="center"><img src="../.gitbook/assets/ai-agent-sub-account.png" alt="Enable trading dialog" width="768"></div>

***

## 3. What Are AI Trading Agents?

AI Trading Agents on Mode let you automate crypto trading using advanced LLMs (Large Language Models).

You choose:

* The AI model
* Whether to Trust or Counter your agent
* Your sub-account
* Your indicator weights
* Your maximum leverage
* The asset you want to trade

Once activated, the agent trades for you 24/7 using live market data and your chosen strategy configuration.

***

## 4. How AI Agents Work

* Reads live market data and x402 indicator values
* Evaluates market structure using Donchian Channels
* Assesses momentum using MACD
* Forms a directional trade decision (long or short)
* Applies your selected execution mode (trust or counter)
* Selects position size within your leverage limits
* Monitors open positions using predefined risk logic

You can pause or delete the agent at any time.

***

## 5. Creating an Agent (Step-by-Step)

Your UI provides a 6-step creation flow. Here is the full guide:

***

### **Step 1 — Choose Your AI Model**

Select which LLM will power your agent:

* **GPT-5.1 Instant**
* **Claude Opus 4.5**
* **Grok 4.1 Fast Reasoning**

Each model has its own reasoning style but follows the same trading rules.

<figure><img src="../.gitbook/assets/image (2) (1).png" alt=""><figcaption></figcaption></figure>

### **Step 2 — Choose a Sub-Account**

Agents trade from a dedicated sub-account so your funds remain isolated.

You can:

* Use an existing sub-account
* Create a new one

Your current balance is shown so you know how much the agent can trade with.

<div align="center"><img src="../.gitbook/assets/step2.png" alt="Enable trading dialog" width="768"></div>

***

### **Step 3 — Set Max Leverage**

Choose the maximum leverage the agent may use.\
**Range:** 0.5× → 5×

The agent selects leverage dynamically based on signal strength but will **never exceed your limit**.

The UI shows your approximate position size.

<figure><img src="../.gitbook/assets/Screenshot 2025-12-17 at 13.35.42.png" alt=""><figcaption></figcaption></figure>



***

### **Step 4 — Choose Your Asset**

Pick one asset for the agent to trade:

* **BTC**
* **XAU** (Gold)
* **XAG** (Silver)

One agent can trade **multiple** assets.

<figure><img src="../.gitbook/assets/image (3) (1).png" alt=""><figcaption></figcaption></figure>

***

### **Step 5 — Review & Activate**

You'll see a summary of:

* Sub-account
* AI model
* Max leverage
* Asset
* Indicator weights
* Position size

Press **Create Agent**, then sign the message to activate.\
Your agent is now live.

<figure><img src="../.gitbook/assets/Screenshot 2025-12-17 at 14.59.14.png" alt=""><figcaption></figcaption></figure>



***

## 6. Viewing Your Agent's Performance

Open the **Portfolio** tab to monitor:

* Portfolio value
* Total PnL
* Realized PnL
* Unrealized PnL
* Open positions
* Closed positions

All metrics update in real time.

<div align="center"><img src="../.gitbook/assets/portfolio.png" alt="Enable trading dialog" width="768"></div>

***

## 7. Reviewing LLM Logs

Every agent decision is logged. You'll see:

* The AI's reasoning
* Individual signal values
* Why it entered or avoided a trade
* Risk considerations
* Leverage decisions

This gives full transparency and helps you understand how your agent behave.

<div align="center"><img src="../.gitbook/assets/llm-logs.png" alt="Enable trading dialog" width="768"></div>

***

## 8. Best Practices

* Start with **lower leverage** until you're comfortable
* Keep enough USDC in the sub-account for volatility
* Review LLM logs regularly

***

## 9. Pausing or deleting an Agent

You may pause or delete an agent at any time.\
When closed:

* No new positions will be opened
* Trades will not be automatically closed, unless take profit or stop loss are hit

<figure><img src="../.gitbook/assets/Screenshot 2025-11-21 at 16.34.01.png" alt=""><figcaption></figcaption></figure>



***

## 10. Risks & Important Notes

* Crypto markets are volatile
* Leverage amplifies gains **and** losses
* Past performance does **not** guarantee future results
* AI models do **not** predict the future
* You should always monitor open positions

Mode agents are designed to be cautious, but losses are still possible.

***

## 11. FAQ

### **Can I run multiple agents?**

Yes — one per sub-account.

### **Can I edit an agent after activation?**

Yes, you can  pause or delete it.

### **Which indicators are used?**

Donchian Channel, MACD.

### **Does the agent use stop-loss logic?**

Yes. All agents apply logical SL/TP rules where appropriate.

### **How often does the agent trade?**

Agents always have a bias, but will only take trades when indicators agree.

***

## 12. Summary

Mode's AI Trading Agents allow anyone to run a structured, data-driven crypto trading system powered by advanced LLMs — without coding or manual execution.

**You set the rules.**\
**The agent handles the rest.**
