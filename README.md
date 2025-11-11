<h1 align="center">🪙 Coin Flip 🪙</h1>
<p align="center">
  <b>A simple Node.js API that simulates a coin flip — returning Heads or Tails from the server side.</b><br>
  <i>No frameworks. Pure Node.js. Deployed on Render.</i>
</p>

<p align="center">⭐️ If you enjoy this project, consider giving it a star! ⭐️</p>

<p align="center">
  <a href="https://github.com/AngelBelRoth/server-coins/stargazers">
    <img src="https://img.shields.io/github/stars/AngelBelRoth/server-coins?style=flat-square&color=ff69b4" alt="Stars" />
  </a>
  <a href="https://github.com/AngelBelRoth/server-coins/issues">
    <img src="https://img.shields.io/github/issues/AngelBelRoth/server-coins?style=flat-square&color=blueviolet" alt="Issues" />
  </a>
  <a href="https://server-coins.onrender.com">
    <img src="https://img.shields.io/badge/Live-Demo-success?style=flat-square&logo=render&logoColor=white" alt="Live Demo" />
  </a>
</p>

---

## Overview

**Server Coins** is a minimalist **Node.js API** that flips a virtual coin and returns the result — `heads` or `tails`.  
It’s built using only the **native HTTP module**, demonstrating how lightweight APIs can be built without any frameworks.

 *A great example for learning randomness, APIs, and simple backend logic.*

---

## ⚙️ Features

- 🔹 **Framework-free** — pure Node.js HTTP server  
- 🔹 **Randomized output** — simulates a fair coin toss  
- 🔹 **Fast & lightweight** — minimal code, instant response  
- 🔹 **Deployed on Render** — publicly accessible endpoint  

---

<img width="1600" height="765" alt="Screenshot 2025-11-10 at 20 02 50" src="https://github.com/user-attachments/assets/a3cca403-f885-4a4c-916a-ebd69722d0c2" />
<img width="1600" height="765" alt="Screenshot 2025-11-10 at 20 02 25" src="https://github.com/user-attachments/assets/38d4ed3f-060d-42a0-bff6-d75861c8a6a4" />

---

## 📦 Installation

To run this project locally:

```bash
# Clone the repository
git clone https://github.com/AngelBelRoth/server-coins.git

# Enter the folder
cd server-coins

# Install dependencies (if any)
npm install

node server.js

http://localhost:8001

GET /flip

{
  "result": "heads"
}
{
  "result": "tails"
}

server-coins/
├── server.js        # Main Node.js server file
├── package.json     # Metadata and dependencies
└── README.md        # Project documentation



