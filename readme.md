<p align="center">
  <img src="homeassistant/image/stadium_banner.jpg" alt="Stadium – Home Assistant Project Banner" width="100%">
</p>


Hi there!  
Welcome to my personal smart home project, codenamed **“Stadium”** – a local-first, privacy-respecting, and modular Home Assistant setup.

I'm running this on a Lenovo ThinkCentre M710q with RHEL 9.5, virtualized via KVM. The goal: reliable automation, native Apple Home integration, and a clean structure I can build on.

---

## 📊 Quick Stats

| Description               | Value                          |
|---------------------------|--------------------------------|
| Entities in total         | 409           |
| Number of sensors         | 190    |
| Installed add-ons         | 0           |
| HACS components (custom)  | 8  |

---

## ⚙️ Hardware Overview

- 💻 **Device**: Lenovo ThinkCentre M710q (Intel i5)
- 🧠 **OS**: Red Hat Enterprise Linux 9.5
- 🖥️ **Hypervisor**: KVM + Home Assistant OS VM
- 📡 **Zigbee**: Sonoff Zigbee Dongle Plus (via ZHA)
- 🌐 **Thread / Matter**: Apple HomePod mini (Thread Border Router)

---

## 🧠 Architecture at a Glance

- Home Assistant OS in a dedicated KVM VM
- Reverse proxy managed via **Traefik**, protected with **Authentik (OIDC)**
- Zigbee (ZHA), Matter, MQTT and HomeKit all integrated
- Secure automation deployment and secrets handling
- Backup to Google Drive and config versioning with GitHub

---

## 🧩 Installed Add-ons

🚧 [Under Construction](https://github.com/custom-components/readme/issues/22) 🚧

---

## 🧬 HACS Integrations

These are custom components installed through HACS:
- [Adaptive Lighting](https://github.com/basnijholt/adaptive-lighting): _Adaptive Lighting custom component for Home Assistant_
- [Alarmo](https://github.com/nielsfaber/alarmo): _Easy to use alarm system integration for Home Assistant_
- [Generate Readme](https://github.com/custom-components/readme): _Use Jinja and data from Home Assistant to generate your README.md file_
- [HACS](https://github.com/hacs/integration): _HACS gives you a powerful UI to handle downloads of all your custom needs._
- [Header Authentication](https://github.com/BeryJu/hass-auth-header): _Home Assistant custom component, which allows you to delegate authentication to a reverse proxy._
- [Presence Simulation](https://github.com/slashback100/presence_simulation): _Home Assistant Presence Simulation_
- [Scene Presets](https://github.com/Hypfer/hass-scene_presets): _Hue-like scene presets for lights in home assistant_
- [Spook 👻 Your Homie](https://github.com/frenck/spook): _A scary 👻 powerful toolbox 🧰 for Home Assistant 🏡_

---

## 🎨 Lovelace Plugins

---

## 🎭 Themes

---

## 🤖 Favorite Automations

Here are some automations I use daily or am particularly proud of:

- 💡 Adaptive Lighting that adjusts based on sun position and presence
- 🕵️‍♂️ Presence detection using UniFi + iPhone + MQTT trackers
- 🔔 Ring Intercom video & MQTT integration for door alerts
- 💤 Sleep mode scenes triggered via Shortcuts + motion sensors
- 🎙️ Google Translate TTS alerts (e.g. for smoke or intrusion)

---

## 🔒 Security & Backups

- 🔐 Access secured with Traefik + Authentik
- 📦 Daily encrypted backups pushed to Google Drive
- 🧾 Secrets are stored securely in `secrets.yaml`
- 🔍 Periodic checks with Lynis and SSH terminal access

---

## 📝 Final Notes

This README is automatically generated using the  
[custom-components/readme](https://github.com/custom-components/readme) integration.

If you’re reading this and are working on your own smart home — feel free to borrow ideas or reach out!