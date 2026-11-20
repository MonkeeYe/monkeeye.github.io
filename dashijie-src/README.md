# 大师姐 Astro 试验版

这个目录是 Astro 的源代码工程。

## 本地运行
```bash
npm install
npm run dev
```

## 构建
```bash
npm run build
```
构建后会生成 `dist/`。

## 发布到现有 GitHub Pages
把 `dist/` 里的内容复制到 `monkeeye.github.io/dashijie/`，然后在 `monkeeye.github.io` 仓库执行：
```bash
git add dashijie
git commit -m "publish dashijie astro site"
git push
```

## 新增文章
复制 `src/content/posts/distributor/` 为一个新目录，例如 `src/content/posts/second-post/`，修改其中 `index.md`。重新 `npm run build` 后，首页会自动出现新文章。
