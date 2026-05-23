# 训练进度报告 · {{PERIOD}}

## 训练出勤
- 计划训练天数：{{PLANNED_DAYS}} 天
- 实际完成天数：{{ACTUAL_DAYS}} 天
- 出勤率：{{ATTENDANCE_RATE}}%

## 主要动作进展
| 动作 | 周期初重量 | 当前重量 | 增幅 | 状态 |
|------|-----------|---------|------|------|
{{#each MAIN_LIFTS}}
| {{name}} | {{start_weight}}kg | {{current_weight}}kg | {{increment}}kg | {{status}} |
{{/each}}

## 训练容量趋势
{{VOLUME_TREND}}

## 下周调整建议
{{#each SUGGESTIONS}}
- {{this}}
{{/each}}