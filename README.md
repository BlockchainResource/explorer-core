This is the core implementation of the VNS blockchain explorer project.

## The project is divided into three modules
### block_scan 
   Scan the blocks, then push the parsed data out through kafka.
### vns_contract
   Parse the normal contract transactions, currently only supports erc20 contract creation and transfer action. 
### vns_bancor
   Parse the bancor protocol, currently only supports the contract type in the official bancor.

## Dependencies
- Mysql Server
- kafka Server 
- web3 lib(by vns)

## Compile
See the README file in the sub directory.

## Run
- Run block_scan first.
- Run vns_contract to parse ERC20 contract
- Run vns_bancor to parse bancor protocol

    
