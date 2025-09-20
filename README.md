
# 💻 Multimedia Programming Foundation Project

**Description:**
This is a simple desktop-like system application built with multiple apps including Login, Home, Notepad, Text File Editor, Mini Browser (ChRUme), and Photo Editor. Users can interact with shortcuts, save files, open multiple instances, and play multimedia content.

---

## 🌟 Features

### 1️⃣ Login Page

* **Functionality:**

  * Enter password to access Home Page.
  * Password: `123`
  * ❌ Wrong password → shows "Wrong password!"
  * ✅ Correct password → redirects to Home Page

---

### 2️⃣ Home Page

* **Functionality:**

  * Default shortcuts: 🗑 Trash, 📝 Notepad, 🌐 ChRUme
  * Click shortcuts to open apps.
  * Task Bar menu:

    * **Window:** Log Out / Shutdown
    * **Notepad:** open Notepad
  * Auto-organizes shortcuts in multiple columns if >5 shortcuts

---

### 3️⃣ Notepad Application

* **Functionality:**

  * Open multiple Notepad instances.
  * Save text via File > Save.
  * Default file names: `text.txt`, `text1.txt`, etc.
  * Rename allowed with unique alphanumeric names.
  * Saved files generate new shortcut on Home Page.

---

### 4️⃣ Text File Application

* **Functionality:**

  * Open file via shortcut.
  * Title shows file name.
  * Content auto-loads last saved text.
  * Edit and save updates internal database.

---

### 5️⃣ ChRUme Mini Browser

* **Functionality:**

  * Open multiple instances.
  * Search Bar content:

    * **Empty:** Default empty page
    * **Unknown domain:** Shows "This site can’t be reached"
    * **RUtube.net:** Plays `DiamondJack.mp4` (Play/Pause)
    * **RUtify.net:** Plays `PromQueen.mp3` (Play/Pause, slider)
    * **stockimages.net:** Shows cat images, with Download button

      * Saved images appear as shortcuts on Home Page

---

### 6️⃣ Photo Editor Application

* **Functionality:**

  * Open image via shortcut.
  * Zoom in/out using slider.
  * Pan image to view hidden areas.
  * Rotate image 90° per click via menu.

---

## 🛠 Technical Details

* **Platform:** Java Desktop Application
* **IDE:** Eclipse IDE
* **UI Components:** JavaFX / Swing (depending on implementation)
* **File Handling:** Text files (.txt) & Image files (.jpg)
* **Multimedia Support:** MP4 Video & MP3 Audio
* **Shortcut System:** Dynamic creation on Home Page

---

## 🚀 How to Run

1. **Clone Repository:**

```bash
git clone https://github.com/username/MultimediaProject.git
```

2. **Open in Eclipse:**

* Launch **Eclipse IDE**
* File → Import → Existing Java Project → navigate to cloned folder → Finish

3. **Build & Run:**

* Right-click project → Run As → Java Application
* Application starts at Login Page.

---

## 👏 Credits

* Emily Wilkinson – Lead Developer & UX Designer
* Liona Loren – UX Research & Implementation

---

## 📄 License

This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.

---

