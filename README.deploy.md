# 大明人物关系图 · 静态站

由 `生成公开可访问网页版.zip` 解压得到的纯静态站点，可直接部署到 GitHub Pages / Netlify / Vercel / Cloudflare Pages。

## 部署到 GitHub Pages

1. 在 GitHub 新建一个空仓库（Public）。
2. 把本目录内容 push 到该仓库的 `main` 分支。
3. 仓库 → Settings → Pages → Source 选择 `Deploy from a branch` → `main` / `/ (root)` → Save。
4. 等约 1 分钟，访问 `https://<你的用户名>.github.io/<仓库名>/`。

## 本地预览

```bash
python3 -m http.server 8000
# 浏览器打开 http://localhost:8000/
```
