# 我的世界 · 资源档案馆

一个纯静态的单页资源下载站：动态壁纸背景、蓝奏云下载入口、响应式排版。

## 技术

- 原生 HTML / CSS / JS，无构建步骤
- 桌面端 1440×810、移动端 960×540 动态背景，自动切换
- `prefers-reduced-motion` 下自动回退静态封面
- 所有资源本地托管，不依赖第三方 CDN

## 本地预览

直接用浏览器打开 `index.html`，或：

```bash
python -m http.server 8080
```

## 部署

Cloudflare Pages：

- Framework preset：None
- Build command：留空
- Build output directory：`/`

站点入口为根目录的 `index.html`。
