# craft

大强同学 / Derek Zhao 个人品牌网站。

## 技术栈

- **HTML5** - 语义化标记
- **Tailwind CSS** (CDN) - 原子化样式
- **Vanilla JS** - 交互逻辑

无需构建工具，直接用浏览器打开 `index.html` 即可预览。

## 项目结构

```
craft/
├── index.html              # 主页面
├── assets/
│   ├── css/
│   │   └── style.css       # 自定义样式（动画等）
│   └── images/             # 图片资源目录
└── README.md
```

## 使用方法

1. 浏览器打开 `index.html` 即可查看效果
2. 修改 `index.html` 中的内容即可自定义

## 部署

支持任意静态托管平台：

- **Cloudflare Pages** - 推荐，国内访问快
- **Vercel** - 自动 HTTPS，GitHub 推送自动部署
- **Netlify** - 免费额度够用
- **EdgeOne** - 腾讯云，国内节点

推送 GitHub 后，在对应平台导入仓库即可一键部署。
