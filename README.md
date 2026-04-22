## 🎯 Overview

Stabilizer-BOT is a Python testnet bot that fully automates claiming all tokens from faucets, generating swap volume, and adding liquidity to pools.

**🔗 Get Started:** [Register on Stabilizer](https://app.stabilizer.finance)

> **Important:** Connect new evm wallet.

## ✨ Features

- 🚰 **Claim Test Token** - Automated claim daily USDT, USDC, USDS Faucet
- 🔁 **Swap Test Tokens** - Automated swap token, 2M volume dily
- 💧 **Add Liquidity** - Automated add Liquidity pools
- 👥 **Multi-Account Support** - Soon
- ⚠️ **Approve First all Pairs on browser before run**

## 📋 Requirements

- **Python:** Version 3.9 or higher
- **pip:** Latest version recommended
- **Compatible libraries:** See requirements.txt

## 🛠 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/AmanDiAngkasa/Stabilizer-Testnet-BOT.git
cd Stabilizer-Testnet-BOT
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
# or for Python 3 specifically
pip3 install -r requirements.txt
```

## ⚙️ Configuration

### Account Setup

Create or edit `accounts.txt` in the project directory:

```
PRIVATE_KEY=0x....
```

## 🚀 Usage

Run the bot using one of the following commands:

```bash
python main.py
# or for Python 3 specifically
python3 main.py
```
