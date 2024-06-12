# MyToken Solidity Contract

This repository contains the implementation of the MyToken Solidity contract, which fulfills the requirements outlined below.

## Description

1. The contract has public variables to store details about the coin (Token Name, Token Abbrv., Total Supply).
2. It includes a mapping of addresses to balances.
3. There's a mint function that increases the total supply by a specified value and increases the balance of the sender address by that amount.
4. It has a burn function that decreases the total supply and the balance of the sender by a specified value.
5. The burn function includes conditionals to ensure the balance of the sender is sufficient for the amount to be burned.

## Contract Details

- **Token Name:** Tera
- **Token Abbreviation:** TR
- **Initial Total Supply:** 0 (can be increased using the mint function and decreased using mint function)

## Execution

1. Deploy the contract.
2. Use the `mint` function to create new tokens by specifying an address and the value to mint.
3. Use the `burn` function to destroy tokens by specifying an address and the value to burn. Ensure that the sender's balance is sufficient to burn the specified amount.
4. Solidity contracts can be compiled and tested in an online Remix IDE.
5.Where we test cases to verify the functionality of the mint and burn functions, ensuring they behave as expected under different scenarios.

## Authors
Anamika Sharma
anamika123sha@gmail.com

## License

This contract is licensed under the [MIT License](LICENSE).
