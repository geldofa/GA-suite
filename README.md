# 🪟 GA Suite: Smart Automations

Developed by GA, this suite is a high-performance collection of Home Assistant blueprints designed for various tasks

[![HACS Badge](https://img.shields.io/badge/HACS-Custom-orange.svg)](https://hacs.xyz/)
![Home Assistant](https://img.shields.io/badge/Home%20Assistant-2024.1.0%2B-blue)

## 🛠 Features in the GA Suite

### 🛰 GA Blinder - Main Logic
The flagship automation for daily use.
* **Sun-Adaptive:** Opens and closes with the sun, featuring customizable offsets.
* **Lux-Response:** Automatically moves to a specific percentage when it's too bright (perfect for protecting furniture or reducing glare).
* **The Smoothing Engine:** Built-in time delay (smoothing) to ensure the blinds don't react to temporary shadows or clouds.
* **GA Manual Override:** Intelligent logic that detects if you've moved the blinds by hand and halts automation to respect your manual choice.

### 🔋 GA Battery Guard
Keep your hardware running.
* Proactive monitoring of blinder battery levels.
* Automated mobile alerts before the blind becomes unresponsive.

---

## 🚀 Installation

### Via HACS
1. Open **HACS** in your Home Assistant instance.
2. Navigate to **Automation**.
3. Click the **three dots** (top right) > **Custom repositories**.
4. Paste the URL of this repository.
5. Select **Blueprint** as the category and click **Add**.

---

## 📝 Configuration Notes
* **Entity Support:** Works with any device in the `cover` domain.
* **Lux Smoothing:** A setting of **5 to 8 minutes** is the "sweet spot" for most light sensors to prevent rapid opening/closing.
* **Override Reset:** The manual override automatically resets at the next Sun trigger (Sunrise/Sunset), returning the blinds to the GA Suite schedule.

---
*Created with precision by GA.*