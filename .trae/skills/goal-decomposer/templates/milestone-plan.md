# Milestone 计划 · {{GOAL_NAME}}

## 总览
- **开始时间**：{{START_DATE}}
- **目标完成**：{{END_DATE}}
- **总周期**：{{DURATION}}

---

{{#each MILESTONES}}
## Milestone {{index}}: {{title}}
> 目标完成时间：{{due_date}}
> 完成标志：{{completion_sign}}

### 行动任务
{{#each actions}}
- [ ] {{task}} `预估：{{time_cost}}`
{{/each}}

---
{{/each}}

## 风险提示
{{#each RISKS}}
- {{this}}
{{/each}}