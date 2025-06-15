# *Smart Directory Management System*

An intelligent Python-based tool that helps you organize, scan, detect duplicates, and undo file operations — all via a modern Tkinter-powered GUI.

🚀 Features
✅ Automatic File Organization
Categorizes files into folders like Images, Documents, Audio, Code, etc. using file extensions and MIME types.

✅ Duplicate File Detection
Identifies duplicate files by comparing their content hash (MD5).

✅ Undo Last Action
Reverts the last organization operation to restore original file locations.

✅ Visual Preview
Preview how files will be moved before confirming.

✅ Modern GUI Interface
User-friendly, responsive interface using Tkinter and TreeView.

📷 GUI Preview
(Optional: Add screenshots here)

🛠 Technologies Used
Python 3.x

Tkinter – GUI

hashlib – File hashing for duplicates

magic – MIME type detection

os, shutil – File system operations

Pillow (optional) – For future image metadata handling

📦 Installation
1. Clone this repository
bash
Copy
Edit
git clone https://github.com/your-username/smart-directory-manager.git
cd smart-directory-manager
2. Install required packages
Ensure you have Python 3 installed.

bash
Copy
Edit
pip install -r requirements.txt
If tkinter fails to install via pip (on some systems), you may need to install it through your system’s package manager (e.g., sudo apt install python3-tk on Ubuntu).

💻 Usage
bash
Copy
Edit
python directory_manager.py
🧭 How to Use
Select a Directory
Browse and select the folder you want to scan and manage.

Scan
Click Scan to view all files in the directory.

Organize Files
Click Organize to auto-categorize files into folders.

Undo
If something goes wrong, click Undo to revert.

Detect Duplicates
Find and delete duplicate files by content hash.

Preview
See how files will be moved before confirming with the Preview Changes button.

📁 Folder Categorization Logic
Files are sorted into these categories:

Category	Extensions
Images	.jpg, .jpeg, .png, .gif, .bmp
Documents	.pdf, .doc, .docx, .txt
Spreadsheets	.xls, .xlsx, .csv
Presentations	.ppt, .pptx
Archives	.zip, .rar, .7z
Audio	.mp3, .wav
Video	.mp4, .avi
Executables	.exe, .msi
Code	.py, .js
Other	All uncategorized extensions

📂 Project Structure
bash
Copy
Edit
.
├── directory_manager.py    # Main GUI + backend logic
├── requirements.txt        # Dependencies
└── README.md               # Project documentation
🤝 Contributing
Contributions are welcome!

Fork the repo

Create a new branch: git checkout -b feature-name

Make your changes

Commit: git commit -m "Added new feature"

Push: git push origin feature-name

Open a Pull Request

🧑‍💻 Author
Shashank Singh
📧 shashanksingh9048@gmail.com

🏅 Acknowledgements
Tkinter and Python’s standard libraries

python-magic, Pillow

Inspiration from file automation and decluttering tools
