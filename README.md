# Simple Resume Template

这是一个简洁的个人简历网站模板，使用原生 HTML 和 CSS 构建，适合展示个人简介、技能、经历、项目和联系方式。

## 页面预览

页面目前包含以下部分：

- 个人简介与简历入口
- 技能标签
- 教育和工作经历
- 项目列表
- 联系方式

页面中的姓名、经历、项目和邮箱均为示例内容。发布前请替换为你自己的信息。

## 项目结构

```text
simple_resume_template/
├── index.html             # 页面内容与结构
└── assets/
    └── css/
        └── styles.css     # 页面样式与移动端布局
```

## 本地预览

本项目是纯静态网页，无需安装依赖或执行构建步骤。

1. 下载或克隆项目。
2. 在浏览器中打开 `index.html`。

也可以在项目目录启动任意静态文件服务器，然后访问其提供的本地地址。例如，安装了 Python 的环境可以运行：

```bash
python -m http.server 8000
```

然后打开 <http://localhost:8000>。

## 个性化设置

### 修改页面内容

编辑 `index.html`，替换示例姓名、个人介绍、技能、经历、项目和联系邮箱。简历按钮、项目链接和联系链接当前使用占位链接（`#`），请改成实际地址。

### 修改样式

编辑 `assets/css/styles.css`，可以调整颜色、字体、间距、字号和移动端布局。文件开头的 CSS 自定义属性定义了页面的基础颜色：

```css
:root {
  --paper: #f6f6f4;
  --ink: #121212;
  --muted: #686864;
  --line: #d8d8d2;
}
```

## 部署到 GitHub Pages

1. 将项目推送到 GitHub 仓库。
2. 打开仓库的 **Settings → Pages**。
3. 在 **Build and deployment** 中选择从分支部署。
4. 选择包含 `index.html` 的分支和目录（通常为 `main` 与 `/(root)`），保存设置。
5. 等待 GitHub Pages 完成部署，再通过页面显示的网址访问网站。

## 技术栈

- HTML5
- CSS3
- 无外部依赖

## 许可证

本项目采用 [The Unlicense](https://unlicense.org)，将软件发布到公有领域。你可以自由使用、修改、分发，包括商业用途。完整条款见 [LICENSE](LICENSE)。

