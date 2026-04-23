# viewPure.sol
viewPure.sol
pragma solidity ^0.8.20;
contract ViewPure {
    uint public x = 10;

    function getX() public view returns(uint) {
        return x;
    }

    function add(uint a, uint b) public pure returns(uint) {
        return a + b;
    }
}
