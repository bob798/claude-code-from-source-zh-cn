# Claude Code from Source 简体中文译本

原作者：Alejandro Balderas。[原项目仓库](https://github.com/alejandrobalderas/claude-code-from-source) · [原书在线版](https://claude-code-from-source.com)

本仓库收录《Claude Code from Source》的非官方简体中文译本，供读者学习和审阅。原书是独立的技术分析，与 Anthropic 无隶属、背书或赞助关系。Claude Code 是 Anthropic 的产品。原书的代码示例均为用于说明架构模式的原创伪代码。

## 翻译基准与授权

译文以原仓库 `main` 的提交 [`a6d5e452a8e0dd925c22c407c84611b1994562eb`](https://github.com/alejandrobalderas/claude-code-from-source/commit/a6d5e452a8e0dd925c22c407c84611b1994562eb) 为基准。中英文章节使用相同文件名，便于逐章对照。

基准版本未发现适用于本书的一般许可证。[Issue #3](https://github.com/alejandrobalderas/claude-code-from-source/issues/3) 中，原作者应 `simplex86` 的请求同意其发布独立中文译本，条件是标注原项目、链接原仓库和网站，并且不作商业用途。该回复针对 simplex86 的申请，不构成对本译者或本仓库的明确授权。本译本仓库目前未声明许可证，相关授权仍待原作者和维护者确认。译本已提交至[上游 PR #7](https://github.com/alejandrobalderas/claude-code-from-source/pull/7)，等待原作者和维护者审阅。

## 阅读说明

18 章均已完成初译和批次自查，仍待人工技术审校。已完成章节的链接指向中文译文，其余链接指向英文原文。关键术语见[术语表](GLOSSARY.md)。

## 章节目录与进度

| 章 | 章节 | 中文进度 |
| --- | --- | --- |
| 01 | [AI 智能体的架构](ch01-architecture.md) | 已翻译，待人工审校 |
| 02 | [快速启动：引导流程](ch02-bootstrap.md) | 已翻译，待人工审校 |
| 03 | [状态：双层架构](ch03-state.md) | 已翻译，待人工审校 |
| 04 | [与 Claude 通信：API 层](ch04-api-layer.md) | 已翻译，待人工审校 |
| 05 | [智能体循环](ch05-agent-loop.md) | 样章已完成，待人工审校 |
| 06 | [工具：从定义到执行](ch06-tools.md) | 已翻译，待人工审校 |
| 07 | [并发执行工具](ch07-concurrency.md) | 已翻译，待人工审校 |
| 08 | [启动子智能体](ch08-sub-agents.md) | 已翻译，待人工审校 |
| 09 | [分叉智能体与提示词缓存](ch09-fork-agents.md) | 已翻译，待人工审校 |
| 10 | [任务、协调与智能体集群](ch10-coordination.md) | 已翻译，待人工审校 |
| 11 | [记忆：跨会话学习](ch11-memory.md) | 已翻译，待人工审校 |
| 12 | [扩展机制：Skill 与 Hook](ch12-extensibility.md) | 已翻译，待人工审校 |
| 13 | [终端界面](ch13-terminal-ui.md) | 已翻译，待人工审校 |
| 14 | [输入与交互](ch14-input-interaction.md) | 已翻译，待人工审校 |
| 15 | [MCP：通用工具协议](ch15-mcp.md) | 已翻译，待人工审校 |
| 16 | [远程控制与云端执行](ch16-remote.md) | 已翻译，待人工审校 |
| 17 | [性能：每毫秒、每个 token 都重要](ch17-performance.md) | 已翻译，待人工审校 |
| 18 | [尾声：我们学到了什么](ch18-epilogue.md) | 已翻译，待人工审校 |

## 声明

本译本对应的原书声明如下。译文仅用于传达原作者的项目说明。

Claude Code from Source 不包含任何 Claude Code 源代码。所有代码块都是使用不同变量名编写的原创伪代码，用于说明架构模式。项目不包含专有提示词文本、内部常量或精确函数实现。项目仅供教育用途，帮助工程师理解生产级 AI 编码智能体背后的设计模式。

原书封面上的 “NO’REILLY” 是仅供说明用途的戏仿梗图，与 O’Reilly Media 无关。螃蟹只是螃蟹。

原书是独立分析。Claude Code 是 Anthropic 的产品。本书与 Anthropic 无隶属、背书或赞助关系。
