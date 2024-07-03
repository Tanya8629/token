# token
This Solidity program is a simple program writtened to ctreate an ERC 20 token
Description 
This program is a simple contract written in Solidity, a programming language used for developing smart contracts similarly in this program we created smart contract named timetoken in which we imported some predefined libraries and created an erc20 token. Getting Started Executing program To run this program, you can use Remix, an online Solidity IDE. To get started, go to the Remix website at https://remix.ethereum.org/.

Once you are on the Remix website, create a new file by clicking on the "+" icon in the left-hand sidebar. Save the file with a .sol extension (e.g., HelloWorld.sol). Copy and paste the following code into the file: // SPDX-License-Identifier: MIT pragma solidity ^0.8.0;
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.0;

import "@openzeppelin/contracts/token/ERC20/ERC20.sol";

contract TimeToken is ERC20 { 
   constructor() ERC20("Time Token", "TT") {

     _mint(msg.sender, 100 * 10 ** decimals());
   }
}
 To compile the code, click on the "Solidity Compiler" tab in the left-hand sidebar. Make sure the "Compiler" option is set to "0.8.4" (or another compatible version), and then click on the "Compile HelloWorld.sol" button.

Once the code is compiled, you can deploy the contract by clicking on the "Deploy & Run Transactions" tab in the left-hand sidebar. Select the "time token" contract from the dropdown menu, and then click on the "Deploy" button.

Once the contract is deployed, you can interact with it by calling the elligible and license requirement function.

License This project is licensed under the MIT License - see the LICENSE.md file for details
