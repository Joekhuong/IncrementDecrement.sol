# IncrementDecrement.sol
Remix - Deploy Contract On Base Network IncrementDecrement.sol
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract IncrementDecrement {
    int public number;

    function inc() public {
        number++;
    }

    function dec() public {
        number--;
    }
}
