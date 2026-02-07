# ⌨️ Coding Keyboard: Privacy-First Accessory IME

[![Kotlin](https://img.shields.io/badge/Kotlin-1.9+-7F52FF?logo=kotlin&logoColor=white)](https://kotlinlang.org/)
[![Android](https://img.shields.io/badge/Android-15.0_(SDK_35)-3DDC84?logo=android&logoColor=white)](https://developer.android.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Privacy](https://img.shields.io/badge/Privacy-Zero_Permissions-blue)](https://github.com/your-username/your-repo#privacy--security)

A specialized Android Input Method Editor (IME) designed for developers and data analysts who need high-speed access to coding symbols without compromising their privacy.

---

## 🚀 The Problem & Solution
Standard mobile keyboards often bury coding symbols (like `->`, `{`, `|`, or `%>%`) deep within sub-menus, slowing down mobile development and data analytics workflows, something I felt keenly trying to code on my Fold 5. Most third-party keyboards also require invasive "Full Access" or Internet permissions, and I couldn't find any keybaord that genuinely allowed coding shortcuts to be used as separate keys. 

**Coding Keyboard** solves this by adding two toggleable, customizable accessory rows to your mobile environment—offering **20 custom key slots** wih 13 Default Presets to choose from (and even 2 custom presets for you to record your own macros) in a strictly offline environment.

## ✨ Features
* **Language-Specific Presets:** Instant layouts for **Python, R, SQL, C++, HTML, JavaScript, Kotlin,** and **Termux**.
* **Dynamic Clipboard Row:** Dedicated accessory row that evolves as you copy text, streamlining the "copy-paste" cycle.
* **Full Customization:** Two "Custom" profiles allowing you to save your most-used shell commands or code snippets.
* **Modern Material UI:** High-contrast Cyan & Midnight theme optimized for visibility on high-resolution displays (tested on Pixel 7/8/9).

## 🔒 Privacy & Security (Zero-Data Policy)
This project was built on the principle of **Data Minimisation**:
* **No Internet Permission:** The app physically cannot send data to an external server.
* **No File Access:** We do not read your local storage.
* **No Data Collection:** We do not track keystrokes, personal info, or usage analytics.
* **Merchant-Free:** This app is hosted on GitHub to bypass the public doxxing requirements (Legal Address visibility) imposed by traditional app stores (aka Google Play Store)

## 🛠️ Tech Stack
* **Language:** 100% Kotlin
* **Architecture:** Component-based Android IME Service
* **UI:** Custom XML Drawables & LayerLists for high-performance rendering
* **Optimization:** R8/ProGuard enabled for minimized APK footprint and code obfuscation

## 📸 Gallery
| 1. Coding Preset (R/Python) | 2. Custom Settings | 3. Key Customization |
| :---: | :---: | :---: |
| <img src="screenshots/action.png" width="250"> | <img src="screenshots/settings.png" width="250"> | <img src="screenshots/edit.png" width="250"> |

---

## 📦 Installation & Setup
1. Download the latest **APK** from the Releases section.
2. Install the APK (Allow "Install from Unknown Sources" if prompted).
3. Open the app and follow the setup guide
4. (No internet or other permissions needed)

---

*Developed by Sulayman_C
