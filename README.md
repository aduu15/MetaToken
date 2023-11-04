# MyToken

A simple Ethereum token contract that allows minting and burning of tokens.


## Token Details

- Token Name: Adarsh
- Token Symbol: Singh
- Total Supply: 0

## Functions

### mint

`function mint(address _addr, uint _value)`

Mints new tokens and assigns them to the specified address.
- `_addr` - The address to receive the minted tokens.
- `_value` - The amount of tokens to mint.

### burn

`function burn(address _addr, uint _value)`

Burns existing tokens held by the specified address.
- `_addr` - The address that holds the tokens to be burned.
- `_value` - The amount of tokens to burn.

### balance

`mapping(address => uint) public balance`

A mapping that holds the balance of each address.

## Usage

1. Deploy the contract to an Ethereum network.
2. Call the `mint` function to mint new tokens and assign them to an address.
3. Call the `burn` function to burn existing tokens held by an address.
4. Use the `balance` mapping to get the balance of an address.
