# 🧠 Pro Code Editor — Unity Editor Extension

**Pro Code Editor** is a lightweight, in-editor script viewer and editor for Unity.  
Designed for quick edits, reviewing code, or scripting small changes — right inside the Unity Editor.

Built with ❤️ by [Krishnamohan Yagneswaran](https://github.com/Krishnamohan33)

---

## ✨ Features

- 🗂️ Open `.cs`, `.txt`, and `.shader` files directly from the Unity Editor  
- 📝 Built-in text editor for live editing  
- 💾 Save changes instantly and refresh the Asset Database  
- 📜 Clean, scrollable code view with change tracking  
- 🙌 Friendly UI integrated into Unity’s `Tools` menu  
- 🔒 Prevents accidental loss with unsaved changes tracking  

---

## 📥 Getting Started

### 1. Installation

Copy the `ProCodeEditor.cs` script into an `Editor` folder inside your Unity project:


> ℹ️ The script **must** be placed inside an `Editor` folder. Unity only compiles editor scripts placed in such folders.

### 2. Usage

- Open Unity
- Navigate to `Tools > Pro Code Editor`
- Click **Open** to load a `.cs`, `.txt`, or `.shader` file
- Edit the content freely
- Click **Save** to write changes back to the file

---

## 🖥️ UI Overview

| Button     | Description                                 |
|------------|---------------------------------------------|
| **Open**   | Opens a file picker to choose a code file   |
| **Save**   | Saves changes back to the file              |
| **Label**  | Displays current file name (if any)         |

The editor automatically tracks unsaved changes, helping prevent data loss.

---

## ⚙️ Code Breakdown

### `ShowEditor()`
Initializes and displays the editor window.

### `OnGUI()`
Draws the editor UI including the scrollable text area and footer.

### `DrawToolbar()`
Renders the top toolbar with Open, Save buttons and file name display.

### `DrawFooter()`
Adds a simple footer with author credit and a GitHub link.

### `LoadFile(path)`
Reads and loads the selected file content.

### `SaveFile()`
Writes updated content to the original file and refreshes the AssetDatabase.

---

## 🙋‍♂️ Why Use This?

While full IDEs like Visual Studio or Rider are powerful, sometimes you just need:

- A quick fix in a script
- A glance at shader logic
- Lightweight editing while testing in Play Mode

**Pro Code Editor** is ideal for fast, in-Unity edits.

---

## 📎 Limitations

- This is a **plain text editor** — no syntax highlighting or autocomplete
- Not a replacement for a full IDE (but a handy complement)

---

## 🧑‍💻 Author

**Krishnamohan Yagneswaran**  
🔗 [GitHub Profile](https://github.com/Krishnamohan33)

---

## 📄 License

This project is licensed under the MIT License — free to use, modify, and distribute.

---


