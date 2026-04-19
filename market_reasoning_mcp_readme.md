# 🧠 Market Reasoning MCP Agent

An AI-powered market analysis system that explains why stock prices move
using real-time financial news, stock data, and large language model
reasoning in an MCP-style architecture.

Built for Google Colab, this project demonstrates how agentic systems
can transform raw market signals into causal explanations, not just
numerical changes.

------------------------------------------------------------------------

## 🚀 What This Project Does

This system answers a simple but powerful question:

> Why did this stock move?

It does this by:

1.  Fetching real-time financial news (Google News RSS)
2.  Pulling recent stock price data (yfinance)
3.  Structuring both into a reasoning prompt
4.  Sending it to Gemini API
5.  Returning a concise causal explanation

------------------------------------------------------------------------

## 🏗️ System Architecture

RSS News + Stock Data -\> MCP Tools -\> Prompt Builder -\> Gemini LLM
-\> Explanation

------------------------------------------------------------------------

## 🧠 Key Idea

Traditional tools show price changes.

This system explains causality behind them.

------------------------------------------------------------------------

## ⚙️ Features

-   Real-time stock data
-   Live news aggregation
-   AI causal reasoning
-   MCP-style tool structure
-   Colab-ready execution

------------------------------------------------------------------------

## 🧪 Example Output

Stock increased +1.8%

News: Apple launches AI features Strong earnings report

Reason: Strong earnings and AI announcements likely drove the increase.

------------------------------------------------------------------------

## 🔮 Future

-   Multi-agent reasoning
-   Memory system
-   Market pattern recognition
-   Full API deployment
