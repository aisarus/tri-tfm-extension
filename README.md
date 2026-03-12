# TRI·TFM v3.0: Chrome Extension (Lexeme Injection)

![Manifest V3](https://img.shields.io/badge/manifest-v3-green.svg)

This is the B2C monetization engine for the TRI·TFM v3.0 LLM Evaluation Framework. It bypasses the massive API costs associated with evaluating LLM outputs by injecting custom **Lexemes** directly into the user's browser, leveraging their existing ChatGPT Plus or Claude Pro subscription for the computational heavy lifting.

## 🧠 The Concept (Zero-Cost Inference)
Traditional evaluation SaaS platforms (DeepEval, Patronus) charge huge API fees because they run the LLM-as-a-judge on their own backend. 
Our extension simply injects mathematically proven, hyper-optimized system prompts (Lexemes) into the user's current session. The user's browser does the evaluation. Your API cost is **$0**.

## 🚀 Features
- **One-Click Balance Score:** Injects the $0.75F - 0.25B$ formula directly into the active tab.
- **M-Axis Depth Evaluator (The "Ruthlessness Lexeme"):** Forces the LLM to penalize its own superficial writing by 0.5 points per paragraph of "water" text.
- **Cross-Platform:** Works on ChatGPT (`chatgpt.com`) and Claude (`claude.ai`).

## 🛠️ How to Install (Developer Mode)
1. Download or clone this repository (`tri-tfm-extension`).
2. Open Google Chrome and navigate to `chrome://extensions/`.
3. Enable **Developer mode** in the top right corner.
4. Click **Load unpacked** and select the `tri-tfm-extension` folder.
5. The extension icon will appear in your toolbar.

## 💰 Monetization Path (The B2C Growth Hack)
- **Free Tier:** Basic Facts (F) and Bias (B) evaluation.
- **Pro Tier ($10/month):** Unlocks the M-Axis Depth Evaluator, custom weight tuning, and JSON export.

## 📝 Note on DOM Selectors
The extension uses standard selectors (`textarea#prompt-textarea`, `div[contenteditable="true"]`) to inject text. These may need periodic updates if OpenAI or Anthropic change their frontend UI structures.
