# MetaCrafterToken

MyToken is an Ethereum ERC20 token contract that allows the contract owner to mint tokens to a provided address, and users to burn and transfer tokens.

## Features

- Mint tokens to a specified address by the contract owner.
- Burn tokens by any user.
- Transfer tokens between addresses.

## Prerequisites

- Remix-IDE

## Contract Details

- Name: MetaCrafterToken
- Symbol: MCT
- Decimals: 18

### Functions

#### `mint(address account, uint256 amount)`

Mints new tokens and assigns them to the specified account.

- `account`: The address to which the tokens will be minted.
- `amount`: The number of tokens to mint.

This function can only be called by the contract owner.

#### `burn(uint256 amount)`

Burns the specified number of tokens from the caller's account.

- `amount`: The number of tokens to burn.

#### `transfer(address recipient, uint256 amount)`

Transfers tokens from the caller's account to the specified recipient.

- `recipient`: The address to which the tokens will be transferred.
- `amount`: The number of tokens to transfer.

## License

MIT License-see deatils [here](https://github.com/gks2022004/MetaCrafterToken/blob/main/LICENSE)

Copyright (c) 2023 Gaurav Kumar Singh

