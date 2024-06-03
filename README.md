# Eth.Proof.Beginner
MyToken Contract

Overview:
The MyToken smart contract is a simple implementation of a cryptocurrency token on the Ethereum blockchain. This contract allows the creation, minting, and burning of tokens while maintaining the total supply and individual balances.

Requirements:
Public Variables: The contract includes public variables to store details about the token, including its name, abbreviation, and total supply.
Balances Mapping: The contract includes a mapping to associate addresses with their respective token balances.
Mint Function: The contract includes a function to mint new tokens, increasing both the total supply and the balance of the specified address.
Burn Function: The contract includes a function to burn tokens, decreasing both the total supply and the balance of the specified address. This function includes a check to ensure the address has enough tokens to burn.

Functions:
Public Variables
string public tokenName: Stores the name of the token.
string public tokenAbbrv: Stores the abbreviation of the token.
uint public totalSupply: Stores the total supply of the token.
Mapping
mapping (address => uint) public balances: Associates each address with its respective balance.

Mint Function:
The mint function increases the total supply and the balance of the specified address by the given value.

Burn Function:
The burn function decreases the total supply and the balance of the specified address by the given value, ensuring the address has sufficient balance to burn the tokens.

License:
This contract is licensed under the MIT License.
