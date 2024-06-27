# Local-Store Smart Contract

## Overview
The 'localStore' smart contract is a simple inventory management system implemented in Solidity. It manages the number of items on an electronic shelf, ensuring the shelf is neither overfilled nor empty.

## Features
The 'NumberChecker' contract provides three primamry features for interacting and modifying a stored number 'a'. These features demonstrate different error handling mechansim in Solidity:
1. The contract initializes the 'electronicshelf' to 10 upon deployment.
2. Function 'additems' allows the updation of 'items' if more items are added using require for error handling.
3. Function 'shelfIsnotFull' checks if the shelf can accept more items uisng 'require' and 'assert' to ensure the correct conditions.
4. Function 'she;fIsfull' checks if the shelf has reached it's maximum capacity using 'require' and 'revert' for error handling.

# Steps to execute localStore Smart COntract on Remix IDE
## Prerequisites
1. Open Remix IDE
2. Create a new file
3. Copy the contract code
4. Compile the contract
5. Deploy the contract
6. Interact with the deployed contract

## Aurthor
Farhat Mbarak Saleh

## License
This project is licensed under the MIT license - see the LICENSE.md file for details.

