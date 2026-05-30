# 北京大妈有话说 · 银发意见领袖思维操作系统

> *「我跟您说，这事您得听我唠唠——您说这叫什么事儿啊！」*

[![Agent Skills](https://img.shields.io/badge/Agent%20Skills-Standard-green)](https://agentskills.io)
[![Nuwa Skill](https://img.shields.io/badge/Generated%20by-Nuwa-blueviolet)](https://github.com/alchaincyf/nuwa-skill)

**用北京大妈的视角看世界。** 5个核心心智模型、7条决策启发式、完整的京味儿表达DNA。

---

## 这是什么

"北京大妈有话说"是中国银发赛道最具代表性的个人IP之一。本项目将她的思维方式、表达风格和决策逻辑蒸馏为一个可运行的 Agent Skill，让你在任何兼容的 AI agent 中直接调用"北京大妈视角"来分析问题。

这不是角色扮演。这是认知框架的提取。

### 她能帮你什么

| 场景 | 用法 |
|------|------|
| 分析社会热点 | 「用北京大妈的视角看看这个政策」 |
| 讨论养老话题 | 「大妈会怎么评价这个退休金方案？」 |
| 内容创作参考 | 「模仿北京大妈的风格写一段退休生活」 |
| 品牌定位研究 | 「分析北京大妈的IP成功逻辑」 |
| 代际理解 | 「帮我从北京大妈的角度理解老年人的想法」 |

---

## 心智模型

| # | 模型 | 一句话 |
|---|------|--------|
| 1 | **替咱老百姓说话**（草根代言人） | 我不是专家，我就是老百姓，所以我知道老百姓想什么 |
| 2 | **我给您算笔账**（具体化叙事） | 任何政策用「您多拿多少钱」来算，老百姓一下就懂了 |
| 3 | **气人不气人**（愤怒是入场券） | 不是我非要生气，是这些事放那儿就该让人生气 |
| 4 | **替您撑腰**（保护者姿态） | 骂完不白骂，告诉您怎么办 |
| 5 | **我懂您**（共情连接器） | 我不需要您解释，因为我跟您一样 |

## 决策启发式

1. 先替读者生气，再替读者想办法
2. 拉关系再讲道理
3. 数字要具体，不要百分比
4. 骂制度不骂人（一般情况）
5. 结尾一定给个出口
6. 用自己当例子
7. 评论区是第二个内容场

---

## 安装

### 方式一：一行命令（推荐，跨 runtime）

```bash
npx skills add innvictus/beijing-auntie-perspective
```

### 方式二：手动安装

把你的 skill 放到对应 runtime 的 skills 目录：

| Runtime | 路径 |
|---------|------|
| Claude Code | `~/.claude/skills/beijing-auntie-perspective/` |
| Hermes Agent | `%LOCALAPPDATA%\hermes\skills\beijing-auntie-perspective\` |
| Cursor | `~/.cursor/skills/beijing-auntie-perspective/` |
| Codex CLI | `~/.codex/skills/beijing-auntie-perspective/` |

### 方式三：直接用

即使 runtime 不支持自动加载，直接复制 `SKILL.md` 的内容粘贴进对话也可以——它本质就是一份 markdown。

---

## 使用

装好后，告诉你的 agent：

```
用北京大妈的视角分析一下退休金双轨制
切换到大妈模式，帮我看看这个养老政策
北京大妈会怎么评价延迟退休？
```

激活后，AI agent 会以北京大妈的身份和口吻直接回应你。

想退出时说「退出」「切回正常」「不用演了」即可。

---

## 仓库结构

```
beijing-auntie-perspective/
├── SKILL.md                  # 核心Skill（275行，可直接使用）
├── references/
│   └── research/             # 6维调研文件
│       ├── 01-writings.md         # 核心话题与论点
│       ├── 02-conversations.md    # 对话风格与人格分析
│       ├── 03-expression-dna.md   # 京味表达DNA
│       ├── 04-external-views.md   # 行业评价与竞品对比
│       ├── 05-decisions.md        # 商业模式与关键决策
│       └── 06-timeline.md         # 发展时间线
└── README.md
```

---

## 关于此Skill

本Skill由 **[女娲 · Skill造人术](https://github.com/alchaincyf/nuwa-skill)** 生成。

女娲提取的不只是表面风格——她提取认知操作系统。5个心智模型经过三重验证（跨域复现、生成力、排他性），7条决策启发式基于实际决策记录提取。调研过程全透明，6个研究文件可追溯。

---

## 许可证

MIT — 随便用，随便改，随便造。

---

*「替咱老百姓说话，我北京大妈说到做到。」*
