# TECHNO4 Threads Components (`techno4-threads-components`)

<div align="center">

**Бібліотека вузлів та компонентів ThreadsStream для Threads Studio**  
*ThreadsStream node and component library for Threads Studio*

[![License: LGPL-3.0-or-later](https://img.shields.io/badge/License-LGPL--3.0--or--later-blue.svg)](LICENSE)
[![Organization](https://img.shields.io/badge/Organization-CO%20%C2%ABCF%20TECHNO4%C2%BB-green.svg)](https://techno4.online)

---

### [🇺🇦 Українська](#-українська) &nbsp;|&nbsp; [🇬🇧 English](#-english)

---

</div>

<br>

---

## 🇺🇦 Українська

### 🎯 Мета проєкту
> **Вільна ініціатива підтримки сучасних інструментів розробника за підтримки благодійної організації «БЛАГОДІЙНИЙ ФОНД ТЕХНО4» (CO «CF TECHNO4»).**

`techno4-threads-components` — це офіційна бібліотека готових вузлів, сервісів та блоків автоматизації для середовища візуального програмування **Threads Studio** у складі **TECHNO4 FRAMEWORK2**.

### 🧩 Склад бібліотеки
Репозиторій містить понад 140 компонентів, розподілених за функціональними напрямками:
- **Мережа та протоколи**: REST маршрути, WebSockets, MQTT брокери та підписки, HTTP запити, проксі.
- **Апаратні підсистеми**: Серійні порти (Serial COM), потокове аудіо, телеметрія.
- **Бази даних**: Вбудована NoSQL, PostgreSQL, MongoDB, MySQL, InfluxDB, SQLite3.
- **Обробка даних**: Data Mapper, JSON Schema валідатор, Data Sorter, CSV парсер, регулярні вирази.
- **Штучний інтелект**: Інтеграція Ollama, ChatGPT API, AI контексти.
- **Логіка та управління**: Тригери, розклади (crontab), затримки, черги, лімітери, таймаути.

### 🛠 Збірка реєстру компонентів
Для оновлення індексу компонентів та генерації `db.json`:

```bash
npm run build:db
```

### 🧪 Тестування компонентів
```bash
npm test
```

### 📚 Офіційна документація
Докладний опис та посібники:  
👉 **[https://techno4.online/надбання/фреймворк](https://techno4.online/%D0%BD%D0%B0%D0%B4%D0%B1%D0%B0%D0%BD%D0%BD%D1%8F/%D1%84%D1%80%D0%B5%D0%B9%D0%BC%D0%B2%D0%BE%D1%80%D0%BA)**

### ⚖️ Ліцензія та права
Вихідний код розповсюджується за ліцензією **LGPL-3.0-or-later**.  
Підтримується: **благодійна організація «БЛАГОДІЙНИЙ ФОНД ТЕХНО4»** (`CO «CF TECHNO4»`).  
Автор: **Mykola Zghurskyi** (`mykola@techno4.online`).  
Містить адаптовані компоненти із проєкту Total.js Threads (MIT License).

<br>

---

## 🇬🇧 English

### 🎯 Project Mission
> **A free initiative supporting modern developer tools, supported by the charitable organization "CO «CF TECHNO4»" (благодійна організація «БЛАГОДІЙНИЙ ФОНД ТЕХНО4»).**

`techno4-threads-components` is the official library of pre-built ThreadsStream nodes, microservices, and automation blocks for the **Threads Studio** visual development engine in **TECHNO4 FRAMEWORK2**.

### 🧩 Component Catalog
The repository provides over 140 production-grade components across essential categories:
- **Networking & Protocols**: REST routes, WebSockets, MQTT brokers & subscriptions, HTTP client requests.
- **Hardware & IoT**: Serial COM ports, streaming audio pipelines, real-time telemetry.
- **Data Persistence**: Embedded NoSQL, PostgreSQL, MongoDB, MySQL, InfluxDB, SQLite3.
- **Data Pipelines**: Data Mappers, JSON Schema validators, Data Sorters, CSV datasets.
- **Artificial Intelligence**: Ollama local models, ChatGPT API integrations, AI contexts.
- **Control Flow**: Triggers, crontabs, delays, queues, throttles, timeouts.

### 🛠 Rebuilding Component Database
To index all components and update `db.json`:

```bash
npm run build:db
```

### 🧪 Running Unit Tests
```bash
npm test
```

### 📚 Official Documentation
For detailed guides and references:  
👉 **[https://techno4.online/надбання/фреймворк](https://techno4.online/%D0%BD%D0%B0%D0%B4%D0%B1%D0%B0%D0%BD%D0%BD%D1%8F/%D1%84%D1%80%D0%B5%D0%B9%D0%BC%D0%B2%D0%BE%D1%80%D0%BA)**

### ⚖️ License & Attribution
Distributed under the **LGPL-3.0-or-later** license.  
Published and supported by **CO «CF TECHNO4»** (`благодійна організація «БЛАГОДІЙНИЙ ФОНД ТЕХНО4»`).  
Author: **Mykola Zghurskyi** (`mykola@techno4.online`).  
Contains derivatives of Total.js Threads components (MIT License).