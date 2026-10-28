# ScamShield

Paste any suspicious SMS, WhatsApp message or email and ScamShield tells you if it is Safe, Suspicious or a Scam, with red flags and what to do next.

## Why
Fake KYC, UPI and lottery scams cost people their savings every day. ScamShield gives everyone a quick way to check a message before acting on it.

## Features
- Verdict: Safe / Suspicious / Scam
- Risk score (0-100)
- Red flags and recommended actions
- Runs on a local Ollama model, so your messages never leave your laptop
- Offline keyword checker as backup

## How to run
1. Install Ollama and run `ollama pull llama3.2`
2. Set `OLLAMA_ORIGINS=*` and restart Ollama
3. Open `scamshield-ollama.html` in your browser (or use VS Code Live Server)
4. Paste a message and click Check message

## Tech
HTML, CSS, JavaScript, Ollama (llama3.2)

## Future plans
WhatsApp bot, Hindi and regional language support, family protection mode
