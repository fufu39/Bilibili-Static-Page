# **Bilibili静态页面复刻**

> 项目完成时间：2023.10
>
> 耗时约4日

Bilibili静态页面复刻是一个基于原版哔哩哔哩网站首页的静态页面重现项目。

项目采用纯HTML和CSS构建，集成了自定义的bilifont图标库，旨在通过精确还原B站首页的视觉效果和布局结构，展示前端静态页面开发的基本技能。

## **✨ 主要功能 (Features)**

![首页预览图](./README.assets/index-preview.png)

- **精确复刻的导航栏**
  - 包含完整的导航菜单、搜索框和用户信息区域
  - 集成自定义bilifont图标字体，实现B站特有的图标效果

- **首页Banner区域**
  - 还原B站特色的大型横幅背景
  - 实现Logo和品牌标识的精确定位

- **频道分类导航**
  - 展示B站各个内容频道的分类入口
  - 使用flex布局实现响应式排列

- **推荐内容展示**
  - 包含轮播图区域，支持图片切换功能
  - 视频卡片网格布局，展示缩略图、标题和UP主信息

- **视频信息卡片**
  - 精确还原B站视频卡片样式，包含播放量、弹幕数等信息
  - 实现悬停效果和交互反馈

- **自适应布局**
  - 保证在不同尺寸屏幕下的基本显示效果
  - 设置最小宽度确保关键内容不被破坏

## 🛠️ 基础工具与技术栈 (Tools & Tech Stack)

- **开发语言**：HTML5, CSS3
- **图标系统**：自定义bilifont字体图标库
- **图片资源**：WebP格式优化的图片资源
- **布局技术**：
  - Flexbox弹性布局
  - CSS Grid网格布局
  - 相对/绝对定位混合布局
- **样式技术**：
  - CSS变量
  - 线性渐变
  - 过渡动画
  - 伪元素与伪类

## 📁 项目结构

```html
bilibili-static-page/
├── CSS/               # 样式文件
│   ├── base.css       # 基础样式重置
│   └── index.css      # 主页样式
├── bilifont/          # 自定义图标字体
│   └── src/           # 字体源文件
│       ├── bilifont.css
│       └── iconfont.ttf
├── images/             # 静态图片资源
├── uploads/            # 内容图片资源
└── index.html          # 主页HTML
```

## 🚀 快速开始 (Getting Started)
1. **克隆仓库**

   ```bash
   git clone git@github.com:yourusername/bilibili-static-page.git
   ```

2. **进入项目目录**

   ```bash
   cd bilibili-static-page
   ```

3. **本地运行**

   - 直接在浏览器中打开index.html
   - 或使用VSCode的Live Server插件启动




------

***本项目仅供学习用途，禁止用于商业用途。***