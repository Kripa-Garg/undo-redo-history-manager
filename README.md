# 🚀 Undo / Redo History Manager

A modern browser-based text editor implementing **Undo/Redo functionality using LIFO Stack Data Structures**.

This project demonstrates how real-world editors like VS Code and Google Docs manage editing history internally using stack-based state management.

---

## ✨ Key Features

- Undo / Redo functionality
- LIFO Stack implementation
- Real-time stack visualization
- Keyboard shortcuts support
- Auto snapshot saving
- Dynamic line numbers
- Character & line counter
- Modern dark-themed responsive UI

---

## 🧠 Core Concept

The project uses **two stacks**:

- **Undo Stack** → Stores previous editor states
- **Redo Stack** → Stores undone states for restoration

### Workflow

- Typing pushes states into the Undo Stack
- Undo restores previous states
- Redo restores undone states
- New edits clear Redo history (branch invalidation)

---

## ⌨️ Keyboard Shortcuts

| Shortcut | Action |
|---|---|
| `Ctrl + Z` | Undo |
| `Ctrl + Y` | Redo |
| `Ctrl + Shift + Z` | Redo |
| `Ctrl + S` | Save Snapshot |

---

## 🛠️ Technologies Used

- HTML5
- CSS3
- Vanilla JavaScript

---

## 📊 Concepts Demonstrated

- Stack Data Structure
- LIFO Principle
- State Management
- Event Handling
- Debouncing
- DOM Manipulation

---

## 👨‍💻 Author

**Kripa Garg**  
B.Tech AIML Student
