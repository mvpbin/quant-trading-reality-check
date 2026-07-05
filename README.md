# Quant Trading Reality Check

一个面向 Codex 的量化策略研究 Skill，用中文帮助普通用户把交易想法拆成可验证的策略假设、回测计划、风险检查和复盘流程。

它的定位不是“AI 帮你赚钱”，而是“AI 帮你少被漂亮故事和漂亮回测骗”。

## 它能做什么

- 把量化交易、AI 交易、预测市场文章翻译成大白话。
- 把模糊交易想法整理成策略卡片。
- 设计最小回测方案，包括数据、基准、成本和样本外验证。
- 审查回测或纸面交易结果，判断是否可能过拟合。
- 提醒手续费、滑点、流动性、相关性、回撤、仓位和停止条件。

## 它不做什么

- 不提供个性化买入、卖出、做空、加杠杆建议。
- 不保证任何策略盈利。
- 不把 AI 生成代码、漂亮图表或单次回测当成真实优势。
- 不默认支持实盘下单、交易 API 写操作、账号凭证处理或自动交易。

## 安装

把仓库克隆到 Codex skills 目录：

```bash
git clone https://github.com/mvpbin/quant-trading-reality-check.git ~/.codex/skills/quant-trading-reality-check
```

Windows PowerShell 示例：

```powershell
git clone https://github.com/mvpbin/quant-trading-reality-check.git "$env:USERPROFILE\.codex\skills\quant-trading-reality-check"
```

重启 Codex 后即可在可用 skills 中看到它。

## 使用示例

```text
用 quant-trading-reality-check，我是小白。请把这个交易想法变成策略卡片，
先不要写复杂代码，也不要给实盘建议，只告诉我最小验证步骤。
我的想法是：……
```

```text
用 quant-trading-reality-check，帮我审查这个回测结果是不是可能过拟合，
重点看手续费、滑点、样本外结果、最大回撤和停止条件。
```

```text
用 quant-trading-reality-check，把这篇量化交易文章翻译成大白话，
告诉我哪些能学，哪些不能照做。
```

## 推荐工作流

1. 先写一句话策略假设：为什么市场可能错。
2. 再做策略卡片：交易对象、信号、入场、出场、风险限制。
3. 设计回测：数据、时间范围、成本、基准、样本切分。
4. 对比简单基准：买入持有、空仓、随机入场或简单均线。
5. 看风险指标：最大回撤、连续亏损、换手、容量和相关性。
6. 纸面交易验证：用真实可成交价格观察策略是否还成立。
7. 只有通过验证，才讨论下一轮研究；不要跳到实盘。

## 风险提示

金融交易属于高风险行为。这个 Skill 只用于学习、研究、回测设计和风险审查，不构成投资建议、财务建议、法律建议或税务建议。

如果涉及真实资金、杠杆、衍生品、自动下单、账号权限或合规问题，请先咨询有资质的专业人士，并使用你能承受损失的最低风险方式验证。

## 授权

本项目使用 MIT License，详见 [LICENSE](LICENSE)。
