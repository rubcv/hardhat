# Hardhat pipeline for CI/CD Smart Contract testing.

Packages used:
* **solhint** for linting Solidity code. Configuration file: .solhint.json (https://github.com/protofire/solhint)
* **prettier**, **prettier-plugin-solidity** for formatting Solidity code. (https://github.com/prettier-solidity/prettier-plugin-solidity)
* **solidity-coverage** which reports the coverage of the tests implemented (lines evaluated, conditions not passed, etc)
* **hardhat-gas-reporter** to estimate the gas cost of the Smart Contract. (https://github.com/cgewecke/hardhat-gas-reporter)