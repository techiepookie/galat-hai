# 🚫 **Galat Hai — Smart Site Blocker (Chrome Extension)**

![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)
![MV3](https://img.shields.io/badge/Manifest%20Version-3-blue?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge)
![Size](https://img.shields.io/badge/Ultra--Light-<50KB-orange?style=for-the-badge)
![Fun](https://img.shields.io/badge/Fun%20Level-🔥🔥🔥-ff69b4?style=for-the-badge)

*A funky, fun, and fast Chrome extension that blocks "galat" websites and redirects users to a custom video page. Lightweight, stylish, and built with Manifest V3.*

---

## ✨ **Features**

💥 Blocks unwanted websites instantly using **DNR (Declarative Net Request)**
🎬 Redirects to your own **custom hosted HTML + video page**
👀 Works in **normal + incognito mode**
⚡ Zero performance impact (no background scripts needed)
🧩 Fully open source + customizable
😂 Perfect for pranks, fun, and discipline

---

## 🏗 **Folder Structure**

```
galat_hai/
 ├── manifest.json
 ├── rules.json
 ├── redirect.html (hosted online)
 ├── icon.png
 └── README.md
```

---

## 🚀 **Installation (Developer Mode)**

1. Download or clone this repo.
2. Open Chrome and go to:

```
chrome://extensions
```

3. Toggle **Developer Mode** ON.
4. Click **Load Unpacked**.
5. Select the extension folder.
6. Enjoy the magic 🎉

---

## 🛡 **How It Works**

This extension uses Chrome's official **Manifest V3 DNR API**:

* No background tasks
* No CPU usage
* No privacy issues
* Extremely fast URL filtering

When a URL matches any keyword in `rules.json`, Chrome instantly redirects the user to your custom HTML page.

---

## 🎯 **Editing Blocked Keywords**

Open `rules.json` and modify:

```json
"urlFilter": "porn"
```

Add new rules by copying blocks. Reload extension after changes.

---

## 🎨 **Custom Icon Setup**

Use your own `icon.png` and update manifest:

```json
"icons": {
  "16": "icon.png",
  "32": "icon.png",
  "48": "icon.png",
  "128": "icon.png"
}
```

Icon recommended sizes: `128×128`.

---

## 🌐 **Hosting Your Redirect Page**

You can host your funny redirect page on:

* GitHub Pages (free)
* Cloudflare Pages (fastest)
* Netlify
* Vercel
* Any HTTPS domain


---

## 🖼 **Screenshots**

<img width="1516" height="817" alt="image" src="https://github.com/user-attachments/assets/8f40588c-9956-4699-b23b-5e65dc400793" />


---

## 🔐 **Privacy Policy**

* ❌ No tracking
* ❌ No analytics
* ❌ No data collection
* ✔ 100% safe for users

---


## 💚 **Credits & Love**

Made with ❤️, JavaScript, and full-time vibes.
Use it for fun, learning, or just to mess with friends 🤣

---

## ⭐ **Want to Improve It?**

Feel free to fork, PR, or star ⭐ the repo!

---

🔥 *Galat ka time gaya. Ab productivity ka time hai.*
