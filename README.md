# 灵犀指标平台

灵犀指标平台是一个企业级数据指标管理系统的高保真前端原型，旨在提供直观、高效的指标定义、管理和分析体验。

## 项目概述

本项目是一个纯前端原型，使用HTML、TailwindCSS和JavaScript实现，不依赖后端服务。数据通过浏览器的localStorage在不同页面间共享，实现了基本的增删改查功能。

## 功能特点

- **指标管理**：创建、查看、编辑和删除数据指标
- **维度管理**：支持创建和管理业务维度，与指标关联
- **多视图展示**：支持卡片式和表格式两种指标浏览模式
- **指标详情**：展示指标的基本信息、趋势分析、SQL说明、使用记录等
- **多维分析**：支持按不同维度分析指标数据
- **维度筛选**：实现了现代化的多选组件，方便选择和管理维度

## 项目结构

- `index.html` - 指标列表主页
- `metric-detail.html` - 指标详情页
- `dimension.html` - 维度管理页面
- `create-metric.html` - 指标创建页面
- `sidebar.html` - 全局侧边栏组件
- `package.json` - 项目配置文件
- `README.md` - 项目说明文件
- `# 灵犀指标平台.md` - 原始产品需求文档

## 开发环境设置

1. 克隆仓库：
```bash
git clone https://github.com/villian1992/lingxi-indicator-platform.git
cd lingxi-indicator-platform
```

2. 安装依赖：
```bash
npm install
```

3. 启动开发服务器：
```bash
npm run dev
```

这将启动一个开发服务器，并自动在浏览器中打开项目。当您修改任何HTML文件时，浏览器会自动刷新。

## 技术栈

- **HTML5** - 页面结构
- **TailwindCSS** - 样式和布局
- **JavaScript** - 交互逻辑
- **Font Awesome** - 图标库
- **ECharts** - 图表展示
- **localStorage** - 本地数据存储

## 部署说明

本项目是纯静态网站，可以部署在任何支持静态网站的服务上，如GitHub Pages、Vercel、Netlify等。

## 浏览器兼容性

- Chrome (推荐)
- Firefox
- Safari
- Edge

## 许可证

MIT 