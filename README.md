# NORVA STUDIO 网站源码

- `index.html`：全站（CSS 与 JS 均内联在内），GitHub Pages 入口。
- `assets/onething/today.json`：今日一事当日条目（当前为 2026-11-24「章鱼实时编辑RNA」）。
- `.nojekyll`：告诉 GitHub Pages 不用 Jekyll 处理。

部署：把以上文件（保持目录结构）传到 GitHub 仓库根目录，开 GitHub Pages 即可。

每日更新：只改 `assets/onething/today.json` 一个文件。

待办：每日自动生成工作流（generate.py + .github/workflows/daily.yml）尚未移入本仓库，仍在 one-thing-live 仓库；移入时要改 today.json 路径并补第 9 类科技与 AI。
