# 365能歌善舞 · 同修全息查阅中心

## 部署到 GitHub Pages

### 方法一：新建仓库（推荐）

1. 在 GitHub 新建一个仓库（如 `365`）
2. 将 `365/` 文件夹里的内容上传到仓库根目录
3. 进入仓库 **Settings → Pages**
4. **Source** 选择 `main` 分支，文件夹选 `/ (root)`，点 **Save**
5. 等待 1-2 分钟，访问 `https://你的用户名.github.io/365/`

### 方法二：加入现有仓库的 docs 文件夹

1. 将 `365/` 文件夹重命名为 `docs/`
2. Push 到你的仓库
3. **Settings → Pages → Source** 选择 `main` 分支，文件夹选 `/docs`

### 文件结构

```
├── index.html      ← 主页面（31KB）
├── images/
│   ├── image_1.jpg ← 首页背景
│   ├── image_2.jpg ← 宝塔背景
│   ├── image_3.jpg ← 搜索页背景
│   └── image_4.gif ← 加载动画
└── .nojekyll       ← 告诉 GitHub 不要用 Jekyll 处理
```

### 微信分享

已添加 Open Graph 标签，分享到微信时会显示标题和缩略图。
