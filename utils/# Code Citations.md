# Code Citations

## License: Apache_2_0
https://github.com/celo-org/docs/tree/8e32888eb86c6f5e08f5021422fe728bfc53f1dc/blog/03-17-2023-Celo-Integration-with-Web3/Celo-Integration-with-Web3.md

```
SPDX-License-Identifier: MIT
pragma solidity ^0.8.0;

import "@openzeppelin/contracts/token/ERC20/ERC20.sol";

contract MyToken is ERC20 {
    constructor(uint256 initialSupply) ERC20("MyToken", "MTK") {
        _mint(
```


## License: inconnu
https://github.com/joinpursuit/pursuit-crypto-lessons/tree/1adaba130f9362cd6bce6c622803d870848f3516/solidity_basics/lessons/lesson_10.md

```
pragma solidity ^0.8.0;

import "@openzeppelin/contracts/token/ERC20/ERC20.sol";

contract MyToken is ERC20 {
    constructor(uint256 initialSupply) ERC20("MyToken", "MTK") {
        _mint(msg.sender, initialSupply);
```

