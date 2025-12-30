# 杭州牛书科技有限公司官网 - GitHub Pages 版

这是杭州牛书科技有限公司官网的静态版本，完全克隆了原网站的视觉效果和交互逻辑，专为 **GitHub Pages** 部署而优化。

## 📋 项目说明

本项目是对原 React 应用的静态化处理，保留了所有的视觉效果、动画和交互体验，同时适配了 GitHub Actions 自动部署流程。

## 📁 项目结构

```
niushu-github-pages/
├── index.html              # 主页面
├── assets/                 # 核心资源（CSS 样式、JS 逻辑）
├── images/                 # 所有的图片资源
├── .github/workflows/      # GitHub Actions 部署配置
│   └── static.yml          # 自动部署工作流
└── README.md               # 本文档
```

## 🎨 设计特色

- **深色科技风格**：深蓝色背景配合青色强调色
- **动态动画效果**：网格背景、粒子效果、滚动动画
- **响应式设计**：完美适配桌面、平板和移动设备
- **高性能**：优化的静态资源加载

## 📞 联系方式

- **公司名称**：杭州牛书科技有限公司
- **官网**：www.niubook.com
- **邮箱**：admin@niubook.com
- **电话**：188-5295-0819
- **地址**：浙江省杭州市西湖区灵隐街道惠民服务综合楼3257室

## 🚀 部署到 GitHub Pages

### 步骤 1：创建 GitHub 仓库

1. 登录 [GitHub](https://github.com)
2. 点击 "New" 创建新仓库
3. 填写仓库名称：`niushu-website`
4. 设置为 **Public**
5. 点击 "Create repository"

### 步骤 2：上传代码

```bash
# 进入项目目录
cd niushu-github-pages

# 初始化 Git 仓库
git init
git add .
git commit -m "🎉 Initial commit: 杭州牛书科技官网 GitHub Pages 版"

# 添加远程仓库（替换为您的仓库地址）
git remote add origin https://github.com/YOUR_USERNAME/niushu-website.git

# 推送代码
git branch -M main
git push -u origin main
```

### 步骤 3：开启 GitHub Pages

1. 进入 GitHub 仓库页面
2. 点击 **Settings** -> **Pages**
3. 在 **Build and deployment** -> **Source** 下选择 **GitHub Actions**
4. 部署会自动开始（查看 **Actions** 选项卡了解进度）

### 步骤 4：访问网站

部署成功后，访问：
```
https://YOUR_USERNAME.github.io/niushu-website/
```

## 💻 本地预览

```bash
# 使用 Python 启动本地服务器
python3 -m http.server 8000
```
然后在浏览器中访问：`http://localhost:8000`

---

© 2023-2025 杭州牛书科技有限公司 版权所有
