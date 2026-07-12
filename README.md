# sangling1980 个人主页

简洁的 GitHub Pages 个人主页

## 📁 文件结构

```
personal-profile/
├── index.html      # 主页面
├── style.css       # 样式文件
└── README.md       # 说明文档
```

## 🚀 部署到 GitHub Pages

### 方法一：通过 GitHub 网页操作（推荐）

1. **创建仓库**
   - 访问 https://github.com/new
   - 仓库名称填写：`sangling1980.github.io`（注意：必须使用这个格式）
   - 设置为 Public 公开仓库
   - 点击 "Create repository"

2. **上传文件**
   - 点击 "uploading an existing file"
   - 将 `index.html` 和 `style.css` 两个文件拖拽上传
   - 在底部提交信息框中输入 "Initial commit"
   - 点击 "Commit changes"

3. **等待部署**
   - GitHub 会自动部署，约 1-2 分钟后
   - 访问：https://sangling1980.github.io

### 方法二：使用 Git 命令行

```bash
# 配置 git（首次使用需要）
git config --global user.name "sangling1980"
git config --global user.email "your-email@example.com"

# 初始化仓库并添加文件
git add .
git commit -m "Initial commit"

# 添加远程仓库（替换为你的仓库地址）
git remote add origin https://github.com/sangling1980/sangling1980.github.io.git

# 推送到 GitHub
git branch -M main
git push -u origin main
```

## ✏️ 自定义内容

### 修改个人信息
编辑 `index.html`，修改以下内容：
- `<h1>` 中的用户名
- `<p class="title">` 中的标题
- `<section class="about">` 中的个人介绍

### 添加头像
在 `<div class="avatar">` 中添加头像图片：
```html
<div class="avatar">
    <img src="your-avatar.jpg" alt="头像">
</div```
同时修改 CSS：
```css
.avatar {
    /* 修改为适配图片 */
}
.avatar img {
    width: 100%;
    height: 100%;
    border-radius: 50%;
    object-fit: cover;
}
```

### 修改社交媒体链接
找到 `<div class="social-links">`，修改 `href` 属性为你的实际链接

### 修改技能标签
找到 `<div class="skill-tags">`，修改或添加 `<span class="tag">` 元素

### 修改配色方案
编辑 `style.css`，修改渐变色和配色：
- 主渐变色：`linear-gradient(135deg, #667eea 0%, #764ba2 100%)`
- 调整颜色代码即可

## 📱 响应式设计

页面已优化为响应式设计，在手机、平板和桌面端都能良好显示。

## 🎨 特性

- 简洁现代的设计风格
- 渐变背景和卡片式布局
- 社交媒体链接悬停效果
- 技能标签交互效果
- 完全响应式，适配所有设备
- 纯 HTML/CSS，无 JavaScript 依赖

## 📧 自定义域名（可选）

如果你有自己的域名，可以绑定到 GitHub Pages：

1. 在仓库设置中找到 "Pages"
2. 在 "Custom domain" 中输入你的域名：`shining888`
3. 添加 DNS 记录（CNAME 指向 sangling1980.github.io）
4. 等待 DNS 生效

## 🔧 维护

要更新主页内容：
1. 编辑本地文件
2. 运行 `git add .` 和 `git commit -m "你的更新信息"`
3. 运行 `git push`

## 📝 许可

MIT License