# Pharos Testnet BOT
Pharos Testnet BOT
- Telegram : https://t.me/Frankkk_Z
- Register Here : [Pharos Testnet](https://testnet.pharosnetwork.xyz/experience?inviteCode=jZAwdLy87h4BjDi9)
- Connect New Wallet
- Connect X & Discord Account

## Features

  - Auto Get Account Information
  - Auto Run With [Proxyscrape Free Proxy](https://proxyscrape.com/free-proxy-list) - `Choose 1`
  - Auto Run With Private Proxy - `Choose 2`
  - Auto Run Without Proxy - `Choose 3`
  - Auto Rotate Invalid Proxies - `y` or `n`
  - Auto Claim Daily Check-In
  - Auto Claim Faucet PHRS - USDC - USDT
  - Auto Make Transfer to Random Address
  - Auto Wrapped - Unwrapped PHRS/WPHRS
  - Auto Add LP WPHRS/USDC - WPHRS/USDT
  - Auto Swap WPHRS - USDC - USDT
  - Multi Accounts

## Requirements

- Make sure you have Python3.9 or higher installed and pip.

## Environment Setup

1. **Windows:**
   ```bash
   # Install Python
   - Download Python from: https://www.python.org/downloads/
   - Choose Python version 3.9 or higher
   - During installation, check "Add Python to PATH"
   
   # Verify Python and Pip installation
   python --version
   pip --version
   ```

2. **Linux/Ubuntu:**
   ```bash
   # Update package list
   sudo apt update
   
   # Install Python
   sudo apt install python3
   sudo apt install python3-pip
   
   # Verify versions
   python3 --version
   pip3 --version
   ```

3. **MacOS:**
   ```bash
   # Install Homebrew if not installed
   /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
   
   # Install Python
   brew install python
   
   # Verify versions
   python3 --version
   pip3 --version
   ```

4. **Set Up Virtual Environment (Recommended):**
   ```bash
   # Install virtualenv if not installed
   pip install virtualenv

   # Create virtual environment
   python -m venv pharos-env
   # Or for Linux/MacOS
   python3 -m venv pharos-env

   # Activate virtual environment
   # For Windows:
   pharos-env\Scripts\activate
   # For Linux/MacOS:
   source pharos-env/bin/activate

   # Your terminal should now show (pharos-env)
   # To deactivate when done:
   deactivate
   ```

## Installation

1. **Clone The Repositories:**
   ```bash
   git clone https://github.com/vonssy/PharosTestnet-BOT.git
   ```
   ```bash
   cd PharosTestnet-BOT
   ```

2. **Install Requirements:**
   ```bash
   pip install -r requirements.txt #or pip3 install -r requirements.txt
   ```

### Note: Check your web3, eth-account, eth-utils, and eth-abi library version first. If not same with version in requirements.txt, u must uninstall that library.
- **Check Library Version**
  ```bash
    pip show libary_name
  ```
- **Uninstall Library**
  ```bash
    pip uninstall libary_name
  ```
- **Install Library With Version**
  ```bash
    pip install libary_name==version
  ```

## Configuration

- **accounts.txt:** You will find the file `accounts.txt` inside the project directory. Make sure `accounts.txt` contains data that matches the format expected by the script. Here are examples of file formats:
  ```bash
    your_private_key_1
    your_private_key_2
  ```

- **proxy.txt:** You will find the file `proxy.txt` inside the project directory. Make sure `proxy.txt` contains data that matches the format expected by the script. Here are examples of file formats:
  ```bash
    ip:port # Default Protcol HTTP.
    protocol://ip:port
    protocol://user:pass@ip:port
  ```

## Run

```bash
python bot.py #or python3 bot.py
```

## Buy Me a Coffee

- **EVM:** 0x9cd22703a97a5f99bc308bcdc1aa4f3bc21e0c2c

# Auto_Bot-_Pharos
