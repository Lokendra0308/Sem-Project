🚀 Blockchain-Based Drug Inventory and Supply Chain Management
A decentralized system to track, manage, and authenticate drugs across the pharmaceutical supply chain using Blockchain technology and Smart Contracts.

📋 Table of Contents
About the Project
Tech Stack
Features
System Architecture
Getting Started
Smart Contracts
Testing
Challenges Faced
Future Enhancements
Contributing
License
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
📖 About the Project
The pharmaceutical supply chain faces issues like counterfeit drugs, inventory mismanagement, and lack of transparency.
This project builds a secure, transparent, and traceable drug inventory system using blockchain technology, ensuring authenticity and efficiency from manufacturer to end consumer.
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
🛠️ Tech Stack
Blockchain Framework: Ethereum / Hyperledger Fabric

Smart Contracts: Solidity

Backend: Node.js / Express.js

Frontend: React.js / Next.js

Database (Off-Chain): IPFS / MongoDB (optional)

Tools: MetaMask, Hardhat/Truffle, Ganache (for local testing)
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
✨ Features
📦 Drug Registration by Manufacturer

🔗 Real-Time Inventory Tracking

🏬 Distributor & Pharmacy Management

🔍 Complete Traceability of each drug batch

🛡️ Tamper-Proof Records with blockchain immutability

🧾 Smart Contract Automation for secure transactions

🧠 Role-Based Access Control (Manufacturer, Distributor, Pharmacy, Admin)
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
🏛️ System Architecture

[Manufacturer] -> [Blockchain Network] <- [Distributor] <- [Pharmacy]
                                 ↓
                          [Frontend Dashboard]
                                 ↓
                           [Off-chain Storage (IPFS)]
Every movement of a drug batch updates the blockchain.

Users interact through a decentralized .

Optional IPFS storage for detailed batch documents.

🧰 Getting Started
Prerequisites
Node.js and npm

Hardhat/Truffle

MetaMask wallet

Git

Installation
bash
Copy
Edit
git clone https://github.com/lokendra08/drug-inventory-blockchain.git
cd drug-inventory-blockchain
npm install
Running Locally
bash
Copy
Edit
npx hardhat node
npx hardhat run scripts/deploy.js --network localhost
npm start
Connect your MetaMask to localhost:8545 network!

📝 Smart Contracts
DrugInventory.sol
Handles drug batch creation, updates, and ownership transfers.

Roles.sol
Manages user roles (Manufacturer, Distributor, Pharmacy).

SupplyChain.sol
Central controller contract for supply chain flow.

🧪 Testing
Unit Tests:
Test smart contract functions using Hardhat/Chai.

Integration Tests:
Simulate full drug lifecycle from creation to delivery.

bash
Copy
Edit
npx hardhat test
🧠 Challenges Faced
Gas optimization during smart contract execution.

Managing private data on a public blockchain.

Building a user-friendly interface for blockchain interaction.

🚀 Future Enhancements
🌐 Deployment on Ethereum Mainnet or Polygon Network.

📡 IoT Integration for live environmental tracking.

📈 Predictive Analytics for inventory demand forecasting.

🧩 Full mobile app version for easy access.

