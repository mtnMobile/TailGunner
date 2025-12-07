# TailGunner

**TailGunner** is a retro, arcade-style space defense game originally written as a **Java Applet**.  
This repository preserves the complete historical project — including the applet source code, screenshots, sounds, and the original HTML documentation.

---

## 📘 Original Documentation

The authentic documentation for this project is preserved in:

**`index.html`**

It includes screenshots, thumbnails, and the original web layout used when the game was first released.

To view it locally:

```
file:///path/to/TailGunner/index.html
```

---

## 📂 Project Contents

```
TailGunner/
├── TailGunner.java        # Main Java applet source code
├── tailgunner.html        # Applet runner page
├── index.html             # Original documentation page
├── license.txt            # License terms (please read)
│
├── blast.au               # Sound effects
├── explode.au
├── debris.au
├── fire.au
├── passing.au
├── targeted.au
│
├── scrnshot1.jpg          # Full-size screenshots
├── scrnshot2.jpg
├── scrnshot3.jpg
├── scrnshot4.jpg
│
├── thumb1.gif             # Thumbnail images
├── thumb2.gif
├── thumb3.gif
└── thumb4.gif
```

---

## 🕹️ Running TailGunner

### **Option 1 — Run with `appletviewer` (Java 6–8)**

Install a legacy JDK that still supports applets and run:

```bash
appletviewer tailgunner.html
```

This launches the game exactly as it originally ran inside a browser.

---

### **Option 2 — Modernize Into a Desktop Java Application**

Modern Java versions (11, 17, 21+) no longer support applets.  
To run or extend TailGunner today, you can convert it into a standalone application by:

- Adding a `main()` method  
- Replacing applet lifecycle calls (`init()`, `start()`)  
- Updating image & audio loading to use classpath references  
- Using Java2D or another rendering approach  

If you'd like a modernized version generated automatically, just ask.

---

## 🎮 Gameplay Summary

| Action | Description |
|--------|-------------|
| Move crosshair | Move the mouse to aim |
| Fire | Click mouse button |
| Goal | Shoot ships before they pass your craft |
| Lose condition | Too many enemy ships escape |

---

## 🔉 Audio

TailGunner uses `.au` sound files for:

- Laser fire  
- Explosions  
- Debris  
- Passing ships  
- Target lock  

These can be modernized easily when converting to a standalone application.

---

## 🛠️ Compatibility

| Environment | Supported | Notes |
|------------|-----------|-------|
| Modern Browsers | ❌ | Java applets fully removed |
| Java 17+ | ⚠️ | Applet API removed; requires modernization |
| Java 8 | ✔️ | Last widely available version with appletviewer |
| OpenJDK 6–8 | ✔️ | Fully compatible |

---

## 📜 License

This project is distributed under the terms found in:

**`license.txt`**

Please review the license before modifying or redistributing any code, images, or audio assets.

---

## ❤️ Purpose

This repository exists to preserve an early example of Java arcade game development.  
The code and documentation remain in their original format for historical and educational purposes.
