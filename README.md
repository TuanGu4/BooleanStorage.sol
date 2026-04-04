# BooleanStorage.sol
BooleanStorage.sol2
pragma solidity ^0.8.20;

contract BooleanStorage {
    bool public status;

    function setStatus(bool _status) public {
        status = _status;
    }
}
