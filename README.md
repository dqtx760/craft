# huasheng-ai-clone

huasheng.ai 个人网站的静态复刻版本。

## 技术栈

- **HTML5** - 语义化标记
- **Tailwind CSS** (CDN) - 原子化样式
- **Vanilla JS** - 交互逻辑

无需构建工具，直接用浏览器打开 `index.html` 即可预览。

## 项目结构

```
huasheng-ai-clone/
├── index.html              # 主页面
├── assets/
│   ├── css/
│   │   └── style.css       # 自定义样式（动画等）
│   └── images/             # 图片资源目录
│       ├── avatar-bogart.jpg  # 头像（需自行添加）
│       └── og-default.png     # OG 分享图（需自行添加）
└── README.md
```

## 使用方法

1. 将 `assets/images/` 中放入对应的图片资源
2. 浏览器打开 `index.html` 即可查看效果
3. 修改 `index.html` 中的内容即可自定义

## 自定义修改

所有内容都在 `index.html` 中，可直接编辑：

- **个人信息** - 修改姓名、简介、联系方式等
- **作品列表** - 在 "Selected Works" 区域添加/修改作品
- **数据指标** - 在 "Key Metrics" 区域修改数字
- **媒体/播客** - 在 "Press & Podcasts" 区域修改
- **服务项目** - 在 "Services" 区域修改

## 部署

推荐使用 GitHub Pages：

1. 创建 GitHub 仓库
2. 推送代码
3. 在 Settings > Pages 中选择 main 分支
4. 即可通过 `https://username.github.io/repo-name` 访问
