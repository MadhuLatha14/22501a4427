# 🔗 URL Shortener Microservice

This project is part of the AffordMed Campus Hiring Evaluation. It implements a robust **HTTP URL Shortener** microservice with logging, analytics, and unique short link generation using **Node.js**, **Express**, and **MongoDB**.

## 🚀 Features

- ✂️ Shortens long URLs with optional custom shortcodes
- ⏳ Expiry logic for short URLs (default: 30 minutes)
- 🔐 Pre-authorized API access (no login/registration required)
- 🧾 Analytics: Tracks clicks, timestamps, sources, and locations
- 📋 Logging Middleware (as per Pre-Test Setup)
- ⚠️ Proper error handling with descriptive messages
- ✅ Unique short link generation with collision handling

---

## 📦 Tech Stack

- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Utilities**: nanoid (shortcode generation), geoip-lite (location), useragent (client info)
- **Environment**: dotenv



