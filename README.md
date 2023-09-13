# Lottery_Smart_Contract
The smart contract is a lottery system written in Solidity. It allows users to enter the lottery by sending a minimum of 1 ether. 
The manager initiates the lottery and picks a random winner among the participants, transferring the entire contract balance to them. 
The contract ensures that the manager cannot enter and that each player can participate only once. Users can query the list of players. 
The contract uses a sha256-based random number generation method. Upon selecting a winner, it resets the lottery by creating a new empty list of players.
SPDX-License-Identifier is MIT, and it's compatible with Solidity version 0.8.



## Flow

![image](https://github.com/Abchoudhary2512/Lottery_Smart_Contract/assets/97343691/9b3f435e-f192-40e8-97a0-a5654ec6f20b)
