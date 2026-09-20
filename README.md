# Creative Machines, Creative Sketches

Workshop 静态网站，首页直接展示 `assets/teaser_v2.png`，无需安装依赖或构建。

## 本地预览

在项目目录运行 `python3 -m http.server 8000`，然后访问 http://localhost:8000。

## GitHub Pages

1. 将本目录文件（包括 `.nojekyll`）上传到 GitHub 仓库的 `main` 分支。
2. 在仓库 **Settings → Pages** 中选择 **Deploy from a branch**。
3. 选择 `main` 分支和 `/ (root)` 目录，保存。

图片使用相对路径，兼容 `https://<用户名>.github.io/<仓库名>/`。
