# 🗂️ File Organizer Tool

A Python-based local file organizer that automatically sorts files in a specified folder into categorized subfolders (Images, Documents, Videos, etc.).

## 📌 Description

This tool helps you clean up a cluttered folder by organizing files based on their file types. It uses file extension mapping and moves files into corresponding subdirectories.

Developed by **Mahlaxmi**.

---

## ⚙️ Features

- ✅ Automatically detects and organizes files into:
  - `Images/` (e.g., `.jpg`, `.png`, `.jpeg`, `.gif`)
  - `Documents/`:
    - `Documents/PDFs/` (e.g., `.pdf`)
    - `Documents/` (e.g., `.txt`, `.docx`)
  - `Videos/` (e.g., `.mp4`, `.mkv`)
- ✅ Creates necessary directories if they don’t exist.
- ✅ Handles exceptions during the move process.
- ✅ Accepts folder path as user input.
- ✅ Optional: Adds support for organizing by creation/modification date.
- ✅ Bonus:
  - Can be run as a CLI tool with arguments.
  - Generates a summary log file of moved files.

---

## 🧰 Technologies Used

- Python 3.x
- Libraries:
  - `os`
  - `shutil`
  - `pathlib`
  - `sys` *(optional, for CLI)*

---

## 🚀 How to Run

### Option 1: Basic Interactive Mode

```bash
python file_organizer.py
