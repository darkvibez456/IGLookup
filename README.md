
<div align="center">

```
  ██╗ ██████╗ ██╗      ██████╗  ██████╗ ██╗  ██╗██╗   ██╗██████╗ 
  ██║██╔════╝ ██║     ██╔═══██╗██╔═══██╗██║ ██╔╝██║   ██║██╔══██╗
  ██║██║  ███╗██║     ██║   ██║██║   ██║█████╔╝ ██║   ██║██████╔╝
  ██║██║   ██║██║     ██║   ██║██║   ██║██╔═██╗ ██║   ██║██╔═══╝ 
  ██║╚██████╔╝███████╗╚██████╔╝╚██████╔╝██║  ██╗╚██████╔╝██║     
  ╚═╝ ╚═════╝ ╚══════╝ ╚═════╝  ╚═════╝ ╚═╝  ╚═╝ ╚═════╝ ╚═╝     
```

**Instagram Account Info Tool**

![Python](https://img.shields.io/badge/Python-3.7%2B-blue?style=for-the-badge&logo=python)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)
![Platform](https://img.shields.io/badge/Platform-Linux%20%7C%20Windows%20%7C%20Mac-lightgrey?style=for-the-badge)
![Author](https://img.shields.io/badge/Author-darkvibez456-red?style=for-the-badge)

</div>

---

## 📌 About

**IGLookup** is a command-line tool to fetch public Instagram account information using a username. It displays account details, last posts, and saves the data locally as a JSON file.

---

## ✨ Features

- 📊 Fetch Instagram account info (ID, name, bio, followers, etc.)
- 📸 Display last 5 posts with likes, comments & URLs
- 💾 Auto-save results to `output/` folder as JSON
- 🎨 Colorful terminal UI with loading animation
- ⚡ Fast & lightweight — only needs `requests`

---

## 📦 Installation

```bash
# 1. Clone the repo
git clone https://github.com/darkvibez456/IGLookup.git
cd IGLookup

# 2. Install dependencies
pip install -r requirements.txt

# 3. Run
python3 iginfo.py
```

---

## 🖥️ Usage

```bash
python3 iginfo.py
```

```
  ┌─[IGLookup]
  └─▶ Enter Username: cristiano
```

Output will be saved in `output/cristiano_20260527_151600.json`

---

## 📁 File Structure

```
IGLookup/
├── iginfo.py          # Main script
├── requirements.txt   # Dependencies
├── README.md          # Documentation
├── LICENSE            # MIT License
├── CHANGELOG.md       # Version history
├── .gitignore         # Git ignore rules
└── output/            # Saved JSON results (auto-created)
```

---

## ⚠️ Disclaimer

> This tool is intended for **educational purposes only**.  
> Only use it on **public accounts** or accounts you have permission to look up.  
> The author is **not responsible** for any misuse.

---

## 👤 Author

**darkvibez456**  
🔗 [github.com/darkvibez456](https://github.com/darkvibez456)

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
