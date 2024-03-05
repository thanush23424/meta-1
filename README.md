# ERC20 Token and Vault Contracts

This repository contains Solidity smart contracts for ERC20 token and a Vault.

## Overview

The ERC20 token contract implements the standard ERC20 interface for Ethereum tokens. It allows for the creation, transfer, and management of fungible tokens.

The Vault contract provides a secure storage solution for tokens. Users can deposit tokens into the Vault, withdraw them, and check their balance within the Vault.

## Features

### ERC20 Token Contract
- Implements the ERC20 standard interface.
- Allows for token transfers between addresses.
- Supports approval and allowance mechanisms for delegated token transfers.
- Provides functions to query token balances.

### Vault Contract
- Securely stores tokens deposited by users.
- Users can deposit tokens into the Vault.
- Allows users to withdraw tokens from the Vault.
- Provides functions to check token balances within the Vault.

## Development

- The contracts are written in Solidity version ^0.8.0.
- Unit tests are provided in the `test/` directory to ensure the contracts function as expected.
- Continuous integration can be set up to automatically test and deploy the contracts.

## Contributing

Contributions to this project are welcome. Feel free to open issues for bug fixes or feature requests, and submit pull requests with improvements.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
