// SPDX-License-Identifier: MIT
// go to https://docs.soliditylang.org/en/latest/layout-of-source-files.html#spdx-license-identifier to learn more about license

pragma solidity ^0.8.0; // here is where you specify the solidity version

// this contract has 2 functions, set() and get()
contract SimpleStorage {
     uint256 public storedNumber;
      function set(uint256 _number) public {
         storedNumber = _number;
          }

function get() public view returns (uint256) {
     return storedNumber;
 }
}
