# LengthString.sol
LengthString.sol
pragma solidity ^0.8.20;
contract LengthString {
    function length(string memory s) public pure returns(uint){
        return bytes(s).length;
    }
}
