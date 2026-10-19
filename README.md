# 王阳明.skill

## 在你的龙场，重新立定自己。

**心即理 · 知行合一 · 致良知 · 事上磨**

[📥 下载 Skill](https://github.com/wangxingjian703-coder/wang-yangming-skill/archive/refs/heads/main.zip) · [🚀 安装方法](#installation) · [💬 开始对话](#conversation) · [📚 原典依据](#sources)

> 处境一时难改，难过也是实在的。
>
> 先看看，还有哪一件事是你愿意做、眼下也做得动的。
>
> **那一步可以很小，不必先证明自己已经想通。**
>
> —— 本项目的现代对话示例，非王阳明原话

以《传习录》《大学问》《教条示龙场诸生》为依据，让阳明心学走进具体的生活：陪你分析一个选择，面对一次挫折，也陪你把道理落到今天能做的一件事上。

这是基于文献的思想模拟，现代应用由本项目编写，不代表王阳明本人的真实发言。

---

## 🧭 目录

- [📦 它能陪你做什么](#features)
- [💬 开始一场对话](#conversation)
- [🚀 下载与安装](#installation)
- [🌱 这份 Skill 的思路](#approach)
- [📚 原典与资料](#sources)
- [🗂️ 仓库结构](#structure)
- [🤝 一起完善](#contributing)
- [📄 开源许可](#license)

---

<a id="features"></a>

## 📦 它能陪你做什么

| 你正在经历 | 可以怎样聊 |
| --- | --- |
| 🧭 面临选择 | 把现实条件、心中所重与行动后果一起看清 |
| 🌧️ 遭遇挫折 | 承认处境的艰难，重新寻找仍可自主选择的部分 |
| 📖 学习拖延 | 辨认害怕、疲惫或方法上的障碍，找到一个能开始的动作 |
| 🪞 在意评价 | 看清他人的评价怎样影响你，辨认自己的方向 |
| 🍵 想说说心里话 | 用温和、直率的现代中文交流，留出倾诉的空间 |
| 📜 想读懂心学 | 结合原典解释概念，分清古人原话与现代应用 |

无需 API Key、外部服务或运行脚本。它是一套供支持 Skill 的 AI 工具使用的指令与参考资料。

<a id="conversation"></a>

## 💬 开始一场对话

```text
用王阳明的视角，帮我看看：我很在意别人怎么看我，该怎么办？

阳明先生，我明明知道该学习，却总在逃避，想跟你聊聊。

龙场悟道让我振奋。处在不顺的阶段，我怎样重新立定自己？

用心学分析这个选择，但也请帮我检查现实条件与风险。

解释一下知行合一，并告诉我哪些是原文、哪些是现代应用。
```

<a id="installation"></a>

## 🚀 下载与安装

### 方法一：让 Codex 帮你安装

把本仓库网址发给 Codex，并说：

```text
请使用 skill-installer，从下面的 GitHub 仓库安装
wang-yangming-perspective 文件夹里的 Skill：
https://github.com/wangxingjian703-coder/wang-yangming-skill
```

### 方法二：手动下载

**[📥 点击下载完整 ZIP](https://github.com/wangxingjian703-coder/wang-yangming-skill/archive/refs/heads/main.zip)**

1. 点击仓库的 **Code → Download ZIP**，解压。
2. 将 `wang-yangming-perspective` 整个文件夹复制到你的个人 Skills 目录。本机使用 `~/.codex/skills/`；若设置了 `CODEX_HOME`，则使用其 `skills/` 子目录。不同工具或版本的目录可能有差异。
3. 打开新对话；若尚未发现它，重启 Codex 后查看。文件夹内须直接包含 `SKILL.md`，不要重复嵌套一层同名文件夹。
4. 输入：

```text
$wang-yangming-perspective
陪我分析一下眼前的问题。
```

其他兼容 Agent Skills 的工具可复用核心 `SKILL.md` 和 `references/`，请按对应工具的安装方式放置。`agents/openai.yaml` 是可选的 Codex 界面元数据。

---

<a id="approach"></a>

## 🌱 这份 Skill 的思路

- **心即理：** 辨认内心的价值与动机，同时认真调查事实。
- **知行合一：** 把理解落实到具体行动，再依据结果修正。
- **致良知：** 不自欺，也不把一时冲动当作永远正确。
- **事上磨：** 在日常事务中练习，不把承受伤害当成修养。
- **立志与改过：** 有方向，允许犯错、补救与重新开始。
- **龙场主题：** 谈困境与自处，承认现实限制，保留行动与求助的空间。

默认温和、直率，以现代中文交流。可以聊天，也可以深入分析；不会每次都套同一张清单。普通史实查询不会自动进入角色。

<a id="sources"></a>

## 📚 原典与资料

原典入口、核验范围和待核实项见 [sources.md](wang-yangming-perspective/references/sources.md)。概念说明见 [teachings.md](wang-yangming-perspective/references/teachings.md)，困境对话设计见 [longchang.md](wang-yangming-perspective/references/longchang.md)。

本版核对了四个原典网页中的相关段落，未做全集校勘。龙场悟道的年谱情节尚未逐条核验，不据此编造当夜独白，也不把晚年的全部思想集中成一次神奇顿悟。历史文本、白话解释和当代建议须区分。

<a id="structure"></a>

## 🗂️ 仓库结构

```text
wang-yangming-skill/
├── README.md
├── LICENSE
└── wang-yangming-perspective/
    ├── SKILL.md
    ├── agents/openai.yaml
    └── references/
        ├── teachings.md
        ├── longchang.md
        └── sources.md
```

<a id="contributing"></a>

## 🤝 一起完善

如果你愿意，可以在 [Issues](https://github.com/wangxingjian703-coder/wang-yangming-skill/issues) 分享实际试聊的问题与回答，或通过 PR 补充原典出处、纠正理解、改进对话。

内容结构已做本地检查；角色表现受所用模型影响，尚未经过独立模型行为评测。

---

<a id="license"></a>

## 📄 开源许可

本项目原创指令、说明与现代示例采用 [MIT License](LICENSE)。所链接原典及第三方网站内容的权利状态依其各自说明；本许可不覆盖第三方译注与编辑内容。
