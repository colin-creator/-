# 生信刷题神器

这是北京协和医学院应用生物信息学课程中出现过的习题整理，不懂考试会不会有原题，但是我就复习这些了，希望老师高抬贵手。

## 在线访问

GitHub Pages 地址：https://colin-creator.github.io/-/

> 仓库名为 `-`（一个横杠）。首次发布需在 Settings → Pages → Build and deployment 中将 Source 设为 GitHub Actions，并确认部署工作流成功。

原 Netlify 地址：https://pumcbioinfoquiz.netlify.app/

## 本地使用

下载 `index.html`，用浏览器打开即可使用。

## 功能特点

- 移动端界面
- 刷题与背题模式
- 即时答案反馈和解析
- 收藏夹、错题本与题目进度显示

## 部署

推送到 `main` 或在 Actions 中手动运行 `Deploy to GitHub Pages`。工作流使用 `contents: read`、`pages: write` 和 `id-token: write`，部署至 `github-pages` 环境。
