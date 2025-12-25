# Mailya Landing Page

简约大气的 Mailya 产品首页，用于 GitHub Pages 部署。

## 部署到 GitHub Pages

### 方法一：直接上传

1. 在 GitHub 创建新仓库，命名为 `mailya-landing` 或 `mailya.github.io`
2. 上传 `index.html` 文件到仓库根目录
3. 进入仓库 Settings → Pages
4. Source 选择 `main` 分支，目录选择 `/ (root)`
5. 点击 Save，等待几分钟即可访问

### 方法二：命令行

```bash
# 创建本地仓库
mkdir mailya-landing && cd mailya-landing
git init

# 复制 index.html 到此目录

# 提交
git add .
git commit -m "Initial commit"

# 推送到 GitHub
git remote add origin https://github.com/YOUR_USERNAME/mailya-landing.git
git push -u origin main
```

然后在 GitHub 仓库设置中启用 Pages。

## 自定义域名（可选）

1. 在仓库根目录创建 `CNAME` 文件
2. 写入你的域名，如 `mailya.asia`
3. 在域名 DNS 设置中添加 CNAME 记录指向 `YOUR_USERNAME.github.io`

## 设计说明

- **风格**: Refined Editorial Minimalism（克制的编辑风格极简主义）
- **配色**: 深炭灰背景 + 暖白文字 + 金色点缀
- **字体**: Noto Serif SC（标题）+ Noto Sans SC（正文）
- **动效**: 滚动渐入动画，简洁不抢眼
