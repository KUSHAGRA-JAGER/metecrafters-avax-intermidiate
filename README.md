# README.md

## DegenGamingToken
This is a basic ERC20 token contract implemented in Solidity. It allows for the creation, transfer, and management of a custom token called "Degen Token" with the symbol "DEGEN".

### Features

Token creation with a fixed total supply
Token transfer between addresses
Token approval and allowance management
Token burning and redemption
Event emission for token transfers and approvals
Functions

--> mint(address _to, uint _amount): Mints new tokens and assigns them to the specified address


--> transfer(address _to, uint _amount): Transfers tokens from the caller's address to the specified address


--> approve(address _spender, uint _amount): Approves the specified address to spend tokens on behalf of the caller


--> transferFrom(address _from, address _to, uint _amount): Transfers tokens from one address to another, using an approved allowance


--> redeem(uint _amount): Redeems tokens for items in the in-game store (to be implemented by Degen Gaming)


--> balanceOf(address _owner): Returns the token balance of the specified address


--> allowance(address _owner, address _spender): Returns the approved allowance of the specified address for the specified spender


--> burn(uint _amount): Burns tokens, reducing the total supply


Security

Only the contract owner can mint new tokens
Token transfers and approvals are restricted to the token owner or approved addresses
Token burning is restricted to the token owner
License

This contract is licensed under the MIT License.
