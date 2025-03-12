# 公司产品展示网站

这是一个现代简约风格的公司产品展示网站，采用响应式设计，支持各种设备访问。

## 特点

- 现代简约的设计风格
- 响应式布局，适配移动端和桌面端
- 流畅的动画效果
- 产品轮播展示
- 交互式导航菜单
- 社交媒体集成

## 技术栈

- HTML5
- CSS3
- JavaScript (ES6+)
- Swiper.js (轮播组件)
- AOS (滚动动画)
- Font Awesome (图标)
- Google Fonts (字体)

## 快速开始

1. 克隆项目到本地
2. 确保所有图片资源放置在 `img` 目录下：
   - `img/hero-bg.jpg` - 首页背景图
   - `img/product1.jpg` - 产品1图片
   - `img/product2.jpg` - 产品2图片
   - `img/product3.jpg` - 产品3图片
   - `img/logo-white.png` - 底部白色logo
   - `img/iso-cert.png` - ISO认证图标

3. 在浏览器中打开 `index.html` 即可预览

## 自定义配置

### 修改颜色主题

在 `styles.css` 文件中修改根变量：

```css
:root {
    --primary-color: #0A2463;    // 主色调
    --accent-color: #FF6B6B;     // 强调色
    --light-gray: #F5F5F5;       // 浅灰色
    --dark-gray: #333333;        // 深灰色
}
```

### 添加新产品

在 `main.js` 文件中的 `products` 数组中添加新产品：

```javascript
const products = [
    {
        id: 4,
        name: '新产品名称',
        description: '产品描述文本',
        image: 'product4.jpg'
    },
    // ...
];
```

## 浏览器支持

- Chrome (最新版)
- Firefox (最新版)
- Safari (最新版)
- Edge (最新版)

## 注意事项

1. 所有图片需要经过优化压缩
2. 建议使用 WebP 格式的图片以获得更好的加载性能
3. 确保所有图片都有正确的 alt 属性
4. 社交媒体链接需要更新为实际的社交媒体账号地址

## 许可证

MIT License 