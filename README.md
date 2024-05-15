## Description of Types-of-Functions-ETH-AVAX

This document presents a straightforward ERC20 token smart contract named MyToken, implemented in Solidity. The contract facilitates token minting, burning, and transferring functionalities, inheriting from the OpenZeppelin ERC20 contract.

## Prerequisites

Solidity compiler version 0.8.25
OpenZeppelin contracts library
Utilization
To utilize this smart contract, adhere to these steps:

Deploy the MyToken contract, specifying the desired name, symbol, and initial supply.
Employ the mint function to generate tokens and distribute them.
Utilize the burn function to eliminate tokens.
Employ the standard ERC20 transfer function to move tokens between addresses.
Smart Contract Overview

MyToken: The principal contract embodying ERC20 token capabilities.
constructor: Initializes the token with a designated name, symbol, and initial supply.
onlyOwner: A modifier limiting access to specific functions to the contract owner exclusively.
mint: Functionality to generate new tokens, accessible solely by the contract owner.
burn: Functionality to eradicate tokens.
transfer: An overridden ERC20 function enabling token transfers between addresses.
## Authored by
Sean Ydnar A. Abellanosa

## Licensing
This project is governed by the MIT License - refer to the LICENSE.md file for specifics.
