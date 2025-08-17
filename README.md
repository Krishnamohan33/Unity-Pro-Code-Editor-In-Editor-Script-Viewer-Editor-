# 🧠 Pro Code Editor — Unity Editor Extension

[![Unity](https://img.shields.io/badge/Unity-2021%2B-black?logo=unity)](https://unity.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/Krishnamohan33/ProCodeEditor?style=social)](https://github.com/Krishnamohan33/ProCodeEditor)
[![Made with ❤️](https://img.shields.io/badge/made%20with-%E2%9D%A4-red)](https://github.com/Krishnamohan33)

---

**Pro Code Editor** is a lightweight yet powerful in-editor code viewer and editor for Unity.  
Ideal for quick script edits, shader tweaks, or reading code — without leaving the Unity Editor.

---

## ✨ Features

- 🗂️ Open `.cs`, `.txt`, and `.shader` files directly in Unity
- 📝 Rich-text style editing interface
- 💾 Save changes with one click (AssetDatabase auto-refresh)
- 🔄 Change tracking with `isDirty` flag
- 🪟 Integrated into Unity’s `Tools` menu
- 👨‍💻 Developer-friendly UI, supports scroll and autosizing
- 🔒 Prevents accidental loss with unsaved change tracking

---

## 🚀 Pro Premium Edition (Coming Soon)

Upgrade to **Pro Code Editor Premium** for advanced features:

| Feature                                | Free | Premium |
|----------------------------------------|:----:|:-------:|
| Open/Save `.cs`, `.txt`, `.shader`     | ✅   | ✅      |
| Syntax Highlighting (C#, ShaderLab)    | ❌   | ✅      |
| Line Numbering                         | ❌   | ✅      |
| Find & Replace                         | ❌   | ✅      |
| Custom Themes (Dark/Light)             | ❌   | ✅      |
| Git Diff Integration                   | ❌   | ✅      |
| Tabbed Editor UI                       | ❌   | ✅      |
| Undo/Redo Stack                        | ❌   | ✅      |
| Auto Backup on Save                    | ❌   | ✅      |

> 🎁 Want early access to the Premium build? Reach out via [GitHub Discussions](https://github.com/Krishnamohan33/ProCodeEditor/discussions)

---

## 📥 Getting Started

### 1. Installation

> ⚠️ Unity only compiles editor tools inside folders named `Editor`.

### 2. Open the Editor

- Navigate to `Tools > Pro Code Editor`
- Click **Open** to load a file
- Edit and **Save** when done!

---

## 🖥️ Toolbar Overview

| Button     | Description                                 |
|------------|---------------------------------------------|
| **Open**   | Choose a `.cs`, `.txt`, or `.shader` file   |
| **Save**   | Writes file content and refreshes assets    |
| **Label**  | Displays the currently opened filename      |

---

## ⚙️ Developer Notes

### `ShowEditor()`

Creates and displays the EditorWindow.

### `OnGUI()`

Draws UI layout: scroll view, text area, and footer.

### `DrawToolbar()`

Top bar with open/save and current file name.

### `DrawFooter()`

Author credit with clickable GitHub link (uses rich text).

### `LoadFile(path)`

Reads file content into editor.

### `SaveFile()`

Writes changes and refreshes Unity's `AssetDatabase`.

---

## 📎 Limitations (Free Version)

- No syntax highlighting or IntelliSense
- No multi-file or tabbed interface
- No undo/redo support (yet)

---

## 🧑‍💻 Author

**Krishnamohan Yagneswaran**  
🔗 [GitHub Profile](https://github.com/Krishnamohan33)

---

## 📄 License

[MIT](LICENSE) — free to use, modify, and distribute.

---

## 💬 Feedback / Contribute

Pull requests, feedback, and feature requests are welcome!  
👉 [Start a discussion](https://github.com/Krishnamohan33/ProCodeEditor/discussions)

---

## 🔮 Coming Soon

- VS Code plugin sync
- Unity Console integration
- Autoformatting with Roslyn

Stay tuned!


Drop the script into any `Editor` folder in your Unity project.

