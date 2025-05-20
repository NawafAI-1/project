# 📁 Smart File Organizer (Bash Script)

A simple Bash script that automatically organizes files in a folder into categorized subfolders based on file types (images, documents, videos, music, archives, and others). This tool is perfect for keeping your workspace clean and efficient on Linux systems.

---

## 📌 Features

- Automatically detects and moves:
  - 📷 Images (`.jpg`, `.jpeg`, `.png`)
  - 📄 Documents (`.pdf`, `.docx`, `.txt`)
  - 🎞️ Videos (`.mp4`, `.mkv`)
  - 🎵 Music (`.mp3`, `.wav`, `.m4a`)
  - 📦 Archives (`.zip`, `.tar.gz`)
  - 🧩 Others (all uncategorized files)

- Creates subfolders if they don’t exist.
- Simple and user-friendly CLI interaction.
- Prevents errors by validating folder paths.

---

## 💻 How to Use

### Option 1: Using GitHub Repository

1. Open your terminal.
2. Clone the repository and run the script:

```bash
git clone https://github.com/yourusername/smart-file-organizer.git
cd smart-file-organizer
chmod +x organizer.sh
./organizer.sh
