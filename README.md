<br />

## 🔗 [Live Demo](https://ravikantmahi.github.io/Be-My-Valentine-2/)

<p align="center">
  <img src="https://raw.githubusercontent.com/ravikantmahi/Be-My-Valentine/refs/heads/main/resources/cat-heart.gif" alt="Valentine Gif" width="150">
</p>
<h1 align="center"> Be-My-Valentine-2</h1>
<h2 align="center">💘 Interactive Valentine's Proposal</h2>
<p align="center">
  <b>A playful, high-energy web experience that captures your Valentine's heart (and their response)!</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/Google--Sheets-34A853?style=for-the-badge&logo=googlesheets&logoColor=white" />
</p>

<p align="center">
  <a href="#-features">Features</a> •
  <a href="#-how-it-works">How it Works</a> •
  <a href="#-author">Author</a>
</p>

---

### 📖 About The Project

This isn't just another Valentine's page. **Be-My-Valentine-2** is an interactive challenge. It features a "No" button that refuses to be clicked by jumping anywhere on the user's screen, making it virtually impossible to say no! 

**The Special Part:** This version is integrated with **Google Apps Script**. When a user finally says "Yes" and enters their name, the response is instantly saved to a private Google Sheet, allowing you to track your Valentine's answer in real-time.

---

### ✨ Features

- **🏃‍♂️ Total Screen Dodge:** The "No" button uses `fixed` positioning to jump anywhere in the browser window, avoiding the cursor at all costs.
- **📊 Real-time Data Logging:** Integrated with **Google Sheets API** (via Apps Script) to log:
  - Visitor arrivals (automatic).
  - "Yes" click confirmations with the user's name and timestamp.
- **🎉 Celebration Mode:** High-intensity confetti burst using `canvas-confetti` when the proposal is accepted.
- **📜 Romantic Poetry:** Features a beautiful Hindi Shayari prompt when the user clicks "Yes".
- **📱 Mobile Optimized:** Special `touchstart` logic ensures the "No" button escapes even on touchscreens.
- **📈 Local Visitor Counter:** Tracks individual visits using `LocalStorage`.

---

### ⚙️ How It Works

1. **The Entry:** Every time the page loads, a `fetch` request is sent to a Google Apps Script to log a "New Visitor".
2. **The Chase:** The "No" button calculates the `window` boundaries to ensure it stays visible but remains unclickable.
3. **The "Yes":** Upon clicking "Yes", a prompt appears. The name entered is sent to the Google Sheet backend before the final alert and confetti celebration.

---

### 👨‍💻 Author

**Ravi Kant** *Software Developer | Big Data & Data Science | FullStack Developer*

<p align="left">
<a href="https://ravikantportfolio.vercel.app" target="_blank">
<img src="https://img.shields.io/badge/Portfolio-Visit-blue?style=for-the-badge&logo=vercel&logoColor=white" />
</a>
<a href="https://www.linkedin.com/in/ravikantmahi/">
<img src="https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>
<a href="https://github.com/Ravikantmahi">
<img src="https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white" />
</a>
</p>

---

<p align="center">
Made with 💕 and a little bit of mischief by Ravi Kant
</p>
