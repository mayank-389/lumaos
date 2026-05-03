# 🖥️ Luma OS (Web Desktop)

A fully interactive **web-based desktop operating system UI** built using pure frontend technologies.
It simulates a real OS experience with apps, windows, taskbar, settings, and more.

---

## 🚀 Features

* 🧊 Modern glassmorphism UI
* 🪟 Draggable & resizable windows
* 📌 Taskbar with app management
* 🔍 Search system
* 🧮 Built-in apps:

  * Notes
  * Calculator
  * Todo List
  * Browser
  * Terminal
  * Paint
  * Files
  * Music
  * Clock
  * Weather
* 🔒 Lock screen system
* 📶 WiFi simulation
* 🔊 Volume & battery indicators
* 🎨 Custom wallpaper support
* ⚙️ Quick settings panel

---

## 🧠 Technologies Used

* **HTML5** – Structure
* **CSS3** – UI design, animations, glass effects
* **JavaScript (Vanilla)** – Core logic & OS simulation
* **Browser APIs**:

  * `localStorage` (for saving data like wallpaper, notes, settings)
  * DOM API (for UI rendering and interactions)

---

## ⚙️ “Binary” / Runtime Used

This project does **NOT use a compiled binary** (like `.exe`, `.dll`, etc.).

Instead, it runs on:

* 🌐 **Web Browser Engine**

  * Chromium (Chrome, Edge, Brave)
  * WebKit (Safari)
  * Gecko (Firefox)

### Runtime Environment:

* JavaScript Engine:

  * V8 (Chrome/Edge)
  * SpiderMonkey (Firefox)

### Storage System:

* `localStorage` (acts like lightweight persistent storage)

### Rendering:

* HTML + CSS rendered via browser rendering engine

👉 So effectively:

> **Browser = Runtime + Binary Environment**

---

## 📂 Project Structure

```
Luma-OS/
│── index.html   # Main OS file
│── README.md    # Documentation
```

---

## 🛠️ How to Run

1. Download or clone the project
2. Open `index.html` in any browser
3. Done ✅

No installation required.

---

## 🎯 Customization

### Change Wallpaper

* Upload via Quick Settings
* Or edit:

```js
localStorage.setItem("webos_custom_wallpaper", "your-image-url");
```

### Default Themes

* Gradient-based themes stored in JS

---

## ⚠️ Limitations

* No real file system (simulated only)
* No backend / server
* No real networking (WiFi is simulated)
* Runs entirely client-side

---

## 💡 Future Improvements

* Real file system (IndexedDB)
* App store system
* Multi-user login
* Backend integration
* PWA support

---

## 👨‍💻 Author

Made for learning, UI design, and hackathon projects.

---

## 📜 License

Free to use for educational purposes.
