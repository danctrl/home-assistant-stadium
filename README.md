# 🏟️ Home Assistant – Stadium Instance

Welcome to my **Home Assistant configuration** for the `Stadium` environment — a focused, reliable, and self-hosted smart home setup built with automation, clarity, and resilience in mind.

This public repo serves as:
- 🧠 A version-controlled backup of my Stadium instance
- 📚 A reference for others looking to structure their HA config
- 🔄 A foundation for daily automated syncs to GitHub

> ⚠️ No sensitive information included — `secrets.yaml`, `.storage/`, tokens, and other private data are ignored via `.gitignore`.

---

## 📁 Structure

```bash
/config/
├── configuration.yaml       # Core config
├── automations.yaml         # Manual automations
├── scripts.yaml             # Reusable actions
├── scenes.yaml              # Lighting & moods
├── www/                     # Custom frontend assets
├── custom_components/       # Optional custom integrations
└── ...
```

---

## 🔄 Auto Backup

This configuration is:
- Automatically synced to GitHub **every night at 03:00**
- Using a custom `push.sh` script and `cron`
- Git commits are timestamped for full history traceability

---

## 🚧 Notes

- This is part of a dual-instance setup: see [home-assistant-lounge](https://github.com/danctrl/home-assistant-lounge) for the second zone.
- Everything here is tailored to **my specific hardware, network setup, and use cases** — feel free to fork and adapt.

---

## 🤝 Contributing / Feedback

This project is personal, but if you have **ideas, feedback or questions**, feel free to open an issue or discussion.

---

## 🧙‍♂️ Author

**danctrl** – [danctrl.dev](https://danctrl.dev)  
I build self-hosted systems, clean automations, and occasional chaos.

---
