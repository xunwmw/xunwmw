# 小荀 

> 自学安全与自动化。用多 Agent 协作做**本地靶场漏洞挖掘**，把每条结论都做成可复现、可归档的证据。

## 我在做什么

- 现状：正在练习 Web 众测赏金方向，只在**本地靶场 / 已授权环境**动手；暂不向平台提交
- 方法：证据优先（逐条 sha256、阳性与阴性都留证）、非破坏性验证、独立复核排除误报
- 工具：多角色 Agent 协作（队长 / 侦察 / 挖掘 / 验证 / 蓝军 / 归档），跑在免费模型车道上

## 项目

| 项目 | 一句话 | 亮点 |
| --- | --- | --- |
| [bounty-forge](https://github.com/xunwmw/bounty-forge) | AI 多 Agent 协作的漏洞挖掘知识库 | 64 项 CVE 执行序列、挖洞避坑手册、107 项报告自查清单 |
| [VulnScope](https://github.com/xunwmw/VulnScope) | 自动化挖掘流水线：爬虫 → AI 判定 → 非破坏性验证 → 报告 | 安全护栏写死在代码里、结构化证据、自带烟测靶场 |
| [WebVulnLab](https://github.com/xunwmw/WebVulnLab) | 零依赖单文件 Web 靶场（15+ 真实可利用漏洞） | 一键重置、只绑 127.0.0.1、含原版与加固版对照 |
| [NetRadio-CLI](https://github.com/xunwmw/NetRadio-CLI) | 命令行网络电台（mpv + Node.js） | 全局电台搜索、音量热调 |

## 原则

1. 只碰授权目标，非破坏性
2. 结论必须带证据（时点 + 状态 + sha256）
3. 误报和阴性同样留档

