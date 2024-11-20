# MyToken - A Simple ERC-20 Token Contract

**MyToken** is a basic Solidity smart contract that implements a simple token with minting and burning functionalities. It allows users to create new tokens, increase the total supply, and burn tokens from their balance in a secure and transparent manner.

## Features
- **Minting**: Increase the total supply and assign tokens to a specified address.
- **Burning**: Reduce the total supply and deduct tokens from a specified address.
- **Basic Token Information**: Public variables to store the token's name, abbreviation, and total supply.

## Requirements
- Solidity version: 0.8.18
- Ethereum or compatible blockchain (e.g., Binance Smart Chain, Polygon)

## Contract Functions
- `mint(address account, uint value)`: Mints new tokens and assigns them to a specified account.
- `burn(address account, uint value)`: Burns a specified amount of tokens from an account, reducing the total supply.

## How to Use
1. Deploy the contract on an Ethereum-compatible network using a tool like Remix or Hardhat.
2. Interact with the `mint` and `burn` functions:
   - Use the `mint` function to increase the token supply by specifying an address and the number of tokens to mint.
   - Use the `burn` function to decrease the token supply by specifying an address and the number of tokens to burn (tokens will be deducted from the specified account’s balance).

## Example Use Case
- **Minting**: You can mint new tokens to an address when they join your platform or perform specific actions.
- **Burning**: Tokens can be burned as part of a deflationary mechanism, rewards system, or token buyback.



