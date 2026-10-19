# 🚀 Postman API Testing & Integration Portfolio

Welcome to my API Testing portfolio project! This repository contains comprehensive Postman collections demonstrating hands-on experience with API querying, cURL request extraction, and real-time bot automation under a Linux environment.

---

## 📌 Project Overview

This portfolio covers three core API modules, showcasing different authentication methods, request structures, and payload formats:

1. **NewsAPI** (`News API`)
   - **Focus:** Query parameters, data filtering, and HTTP GET operations.
   - **Key Highlights:** Fetching top headlines and filtering news articles by parameters (e.g., query terms, country, and pagination).

2. **HH.ru (HeadHunter API)** (`HH.ru`)
   - **Focus:** Web scraping workflow integration via Browser DevTools.
   - **Key Highlights:** Extracting live cURL requests from DevTools (Network tab) and importing/converting them into structured Postman requests for job vacancy searches.

3. **Telegram Bot API** (`Telegram Bot`)
   - **Focus:** Bot control via Token Authentication, Environment Variables, and JSON payloads.
   - **Key Highlights:** 
     - `getMe`: Validating bot token and metadata.
     - `getUpdates`: Polling incoming user messages and extracting dynamic `chat_id`s.
     - `sendMessage`: Sending automated HTTP POST messages with custom JSON payloads (`chat_id`, `text`).

---

## 🛠️ Environment & Tools

- **OS:** Linux (Ubuntu / Debian)
- **API Client:** Postman Desktop App / Web Agent
- **Data Formats:** JSON, cURL, Query Parameters
- **Version Control:** Git & GitHub

---

## 📂 Repository Structure

```text
.
├── Postman_API_Portfolio.postman_collection.json   # Exported Postman Collection (v2.1)
└── README.md                                       # Project Documentation
