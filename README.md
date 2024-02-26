<div align="center">
  <h1>🔒 MultiSignature Wallet Contract</h1>
  <img src="https://img.shields.io/badge/License-MIT-green.svg" alt="License: MIT">
  <br>
  <p>This repository contains a Solidity smart contract for a MultiSignature Wallet. The contract enables multiple owners to collectively manage funds, requiring a predefined number of confirmations from the owners before executing transactions.</p>
</div>

## 🚀 Features
- **Multi-Owner Support**: The wallet accommodates multiple owners, each with the authority to submit and confirm transactions.
- **Confirmation Requirement**: Transactions necessitate a specified number of confirmations before execution.
- **Transaction Execution**: Once a transaction receives the requisite confirmations, any owner can execute it, transferring the specified amount to the intended recipient.
- **Event Logging**: Events are emitted during transaction submission, confirmation, and execution for transparency and auditing.

## 💼 Usage
### Deployment
1. Deploy the contract by providing an array of owner addresses and the required number of confirmations.
2. Ensure that the confirmation count is within the total number of owners.

### Interacting with the Contract
- **submitTransaction**: Owners can submit a transaction by specifying the recipient's address and the amount to transfer.
- **confirmTransaction**: Owners can confirm pending transactions initiated by others.
- **executeTransaction**: Once a transaction garners the necessary confirmations, any owner can execute it to transfer the funds.

## 🧪 Testing
- Employ Solidity testing frameworks such as Truffle or Hardhat for comprehensive testing.
- Test cases should encompass scenarios such as transaction submission, confirmation, execution, invalid inputs, and edge cases.

## 🙌 Author
[Ayush Chauhan](https://github.com/AyushChauhan3757)

## 🌟 Acknowledgments
- Tutorial Used: https://youtu.be/uoQhMFAZ6V0?si=vMAypgFDKWxpGzal
