# 刘紫琼 · 个人作品集

🔗 **在线访问：** https://liu1-g.github.io

---

个人静态作品集网站，展示个人简介、技术栈、项目案例与求职简历。原生 HTML + CSS + 少量 JS 实现，无框架、无构建、无任何依赖，纯静态页面直接托管于 GitHub Pages。

## ✨ 内容板块

- **个人简介** — 求职岗位与个人介绍
- **技术栈** — 13 项常用技术标签
- **项目案例** — 4 个代表性项目，点击卡片进入详情
- **简历下载** — PDF 版简历一键下载
- **移动端适配** — 响应式布局，手机访问自动适配

## 🛠 本地预览

无需安装任何工具，克隆后直接打开即可：

```bash
# 克隆仓库
git clone https://github.com/LIU1-G/LIU1-G.github.io.git

# 进入目录，双击 index.html 用浏览器打开
cd LIU1-G.github.io
```

> 💡 也可以用 Python 起一个本地服务：`python -m http.server 8000`

## 📂 目录结构

```
LIU1-G.github.io/
├── index.html              # 主页
├── case.html               # 项目详情页（case.html?id=xxx）
├── assets/
│   ├── images/             # 证件照等图片资源
│   └── pdf/                # 简历 PDF
└── README.md
```

## 📝 更新说明

推送到 `main` 分支后，GitHub Pages 自动部署：

```bash
git add .
git commit -m "update portfolio"
git push origin main
```

部署完成后约 1 分钟即可在 https://liu1-g.github.io 查看最新版本。
