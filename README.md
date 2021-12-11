# CryptoZombies


Define compiler version
```solidity
pragma solidity ^0.4.19;
```

Import external contract files
```solidity
import "./anothercontract.sol";
```

Create the contract
```solidity
contract MyContract {

}
```


## Memory Types
- storage (armazenamento): Blockchain (HD).
- memory (memória): Function execution (RAM).

## Functions
```solidity
function name() {

}

### Visibility Modifiers
- public
- private
- internal
- external

### Status Modifiers
- pure
- view

## Modifier Functions
```solidity
modifier name() {
  require();
  _;
}

## Payable Functions
```solidity
function name() external payable {

}

## Smart Contracts Libraries

- [OpenZeppelin](https://openzeppelin.com/)
