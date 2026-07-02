# 小学英语单词练习 - 网页版部署说明

这个文件夹是一个纯静态网页，不需要服务器程序。

## 推荐：GitHub Pages

1. 登录 GitHub。
2. 新建一个公开仓库，例如 `kids-vocab`。
3. 把本文件夹里的所有文件上传到仓库根目录：
   - `index.html`
   - `.nojekyll`
   - `README.md`
4. 进入仓库的 `Settings`。
5. 左侧选择 `Pages`。
6. 在 `Build and deployment` 里选择：
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
7. 保存后等待 1-3 分钟。
8. GitHub 会生成一个网址，通常类似：
   `https://你的用户名.github.io/kids-vocab/`

后续更新时，直接重新上传新版 `index.html`，小朋友继续用同一个链接。

## 备用：Netlify Drop

如果 Netlify 账号可用，也可以把整个 `vocab-web` 文件夹拖到 Netlify Drop。

## 其他可选服务

- Cloudflare Pages
- Vercel
- 阿里云 OSS / 腾讯云 COS / 七牛云静态网站

## 注意

- 本地路径只能在你自己的电脑上打开，发给别人不能直接用。
- 上线后，孩子的学习进度会保存在他自己设备的浏览器里，不会上传到 GitHub。
- 如果换手机、换浏览器、清除浏览器数据，进度会丢失。
- 想让家长跨设备查看进度，需要再加账号和云端数据库。
