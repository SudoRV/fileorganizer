File Organizer CLI 📂

A simple command-line tool to automatically organize files in a directory based on their extensions.

🚀 Features

✔ Automatically moves files into categorized folders based on extensions
✔ Supports all file types
✔ Avoids overwriting existing files
✔ Fast and lightweight


---

📥 Installation

1️⃣ Install via pip (Recommended)

pip install file-organizer-cli

2️⃣ Install from Source

git clone https://github.com/yourusername/file-organizer-cli.git
cd file-organizer-cli
pip install --editable .


---

🔧 Usage

Basic Command

To organize files inside a folder:

arrange /path/to/folder

Example

Before running:

Downloads/
├── report.pdf
├── music.mp3
├── photo.jpg

After running:

Downloads/
├── pdf/
│   ├── report.pdf
├── mp3/
│   ├── music.mp3
├── jpg/
│   ├── photo.jpg


---

🛠 Development

If you want to modify this tool, follow these steps:

git clone https://github.com/yourusername/file-organizer-cli.git
cd file-organizer-cli
pip install --editable .

Now you can test changes by running:

arrange /path/to/folder


---

📄 License

This project is licensed under the MIT License.


---

🤝 Contributing

Feel free to open an issue or submit a pull request! 🚀


---

📌 Notes

Ensure Python 3.6+ is installed.

Run pip uninstall file-organizer-cli to remove the package.



file_organizer/
│── file_organizer/   # Package source folder
│   ├── __init__.py   # Marks it as a package
│   ├── organize.py   # Your script
│── setup.py          # Setup script
│── README.md         # Project description
│── LICENSE           # (Optional) License file
│── requirements.txt  # (Optional) Dependencies