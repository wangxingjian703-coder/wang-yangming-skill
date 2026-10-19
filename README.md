# 王阳明 · 心学对话 Skill

以《传习录》《大学问》《教条示龙场诸生》为依据，用王阳明心学的视角分析问题，也陪你谈学习、选择、挫折与生活。

**在困境中重新立定自己，在具体事情上练习知行合一。**

这是基于文献的思想模拟，现代应用由本项目编写，不代表王阳明本人的真实发言。无需 API Key、外部服务或运行脚本；它向支持 Skill 的 AI 工具提供指令与参考资料。

## 可以怎样用

```text
用王阳明的视角，帮我看看：我很在意别人怎么看我，该怎么办？

阳明先生，我明明知道该学习，却总在逃避，想跟你聊聊。

龙场悟道让我振奋。处在不顺的阶段，我怎样重新立定自己？

用心学分析这个选择，但也请帮我检查现实条件与风险。

解释一下知行合一，并告诉我哪些是原文、哪些是现代应用。
```

## 安装到 Codex

### 让 Codex 安装

把本仓库网址发给 Codex，并说：

> 请使用 skill-installer，从这个仓库安装 wang-yangming-perspective 文件夹里的 Skill。

### 手动下载

1. 点击仓库的 **Code → Download ZIP**，解压。
2. 将 `wang-yangming-perspective` 整个文件夹复制到你的个人 Skills 目录。本机使用 `~/.codex/skills/`；若设置了 `CODEX_HOME`，则使用其 `skills/` 子目录。不同工具或版本的目录可能有差异。
3. 打开新对话；若尚未发现它，重启 Codex 后查看。文件夹内须直接包含 `SKILL.md`，不要重复嵌套一层同名文件夹。
4. 输入：

```text
$wang-yangming-perspective
陪我分析一下眼前的问题。
```

其他兼容 Agent Skills 的工具可复用核心 `SKILL.md` 和 `references/`，请按对应工具的安装方式放置。`agents/openai.yaml` 是可选的 Codex 界面元数据。

## 设计重点

- **心即理：** 辨认内心的价值与动机，同时认真调查事实。
- **知行合一：** 把理解落实到具体行动，再依据结果修正。
- **致良知：** 不自欺，也不把一时冲动当作永远正确。
- **事上磨：** 在日常事务中练习，不把承受伤害当成修养。
- **立志与改过：** 有方向，允许犯错、补救与重新开始。
- **龙场主题：** 谈困境与自处，承认现实限制，保留行动与求助的空间。

默认温和、直率，以现代中文交流。可以聊天，也可以深入分析；不会每次都套同一张清单。普通史实查询不会自动进入角色。

## 资料与边界

原典入口、核验范围和待核实项见 [sources.md](wang-yangming-perspective/references/sources.md)。概念说明见 [teachings.md](wang-yangming-perspective/references/teachings.md)，困境对话设计见 [longchang.md](wang-yangming-perspective/references/longchang.md)。

本版核对了四个原典网页中的相关段落，未做全集校勘。龙场悟道的年谱情节尚未逐条核验，不据此编造当夜独白，也不把晚年的全部思想集中成一次神奇顿悟。历史文本、白话解释和当代建议须区分。

内容结构已做本地检查；角色表现仍受所用模型影响，应通过真实对话继续改进。此 Skill 未经过独立模型行为评测。欢迎提交带具体问题与回答的 Issue，或通过 PR 补充可靠出处。

## 仓库结构

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

## 许可

本项目原创指令、说明与现代示例采用 [MIT License](LICENSE)。所链接原典及第三方网站内容的权利状态依其各自说明；本许可不覆盖第三方译注与编辑内容。
