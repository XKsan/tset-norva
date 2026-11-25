# NORVA STUDIO 网站 v2（多页面版）

结构：
- index.html —— 首页：水面首屏 + 今日一事条 + 星图导航
- assets/pages/ —— 8 个独立页面：onething.html（今日一事）、experiments.html（实验 4 件）、originals.html（antmonologue）、products.html（5 个系统）、archive.html（放映室＋归山记录）、method.html（方法·身语意）、projects.html（委托）、contact.html（联系）
- assets/onething/today.json —— 今日一事当日条目（只显示当日一条）
- .nojekyll —— 让 GitHub Pages 不走 Jekyll

上传：把本包全部文件解压到 GitHub 仓库根目录，覆盖旧文件。仓库已开 Pages（main 分支、根目录）的话，推送后约 1 分钟生效，网址不变：https://xksan.github.io/tset-norva/

每日更新今日一事：只换 assets/onething/today.json 一个文件（去旧站 https://xksan.github.io/one-thing-live/ 取当日条目），其他文件不用动。

注意：
- 全站不写价格；联系邮箱 tbmax.in@hotmail.com，微信 HMC-NORVA。
- 字体为本地系统字体栈，不依赖 Google Fonts。
- 首页不放标语；「从现实需求出发，在创作与技术之间持续探索。」只在方法页。
