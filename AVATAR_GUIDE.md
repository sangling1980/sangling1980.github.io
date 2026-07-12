# 🌐 中英文切换和头像配置指南

## ✅ 已完成功能

### 🔄 中英文切换
- 页面右上角添加了"中文 | English"切换按钮
- 点击即可在中文和英文之间切换
- 所有内容都已配置双语版本

### 👤 头像配置
- 当前使用图标作为头像占位
- 可以轻松替换为真实照片

---

## 📸 如何替换头像照片

### 方法1：使用真实照片

1. **准备头像照片**：
   - 建议尺寸：400x400 像素
   - 格式：JPG、PNG 或 WebP
   - 命名为：`avatar.jpg`

2. **放置到项目目录**：
   ```
   C:\Users\Administrator\personal-profile\avatar.jpg
   ```

3. **修改HTML文件**：
   找到 `<div class="avatar">` 部分，将：
   ```html
   <div class="avatar">
       <i class="fas fa-user-tie"></i>
   </div>
   ```
   
   改为：
   ```html
   <div class="avatar">
       <img src="avatar.jpg" alt="Shining">
   </div>
   ```

### 方法2：使用专业图标库头像

如果你喜欢现在的图标样式，可以选择其他更专业的图标：

```html
<div class="avatar">
    <i class="fas fa-user-graduate"></i>  <!-- 学者风格 -->
</div>
```

可选图标：
- `fa-user-graduate` - 学者
- `fa-user-tie` - 商务人士
- `fa-user-md` - 医疗专业
- `fa-id-card` - 身份卡片

### 方法3：使用在线头像服务

```html
<div class="avatar">
    <img src="https://api.dicebear.com/7.x/avataaars/svg?seed=Shining" alt="Shining">
</div>
```

---

## 🚀 上传更新

修改完成后，上传到GitHub：

```bash
cd C:\Users\Administrator\personal-profile
git add .
git commit -m "Add language switching and avatar"
git push
```

访问 https://sangling1980.github.io/ 查看更新效果

---

## 💡 头像设计建议

### 专业头像特征：
✅ 正面清晰的照片
✅ 简洁的背景
✅ 适合裁剪为圆形
✅ 表情自然、专业
✅ 光线均匀

### 避免：
❌ 模糊的照片
❌ 复杂背景
❌ 非正式穿着
❌ 过度美颜

---

现在你可以选择添加真实头像照片，或者保持当前的图标样式！