<div align="center">

# 👋 Vsevolod Samoylov

### QA Engineer · Python · API · Backend · Automation

I work with real products end to end: **UI → API → database → logs → integrations → failure recovery → release decision**.

[Portfolio](https://vsevolodqa.ru/) · [Telegram](https://t.me/vsevolod_qa) · [LinkedIn](https://www.linkedin.com/in/vsevolod-samoylov)

</div>

---

## 🚀 Production engineering

### [Auto-Pricing Bot — GGSEL + DigiSeller](https://github.com/Urushihara24/monitoring-bot)

Production marketplace automation service for competitor monitoring, seller-side repricing and order-chat operations.

**Stack:** Python · Telegram Bot API · GGSEL/DigiSeller APIs · SQLite · Docker · GitHub Actions · pytest

**Engineering focus:**
- isolated marketplace/product profiles;
- resilient storefront parsing and seller API integration;
- price floors, cooldowns, weak-signal filters and idempotent updates;
- fail-closed `DRY_RUN` write boundary;
- Telegram operations and diagnostics;
- non-root Docker runtime, health checks and CI/security verification.

[Repository →](https://github.com/Urushihara24/monitoring-bot) · [Operations →](https://github.com/Urushihara24/monitoring-bot/blob/main/OPERATIONS.md) · [Architecture →](https://github.com/Urushihara24/monitoring-bot/blob/main/docs/ARCHITECTURE.md)

---

## 🔬 Commercial QA work

Sanitized documentation from real paid QA engagements and production product assessments.

| Project | Scope | Result |
|---|---|---|
| **[AI SaaS Platform](https://github.com/Urushihara24/commercial-ai-saas-qa)** | AI runtime · agents · HTTP/OpenAPI integrations · responsive/E2E | **150+ checks**, **20+ defects**, P0/P1 risk coverage |
| **[PRTV.pro](https://github.com/Urushihara24/prtv-pro-test-case)** | Web · Mobile · Android TV · billing · OAuth/POS · migration | **228-case suite**, **45 defects** |
| **[Telaboro](https://github.com/Urushihara24/Telaboro-QA-Case-)** | Android · Admin · API · PostgreSQL · Stripe · Logcat | **150+ cases**, release-blocking payment/profile defects isolated |
| **[Mailshade](https://github.com/Urushihara24/mailshade-qa-case)** | Chrome extension · Gmail · exploratory · UX · localization | **19 findings**, screenshots/video/CSV evidence |
| **[Android TV QA](https://github.com/Urushihara24/qa-android-tv-case)** | Playback · cache · offline USB · schedules | scenario-based defects with runtime evidence |
| **[ChatPlace](https://github.com/Urushihara24/chatplace-qa-test)** | paid Telegram onboarding · API contract · bot/channel binding | release **NO-GO** with traceable blocker evidence |

---

## 🐍 Python systems & automation

### [Exportum Bot](https://github.com/Urushihara24/Exportum_bot)
Commercial Telegram workflow system for agricultural logistics: role-based FSM flows, deal/delivery lifecycle, reporting and Google Sheets integration.

### [Orcestre](https://github.com/Urushihara24/Orcestre)
Telegram-controlled Epic account/campaign manager with PostgreSQL, SQLAlchemy, scheduling, rate controls, diagnostics and Docker deployment.

### [Proxy Seller Desktop Launcher](https://github.com/Urushihara24/Proxy)
Cross-platform Python/Tkinter desktop application for Proxy-Seller API workflows: order calculation, purchase, activation, system proxy configuration and reconnect flows.

---

## 🧪 API QA automation

### [DummyJSON API Regression Suite](https://github.com/Urushihara24/DummyJSON_Test)
Python + pytest + requests regression suite covering authentication, cart CRUD, negative authorization and observed API-contract behavior with CI execution.

### [Nebus / QIWI Payment API Suite](https://github.com/Urushihara24/nebus-qiwi-tests)
Payment API validation using Python, pytest, Playwright `APIRequestContext` and Postman, with explicit safety boundaries around live payment requests.

---

## 🧰 Core stack

**QA / API:** `Postman` · `Swagger/OpenAPI` · `REST API` · `SQL` · `PostgreSQL` · `Kibana` · `Charles Proxy` · `DevTools` · `Android Studio / Logcat`

**Python / automation:** `Python` · `pytest` · `Playwright` · `requests` · `FastAPI` · `asyncio` · `SQLAlchemy`

**Delivery:** `Docker` · `GitHub Actions` · `GitLab CI` · `Linux` · `Jira` · `TestRail` · `Allure`

---

## 🧭 How I investigate failures

```text
Business risk
    ↓
Critical path / state transition
    ↓
Reproduce
    ↓
UI + API + DB + logs evidence
    ↓
Root-cause hypothesis
    ↓
Fix verification
    ↓
Release decision / regression scope
```

---

## 📌 Recommended starting points

1. **[monitoring-bot](https://github.com/Urushihara24/monitoring-bot)** — production Python automation, integrations, safety and operations.
2. **[commercial-ai-saas-qa](https://github.com/Urushihara24/commercial-ai-saas-qa)** — commercial QA execution and evidence model.
3. **[Telaboro-QA-Case-](https://github.com/Urushihara24/Telaboro-QA-Case-)** — mobile/API/payment QA with technical diagnostics.
4. **[PRTV.pro](https://github.com/Urushihara24/prtv-pro-test-case)** — broad release-readiness coverage across Web/Mobile/TV.
5. **[Exportum_bot](https://github.com/Urushihara24/Exportum_bot)** — production Telegram workflow automation.

<div align="center">

### QA and engineering work grounded in real product behavior and technical evidence.

[🌐 vsevolodqa.ru](https://vsevolodqa.ru/) · [💬 Telegram](https://t.me/vsevolod_qa)

</div>
