# AnWen Docs

一个基于 **VuePress 2 + VuePress Theme Hope** 的个人文档站源码仓库，用于整理和发布长期积累的笔记、收藏与专题内容。

> Repository: `anwen-anyi.github.io`  
> Status: Personal documentation site

## 技术栈

- Vue 3
- VuePress 2
- VuePress Theme Hope
- Vite bundler
- Mermaid / KaTeX / ECharts / Chart.js
- PWA、搜索与多媒体相关 VuePress 插件

## 开发

安装依赖后启动本地文档站：

```bash
npm install
npm run docs:dev
```

构建静态站点：

```bash
npm run docs:build
```

如需清理缓存后启动：

```bash
npm run docs:clean-dev
```

## 目录

```text
anwen-anyi.github.io/
├── src/
│   ├── .vuepress/   # VuePress 配置与主题
│   ├── README.md    # 文档站首页
│   ├── collect/     # 收藏 / 整理内容
│   ├── index/       # 索引内容
│   └── other/       # 其他专题
├── package.json
└── pnpm-lock.yaml
```

## 说明

这是内容型仓库，不作为软件产品或独立工具展示。根 README 主要用于说明如何维护文档站；真正的站点内容位于 `src/`。
