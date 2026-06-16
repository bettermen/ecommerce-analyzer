# 🛒 ecommerce-analyzer

电商多平台商品数据分析助手 - WorkBuddy Skill

输入一个商品链接，自动生成跨平台（京东/淘宝/拼多多/抖音电商/1688/苏宁易购）对比分析报告。

## 核心功能

- **链接智能解析** - 自动识别主流电商平台链接
- **商品详情提取** - 价格、规格、评分、评价、店铺信息
- **跨平台搜索** - 自动搜索同款在各平台的售卖情况
- **多维度对比** - 价格/评分/评价数/店铺信誉全方位对比
- **可视化报告** - 交互式HTML报告，含KPI卡片、图表和购买建议

## 技能结构

```
ecommerce-analyzer/
├── SKILL.md                  # 技能定义 & 工作流程
└── scripts/
    └── generate_report.py    # HTML报告生成器
```

## 使用方式

在 WorkBuddy 中输入商品链接即可：

```
分析这个商品：https://item.jd.com/100012345678.html
```

## 覆盖平台

| 平台 | 域名 | 状态 |
|------|------|------|
| 京东 | jd.com | ✅ |
| 淘宝/天猫 | taobao.com / tmall.com | ✅ |
| 拼多多 | pinduoduo.com | ✅ |
| 抖音电商 | douyin.com / jinritemai.com | ✅ |
| 1688 | 1688.com | ✅ |
| 苏宁易购 | suning.com | ✅ |
| 唯品会 | vip.com | ✅ |

## 技术栈

- Python 3.13+
- Chart.js (CDN)
- GitHub Contents API

## 版本

v1.0.0 - 2026-06-16
