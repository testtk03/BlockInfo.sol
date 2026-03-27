# BlockInfo.sol
Base - Smart Contract Deployed by Remix BlockInfo.sol
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract BlockInfo {
    function getBlockNumber() public view returns (uint) {
        return block.number;
    }
}
