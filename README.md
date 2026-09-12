🗂️ File Organiser (Light/Dark Mode)


A desktop GUI application built with Python and Tkinter that automatically organizes files in a selected folder into categorized subfolders based on file type. Includes a safety layer to prevent accidental modification of critical system directories, and a toggleable light/dark theme.


✨ Features
Automatic File Sorting — Scans a folder and moves files into category-based subfolders:

🖼️ Images (.jpg, .jpeg, .png, .gif)

📄 Documents (.pdf, .docx, .doc, .txt, .pptx, .xlsx)

🎬 Videos (.mp4, .mkv, .flv, .avi)

🎵 Music (.mp3, .wav, .aac)

📦 Archives (.zip, .rar, .7z, .tar)

⚙️ Programs (.exe, .msi, .apk)

🐍 Python Files (.py)

📁 Others (uncategorized file types)

Safety Checks — Blocks organization of critical system paths (e.g., C:\, C:\Windows, C:\Program Files, C:\Users) to prevent accidental damage.
Simple GUI — Built with Tkinter, featuring a folder browser and one-click organizing.
Light/Dark Mode Toggle — Switch between light and dark themes on the fly.

🛠️ Tech Stack

Language: Python 3

GUI Framework: Tkinter (standard library)

Core Modules: os, shutil

📋 Prerequisites

Python 3.7 or higher

Tkinter (usually bundled with Python; on Linux install via sudo apt-get install python3-tk if missing)

🚀 Getting Started

Clone the repository

bash
   git clone https://github.com/your-username/file-organiser.git
   cd file-organiser
Run the application
bash

python file_organiser.py

💡 Usage

Launch the app.

Click Browse and select the folder you want to organize.

Click Organise Files — files will be automatically sorted into category folders.

Use Toggle Light/Dark Mode to switch the app's appearance.

🔒 Safety Design

Before organizing, the app validates the selected path against a blocklist of critical system directories. If a protected folder is selected, the operation is cancelled and a warning is shown instead of proceeding — reducing the risk of accidentally disrupting the OS or important system files.

📂 Project Structure

file-organiser/

│

├── file_organiser.py   # Main application (backend + GUI)

└── README.md           # Project documentation

👤 Author

Built by IAKSH — Engineering student passionate about building practical desktop tools.

⭐ If you found this project useful, consider giving it a star!
