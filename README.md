# Minhao Builder Token (MBT)

我的第一个 ERC-20 代币项目，从零基础学习 Solidity 的起点。

## 项目信息
- **Token 名称**：Minhao Builder Token  
- **符号**：MBT  
- **精度**：18 decimals  
- **初始供应**：1,000,000 MBT（部署时全部 mint 给 owner）  
- **合约地址**：0xEafF5C41F61a7A28f5490e094471861054b4B127  
- **部署网络**：Sepolia 测试网  
- **Etherscan 链接**：https://sepolia.etherscan.io/address/0xeaff5c41f61a7a28f5490e094471861054b4b127  
- **源码验证**：已 Verify（公开透明）

## 功能
- 标准 ERC-20（转账、余额查询、授权等）
- Ownable 权限控制：只有部署者（owner）能调用额外 mint 函数
- 学习用初始供应：1,000,000 个 token

## 学习收获
- 掌握 Remix IDE 全流程：编写 → 编译 → 部署 → Verify
- 理解 constructor 初始化、msg.sender、onlyOwner 修饰符
- 学会使用 OpenZeppelin 安全模板，避免常见漏洞
- 从空投玩家到链上 builder 的第一步

## 下一步计划
- 添加 burn 函数（销毁代币）
- 实现简单前端交互（HTML + Web3.js）
- 尝试 Gitcoin 小 bounty（文档或简单代码贡献）
- 探索更多标准：ERC-721 NFT、升级代理合约

欢迎反馈、fork 或讨论！  
@Minhaonb66 | Web3 Builder Journey

最后更新：2026 年 3 月
