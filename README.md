# PD Tracker App

A web-based cloud app for tracking peritoneal dialysis (PD) data including:

- Fluid type and volumes (In/Out)
- Ultrafiltration (auto-calculated)
- Dwell time
- Bowel movement check
- Urine output
- Blood pressure and pulse
- Trend graphs (UF, Urine, BP, Pulse)
- Patient creation and tracking
- Firebase integration for real-time sync

## 🚀 Features

- 📋 Record daily PD exchanges
- 📊 See trend graphs over time
- ➕ Add new patients dynamically
- ☁️ Firebase Realtime Database backend
- 📈 Chart.js integration for visuals
- 🔒 Deployable via GitHub + Vercel

## 📦 Deployment

1. Unzip the project
2. Add your Firebase config to `app.js`
3. Push to a GitHub repo
4. Deploy via [https://vercel.com](https://vercel.com)

## 🔐 Firebase Rules (Development Mode)

```json
{
  "rules": {
    ".read": true,
    ".write": true
  }
}
```

> Change these before production to require authentication.

## 🧾 License

This project is open source and provided as-is for educational and clinical prototyping purposes.

**© 2025 PD Tracker Team. All rights reserved.**

MIT-style license with attribution: You may modify, reuse, or extend this code with attribution to the original author.

---

Made with ❤️ for PD patients, clinicians, and developers.
