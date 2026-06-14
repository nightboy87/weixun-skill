# 微醺 Skill

> 在清醒状态下，召回那些通常只有在“微醺感”里才会冒出来的野生灵感、真实需求和审美底色。

**微醺 Skill** 不是劝人喝酒的工具，也不是酒后聊天分析器。它是一套给 Agent 使用的低防御创意引导方法：通过去身份化、低评判热身、审美触发、反常规追问和 7 天实验收束，帮助用户把平时被理性、职业角色、面子和自我审查压住的想法说出来。

适合这些场景：

- 你有一个想法，但一说出口就变得普通、正确、没劲。
- 你想做一个产品、工具、文章、开源项目、个人品牌，但找不到真正有生命力的内核。
- 你想从吐槽、兴奋点、审美偏好里挖出隐藏需求。
- 你觉得自己被工作流程和职业身份压住了创意。
- 你想要“微醺时会说出来”的真想法，但希望在完全清醒、安全、可复盘的状态下完成。

## 这个 Skill 解决什么问题

很多人不是没有想法，而是想法一进入正式语境就被压平：

- 说出口前先自我审查。
- 写成方案时自动变成正确废话。
- 会议语境里只敢说稳妥版本。
- 真正的审美、欲望、愤怒、反叛性和创意冲动被隐藏起来。

微醺 Skill 的目标不是制造失控，而是**在清醒状态下制造一种低防御、高联想、低评判的创意空间**。

## 设计参考

本仓库借鉴了 Agent Skills 的通用结构：`SKILL.md` 作为主入口，`references/` 放方法论，`assets/` 放模板，`examples/` 放样例。

也参考了 [女娲.skill](https://github.com/alchaincyf/nuwa-skill) 的思路：不要只模仿表层语言，而要提炼更深层的表达 DNA、心智模型、决策启发式、反模式和诚实边界。

但微醺 Skill 的方向不同：

| 项目 | 目标 |
|---|---|
| 女娲.skill | 从外部材料中蒸馏一个人怎么想 |
| 微醺 Skill | 从用户本人身上唤醒平时不敢说、说不清的真实创意和隐藏需求 |

## 安装

### 方式一：让 Agent 自动安装

在支持 Agent Skills 的工具里输入：

```text
帮我安装这个 skill：https://github.com/nightboy87/weixun-skill
```

### 方式二：手动安装

把本仓库复制到对应 runtime 的 skills 目录，例如：

```text
Claude Code: ~/.claude/skills/weixun-skill/
Codex CLI:   ~/.codex/skills/weixun-skill/
Cursor:      ~/.cursor/skills/weixun-skill/
OpenClaw:    ~/.openclaw/workspace/skills/weixun-skill/
Hermes:      ~/.hermes/skills/weixun-skill/ 或按你的 Hermes 配置放置
```

然后重启 Agent。

## 使用方式

安装后，可以直接对 Agent 说：

```text
用微醺 Skill 帮我挖一下这个想法：我想做一个开发者工具，但我不想它像普通效率工具。
```

也可以说：

```text
我有个模糊的公众号选题，但写出来很普通。用微醺 Skill 帮我把更真实、更野的部分挖出来。
```

或者：

```text
我想从这段吐槽里挖真实需求：现在这些企业工具都太像流程表了，没有一点人的感觉。
```

## 输出示例

微醺 Skill 默认输出《微醺灵感蒸馏报告》，包括：

1. 高能原话
2. 底色假设
3. 隐藏需求
4. 审美 DNA
5. 反模式
6. 创意原矿
7. 7 天小实验
8. 下一轮追问

它不会把你贴成某种人格，也不会说“你其实就是怎样的人”。所有判断都以“假设”和“线索”方式呈现。

## 仓库结构

```text
weixun-skill/
├── SKILL.md
├── README.md
├── LICENSE
├── CHANGELOG.md
├── references/
│   ├── low-defense-dialogue.md
│   ├── aesthetic-trigger-bank.md
│   ├── hidden-need-extraction.md
│   ├── safety-boundaries.md
│   └── evaluation-rubric.md
├── assets/
│   ├── session-template.md
│   ├── inspiration-distillation-report-template.md
│   ├── seven-day-experiment-template.md
│   └── prompt-cards.md
└── examples/
    ├── rock-programmer.md
    ├── product-idea.md
    └── writing-topic.md
```

## 设计原则

### 1. 不是喝酒工具

微醺是一种隐喻：低防御、低评判、高联想、高表达欲。用户不需要饮酒，也不应该为了使用这个 Skill 去饮酒。

### 2. 先保护野性，再谈落地

早期不要急着判断商业价值、可行性、成本和排期。先把原矿挖出来，再在最后压缩成 7 天实验。

### 3. 不要把原话消毒成正确废话

用户最有能量的表达，往往不规整、不专业、不成熟。不要过早把它改写成“提升效率、优化体验、赋能用户”这类平滑语言。

### 4. 每次必须收束到行动

灵感如果不落地，很快会消散。每次会话至少输出一个 7 天内能完成的小实验。

## 不适合的用途

- 心理诊断
- 情绪危机处理
- 酒后状态分析
- 劝酒或饮酒建议
- 操控他人表达真实想法
- 重大人生决策的唯一依据
- 医学、法律、财务等高风险建议

## License

MIT
