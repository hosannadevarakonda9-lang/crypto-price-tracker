Crypto Price Tracker 🔍📈
A simple React + Vite app that fetches live cryptocurrency market data (INR) and shows a searchable table of top coins.

🚀 Features

Search cryptocurrencies by name (case-insensitive)
Displays top coins (rank, logo, name, symbol, market cap, price in INR, circulating supply)
Uses CoinGecko public API for real-time market data
Built with React and Vite for fast development and HMR

🧰 Tech Stack

Framework: React 19
Bundler / Dev server: Vite
Linting: ESLint
API: CoinGecko public REST API

💻 Local Setup
Requirements:

Node.js (v16+ recommended)
npm or yarn
Install and run locally:

# install deps
npm install

# start dev server
npm run dev

# build for production
npm run build

# preview production build
npm run preview

# run linter
npm run lint


📁 Project Structure (key files)

index.html — App entry
main.jsx — React entry point
App.jsx — Main UI and data fetching (search + table)
App.css — Styles
package.json — Scripts & dependencies
