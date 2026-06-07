# 📚 智能电子书阅读器 - 授权版

> 仓库名：`reader-app-auth`（避免与现有仓库冲突）

## 🚀 部署步骤

### 1. 创建新仓库
- GitHub → New Repository → 名称 **`reader-app-auth`** → Public → Create

### 2. 上传文件
```bash
git clone https://github.com/sgliu123/reader-app-auth.git
cd reader-app-auth
# 放入 index.html 和 licenses.enc
git add .
git commit -m "Initial release with auth"
git push origin main
```

### 3. 开启 GitHub Pages
- Settings → Pages → Source: Deploy from a branch → Branch: `main` / `root` → Save

### 4. 访问地址
- **GitHub Pages**: `https://sgliu123.github.io/reader-app-auth/`
- **jsDelivr CDN**: `https://cdn.jsdelivr.net/gh/sgliu123/reader-app-auth@main/index.html`

## 🔐 授权管理

1. 下载 `admin-generator.html`（从之前的 `reader-app` 文件夹）
2. 在浏览器中打开生成授权码
3. 下载 `licenses.enc` 上传到此仓库替换

---
**版权所有 © 2026 一刀**
