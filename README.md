# File-Organizer-Python-

# 🗂️ File Organizer (Python)

A simple yet powerful Python script to **automatically organize files** in a given directory by file type. Great for cleaning up messy downloads folders, project directories, or any workspace.

---

## 📦 Features

- 🔄 Automatically categorizes files into folders like:
  - `Images/`, `Videos/`, `Documents/`, `Audio/`, `Archives/`, `Data/`, `Others/`
- 🧠 Uses smart extension-based sorting
- 🛠️ Creates folders if they don’t exist
- ✅ Lightweight and fast — no third-party dependencies

---

## 💻 Usage

### ▶️ Run the script

```bash
python organize.py

You’ll be prompted to enter a directory path:

bash
Copy
Edit
Enter the directory path to organize: C:\Users\YourName\Downloads
Once completed, your files will be sorted into subfolders based on type.

📁 File Categories
Category	Extensions
Images	.jpg, .jpeg, .png, .gif, .bmp, .tiff
Videos	.mp4, .mkv, .flv, .avi, .mov
Documents	.pdf, .doc, .docx, .txt, .ppt, .pptx, .xls, .xlsx
Audio	.mp3, .wav, .aac, .flac
Archives	.zip, .rar, .7z, .tar, .gz
Data	.csv, .json, .xml
Others	Everything else

📌 Example Folder Structure After Organizing
arduino
Copy
Edit
Downloads/
├── Images/
├── Videos/
├── Documents/
├── Audio/
├── Archives/
├── Data/
└── Others/
🔧 Requirements
Python 3.6+

No external libraries required (uses os and shutil)
