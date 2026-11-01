# 🌍 worldmonitor 日报 | {{date}} {{weekday}}

> 自动生成于 {{generate_time}} | 数据来源：微博热搜 · 知乎热榜 · 百度热搜 · 抖音热点

---

## 📌 今日重点关注

{{highlights}}

---

{{#each sections}}

## {{icon}} {{name}}

{{#each items}}
### {{rank}}. {{title}}

| 指标 | 数值 |
|------|------|
| 🔥 热度 | {{hot_score}} |
| 📈 趋势 | {{trend}} |
| 📰 来源 | {{sources}} |

**📝 AI 评价分析：**

{{analysis}}

{{/each}}

---

{{/each}}

## 📊 今日总览

- 共收录热点：**{{total_count}}** 条
- 涉及板块：**{{section_count}}** 个
- 热度最高：**{{top_hot.title}}**（{{top_hot.score}}）

---

*本报告由 worldmonitor 自动生成，仅供参考*
