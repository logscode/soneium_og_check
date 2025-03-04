# Soneium OG Badge Batch Query Tool / Soneium OG Badge 批量查询工具

[English](#english) | [中文](#中文)

## English

### Introduction
A web-based tool for batch querying Soneium OG Badge balances. This tool allows users to check both regular and golden OG badge quantities for multiple addresses simultaneously.

### Features
- Batch query support for multiple addresses
- Concurrent processing (adjustable from 1-50 connections)
- Automatic retry for failed queries
- One-click CSV export
- No installation required, works directly in browser

### How to Use
1. Input wallet addresses (one per line)
2. Set concurrent connections (recommended: 10-20)
3. Click "Query" to start
4. Failed addresses will be automatically collected for retry
5. Export results to CSV when finished

### Technical Details
- Built with pure HTML/JavaScript
- Uses Web3.js for blockchain interaction
- Supports MetaMask connection
- Implements rate limiting to prevent overload

## 中文

### 简介
一个基于网页的 Soneium OG Badge 批量查询工具。用户可以同时查询多个地址的普通和黄金 OG badge 数量。

### 功能特点
- 支持多地址批量查询
- 可调节并发数（1-50个连接）
- 失败地址自动收集重试
- 一键导出CSV报表
- 无需安装，浏览器直接使用

### 使用方法
1. 输入钱包地址（每行一个）
2. 设置并发连接数（建议10-20）
3. 点击"查询"开始
4. 失败的地址会自动收集以供重试
5. 完成后可导出CSV结果

### 技术细节
- 纯 HTML/JavaScript 构建
- 使用 Web3.js 进行区块链交互
- 支持 MetaMask 连接
- 实现请求限制防止过载

---

## License / 许可证
MIT License / MIT 许可证
