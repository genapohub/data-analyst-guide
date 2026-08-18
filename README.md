# Data Analyst Guide — 数据分析师方案产出指南

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Version](https://img.shields.io/badge/version-1.0.0-green.svg)](SKILL.md)

一个面向 AI 编程助手的 **数据分析师 Skill**，将数据分析方法论转化为可执行工作流。自动识别 5 类场景（0→1 数据体系搭建 / 中大型分析需求 / 小分析临时取数 / 数据基础设施升级 / 数据探索洞察），按对应清单产出指标体系、埋点方案、BI看板、AB实验方案等完整交付物。

## 适用场景

| 场景 | 示例 | 产出量 |
|------|------|:---:|
| 0→1 数据体系搭建 | 新产品全链路数据基础设施 | 10-12类 |
| 中大型分析需求 | 用户画像、归因分析、LTV建模 | 6-8类 |
| 小分析/临时取数 | 单指标波动分析、活动复盘 | 2-3类 |
| 数据基础设施升级 | 数仓重构、BI工具迁移、实时数仓 | 8-10类 |
| 数据探索/洞察 | 用户行为模式发现、业务洞察 | 3-4类 |

## 触发热词

数据分析、数据体系、埋点、AB实验、BI看板、数据仓库、指标体系、数据报告、用户画像、归因分析

---

## 安装

本 Skill 遵循 **Open Agent Skills 标准**（SKILL.md 格式），兼容以下工具：

### WorkBuddy / CodeBuddy

**方式一：克隆到 skills 目录**
```bash
git clone https://github.com/genapohub/data-analyst-guide.git ~/.workbuddy/skills/data-analyst-guide
```

### Trae

**ZIP 导入**
```bash
git clone https://github.com/genapohub/data-analyst-guide.git
zip -r data-analyst-guide.zip data-analyst-guide/
```
然后在 Trae → **设置** → **Rules & Skills** → **创建** → 上传 `data-analyst-guide.zip`。

### Codex

```bash
# 克隆到 skills 目录
git clone https://github.com/genapohub/data-analyst-guide.git ~/.codex/skills/data-analyst-guide

# 或使用 cc switch (推荐)
git clone https://github.com/genapohub/data-analyst-guide.git ~/.cc-switch/skills/data-analyst-guide
```

若选 CC Switch 克隆后需在cc switch客户端-技能中心里导入技能，选中Codex等工具，重启Codex客户端后在对话中输入 $data-analyst-guide 手动调用。

### Cursor
```bash
# 克隆到 skills 目录
git clone https://github.com/genapohub/data-analyst-guide.git ~/.cursor/skills-cursor/data-analyst-guide
```

重启 Cursor客户端 后自动发现。也可以在对话中输入 `$data-analyst-guide` 手动调用。

---


## 特性

- 5 类场景自动路由识别，产出清单按场景裁剪
- **内置可填空模板**：方法论内置「专题分析报告 / SQL 取数」，产出时按占位符直接填充，文档规范度对齐业界标准

---

## 使用

```
帮我搭建新产品的数据指标体系
设计用户行为埋点方案
这个指标的波动是什么原因
新功能上线，帮我设计AB实验方案
```

## 许可

[MIT](LICENSE) © zhangmengbo
