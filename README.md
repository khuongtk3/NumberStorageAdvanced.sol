# NumberStorageAdvanced.sol
Contract deployed via Web3 NumberStorageAdvanced.sol
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract NumberStorageAdvanced {
    uint public number;

    function setNumber(uint _number) public {
        number = _number;
    }

    function reset() public {
        number = 0;
    }
}
