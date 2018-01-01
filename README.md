# ERC20 Token Standard
source: [https://github.com/ethereum/EIPs/blob/master/EIPS/eip-20-token-standard.md](https://github.com/ethereum/EIPs/blob/master/EIPS/eip-20-token-standard.md)

## Preamble

    EIP: 20
    Title: ERC-20 Token Standard
    Author: Fabian Vogelsteller <fabian@ethereum.org>, Vitalik Buterin <vitalik.buterin@ethereum.org>
    Type: Standard
    Category: ERC
    Status: Accepted
    Created: 2015-11-19


## Simple Summary

A standard interface for tokens.


## Implementation

There are already plenty of ERC20-compliant tokens deployed on the Ethereum network.
Different implementations have been written by various teams that have different trade-offs: from gas saving to improved security.

#### Example implementations are available at
- https://github.com/OpenZeppelin/zeppelin-solidity/blob/master/contracts/token/StandardToken.sol
- https://github.com/ConsenSys/Tokens/blob/master/contracts/StandardToken.sol

#### Implementation of adding the force to 0 before calling "approve" again:
- https://github.com/Giveth/minime/blob/master/contracts/MiniMeToken.sol
