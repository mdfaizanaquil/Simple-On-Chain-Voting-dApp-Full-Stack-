# Simple On-Chain Voting dApp

A full-stack decentralized application that demonstrates a basic on-chain voting system. This project includes a Solidity smart contract and a front-end interface built with HTML, CSS, and Ethers.js.

## Features
- Deploy a voting contract with pre-defined proposals.
- Web interface to view proposals and their current vote counts.
- Allows users to connect their wallet and cast a vote.

## How to Use
1.  **Deploy the Smart Contract:**
    * Open `contracts/Voting.sol` in Remix IDE.
    * Compile and deploy it to your chosen network (e.g., Base Sepolia).
    * When deploying, you must provide the proposal names as an array of strings, for example: `["Proposal A", "Proposal B", "Proposal C"]`
    * After deployment, copy the new contract's address.
2.  **Configure the Front-End:**
    * Open `public/script.js`.
    * Paste the copied contract address into the `CONTRACT_ADDRESS` variable.
3.  **Run the dApp:**
    * Open `public/index.html` in your web browser.
