# Mastering Taproot — 精通比特币脚本编程（中文版）

[Mastering Taproot](https://github.com/aaron-recompile/mastering-taproot) 的交互式 Jupyter 配套，为 Bitcoin Taproot 提供完整的开发者指南。

## 这是什么

这是本书的**交互式配套**。主仓库提供文稿和参考代码，本仓库提供可运行的 Jupyter  notebooks：

- **运行**：逐步执行真实的 Bitcoin Script 示例
- **修改**：调整私钥、脚本、树结构等参数，即时查看结果
- **实验**：尝试「如果…会怎样」的场景
- **可视化**：交互式查看 Taproot 数据结构

## 依赖

```bash
# 1. 激活环境
conda activate bitcoin_course   # 或该项目的 conda 环境

# 2. 安装 btcaaron（本地开发版，推荐）
pip install -e /path/to/btcaaron

# 3. 安装其余依赖
pip install -r requirements.txt
```

- **第 1–4 章**：`bitcoin-utils`（Legacy / P2SH / SegWit）
- **第 5–8 章**：`btcaaron`（Taproot 语义 API）

更多 btcaaron 示例见 `examples/` 目录。

## 在线站点

📖 中文版：[zh.bitcoincoding.dev](https://zh.bitcoincoding.dev)  
📖 英文版：[bitcoincoding.dev](https://bitcoincoding.dev)

## 本书

📚 [github.com/aaron-recompile/mastering-taproot](https://github.com/aaron-recompile/mastering-taproot)

## License

[CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/)
