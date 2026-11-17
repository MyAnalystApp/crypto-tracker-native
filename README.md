<div align="center">

# Crypto Tracker

Live prices, charts and plain-language guides for the top cryptocurrencies.

![React Native](https://img.shields.io/badge/React_Native_0.64-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![React Navigation](https://img.shields.io/badge/React_Navigation-6B52AE?style=flat-square&logo=react&logoColor=white) ![Victory Native](https://img.shields.io/badge/Victory_Native-C43A31?style=flat-square) ![CoinGecko API](https://img.shields.io/badge/CoinGecko_API-8DC63F?style=flat-square) ![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white)

</div>

<table>
  <tr><th>Home</th><th>Top 100</th><th>Coin details</th></tr>
  <tr><td><img src="Images/Home.jpeg" alt="Home" width="250" /></td><td><img src="Images/AllCrypto.jpeg" alt="Top 100 cryptocurrencies" width="250" /></td><td><img src="Images/AboutCrypto.jpeg" alt="Coin details and price chart" width="250" /></td></tr>
</table>

## About

Crypto Tracker is an Android app for following the cryptocurrency market. It lists the top 100 coins by market cap with live prices in Indian rupees, shows interactive price charts for each coin, and explains how Bitcoin and blockchain work for people who are new to crypto. All market data comes from the free [CoinGecko API](https://www.coingecko.com/en/api), so it needs no API key.

## Screenshots

| Welcome | About Bitcoin |
| :---: | :---: |
| <img src="Images/Welcome.jpeg" alt="Welcome screen" width="250" /> | <img src="Images/AboutBitcoin.jpeg" alt="About Bitcoin" width="250" /> |

## Features

- **Home**: trending coins, shortcuts to the top 100 list and exchange rates, and learning resources
- **Top 100**: the top cryptocurrencies by market cap with price and 24-hour change, plus search
- **Coin details**: current price, daily high and low, market cap, volume and an interactive chart for 1 day, 1 week, 1 month or 1 year
- **About Bitcoin**: an illustrated guide to Bitcoin, blockchain, mining and wallets
- **Personal touch**: greets you by the name you enter on the welcome screen

## Tech Stack

| Area | Technology |
| --- | --- |
| App | React Native 0.64, React 17 |
| Navigation | React Navigation (stack) |
| Charts | Victory Native, react-native-svg |
| Data | CoinGecko API (prices in INR) |

## Getting Started

**Prerequisites:** a [React Native development environment](https://reactnative.dev/docs/environment-setup) for Android (Node.js, JDK and Android Studio)

```bash
cd CryptoTracker
npm install
npx react-native run-android
```

For a signed release build, add your own `MYAPP_UPLOAD_*` keystore settings to `~/.gradle/gradle.properties`. They are not stored in this repository.

## Project Structure

```
.
├── CryptoTracker/
│   ├── App.js           # navigation stack
│   ├── screens/         # Welcome, Home, Top100, CryptoInfo, AboutBitcoin, About, Portfolio
│   ├── assets/          # images and fonts
│   └── android/         # native Android project
└── Images/              # README screenshots and graphics
```
