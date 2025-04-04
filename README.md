# Theme Modern Starter

Halo-Theme-Curve是一款集成了现代前端技术栈的 Halo 2.x 的主题博客。
该主题移植自 imsyy 的 vitepress-theme-curve 主题，是借鉴于 Hexo 社区中 张洪 Heo 对 Hexo-Theme-Butterfly 主题的魔改版本。

主题开发文档可查阅：<https://docs.halo.run/2.0.0-SNAPSHOT/developer-guide/theme/prepare>

## 特性

- 使用 [Vite](https://vitejs.dev/) 进行静态资源构建。
- 使用 [Tailwind CSS](https://tailwindcss.com/) 进行样式开发。
- 使用 [@tailwindcss/typography](https://tailwindcss.com/docs/typography-plugin) 作为内容样式。
- 使用 [Iconify](https://iconify.design/) + [@iconify/tailwind](https://iconify.design/docs/usage/css/tailwind/#installation) 作为图标方案。
- 集成了 [Alpine.js](https://alpinejs.dev/)。
- 集成了 ESLint + Prettier。

## 开发

```bash
git clone git@github.com:halo-dev/theme-modern-starter.git ~/halo2-dev/themes/theme-modern-starter
```

```bash
cd ~/halo2-dev/themes/theme-modern-starter
```

```bash
pnpm install 
```

```bash
pnpm dev
```
