# Emiria的个人主页 ✨

一个二次元动漫风格的个人主页，专为GitHub Pages部署设计。

## 🌸 项目特点

- **二次元动漫风格**: 粉嫩配色、樱花飘落效果、可爱动画
- **响应式设计**: 完美适配手机、平板、电脑
- **开箱即用**: 无需复杂配置，直接部署
- **轻量快速**: 纯HTML/CSS/JS，加载速度快

## 📁 项目结构

```
emiriatang.github.io/
├── index.html          # 主页面
├── style.css           # 样式文件
├── image/              # 图片文件夹
│   ├── avatar.png      # 头像（需自行替换）
│   ├── README.md       # 图片说明文档
│   └── .gitkeep        # Git占位文件
└── README.md           # 项目说明
```

## 🚀 部署到GitHub Pages

### 方法一：通过Git命令行

1. **初始化Git仓库**（如果还没有）
   ```bash
   git init
   git add .
   git commit -m "Initial commit - 二次元个人主页"
   ```

2. **关联远程仓库**
   ```bash
   git remote add origin https://github.com/emiriatang/emiriatang.github.io.git
   ```

3. **推送到GitHub**
   ```bash
   git branch -M main
   git push -u origin main
   ```

4. **启用GitHub Pages**
   - 进入仓库的 Settings → Pages
   - Source 选择 `main` 分支
   - 点击 Save

5. **访问你的主页**
   - 几分钟后访问: `https://emiriatang.github.io`

### 方法二：通过GitHub Desktop

1. 克隆仓库到本地
2. 将项目文件复制到仓库文件夹
3. 提交并推送更改
4. 在GitHub上启用Pages功能

## 🎨 自定义配置

### 替换头像

1. 准备一张正方形头像图片（建议200x200像素以上）
2. 命名为 `avatar.png`
3. 放入 `image/` 文件夹
4. 刷新页面即可看到效果

### 修改社交链接

编辑 `index.html` 文件，找到以下部分：

```html
<!-- GitHub链接 -->
<a href="https://github.com/emiriatang" target="_blank" class="social-link github">

<!-- B站链接 -->
<a href="https://space.bilibili.com/你的B站ID" target="_blank" class="social-link bilibili">

<!-- 抖音链接 -->
<a href="https://www.douyin.com/user/你的抖音ID" target="_blank" class="social-link douyin">
```

将链接替换为你自己的账号即可。

### 修改个人信息

在 `index.html` 中修改：
- 用户名：`<h1 class="username">Emiria</h1>`
- 个性签名：`<p class="tagline">二次元爱好者 | 动漫迷 | 游戏玩家</p>`
- 个人介绍：在"关于我"卡片中修改

### 修改配色方案

在 `style.css` 文件开头的 `:root` 部分修改CSS变量：

```css
:root {
    --primary-pink: #ffb7c5;      /* 主粉色 */
    --secondary-pink: #ff9eb5;    /* 次粉色 */
    --purple: #c9a0dc;            /* 紫色 */
    /* ... 其他颜色 */
}
```

## ✨ 特效说明

### 樱花飘落效果
- 自动飘落的樱花花瓣
- 随机大小、位置和速度
- 可通过修改JavaScript调整飘落频率

### 动画效果
- 头像光环脉动
- 卡片悬浮效果
- 图标弹跳动画
- 渐变过渡效果

## 📱 响应式支持

页面已针对以下设备进行优化：
- 📱 手机（<480px）
- 📱 大屏手机（480px-768px）
- 💻 平板和电脑（>768px）

## 🔧 故障排除

### 头像不显示
- 检查图片是否命名为 `avatar.png`
- 确认图片在 `image/` 文件夹中
- 检查文件路径是否正确

### 样式不生效
- 确认 `style.css` 和 `index.html` 在同一目录
- 清除浏览器缓存
- 检查浏览器控制台是否有错误

### GitHub Pages不显示
- 确认已启用Pages功能
- 等待几分钟让GitHub构建
- 检查仓库是否为公开仓库

## 📄 许可证

本项目仅供个人使用，可自由修改和部署。

## 💖 致谢

感谢使用这个模板！希望你喜欢这个二次元风格的个人主页。

---

**Made with 💖 by Emiria**

✨ 祝你使用愉快！如有问题，欢迎联系。