# 🎵 Audio Ultra Player

A lightweight **offline music player web app** built with **pure JavaScript**, designed to play and manage local audio files directly in the browser.

This project demonstrates modern **Web APIs** such as:

* IndexedDB
* Web Audio API
* Media Session API
* Service Worker
* Notifications
* Drag & Drop

The app works completely **offline** and stores music locally inside the browser.

---

# ✨ Features

## 🎧 Music Playback

* Play / Pause
* Previous / Next
* Shuffle mode
* Repeat mode
* Playback speed control
* Seek bar (timeline)

---

## 📁 File Management

* Upload **single audio files**
* Upload **entire music folders**
* Drag & drop audio files
* Download songs from the library
* Delete songs

All tracks are stored locally using **IndexedDB**.

---

## 📚 Music Library

* Search songs instantly
* Highlight currently playing track
* Reorder songs with **drag & drop**

---

## 🎨 Visual Experience

* Real-time **audio spectrum visualizer**
* Animated waveform
* Mini player mode

---

## 📱 Mobile Friendly

Supports modern mobile browser features:

* **Media Session API**
* Lock screen controls
* Background playback
* Notification when a track starts playing

---

## 💿 Album Metadata

Automatically reads:

* Album cover (from ID3 tags)
* Track information from audio files

---

## ⚡ Offline Support

The app includes a **Service Worker**, which enables:

* Offline functionality
* App-like installation
* Faster loading

---

# 🛠 Technologies Used

* **JavaScript (Vanilla)**
* **IndexedDB**
* **Web Audio API**
* **Media Session API**
* **Service Worker**
* **Canvas API**
* **jsmediatags** (for reading ID3 metadata)

---




# 📥 Importing Music

You can add music in two ways:

### Upload files

Select individual `.mp3`, `.wav`, `.ogg` files.

### Upload folder

Import an entire music folder at once.

The app will automatically scan all audio files inside.

---

# 🎮 Keyboard Shortcuts

| Key         | Action             |
| ----------- | ------------------ |
| Space       | Play / Pause       |
| Arrow Right | Forward 5 seconds  |
| Arrow Left  | Backward 5 seconds |
| Ctrl + →    | Next track         |
| Ctrl + ←    | Previous track     |

---

# 📌 Future Improvements

Planned upgrades:

* Smart playlists
* Artist / Album view
* BPM detection
* Advanced equalizer
* Better waveform visualization
* PWA install support

---

# 👨‍💻 Author

Created as a **web audio project** to explore modern browser APIs and build a fully functional **client-side music player**.

---

# 📜 License

This project is open source and available under the **MIT License**.
