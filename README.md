# 🎨 Product Prototypes

> 自然选择号 · 产品原型展示仓库  
> 由 Product Station 自动生成和部署

---

## 📋 概述

本仓库用于存储和展示 Product Station 生成的产品交互原型。

所有原型通过 **GitHub Pages** 自动部署，可通过以下链接访问：

**https://caddyliu.github.io/product-prototypes/**

---

## 📁 目录结构

```
prototypes/
├── YYYY-MM-DD-{项目简称}/
│   ├── index.html          # 原型文件
│   └── metadata.json       # 元数据
└── ...
```

---

## 🚀 自动部署

### 工作流程

1. Product Station 生成原型 → 推送到本仓库
2. GitHub Actions 自动检测 `prototypes/` 目录变化
3. 自动部署到 GitHub Pages
4. 生成访问链接

### 部署时间

通常在推送后 **30-60 秒** 内完成部署。

---

## 📊 元数据格式

每个原型目录包含 `metadata.json`：

```json
{
  "ideaId": "idea-2026-03-16-001",
  "title": "AI 驱动的待办事项应用",
  "theme": "dark-tech",
  "pages": 3,
  "createdAt": "2026-03-16T10:00:00Z",
  "prdVersion": "v1.0",
  "previewUrl": "https://caddyliu.github.io/product-prototypes/2026-03-16-todo-app/"
}
```

---

## 🎨 原型主题

支持 8 种视觉主题：

| 主题 | ID | 适用场景 |
|------|-----|---------|
| 🍼 贴纸可爱 | `sticker-cute` | 母婴/萌宠/儿童 |
| 💼 商务专业 | `biz-pro` | 企业 OA/CRM/B2B |
| 🌿 清新自然 | `fresh-nature` | 健康/运动/冥想 |
| 🌙 暗夜科技 | `dark-tech` | AI/工具/数据 |
| 🎀 少女梦幻 | `girly-dream` | 美妆/社交/日记 |
| 🏛️ 极简素雅 | `minimal-elegant` | 阅读/笔记/奢侈品 |
| 🔥 活力潮流 | `vibrant-pop` | 电商/外卖/社区 |
| 🎓 学院知性 | `academic-smart` | 教育/课程/知识 |

---

## 🔧 技术栈

- **HTML** - 单文件原型（CSS 内联）
- **GitHub Pages** - 静态托管
- **GitHub Actions** - 自动部署

---

## 📬 相关项目

- **Product Station** - 产品工作站
- **Scout Station** - 情报收集
- **Creator Station** - 内容创作

---

*由 Product Station 自动生成 | 自然选择号*
