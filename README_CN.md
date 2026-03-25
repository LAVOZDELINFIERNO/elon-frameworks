# Elon Frameworks

**将 Elon Musk 的核心思维框架应用到你的真实问题中。**

一套结构化思维工具包，提炼自 Eric Jorgenson 的 [*The Book of Elon: A Guide to Purpose and Success*](https://www.elonmuskbook.org/)（2026）。这不是传记摘要，而是一套可操作的心智模型——可以配合任何 AI 助手使用，也可以独立使用。

> **声明**：本项目将公开的思维框架提炼为可操作的工具，不复制书中内容。强烈推荐阅读原书以获取完整的故事、引用和上下文。

## 内容概览

8 个详细框架 + 69 条方法速查索引：

| 框架 | 适用场景 | 文件 |
|------|---------|------|
| **第一性原理思维** | 做决策、挑战假设、成本分析 | [first-principles.md](skills/elon-frameworks/references/first-principles.md) |
| **The Algorithm（算法）** | 优化缓慢/混乱/臃肿的流程 | [the-algorithm.md](skills/elon-frameworks/references/the-algorithm.md) |
| **使命与目标设计** | 寻找方向、明确工作的意义 | [mission-purpose.md](skills/elon-frameworks/references/mission-purpose.md) |
| **极致团队建设** | 招聘、团队结构、文化、绩效 | [team-building.md](skills/elon-frameworks/references/team-building.md) |
| **速度与紧迫感** | 加快节奏、设定时间线、并行化工作 | [speed-urgency.md](skills/elon-frameworks/references/speed-urgency.md) |
| **韧性与失败** | 克服恐惧、拥抱失败、建立抗压力 | [resilience-failure.md](skills/elon-frameworks/references/resilience-failure.md) |
| **系统与制造思维** | 规模化生产、寻找瓶颈、工厂思维 | [systems-manufacturing.md](skills/elon-frameworks/references/systems-manufacturing.md) |
| **69 条核心方法** | 全部方法的速查索引 | [69-methods.md](skills/elon-frameworks/references/69-methods.md) |

## 核心工具

- **白痴指数（Idiot Index）** — 成品成本 / 原材料成本。比值越高，流程越低效。
- **魔法棒数字（Magic Wand Number）** — 如果能完美排列原子，理论最低成本是多少？
- **The Algorithm** — 质疑 → 删除 → 简化 → 加速 → 自动化（顺序至关重要）。
- **十年直觉测试** — 即使经历最糟糕的一年，你还愿意做这件事吗？

## 如何使用

### 配合任何 AI 助手（ChatGPT、Claude、Gemini 等）

将 [SKILL.md](skills/elon-frameworks/SKILL.md) 和相关参考文件的内容复制到对话中作为上下文。例如：

> "这是我希望你使用的思维框架：[粘贴 SKILL.md]。现在，帮我分析我是否应该做一个平价家用储能产品。"

### 配合 Claude Code

**方式一：作为 marketplace 插件安装（推荐）**

1. 在 Claude Code 中添加 marketplace 源：

```
/plugin marketplace add LAVOZDELINFIERNO/elon-frameworks
```

2. 安装技能：

```
/plugin install elon-frameworks@elon-frameworks
```

**方式二：手动安装**

```bash
git clone https://github.com/LAVOZDELINFIERNO/elon-frameworks.git
cp -r elon-frameworks/skills/elon-frameworks ~/.claude/skills/elon-frameworks
```

### 配合 OpenClaw

通过 [ClawHub](https://clawhub.ai) 安装：

```bash
clawhub install elon-frameworks
```

如果尚未安装 CLI：

```bash
npm i -g clawhub
clawhub login
clawhub install elon-frameworks
```

### 作为个人参考

直接阅读 Markdown 文件即可。每个框架包含：
- 核心概念说明
- 分步应用指南
- 输出格式模板
- 常见陷阱提醒

## 框架组合

有些问题适合叠加多个框架使用：

- **创业**：使命 → 第一性原理 → Algorithm
- **规模化生产**：系统思维 → Algorithm → 速度
- **克服犹豫**：韧性 → 使命 → 速度
- **降低成本**：第一性原理（白痴指数）→ Algorithm → 系统思维
- **组建团队**：使命 → 团队建设 → 速度

## 参与贡献

发现缺少的框架或想改进现有内容？欢迎提交 PR。请保持统一结构：
- 核心概念 → 分步应用 → 输出格式 → 常见陷阱
- 框架即工具，不搞个人崇拜
- 可操作，不鸡汤

## 许可证

MIT — 自由使用，广泛分享。

## 致谢

框架灵感来自 Eric Jorgenson 的 [*The Book of Elon*](https://www.elonmuskbook.org/)（Magrathea Publishing, 2026）。推荐购买原书获得完整体验。
