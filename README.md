# BooleanStorage.sol
BooleanStorage.sol2
pragma solidity ^0.8.20;

contract BooleanStorage {
    bool public status;

    function setStatus(bool _status) public {
        status = _status;
    }
}
Update variable naming
Add input validation
Improve security checks
Simplify contract flow
Update deployment config
Improve naming scheme
