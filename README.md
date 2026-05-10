# 🌍 Capago Booking Bot
## CAPAGO APPOINTMENT AUTOMATION ENGINE
> Monitor → Detect → Queue → Book → Confirm

![Python](https://img.shields.io/badge/Python-3.11+-3b82f6?style=flat-square&logo=python&logoColor=white)
![Selenium](https://img.shields.io/badge/Selenium-Automation-10b981?style=flat-square&logo=selenium&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-Browser-6366f1?style=flat-square&logo=playwright&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-Database-22c55e?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-Cache-ef4444?style=flat-square&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-Container-0ea5e9?style=flat-square&logo=docker&logoColor=white)

---

## 🧠 What Is This?

**Capago Booking Bot** is a fully asynchronous automation system engineered to streamline France visa and Schengen visa appointment booking through the Capago platform across multiple countries.

The system continuously monitors real-time appointment availability, detects live visa slots instantly, automates booking workflows, handles waiting room systems, and delivers immediate Telegram notifications for successful reservations.

Built for high-demand visa centers where automation, speed, and uptime are critical.

| Without Automation | With This Bot |
|---|---|
| Endless refreshing | Detect → Reserve |
| Queue waiting | Confirm → Done |
| Missed appointments | Instant Telegram alerts |

---

## 🌍 Supported Countries

| # | Country |
|---|---------|
| 1 | 🇿🇦 South Africa |
| 2 | 🇰🇼 Kuwait |
| 3 | 🇦🇿 Azerbaijan |
| 4 | 🇧🇯 Benin |
| 5 | 🇹🇬 Togo |
| 6 | 🇬🇳 Guinea |
| 7 | 🇧🇫 Burkina Faso |
| 8 | 🇲🇱 Mali |
| 9 | 🇸🇱 Sierra Leone |
| 10 | 🇩🇿 Algeria |
| 11 | 🇳🇦 Namibia |

---

## ⚡ Features

| Feature | Description |
|---|---|
| 🔍 Real-Time Slot Detection | Instantly detects available visa appointment slots |
| 🤖 Automated Booking Workflow | End-to-end booking without manual intervention |
| 🔄 Session Recovery | Self-healing sessions with automatic reconnection |
| 🛡️ Captcha Handling | Built-in captcha solving integration |
| 🌍 Multi-Country Support | 11 countries across Africa & Middle East |
| 📋 Queue Monitoring | Handles waiting room systems automatically |
| 📢 Telegram Notifications | Instant alerts on successful reservations |
| ♻️ Retry Logic | Smart exponential backoff strategy |
| 🔀 Proxy Rotation | Automatic IP management & rotation |
| ⚙️ Multi-threading | Concurrent execution across multiple targets |

---

## 🛠️ Tech Stack

| Technology | Version | Purpose |
|---|---|---|
| Python | 3.11+ | Core language |
| Selenium | Latest | Browser automation |
| Playwright | Latest | Advanced browser control |
| Requests | Latest | HTTP session management |
| MongoDB | Latest | Data persistence |
| Redis | Latest | Queue & caching |
| Docker | Latest | Containerization |

---

## 📁 Project Structure

```
Capago-Booking-Bot/
│
├── Main.py                 # Entry point & orchestrator
├── booking.py              # Core booking logic
├── session_manager.py      # Session handling & recovery
├── captcha_solver.py       # Captcha bypass integration
├── notifications.py        # Telegram alert system
├── config.py               # Configuration loader
├── requirements.txt        # Python dependencies
├── .env                    # Environment secrets (not committed)
└── README.md               # This file
```

---

## 🚀 Quick Start

```bash
# 1. Clone the repository
git clone https://github.com/OnlineUnknowns/Capago-Booking-Bot.git
cd Capago-Booking-Bot

# 2. Install dependencies
pip install -r requirements.txt

# 3. Configure environment
cp .env.example .env
# Edit .env with your credentials

# 4. Run the bot
python Main.py
```

---

## 🔐 Security

- ✅ No hardcoded credentials — environment-based secrets only
- ✅ Session isolation between concurrent workers
- ✅ Full retry handling with exponential backoff
- ✅ Structured logging system for complete audit trail

---

## 💡 Support

If this project helped you, consider giving it a ⭐ on [GitHub](https://github.com/OnlineUnknowns/Capago-Booking-Bot)!

---

*Built with ❤️ for high-demand visa automation workflows.*
