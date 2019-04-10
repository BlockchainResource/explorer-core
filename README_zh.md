# 这是vns的区块链浏览器项目的核心实现。

## 项目分为三个模块
- block_scan
主要完成对vns的区块数据的扫描，通过kafka将数据推送出去。
- vns_contract
主要是对普通合约交易的解析，目前只支持erc20的合约标准的创建和转移动作。
- vns_bancor
主要是对vns上bancor协议的解析，目前只支持官方的bancor中的合约类型的检查。

## 依赖
- Mysql服务
- kafka服务
- web3库(vns官方版本)

## 编译
编译可以参看相关部分目录下的README文件

## 运行
- 需要运行 block_scan
- 如果需要解析ERC20标准的合约，可以运行vns_contract
- 如果需要解析bancor协议，可以运行vns_bancor

