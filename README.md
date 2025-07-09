# 🌐 UAXNETWORK Node Monitoring UI

The **UAXNETWORK Node Monitoring UI** is a lightweight and responsive web-based dashboard designed to monitor and visualize the health, performance, and status of your UAXNODE in real time.

Whether you're a validator, node operator, or developer, this dashboard helps you stay updated on peer status, sync progress, and system metrics — all from a clean, modern interface.

---

## 🚀 Features

- 🔗 Real-time display of peer connections and statuses  
- 📦 Block sync progress and latest block height  
- 🧩 Validator status, uptime, and node identity (enode)  
- 📡 Bandwidth usage and network activity  
- 🌐 Runs on `http://localhost:3000` by default

---

## 🧰 Tech Stack

- **React.js** (frontend framework)
- **Node.js v18+** (runtime)
- **serve** (for static production deployment)

---

## 📦 Requirements

- [Node.js](https://nodejs.org/) v18 or higher  
- npm (comes with Node.js)  
- `serve` package to host the production build  
- Access to the UAXNODE endpoint for real-time data

---

## ⚙️ Installation & Setup

Clone the repo and install dependencies:

git clone https://github.com/UAXNETWORK/uaxnode-dashboard.git
cd uaxnode-dashboard
npm install
serve -s build

---
This will run on:
http://localhost:3000
---
