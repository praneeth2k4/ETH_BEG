
# MyToken Solidity Contract for Minting and Burning

This Solidity contract represents a simple token contract with minting and burning functions.

## Table of Contents

- [Description](#description)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
  - [Minting Tokens](#minting-tokens)
  - [Burning Tokens](#burning-tokens)
- [Authors](#authors)
- [License](#license)

## Description

This Solidity contract, `MyToken.sol`, implements a basic token with the following features:

- Token Name: "SOLANA"
- Token Abbreviation (Symbol): "SOL"
- Initial Total Supply: 0
- A mapping to track token balances for each address.
- A `mintTokens` function for creating new tokens and updating the total supply and balances.
- A `burnTokens` function for destroying tokens, which decreases the total supply and the balance of a specified address, subject to balance checks.

## Getting Started

### Prerequisites

- Solidity 0.8.18 or compatible versionl
- Remix IDE for Online Compilation

### Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/satya112003/ETH_BEG.git
   ```

2. Navigate to the project directory:

   ```bash
   cd ETH_BEG
   ```

3. Compile the `MyToken.sol` contract using a Solidity compiler of your choice.
4. Or compile and Deploy in Remix IDE

## Usage

### Minting Tokens

To create new tokens, use the `mintTokens` function. Provide the recipient's address and the amount of tokens to mint.

### Burning Tokens

To burn (destroy) tokens, use the `burnTokens` function. Provide the address from which to burn tokens and the amount to burn.

## Authors

- Satya 
  - GitHub: satya112003

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

