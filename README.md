# 刘紫琼 · 个人作品集网站

纯静态 HTML 个人作品集站点，无需构建工具、无需虚拟环境。

## 🚀 本地启动

Python 3 自带 HTTP 服务器，一行命令即可：

```bash
# 进入项目目录
cd f:\program\portfolio

# 启动本地服务（默认 8000 端口）
python -m http.server 8080
```

然后浏览器访问：

- 主页：http://localhost:8080/index.html
- 项目详情：http://localhost:8080/case.html

> 💡 想换端口？把 `8080` 改成你想要的数字就行。

## 📁 项目结构

```
portfolio/
├── index.html          # 主页（个人介绍 + 作品列表）
├── case.html           # 项目详情页（通过 ?id=xxx 访问）
├── assets/
│   ├── pdf/
│   │   └── 刘紫琼__Agent应用开发工程师.pdf   # 简历
│   ├── images/
│   ├── css/
│   └── js/
└── README.md
```

## 🛠 推送到 GitHub Pages

```bash
# 首次配置 origin（已完成）
git remote set-url origin https://github.com/LIU1-G/LIU1-G.github.io.git
git branch -M main

# 更新后推送
git add .
git commit -m "update"
git push
```

GitHub Pages 在仓库 Settings → Pages 中开启，分支选择 `main` 即可访问。

## 👤 关于我

**刘紫琼** · Agent应用开发工程师

- Gitee：[@liuziqiongwjk](https://gitee.com/liuziqiongwjk)
- GitHub Pages：[LIU1-G.github.io](https://github.com/LIU1-G/LIU1-G.github.io)

### 作品列表

| 项目 | Gitee 仓库 |
|------|-----------|
| 云创社综合平台 | [cloud-innovation-club](https://gitee.com/liuziqiongwjk/cloud-innovation-club) |
| VLA数据集可视化工具 | [vla_data](https://gitee.com/liuziqiongwjk/vla_data) |
| Leap AI 面试系统 | [leap-interview](https://gitee.com/liuziqiongwjk/leap-interview) |
| 数模辅助平台 | [math-agent](https://gitee.com/math-agent/math-agent) |
