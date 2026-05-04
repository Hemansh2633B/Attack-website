# Async Load Testing & Web Resilience Tool

A high-performance asynchronous HTTP testing tool built with `aiohttp` for evaluating the reliability, rate-limiting, and scalability of web services.

## ⚠️ Important: Responsible Use

This tool is intended **only for authorized testing**:
- Systems you own
- Systems where you have **explicit written permission**

Unauthorized use against third-party services is strictly prohibited.

## Features

- ⚡ Async request execution using asyncio
- 🔁 Configurable request patterns (GET/POST)
- 🧠 Randomized inputs for realistic traffic simulation
- 🧵 Concurrent worker model
- 📊 Basic response logging (status, latency)
- 🔌 Optional proxy support (for testing distributed environments only)

## Installation

```bash
pip install -r requirements.txt
Usage
Edit configuration inside Script.py:

Target endpoints (ONLY authorized domains)

Number of workers

Request rate limits

Delay intervals

Run:

python Script.py



📌 Disclaimer
The author is not responsible for misuse of this software.
Any actions performed using this tool are solely the responsibility of the user.

🤝 Contributing
Contributions are welcome!
Please ensure any additions align with ethical and defensive use cases.

