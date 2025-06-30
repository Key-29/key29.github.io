# key29.github.io

> **Take Down the CCP – 一个去中心化认知战网站**

这是一个以极简高效的静态网站为载体，聚焦对中共认知作战的内容发布、策略分享与工具集成的平台。

## 🎯 项目定位

- 利用 GitHub Pages 和 Gridea 实现 **零服务器成本**的内容发布
- 提供 **认知战术提示词、心理操控话术、战略分析文章**
- 全部内容开源透明，支持 fork 和再创作
- 面向全球用户的中文与多语言传播

## 🛠 技术栈

- **Gridea**：本地内容生成器
- **Markdown**：主内容格式
- **GitHub Pages**：静态托管
- **自定义域名（可选）**：支持绑定独立域名

## 🚀 部署与更新

1. 本地使用 Gridea 写作
2. 通过 Personal Access Token 自动推送到 `main` 分支
3. GitHub Pages 自动构建并发布

### 快速部署

如果你想 fork 并二次构建：

```bash
git clone https://github.com/key-29/key29.github.io.git
cd key29.github.io
# 编辑内容
# 推送到 main 分支
git add .
git commit -m "Update content"
git push origin main
