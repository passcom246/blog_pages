# blog_pages

本仓库是博客的**发布产物**，由源码仓库 [passcom246/blog](https://github.com/passcom246/blog) 执行 `npm run build` 后，
把 `docs/.vitepress/dist` 里的内容复制到本仓库根目录并推送。

- 请勿直接在此仓库修改内容，任何改动都会在下次部署时被覆盖
- 源码仓库：https://github.com/passcom246/blog
- 访问地址：https://passcom246.github.io/blog_pages/

## 更新步骤

1. 在源码仓库改完文章后执行 `npm run build`；
2. 删掉本仓库根目录里的旧产物（保留 `.git`、`.gitignore`、`.nojekyll`、`README.md`）；
3. 把 `docs/.vitepress/dist` 里的内容复制进来；
4. 提交推送（`deploy: 更新博客`），GitHub Pages 会在 1~2 分钟内自动重新发布。