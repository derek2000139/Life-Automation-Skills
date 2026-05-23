# 闪卡集 · {{TOPIC}}
生成时间：{{DATE}}
总数：{{TOTAL_COUNT}} 张

---

{{#each CARDS}}
## Card {{index}} · {{difficulty}}

**Q: {{question}}**

<details>
<summary>查看答案</summary>

{{answer}}

</details>

---
{{/each}}