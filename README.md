🌳 TreeXplorer – Advanced File & Folder Tree Viewer  

🚀 TreeXplorer is a powerful and flexible CLI tool to visualize directory structures with file sizes, timestamps, permissions, and emojis. It's perfect for developers, system admins, and content managers who need a structured view of their files!  

 ✨ Features  

✅ Generate a structured file tree 📂 and save it directly as 📄 <foldername>_FileStructure.txt.  
✅ Show file sizes 📏, timestamps ⏳, and permissions 🔑  
✅ Filter files by type, depth, and hidden status  
✅ Emoji support for better readability 🐍📄🖼️  
✅ Multi-threaded for speed ⚡  
✅ Exportable to text files 📜  

---

 📦 Installation  

 🔧 Clone the Repository  

git clone https://github.com/yourusername/TreeXplorer.git  
cd TreeXplorer  

 ▶️ Run the Script  

Make sure you have Python 3.7+ installed.  

python ls.py --help  

---

 📌 Usage  

 📂 Basic Usage  

Generate the file structure of the current directory:  

python ls.py  

 📑 Show Additional Details  

python ls.py -s -pr -cr -ud -ac  

🔹 -s → Show file/folder sizes 📏  
🔹 -pr → Show permissions (rwx format) 🔑  
🔹 -cr → Show creation date 🕰️  
🔹 -ud → Show last modified date 📅  
🔹 -ac → Show last accessed date ⏳  

 🎨 Clean Mode (Indented Format)  

python ls.py -c  

 📂 Include/Exclude Specific Folders  

python ls.py -i src logs -e node_modules  

🔹 -i → Only include these folders 📁  
🔹 -e → Exclude these folders ❌  

 🎭 Hidden Files & File Type Filtering  

python ls.py -hidden -t .py .md  

🔹 -hidden → Include hidden files 👀  
🔹 -t → Only show specific file types (e.g., `.py`, `.md`) 📜  

 🖼️ Add Emojis for Better Readability  

python ls.py -em  

---

 🛠️ Use Cases  

 1️⃣ Developers & Project Management  

- Quickly visualize project structure  
- Filter files (e.g., only `.js` or `.py`)  
- Save structure for documentation  

python ls.py -i src -t .py -c  

 2️⃣ System Administrators  

- Check file permissions across directories  
- Monitor recently modified files  

python ls.py -pr -ud -ac  

 3️⃣ Data Analysts & Content Managers  

- Get an overview of data files (`.csv`, `.xlsx`)  
- Sort files by last access  

python ls.py -t .csv .xlsx -ac  

 4️⃣ Security & Compliance Checks  

- Identify restricted files  
- Audit access and modification dates  

python ls.py -pr -ac -cr  

---

 📜 License  

This project is licensed under the MIT License – feel free to use, modify, and share!  

---

 🤝 Contributing  

💡 Have ideas for improvements? Fork the repo, create a branch, and submit a pull request! 🚀  

---

 📄 Example Output  

 Default Mode (-em for emojis)  

📂 MyProject  
├── 📁 src  
│   ├── 🐍 main.py (4.5 KB)  
│   ├── 🐍 utils.py (2.1 KB)  
│   └── 📁 templates  
│       ├── 📄 index.html (3.2 KB)  
│       └── 🎨 style.css (1.7 KB)  
└── 📄 README.md (1.2 KB)  

 Clean Mode (-c)  

📂 MyProject (File Structure)  
===========================  
src  
  main.py (4.5 KB)  
  utils.py (2.1 KB)  
  templates  
    index.html (3.2 KB)  
    style.css (1.7 KB)  
README.md (1.2 KB)  

---

🚀 Start organizing your files efficiently with TreeXplorer! 🌳  
