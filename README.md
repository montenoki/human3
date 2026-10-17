# human3

HUMAN 3.0 成长测评的 Claude Code skill（中文）。

它按心智、身体、精神、事业四个象限逐个访谈，判断每个象限的层级和阶段，最后生成一份单文件 HTML 报告：元类型、生活方式原型、四象限地图、核心问题、成长方案和立即行动。

## 出处

HUMAN 3.0 模型和最初的测评 prompt 来自 Dan Koe：[HUMAN 3.0 – A Map To Reach The Top 1%](https://letters.thedankoe.com/p/human-30-a-map-to-reach-the-top-1)。本仓库是它的中文本地化和 skill 封装，版权归原作者。

## 文件

| 文件 | 内容 |
|---|---|
| `SKILL.md` | 测评流程 |
| `MODEL.md` | 模型知识库 |
| `GLOSSARY.md` | 中英术语对照表 |
| `report-template.html` | 报告模板 |
| `PRODUCT.md`、`DESIGN.md` | 报告的设计定位和设计规则（impeccable 使用） |

## 使用

把本目录链接或复制到 `~/.claude/skills/human3`，然后在 Claude Code 里输入 `/human3`。
