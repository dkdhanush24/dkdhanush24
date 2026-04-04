# Hey, I'm Dhanush S 👋

Final year engineering student at TKM Institute of Technology, Kerala.
I build real systems — IoT pipelines, AI-integrated apps, and mobile applications — mostly self-taught, mostly by just starting and figuring it out.

I'm interested in the intersection of **AI/ML**, **embedded systems**, and **full-stack development**. Not the tutorial kind — the kind where things actually run in production and break in interesting ways.

---

## What I'm Working With

**AI / ML**
- LLM integration (GPT-4o-mini function-calling, Llama 3 via Groq)
- Speech-to-text pipelines (Whisper)
- ML — regression, classification, real-world data cleaning (1.9M row dataset)

**IoT / Embedded**
- ESP32 firmware (Arduino C++)
- BLE scanning, MQTT over TLS, WiFiManager captive portal
- GPS tracking (NEO-M8N), 4G LTE integration (A7670E)
- End-to-end IoT pipeline: hardware → cloud → mobile

**Backend**
- Node.js + Express
- Python + Flask
- MongoDB Atlas (Mongoose)
- REST API design, MQTT pub/sub

**Mobile & Frontend**
- React Native + Expo (TypeScript)
- Android native (Kotlin + Jetpack Compose)


---

## Projects

### 🏫 CampusNav
> IoT + AI campus system — built for real deployment at TKM Institute of Technology

A full-stack smart campus platform integrating BLE faculty tracking, an AI chatbot, graph-based campus navigation, and GPS bus tracking.

- ESP32 BLE scanners detect faculty location room-by-room via MQTT pipeline
- GPT-4o-mini chatbot with strict function-calling architecture — LLM only selects tools, never touches raw data
- BFS graph pathfinding for outdoor navigation + step-by-step indoor directions
- React Native mobile app + Node.js backend on MongoDB Atlas
- Bus tracking module: ESP32 + NEO-M8N GPS + A7670E 4G — powered directly from bus battery

`ESP32` `BLE` `MQTT` `Node.js` `MongoDB` `GPT-4o-mini` `React Native` `Google Maps`

---

### 📓 Voice Trading Journal
> Personal tool — built because I actually needed it

An Android app that lets me record my trading reasoning by voice. The audio is transcribed using Groq Whisper, then parsed by Llama 3 70B into structured trade data (timeframe, bias, setup, confluences) and saved as flashcard-style journal entries.

Built this entirely for personal use. Tired of typing out trade notes — now I just talk.

- Android native (Kotlin + Jetpack Compose + Room Database)
- Python Flask backend handling audio upload, Whisper transcription, and Llama 3 structured extraction


`Kotlin` `Jetpack Compose` `Flask` `Groq` `Whisper` `Llama 3` `Room DB`

---

### 🧹 Real-World Data Cleaning Pipeline
> 1.9M rows → 1.7M rows of clean, usable data

Built a data cleaning pipeline on a large real-world dataset. Handled missing values, duplicates, outliers, format inconsistencies, and reduced noise — entirely self-directed, no mentor.

`Python` `Pandas` `NumPy`

---

### 📉 Employee Attrition Prediction
> Classification model to predict employee churn

End-to-end ML project — data preprocessing, feature engineering, model training and evaluation.

`Python` `Scikit-learn` `Pandas`

---

## How I Learn

No bootcamp. No mentor. Mostly LLMs, documentation, and building things until they work.
Everything here was built by actually building it — not following along with someone else's tutorial.

---

## Currently

- 📍 Kerala, India
- 🎓 Final year — graduating soon
- 👀 Open to AI/ML, IoT, or full-stack roles — remote or otherwise
- 📬 Reach me via LinkedIn (link in profile)

---

*I build things for personal use, for projects, and occasionally for clients. If it solves a real problem, it's worth building.*
