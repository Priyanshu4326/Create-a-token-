MyToken Smart Contract

This smart contract implements a basic ERC-20 token with minting and burning functionalities. It is written in Solidity and is compatible with Solidity version 0.8.18.

Contract Overview

The contract provides the following features:

Public variables to store token details (name, abbreviation, and total supply).
A mapping to keep track of the balance of each address.
A mint function to increase the total supply and balance of a specified address.
A burn function to decrease the total supply and balance of a specified address, with a condition to ensure the balance is sufficient for burning.
