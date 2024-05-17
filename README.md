Personal Finance Manager Using Blockchain

Overview

This project is a personal finance management application that leverages blockchain technology to ensure data integrity, security, and transparency. It helps users manage their finances by tracking income, expenses, and investments while providing a decentralized ledger to record all transactions.

Features

Secure Transactions: Utilizes blockchain to ensure all financial transactions are securely recorded and immutable.
Expense Tracking: Allows users to categorize and track their expenses.
Income Management: Facilitates tracking of various income sources.
Investment Tracking: Keeps a record of investments and their performance.
Budgeting: Provides tools to set and manage budgets.
Reporting: Generates comprehensive financial reports and analytics.
User Authentication: Secure login and authentication using blockchain identity management.
Technologies Used

Frontend: React.js, Redux
Backend: Node.js, Express.js
Blockchain: Ethereum, Solidity
Database: MongoDB
Smart Contracts: Solidity, Truffle
User Authentication: JWT, MetaMask
Testing: Mocha, Chai
Prerequisites

Node.js (v14 or higher)
npm or yarn
MongoDB
MetaMask Extension (for interacting with the blockchain)
Truffle (for smart contract development and deployment)
Installation

Clone the Repository

bash
Copy code
git clone https://github.com/your-username/personal-finance-manager-blockchain.git
cd personal-finance-manager-blockchain
Install Dependencies

bash
Copy code
npm install
cd client
npm install
cd ..
Setup Environment Variables
Create a .env file in the root directory and add the following:

makefile
Copy code
MONGODB_URI=<your-mongodb-uri>
JWT_SECRET=<your-jwt-secret>
Setup Blockchain Network

Install and configure MetaMask with a local or test Ethereum network.
Deploy the smart contracts using Truffle.
bash
Copy code
truffle compile
truffle migrate --network <network-name>
Run the Application

bash
Copy code
npm run dev
Access the Application
Open your browser and navigate to http://localhost:3000.

Usage

Register and Login

Use the registration page to create a new account.
Login using your credentials and MetaMask to authenticate.
Manage Finances

Add, edit, or delete income and expense entries.
Track investments and view performance analytics.
Set and manage your budget.
Generate Reports

Navigate to the reports section to generate and view detailed financial reports.
Smart Contracts

The smart contracts are written in Solidity and managed using Truffle.
Located in the contracts directory.
Migration scripts are in the migrations directory.
Test contracts using:
bash
Copy code
truffle test
Contributing

Fork the repository.
Create a new branch:
bash
Copy code
git checkout -b feature/your-feature-name
Make your changes and commit:
bash
Copy code
git commit -m "Add some feature"
Push to the branch:
bash
Copy code
git push origin feature/your-feature-name
Create a pull request.
License

This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgements

Ethereum
Truffle
MetaMask
React
Node.js
MongoDB
For more information, feel free to open an issue or contact the project maintainers.
