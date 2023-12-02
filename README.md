# University-Application-dApp

This repository contains the source code for a smart contract-based decentralized application (DApp). This project is a document verification and application management system designed for educational institutions to streamline the student application process. It allows students to submit their application documents securely, while verifiers can review and verify these documents.

## Table of Contents
- [Overview](#overview)
- [Smart Contracts](#smart-contracts)
- [Getting Started](#getting-started)
- [Usage](#usage)

## Overview
DocuNet aims to simplify the student application process by providing a secure and transparent platform for students and verifiers. Here are the main components and features of the application:

- **Students**: Students can create accounts, submit application documents, and check the status of their applications.
- **Verifiers**: Verifiers are responsible for reviewing and approving documents. They can create accounts and approve or disapprove student applications.
- **University Authority**: The university authority has the power to approve verifiers, disapprove verifiers, and make final decisions on student applications.
- **Document Verification**: Verifiers can upload verified documents, which students can access.

## Smart Contracts
The core functionality of DocuNet is implemented through Ethereum smart contracts. The primary smart contracts in this repository are:

- `DocuNet.sol`: This contract manages student and verifier accounts, document submission, application status, and more.
- `DocuLibrary.sol`: This library defines data structures used by the `DocuNet` contract, including student profiles, verifier profiles, and document details.

## Getting Started
To run DocuNet locally, you need to have an Ethereum development environment set up. You can use tools like [Truffle](https://www.trufflesuite.com/) and [Ganache](https://www.trufflesuite.com/ganache) for this purpose.

1. Clone this repository to your local machine:

   ```
   git clone https://github.com/AviMehta90/University-Application-dApp.git
   cd University-Application-dApp
   ```

2. Install the required dependencies:

   ```
   npm install
   ```

3. Compile and deploy the smart contracts to your local Ethereum network:

   ```
   truffle compile
   truffle migrate
   ```

4. Start the DApp:

   ```
   npm start
   ```

## Usage
- Access the DocuNet DApp by opening it in your web browser. You can interact with the application, create student and verifier accounts, submit documents, and manage student applications.
- Verifiers can approve or disapprove documents, while the university authority can make final decisions on student applications.

## Contributing
We welcome contributions to this project. If you'd like to improve the application, fix bugs, or add new features, please follow these steps:

1. Fork this repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and test them thoroughly.
4. Create a pull request describing your changes and the problem they solve.
