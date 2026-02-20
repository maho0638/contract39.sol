# contract39.sol
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.0;

// Web3 boolean state contract
contract Contract39 {
    bool public active = true;

    function toggle() public {
        active = !active;
    }
}
