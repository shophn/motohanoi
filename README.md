# Motorbike Nguyen Ha · 中文摩托车出行指南

独立设计的静态中文站点框架，采用简洁、精致的 Apple-inspired 视觉语言；不是 EN/FR/VN 仓库的复制品。

## 当前状态

- 网站框架已包含：`index.html`、`guides/index.html`、CSS、JS、SVG favicon、404 页面。
- 语言：简体中文 `zh-CN` / Open Graph `zh_CN`。
- 主题色：
  - Background `#F5F5F7`
  - White `#FFFFFF`
  - Title `#1D1D1F`
  - Text `#6E6E73`
  - Border `#D2D2D7`
  - Accent `#0071E3`
- 纯 HTML/CSS/JS，无付费 API、无构建依赖，支持 GitHub Pages 项目子路径和手机布局。
- 所有联系方式归属于 **Motorbike Nguyen Ha**，与 Nguyễn Tú 品牌完全分开。

## 站点结构

```
index.html                  Homepage
guides/index.html           Practical travel/rental guide
assets/styles.css           Responsive design system
assets/app.js               Accessible mobile menu & footer year
assets/favicon.svg          Original brand mark
404.html                    Fallback page
.nojekyll                   Disable Jekyll processing
.github/workflows/pages.yml GitHub Pages deployment
```

## 发布前检查

1. GitHub → Settings → Pages → Build and deployment → Source: **GitHub Actions**（若尚未启用）。
2. 首先确认 GitHub Pages 项目地址可打开，且首页及 `guides/` 页面、移动端菜单、联系按钮可正常使用。
3. **尚未确认 `zh.rentbikehanoi.com` DNS 和自定义域名，因此没有写入 CNAME。** 待 Hostinger 配置完成后，再在 GitHub Pages Settings 绑定自定义域名并按 GitHub 文档调整 DNS。
4. **当前两份 HTML 都带有 `noindex, follow`**，避免未完成的新站被过早收录。正式上线、内容及域名检查后，人工确认移除 noindex 并补充 sitemap/canonical/hreflang。
5. 检查实际报价、租车合同、车型、押金与中文文字客服能力；不把未经核实的数字写成固定承诺。

## 联系信息 / NAP

Motorbike Nguyen Ha · Ngõ 5 Nguyễn Văn Cừ, Bồ Đề, Long Biên, Hà Nội, Việt Nam

电话：+84 334 699 969 | Zalo: https://zalo.me/0334699969 | WhatsApp: https://wa.me/84334699969

官方网站：https://rentbikehanoi.com/

营业时间：09:00–21:00，每日。

## 编辑规范

- 原创、有帮助的简体中文内容，避免机器式批量翻译和低价值的 SEO 页面。
- 不照搬或批量复制其他语言仓库。
- 任何押金、价格、证件要求、交车政策和越南法律条款，发布前均须核实。
- 品牌及所有联系信息仅使用 Nguyen Ha 的官方信息。
