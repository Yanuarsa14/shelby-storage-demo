# Shelby Storage 

A simple demo project for uploading files to the Shelby decentralized storage network using the Shelby CLI.

## Overview

This project demonstrates how to:

- initialize a Shelby wallet
- request testnet tokens
- upload files to Shelby storage
- manage blobs using the Shelby CLI

## Tech Stack

- Shelby CLI
- Aptos Testnet
- Node.js
- Bash

## Project Structure
```
shelby-storage-demo
├── assets
│   └── datacenter.jpg
├── docs
├── scripts
│   └── upload.sh
└── README.md
```
## Requirements

- Node.js >= 18
- Shelby CLI
- Aptos Testnet wallet

## Installation

Install Shelby CLI:

npm install -g @shelby/cli

Verify installation:

shelby --version

## Setup

Clone this repository:

```

git clone https://github.com/Yanuarsa14/shelby-storage-demo.git
cd shelby-storage-demo
```

## Initialize Shelby

Run:

```
shelby init
```

### Request Testnet Tokens

APT faucet:

https://aptos.dev/network/faucet

ShelbyUSD faucet:

https://docs.shelby.xyz/apis/faucet/shelbyusd

## Upload Example 

Create a small test file:

```
echo "hello shelby" > test.txt
```

Upload it:

```
shelby upload test.txt text.txt -e "1 hour"
```

## Demo

example of a succesfull upload to the Shelby storage network

![Upload Demo](docs/shelbystorage.png)

## Scripts

Upload file using script:

bash scripts/upload.sh


## Author

```
Yanuarsa14
Web3 Developer
```
