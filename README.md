<div align="center">

# 陈丹青.skill

> *「什么叫做救自己呢？就是忠实自己的感觉，认真做每一件事，不要烦，不要放弃，不要敷衍。」*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Agent Skills](https://img.shields.io/badge/Agent%20Skills-Standard-green)](https://agentskills.io)
[![Multi-Runtime](https://img.shields.io/badge/Runtime-Claude%20Code%20·%20Codex%20·%20Cursor%20·%20OpenClaw%20·%20Hermes-blueviolet)](#安装)
[![Nuwa](https://img.shields.io/badge/Made%20with-女娲.skill-orange)](https://github.com/alchaincyf/nuwa-skill)

<br>

**陈丹青式文化观察视角。不是语录合集，也不是本人模拟，是可运行的思维框架。**

**A Chen Danqing-style cultural-analysis lens for AI agents** — mental models, heuristics and voice DNA distilled from 10+ books and 20+ interviews. Perspective, not impersonation.

<br>

基于10+本著作、20+篇深度访谈与节目实录、50+条一手语录、<br>
8个关键决策记录和完整人生时间线的深度调研，<br>
提炼5个核心心智模型、8条决策启发式和完整的表达DNA。使用时保留“不冒充本人、不编造语录、事实先核查”的边界。

[看效果](#效果示例) · [安装](#安装) · [蒸馏了什么](#蒸馏了什么) · [边界](#边界) · [调研来源](#调研来源)

</div>

---

## 效果示例

### 问：现在年轻人都在考公考编，你怎么看？

```
丹青视角  ❯ 我跟你讲，这件事呢，我不好说什么。

            但是你看，我一个上海长大的小孩，16岁就被弄到农村去了，
            那时候也想找个铁饭碗，谁不想呢？后来能考进美院，
            那是运气。不是每个人都有这个运气。

            但是呢，现在这个考公热，你往回看——八九十年代，
            大家往体制外跑，下海经商，多热闹。现在倒过来了，
            全往里挤。这说明什么？说明外面不安全了。

            我不是说考公不对，你们得活嘛。我只是觉得，
            当一个社会里所有年轻人都往一个方向挤的时候，
            这个社会一定出了什么问题。

            不是你们的问题，是这个时代的问题。
```

### 问：我觉得自己什么都看不懂，艺术也好文学也好，觉得自己很没文化

```
丹青视角  ❯ 什么叫做有文化？你看过什么、感受过什么，
            那才是你的。

            我在纽约头几年也什么都看不懂。站在博物馆里，
            伦勃朗的画就在那儿，我看不出好在哪。
            但我就站着看，看了好几年，有一天突然就看见了。

            你不需要先读一本书才能看画。
            好看就是好看，不好看就是不好看。
            这个判断不需要专家帮你做。

            你觉得看不懂，那是因为你已经在试图"懂"了。
            别试图懂，先看。看够了，自然就懂了。

            讯息不等于眼界。眼界是靠看的，不是靠刷的。
```

---

## 安装

### Claude Code / Codex / Cursor / OpenClaw / Hermes

```bash
git clone https://github.com/xiaogege6697/chendanqing-skill.git

# Claude Code（项目级，随仓库走）
mkdir -p .claude/skills && cp -r chendanqing-skill .claude/skills/

# 通用目录（Codex / Cursor / 其他 agent 框架）
mkdir -p ~/.agents/skills && cp -r chendanqing-skill ~/.agents/skills/

# OpenClaw / Hermes
mkdir -p ~/.openclaw/skills && cp -r chendanqing-skill ~/.openclaw/skills/
```

或者手动：
1. 下载 `SKILL.md`
2. 放到你的 Agent Skills 目录下
3. 重启或重新加载即可

## 触发方式

安装后直接对 agent 说：

- 「用陈丹青的视角看看……」「丹青怎么看」「陈丹青模式」
- 「切换到丹青」「如果陈丹青会怎么说」「老克勒视角」

退出视角：「退出」「切回正常」「不用丹青视角」。

---

## 蒸馏了什么

| 维度 | 内容 |
|------|------|
| **核心心智模型** | 说真话作为底线、常识优先、记忆即抵抗、拒绝被规训、眼界高于知识 |
| **决策启发式** | 8条（看见了吗检验、历史上怎么样、常识通不通、谁受益追问、别装自检、好好看原则、体面底线、一步一步救自己） |
| **表达DNA** | 老克勒语气、长句短句交替、冷幽默自嘲、不用学术术语、历史掌故信手拈来 |
| **人生时间线** | 16个关键节点：插队→央美→西藏组画→纽约18年→清华辞职→木心→《局部》 |
| **内在矛盾** | 精英立场vs为大众说话、民国滤镜、说真话的表演性、体制内外的张力 |

---

## 谁适合用

- 想用陈丹青的视角分析文化、教育、社会现象的人
- 需要直率、反套路的第二意见的人
- 想了解中国当代知识分子精神谱系的人
- 喜欢"不装"的人

## 边界

这个 Skill 是公开资料蒸馏出的文化分析视角，不是陈丹青本人，也不代表他的当前私人观点。

- 不冒充本人：用“陈丹青式视角”表达，不声称“我就是陈丹青”
- 不编造语录：可以写“风格化表达”，但必须标明不是原话
- 事实先核查：涉及艺术史、政策、人物、新闻和具体作品时，先查证或标注不确定
- 不借权威压人：观点要靠观察和理由成立，不靠“陈丹青说了算”

详细契约见 [`docs/core-boundary.md`](docs/core-boundary.md)。

---

## 调研来源

### 一手来源
- 《纽约琐记》《退步集》《荒废集》《笑谈大先生》《谈话的泥沼》《无知的游历》《陌生的经验》等
- 《局部》第一、二、三季
- 给清华大学美术学院的辞职报告（2004）
- 《锵锵三人行》《圆桌派》节目实录

### 二手来源
- 与周小辣对话录
- 凤凰网、南都周刊等媒体专访
- 中央美术学院艺术资讯网人物档案

---

## License

MIT，见 [LICENSE](LICENSE)。

## 相关项目

- [tcm-db](https://github.com/xiaogege6697/tcm-db) — 倪海厦中医知识数据库（3,867 条记录 + 2,987 张板书 OCR 转录）
- 更多 AI Skills 见 [github.com/xiaogege6697](https://github.com/xiaogege6697)

---

## 致谢

- 本 Skill 使用 [女娲.skill](https://github.com/alchaincyf/nuwa-skill)（作者：花叔）蒸馏方法论生成
- 参照 [张雪峰.skill](https://github.com/alchaincyf/zhangxuefeng-skill) 的仓库格式

---

<div align="center">

**什么叫做救自己呢？忠实自己的感觉，认真做每一件事。**

</div>
