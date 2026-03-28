# 釜山清明旅行 2026 - 行程可视化网页

🌸 这是一个互动式的釜山旅行行程网页，包含：
- 📅 3 天详细行程安排
- 🗺️ 交互式地图
- 📸 景点图片
- 📕 小红书攻略链接

## 文件说明

- `busan-trip-2026.html` - 主网页文件
- `images/` - 图片文件夹

## 部署到 GitHub Pages

### 步骤 1：创建仓库
1. 登录 GitHub
2. 点击右上角 "+" → "New repository"
3. 仓库名：`busan-trip-2026`
4. 设为 **Public**
5. 点击 "Create repository"

### 步骤 2：上传文件
```bash
# 方法 A：使用 Git 命令行
git init
git add .
git commit -m "Initial commit: Busan trip itinerary"
git branch -M main
git remote add origin https://github.com/你的用户名/busan-trip-2026.git
git push -u origin main

# 方法 B：在 GitHub 网页上传
# 点击 "uploading an existing file"
# 选择 busan-trip-2026.html 和 images 文件夹
# 点击 "Commit changes"
```

### 步骤 3：启用 GitHub Pages
1. 进入仓库的 **Settings**
2. 左侧菜单点击 **Pages**
3. Source 选择 **Deploy from a branch**
4. Branch 选择 **main**，文件夹选择 **/(root)**
5. 点击 **Save**

### 步骤 4：访问网页
等待 1-2 分钟，你的网页就会发布在：
```
https://你的用户名.github.io/busan-trip-2026/busan-trip-2026.html
```

## 自定义

如需修改行程，编辑 `busan-trip-2026.html` 文件即可。

---

**祝旅途愉快！** 🎉
