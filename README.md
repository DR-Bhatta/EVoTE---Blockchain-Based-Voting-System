# EVoTE: Blockchain-Based Voting System

![License](https://img.shields.io/badge/license-Proprietary-red)
![Python](https://img.shields.io/badge/Python-Backend-blue)
![FastAPI](https://img.shields.io/badge/FastAPI-Web%20Framework-009688)
![React](https://img.shields.io/badge/React-Frontend-61DAFB)
![PostgreSQL](https://img.shields.io/badge/Database-PostgreSQL-4169E1)
![Solidity](https://img.shields.io/badge/Solidity-Smart%20Contracts-363636)
![Ethereum](https://img.shields.io/badge/Ethereum-Sepolia-627EEA)

EVoTE is a blockchain-based voting system developed as a Final-Year Computer Engineering group project by four team members:

* Dilli Raj Bhatta
* Dinesh Singh Dhami
* Dipak Shyada
* Samir Bist

The system was developed using React, FastAPI, PostgreSQL, Solidity, and Ethereum to support election management, candidate applications, wallet authentication, voting, and election results. Voting transactions are recorded on the Ethereum Sepolia testnet.

> Note: This project is proprietary. Copying, modification, redistribution, publishing, hosting, or reuse requires prior written permission from the project authors. See [LICENSE.md](LICENSE.md).

## Features

* MetaMask wallet registration and login
* Wallet signature verification with JWT authentication
* Voter, Admin, and SuperAdmin roles
* Institution, organization, and election management
* Candidate registration and admin approval
* Candidate age and registration restrictions
* Scheduled registration and voting periods
* Multiple election seats and vote limits
* Duplicate-vote prevention
* Gasless voting using a backend relayer
* Authorized session keys
* Election result charts
* Blockchain transaction history and Etherscan links
* Admin and voter dashboards

## Tech Stack

* Frontend: React, Vite, Material UI, Recharts
* Backend: Python, FastAPI
* Database: PostgreSQL, SQLAlchemy
* Smart Contracts: Solidity, OpenZeppelin
* Blockchain Development: Hardhat
* Network: Ethereum Sepolia
* Wallet: MetaMask
* Integration: ethers.js, Web3.py

## Project Structure

| Path          | Purpose                                            |
| ------------- | -------------------------------------------------- |
| `frontend/`   | React UI, dashboards, and wallet integration       |
| `backend/`    | APIs, authentication, database, relayer, and tests |
| `blockchain/` | Smart contracts, deployment scripts, and tests     |
| `LICENSE.md`  | Licensing terms                                    |

## Voting Workflow

1. Register and log in using MetaMask.
2. Select an institution, organization, and election.
3. Review available candidates.
4. Cast votes within the allowed seat limit.
5. The backend relays the signed transaction to the smart contract.
6. View results after the voting period closes.

## Academic Context

EVoTE was developed and submitted as a Final-Year Computer Engineering group project at the National Academy of Science and Technology (NAST), affiliated with Pokhara University.

The official project team consisted of:

* Dilli Raj Bhatta
* Dinesh Singh Dhami
* Dipak Shyada
* Samir Bist

The project was developed collaboratively by the four team members as part of their academic project work.

## Team Contributions

EVoTE was developed as a collaborative four-member project. The team contributed to different aspects of the project, including planning, system analysis, design, implementation, testing, documentation, presentation, and final submission.

The project involved work across:

* Project planning and requirement analysis
* System architecture and database design
* Frontend and user-interface development
* Backend API development
* Authentication and wallet integration
* MetaMask integration
* Solidity smart-contract development
* Ethereum Sepolia integration
* Backend relayer and gasless transactions
* Election and voting logic
* Candidate registration and approval
* Testing and debugging
* System integration
* Documentation and diagrams
* Final report and presentation preparation

Individual contributions may have varied across different stages of development, but the project was officially developed and submitted as a four-member group project.

The team also used AI tools as development assistants for activities such as brainstorming, debugging support, code explanations, and documentation refinement. The team reviewed, modified, tested, and integrated the resulting work as part of the development process.

## What We Learned

Building EVoTE provided the team with practical experience in combining full-stack development with blockchain technology.

Through this project, the team gained experience in:

* Full-stack application development
* REST APIs with FastAPI
* PostgreSQL database management
* React application development
* Secure authentication and wallet signatures
* MetaMask integration
* Solidity smart-contract development
* Ethereum integration
* Backend-relayed and gasless transactions
* Election rules and validation
* Backend and smart-contract testing

One of the main aspects of the project was integrating the React frontend, FastAPI backend, PostgreSQL database, MetaMask wallet, and Ethereum smart contracts into one working system.

## License

This project is proprietary, with all rights reserved by the project authors, subject to the rights and licenses applicable to third-party components.

Reuse, modification, redistribution, publishing, or hosting of the project or its original materials requires prior written permission from the project authors, except where separate third-party licenses expressly permit such use.

See [LICENSE.md](LICENSE.md) for the complete licensing terms.

The EVoTE project is publicly visible for demonstration, evaluation, and portfolio purposes, not for unrestricted reuse.

Do not assume that publicly accessible source code is free to copy, modify, republish, or redistribute.

Third-party libraries, packages, assets, and dependencies retain their respective licenses.

## Contributions

Public contributions are not currently accepted.

For collaboration, educational use, research discussion, or licensing inquiries, please contact the project authors through the appropriate contact channels.

## Project Authors

Dilli Raj Bhatta

Dinesh Singh Dhami

Dipak Shyada

Samir Bist

EVoTE: Blockchain-Based Voting System

Copyright © 2026 Dilli Raj Bhatta, Dinesh Singh Dhami, Dipak Shayada, and Samir Bist.

All Rights Reserved.
