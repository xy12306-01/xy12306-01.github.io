# xy-12306 个人导航网站

## 项目概述 📖
个人导航门户网站，包含：
- 智能导航看板系统
- 技术笔记直连通道
- 常用工具快速入口
- 响应式多设备适配

## 功能特性 ✨
✅ 多页面导航架构  
✅ 现代化渐变UI设计  
✅ 卡片式交互布局  
✅ 飞书文档集成  
✅ 第三方服务对接

## 技术栈 🛠️
```
HTML5 | CSS3 | JavaScript
├─ 响应式布局
├─ CSS变量系统
├─ 移动优先原则
└─ 渐进式增强
```

## 目录结构 📂
```
.
├── index.html            # 主门户
├── pages/                # 子页面
│   ├── page01.html       # 导航看板1
│   ├── page02.html       # 导航看板2
│   ├── page03.html       # 网页推荐
│   └── page04.html       # 球球导航
├── assets/               # 静态资源
│   ├── css/
│   │   ├── style.css     # 主样式
│   │   └── style01.css   # 辅助样式  
│   └── js/
│       ├── script.js     # 主逻辑
│       └── script01.js   # 扩展功能
└── README.md            # 项目文档
```

## 维护指南 🔧
### 页面更新
1. 添加新HTML文件到pages目录
2. 在index.html#tools区块添加导航按钮：
```html
<a href="pages/NEW_PAGE.html" class="tool-button">
  <div style="font-size: 2rem;">🎯</div>
  <div>
    <h3>新页面名称</h3>
    <p>功能描述</p>
  </div>
</a>
```

### 链接管理
- 外部链接：修改对应card元素的href属性
- 内部跳转：使用锚点定位（例：#home）

### 样式定制
通过CSS变量系统快速修改主题：
```css
:root {
  --primary-color: #1677ff; /* 主色调 */
  --bg-gradient: linear-gradient(150deg, #f0faff 0%, #e6f2ff 100%);
}
```

## 开发建议 💡
1. 使用VS Code Live Server扩展进行本地预览
2. 修改样式后强制刷新缓存（Ctrl+F5）
3. 移动端测试建议分辨率：375x812（iPhone 12/13）

## 版本记录 📌
| 版本  | 日期       | 更新说明                 |
|-------|------------|--------------------------|
| v1.0  | 2024-03-15 | 基础导航框架搭建完成     |
| v1.1  | 2024-03-20 | 增加智能看板交互功能     |

> 🚀 项目托管于GitHub Pages：https://xy-12306.github.io