# 2024 Washington Chinese Culture Festival
## 鸣谢赞助商 · Sponsor Recognition Package

## 文件说明 / Files

| 文件 | 用途 |
|------|------|
| **index.html** | ⭐ 响应式赞助商 logo 墙（推荐主页面）。47 个 logo，自适应桌面/平板/手机 |
| **logos/** | logo 图片文件夹（index.html 引用，请勿删除或移动） |
| **organizers.html** | 9 个主办单位（中英文 + 缩写）独立页面 |
| **sponsors_text.html** | 文字版赞助商名单（按行业分类） |
| **sponsors_poster.png** | 高清海报版（1520×1850 px），可直接打印 |

## 怎么使用 / How to Use

**本地查看** — 双击 `index.html` 在浏览器打开即可。手机上把整个文件夹传过去，用文件管理器打开 `index.html`。

**上传网站** — 把所有文件（含 `logos/` 文件夹）一起上传到网站根目录或子目录。

**打印** — 三个 HTML 页面都已优化打印样式（去除阴影、保留分栏），用浏览器 Ctrl/Cmd+P 直接打印；或用 `sponsors_poster.png` 印刷。

**微信公众号** — 推荐直接发 `sponsors_poster.png` 图片，最方便。HTML 版本需要先放到自己的服务器。

## 修改提示 / Editing Notes

- 替换 logo：用同名文件替换 `logos/` 里的 PNG 即可，HTML 无需改动
- 改文字（标题、致谢语等）：直接编辑对应 HTML 文件顶部的 `<header>` 和 `<footer>` 段
- 改颜色：HTML 顶部 `:root` 里有 `--accent`（红色）、`--paper`（米色）等变量，改一处全局生效

---
With sincere appreciation · 谨此致谢
