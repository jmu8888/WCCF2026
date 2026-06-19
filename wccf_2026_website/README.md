# 华盛顿中国文化节 2026 · 网站
**Washington Chinese Culture Festival · Multi-Page Site**

第 24 届华盛顿中国文化节官方网站（多页面版本）。

---

## 文件结构

```
site_v2/
├── index.html         首页 · Home · Portal
├── experience.html    文化体验 · 五大体验 + 十大体验站
├── stages.html        两大舞台 · 主舞台 + 互动舞台 + 时间表
├── cuisine.html       舌尖上的中国 · 八大风味 + 五味 + 必吃清单
├── visit.html         参与攻略 · 时间地点 + 三大亮点 + 交通 + FAQ
├── organizers.html    主办单位 · 9 大主办机构
├── sponsors.html      鸣谢赞助商 · 44 家赞助商（按类分组）
├── styles.css         共用样式表（设计令牌 + 导航 + 页脚 + 通用组件）
├── logos/             47 个 PNG 图标（赞助商 + 节日吉祥物熊猫）
└── README.md          本文件
```

---

## 页面导航流

```
Home ─ Experience ─ Stages ─ Cuisine ─ Visit ─ Organizers ─ Sponsors
                                                                 ↓
                                                            （回到首页）
```

每页底部都有 prev/next 卡片链接，可顺序浏览。顶部固定导航栏可任意跳转。

---

## 设计系统

**配色 · Palette**
- 中国红 `#B91C1C` / 红深 `#7F1010`
- 古铜金 `#C4933E` / 浅金 `#E2C485`
- 墨 `#1F1B16` / 米色书纸 `#FAF7F1` `#F2ECDE`

**字体 · Typography**
- 中文标题 — Noto Serif SC（思源宋体 SC）
- 英文标题 — Cormorant Garamond（带斜体强调）
- 正文 — Noto Sans SC（思源黑体 SC）

**关键技术**
- 纯静态 HTML + CSS（无构建步骤、无依赖）
- `clamp()` 实现的流体字号
- CSS Grid + `auto-fit minmax()` 响应式布局
- IntersectionObserver 滚动渐入动画
- 移动端导航折叠为汉堡菜单（≤980px）

---

## 如何使用

直接双击 `index.html` 在浏览器里打开即可。或上传到任意静态托管（Netlify、Vercel、GitHub Pages、Cloudflare Pages 都开箱即用）。

无需 Node、无需 npm、无需服务器。

---

## 内容来源

所有文案基于官方 Promotion Article。9 家主办、44 家赞助商列表与对应 logo 来自活动方提供的赞助名单视觉资料。

---

© 2026 Washington Chinese Culture Festival
