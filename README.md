# 小荀

> 自学安全与自动化。用多 Agent 协作做**本地靶场漏洞挖掘**，把每条结论都做成可复现、可归档的证据。

## 我在做什么

- 现状：正在练习 Web 众测赏金方向，只在**本地靶场 / 已授权环境**动手；暂不向平台提交
- 方法：证据优先（逐条 sha256、阳性与阴性都留证）、非破坏性验证、独立复核排除误报
- 工具：多角色 Agent 协作（队长 / 侦察 / 挖掘 / 验证 / 蓝军 / 归档），优先走免费额度车道，额度耗尽再切备用车道

## 项目

| 项目 | 一句话 | 亮点 |
| --- | --- | --- |
| [vuln-xiuxian](https://github.com/xunwmw/vuln-xiuxian) | AI 多 Agent 协作的漏洞挖掘知识库 | 64 条 CVE 执行序列、挖洞避坑手册、107 项报告自查清单 |
| [shoucuo-vuln-bot](https://github.com/xunwmw/shoucuo-vuln-bot) | 自动化挖掘流水线：爬虫 → AI 判定 → 非破坏性验证 → 报告 | 安全护栏写死在代码里、结构化证据、自带烟测靶场 |
| [onefile-vuln-lab](https://github.com/xunwmw/onefile-vuln-lab) | 零依赖单文件 Web 靶场（15+ 真实可利用漏洞） | 一键重置、只绑 127.0.0.1、含原版与加固版对照 |
| [vuln-lab-quanjiadou](https://github.com/xunwmw/vuln-lab-quanjiadou) | 本地漏洞靶场合集（自建 + DVWA / bWAPP / Juice Shop / Vulhub） | 一键起停、只绑 127.0.0.1、附 Docker 国内镜像加速脚本 |
| [guichu-radio](https://github.com/xunwmw/guichu-radio) | 命令行网络电台（mpv + Node.js） | 全局电台搜索、音量热调 |

## 原则

1. 只碰授权目标，非破坏性
2. 结论必须带证据（时点 + 状态 + sha256）
3. 误报和阴性同样留档

## 反馈 · 合作

> 如果你在使用时发现了任何问题，可以给我发消息或者私信我。不过最好不要私信，本人社恐。欢迎大佬给我的项目提意见。
> 如果你使用时发生了错误或者没法使用，也可以修改我的项目。申请项目合作人。

每个仓库的 Issue 页都有「合作者申请」模板，想一起做哪个项目就在哪个仓库提：
[vuln-xiuxian](https://github.com/xunwmw/vuln-xiuxian/issues/new?template=collaborator_request.md) ·
[shoucuo-vuln-bot](https://github.com/xunwmw/shoucuo-vuln-bot/issues/new?template=collaborator_request.md) ·
[onefile-vuln-lab](https://github.com/xunwmw/onefile-vuln-lab/issues/new?template=collaborator_request.md) ·
[vuln-lab-quanjiadou](https://github.com/xunwmw/vuln-lab-quanjiadou/issues/new?template=collaborator_request.md) ·
[guichu-radio](https://github.com/xunwmw/guichu-radio/issues/new?template=collaborator_request.md)

「申请项目合作人」就是 GitHub 的仓库协作者（Collaborator）：申请通过后你会拿到该仓库的写权限，可以建分支、提 PR、管 Issue。

> 国内网络说明：这些项目在国内直连**基本都能跑**，会卡的一般只是 `git clone` 和 Docker Hub。各个仓库都留了 `docs/ENVIRONMENT.md`，里面有实测数据、官方安装链接，以及官方 WARP 的安装与校验方法。
