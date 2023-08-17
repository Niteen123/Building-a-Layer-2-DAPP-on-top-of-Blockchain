# Layer-2 DAPP on Blockchain - CS765 Spring 2023 Semester

This repository contains the implementation and documentation for the Layer-2 DAPP project as part of the CS765 Spring 2023 Semester.

## Table of Contents

- [Description](#description)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Contributors](#contributors)
- [License](#license)

## Description

This project implements a decentralized application (DAPP) on a layer-2 blockchain network. The DAPP facilitates transactions between users through joint accounts, forming a network of connected users. Users can register, create joint accounts, send amounts, and close accounts using smart contracts written in Solidity.

## Getting Started

### Prerequisites

- Ethereum node (e.g., Truffle/Ganache) set up locally. Refer to [Setup Instructions](https://docs.google.com/document/d/1IfIwdF6vhf4KYP1OYTwFmgqtdHO6nT7m0JaMH1xCIYo/edit?usp=sharing) for guidance.

### Installation

1. Clone this repository:

```bash
git clone https://github.com/your-username/CS765-DAPP-Project.git
cd CS765-DAPP-Project

### Usage
Register Users: Use the registerUser function to register users. Provide user IDs and names as arguments.

Create Joint Accounts: Utilize the createAcc function to create joint accounts between users. Specify user IDs and initial balances.

Send Amount: Execute the sendAmount function to transfer amounts between users, even without a joint account. Ensure sufficient balances.

Close Account: Terminate accounts between users using the closeAccount function. Provide the relevant user IDs.

Run the DAPP: Use the provided Python script (client.py) or another preferred language for interacting with the smart contract and performing transactions.
