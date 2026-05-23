# 训练计划 · {{PLAN_NAME}}

## 基本信息
| 字段 | 内容 |
|------|------|
| 训练目标 | {{GOAL}} |
| 训练频率 | 每周 {{FREQUENCY}} 天 |
| 计划周期 | {{DURATION}} |
| 训练水平 | {{LEVEL}} |
| 可用设备 | {{EQUIPMENT}} |

---

{{#each TRAINING_DAYS}}
## {{day_name}}（{{muscle_focus}}）

### 热身 · 5-10 分钟
{{warmup}}

### 主要动作
| 动作 | 组数 | 次数/时间 | 建议重量 | 组间休息 |
|------|------|-----------|----------|----------|
{{#each main_exercises}}
| {{name}} | {{sets}} | {{reps}} | {{weight_guide}} | {{rest}} |
{{/each}}

### 辅助动作
| 动作 | 组数 | 次数 | 组间休息 |
|------|------|------|----------|
{{#each accessory_exercises}}
| {{name}} | {{sets}} | {{reps}} | {{rest}} |
{{/each}}

### 拉伸 · 5 分钟
{{cooldown}}

---
{{/each}}

## 渐进原则
{{PROGRESSION_GUIDE}}

## 注意事项
{{NOTES}}