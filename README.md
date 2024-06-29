# ETH-AVAX-Module-3
## Creating ERC20 Token
In this project of module 3 of course ETH + AVAX PROOF: Intermediate EVM Course, we are creating our own ERC20 token. The contract owner should be able to mint tokens to a provided address and any user should be able to burn and transfer tokens. This project is deployed on Remix IDE.

## Overview

This repository contains a simple implementation of a token smart contract in Solidity. The `Function` contract allows for minting tokens, burning tokens, and transferring tokens between addresses.

## Features

- **Minting Tokens**: The contract owner can mint new tokens to any specified address.
- **Burning Tokens**: Users can burn (destroy) their own tokens, reducing the total supply.
- **Transferring Tokens**: Tokens can be transferred between addresses.

## Deployment

To deploy the contract, you can use Remix or any other Solidity development environment. Make sure to specify the `name` and `symbol` parameters during deployment.


### Steps

1. **Compile**: Compile the `module3.sol` file using your preferred Solidity compiler.
   
2. **Deploy**: Deploy the compiled contract to an Ethereum blockchain. Specify the `name` and `symbol` parameters during deployment.

3. **Interact**: After deployment, interact with the contract to mint tokens, burn tokens, and transfer tokens between addresses.
## Help
1. Insure that the correct version of complier is written in your contract or set from "compile" button from left side tool bar.
   ```
   pragma solidity ^0.8.20;
   ```
2. Insure to import the files for ERC20 token:
   ```
   import "@openzeppelin/contracts/token/ERC20/ERC20.sol";
   import "@openzeppelin/contracts/access/Ownable.sol";
   import "@openzeppelin/contracts/token/ERC20/extensions/ERC20Burnable.sol";
   ```
3. Ensure that you have passed MIT License in your contract otherwise the complier will show error.
   ```
   // SPDX-License-Identifier: MIT
   ```
# Author
Priyansh [@priyansh06rawat](https://github.com/priyansh06rawat)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
