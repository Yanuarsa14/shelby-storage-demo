# Shelby Storage Demo

This repository demonstrates how to upload files to **Shelby decentralized storage** using the Shelby CLI.

The project provides a simple example of uploading files and automating uploads with a shell script.

---

## Overview

Shelby Storage is designed for decentralized data storage in Web3 applications.  
This demo repository shows how developers can interact with Shelby storage through the CLI.

This repository includes:

- Example files for upload
- Upload automation script
- Documentation screenshot

---

## Project Structure

shelby-storage-demo
│
├── README.md
│
├── assets/
│   ├── a.txt
│   ├── datacenter.jpg
│   └── test.txt
│
├── docs/
│   └── shelbystorage.png
│
└── scripts/
    └── upload.sh

---

## Requirements

Before running this demo, make sure you have:

- Node.js >= 18
- Shelby CLI
- Aptos wallet (testnet)

---

## Installation

Install Shelby CLI globally:

npm install -g @shelby/cli

---

## Verify installation:

shelby --version

---

## Upload Example

Create a sample file:

echo "hello shelby" > test.txt

Upload the file:

shelby upload test.txt

---

## Run Upload Script

Make the script executable:

chmod +x scripts/upload.sh

Run the script:

./scripts/upload.sh

---

## Demo

Example upload result using Shelby CLI.

![Shelby Storage Demo](docs/shelbystorage.png)

---

## Author

GitHub: https://github.com/Yanuarsa14

---

# 3
