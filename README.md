# 🗳️ Voting System Platform

A secure and interactive **web-based voting system** built with **HTML, CSS, and JavaScript**.  
This project simulates a full election workflow — including login, candidate browsing, vote selection, review, and final submission — with a clean RTL interface optimized for Persian text.

![HTML](https://img.shields.io/badge/HTML-5-orange.svg)
![CSS](https://img.shields.io/badge/CSS-3-blue.svg)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)

---

## 🚀 Features

### Authentication
- 🔐 Login with **National ID** and **Certificate Number**
- Validation with helper messages

### Voting Process
- 📋 Browse candidates with **alphabetical filtering**
- 🔎 **Search** candidates by code
- ✅ Select up to **30 candidates**
- 🔄 **Pagination** for large candidate datasets

### Review & Submission
- 📝 Review selected candidates before submission
- ❌ Remove candidates if needed
- 📊 Submit **final vote** with confirmation page

### Interface
- RTL (Right-to-Left) design for Persian text
- Responsive, clean, and modern UI

---

## 🖥️ Platform Screenshots

### 🔑 Login Page
<p align="center">
  <img src="readme_images/login.png" alt="Login Page" width="700">
</p>

### 🗳️ Voting Environment
<p align="center">
  <img src="readme_images/voting.png" alt="Voting Page" width="900">
</p>

### 🔎 Review Page & Final Submission
<p align="center">
  <img src="readme_images/review.png" alt="Review Page" width="900">
</p>

### ✅ Final Submission Page
<p align="center">
  <img src="finalpage.PNG" alt="Final Page" width="700">
</p>

---

## 🎥 Demo

A full workflow demo (Login → Candidate Selection → Review → Final Submission):

<p align="center">
  <img src="readme_images/demo.gif" alt="Voting Demo" width="900">
</p>

---

## 📋 Requirements

This project is **frontend only** — no backend required.  
It runs directly in the browser with no installation needed.

**Files used in the project:**
- `index.html` – main application
- `candidates_names.csv` – list of candidates
- `background.jpg` – login background
- `logo.jpg` – login logo
- `logo2.jpeg` – voting background
- `finalpage.PNG` – final confirmation page

---

## 🚀 Installation

1. **Clone the repository**
```bash
git clone https://github.com/yourusername/voting-system.git
cd voting-system
```

2. **Open the application**
   - Simply open `index.html` in your browser.  
   - No additional setup required.

3. **Candidate Data**
   - The system loads candidates from `candidates_names.csv`.
   - If not found, it will load a **sample candidate list** automatically.

---

## 📂 Repository Structure

```
voting-system/
├── index.html            # Main application
├── candidates_names.csv  # Candidate dataset
├── background.jpg        # Login background
├── logo.jpg              # Logo
├── logo2.jpeg            # Voting background
├── finalpage.PNG         # Final confirmation page
├── readme_images/        # Screenshots + demo GIF
├── README.md             # Project documentation
└── LICENSE               # MIT license file
```

---

## 🔒 Security Notes

- This is a **demo/simulation project**, not intended for real elections.  
- All data is handled **client-side** (no backend or encryption).  
- For production use, integration with a **secure backend, database, and encryption** would be required.

---

## 🤝 Contributing

Contributions are welcome!  
- Open a **Pull Request** for small changes  
- Open an **Issue** for new features or major improvements  

---

## 📜 License

This project is licensed under the **[MIT License](LICENSE)**.

---

⭐ If you find this project useful, please consider starring it on GitHub!
