# 🔍 InterSearch

**InterSearch** is a smart, privacy-aware search API with layered fallbacks and an AI assistant called **“I”**.

## 🧠 Features
- Smart fallback chain:
  1. Primary local search (your data)
  2. Google Custom Search
  3. OpenAI Chat model (GPT-4o-mini by default)
- Built-in cache to reduce API costs
- Simple AI assistant endpoint `/ai` (acts like ChatGPT)

---

## 🚀 Setup

```bash
git clone https://github.com/YOURUSERNAME/intersearch.git
cd intersearch
cp .env.example .env
npm install# 