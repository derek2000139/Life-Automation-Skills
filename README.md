# Life Automation Skills

一套基于 AI 的个人生活自动化技能集，帮助你高效管理日常生活的各个方面。

## 包含的技能

| 技能 | 描述 | 触发词 |
|------|------|--------|
| [quick-journal](.trae/skills/quick-journal/README.md) | 极简日记助手，快速记录日常想法、事件和情绪 | `记录一下`、`今天`、`日记：` |
| [goal-decomposer](.trae/skills/goal-decomposer/README.md) | 目标拆解专家，将模糊愿望转化为可执行的里程碑计划 | `我想`、`我的目标是`、`帮我拆解` |
| [learning-assistant](.trae/skills/learning-assistant/README.md) | 学习方法专家，运用科学方法生成高质量学习材料 | `帮我学`、`用费曼法解释`、`帮我生成复习计划` |
| [fitness-planner](.trae/skills/fitness-planner/README.md) | 健身计划助手，制定训练计划、记录训练、追踪进度 | `帮我制定健身计划`、`我今天练了`、`记录训练` |

## 快速开始

在支持 AI 技能的平台（如 Trae）中，直接使用触发词调用对应技能即可。

```text
/fitness-planner 帮我制定一个减脂计划
/goal-decomposer 我想在年底存 5 万块
/quick-journal 记录一下：今天开了好多会
/learning-assistant 帮我学 JavaScript 闭包
```

## 项目结构

```
.trae/
└── skills/
    ├── quick-journal/          # 快速记录技能
    │   ├── SKILL.md            # 技能定义（含 YAML 配置）
    │   ├── README.md           # 使用说明
    │   ├── templates/          # 输出模板
    │   ├── resources/          # 资源文件（情绪标签等）
    │   └── examples/           # 输入输出示例
    ├── goal-decomposer/        # 目标拆解技能
    ├── learning-assistant/     # 学习助手技能
    └── fitness-planner/        # 健身计划技能
```

## 设计原则

- **本地优先**：所有数据存储在本地，不上传云端
- **务实直接**：不贩卖焦虑，不承诺不切实际的效果
- **可持久化**：每次交互的数据自动保存到本地 `data/` 目录
- **科学依据**：基于运动科学、认知心理学等已验证的方法论

## 授权

本项目采用 MIT 许可证。详见 [LICENSE](./LICENSE) 文件。