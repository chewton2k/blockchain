# Blockchain Project

A simple blockchain application built using Python and Flask. This project demonstrates the core concepts of blockchain, including creating blocks, hashing, and a basic web interface for interacting with the blockchain.

---

## Features

- Create and manage a blockchain with multiple blocks.
- Add transactions and mine new blocks.
- Flask-based web server for interacting with the blockchain.
- REST API endpoints for querying the blockchain and submitting transactions.
- Run locally or over your local network.

---

## Technologies Used

- **Python 3.14**  
- **Flask** for the web server  
- Python libraries: `hashlib`, `json`, `time`, `uuid`, `requests`, `urllib.parse`

---

## Installation

It’s recommended to use a Python virtual environment for development.

```bash
# Clone the repository
git clone https://github.com/chewton2k/blockchain
cd BlockChain

# Create a virtual environment
python3 -m venv venv
source venv/bin/activate  # macOS/Linux
# venv\Scripts\activate   # Windows

# Install dependencies
pip install flask

# To Run
python blockchain.py 
```


## Acknowledgements

This project was inspired and completed with the help of the article:

- [Learn Blockchains by Building One](https://hackernoon.com/learn-blockchains-by-building-one-117428612f46) by Daniel van Flymen