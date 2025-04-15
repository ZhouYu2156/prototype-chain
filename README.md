# JavaScript 原型链可视化工具 (JavaScript Prototype Chain Visualizer)

一个优雅的、交互式的 JavaScript 原型链可视化工具，帮助开发者更好地理解 JavaScript 的原型继承机制。

## ✨ 特性

- 🎨 现代赛博朋克风格的 UI 设计
- 🔄 实时、流畅的交互体验
- 📱 响应式布局，支持缩放和拖拽
- 🔗 优雅的连接线动画效果
- 📚 支持 MDN 文档快速跳转
- 💾 支持导出为 SVG 格式
- 🎯 清晰展示对象属性和类型
- 🛠️ 支持自定义对象添加

## 🚀 技术栈

- D3.js v7 - 强大的数据可视化库
- ES6+ - 现代 JavaScript 语法
- HTML5 & CSS3 - 现代网页技术

## 🎯 功能

- 可视化展示 JavaScript 对象的原型链关系
- 展示对象的所有属性及其类型
- 支持属性类型的颜色区分：
  - 函数 (紫色)
  - 字符串 (绿色)
  - 数字 (橙色)
  - 布尔值 (粉色)
  - 对象 (青色)
  - 访问器 (黄色)
  - undefined (灰色)
- 支持节点拖拽和画布缩放
- 连接线自动更新和动画效果
- 一键重置视图
- 导出为 SVG 格式

## 📦 安装

1. 克隆仓库：

```bash
   git clone https://github.com/your-username/js-prototype-visualizer.git
```

2. 启动本地服务器：
```bash
# 使用 Python3
python -m http.server

# 或使用 Node.js
npx serve
```

3. 在浏览器中访问 `http://localhost:8000`

## 🔨 使用方法

1. 页面加载时会自动显示内置的示例原型链
2. 可以通过拖拽节点来调整位置
3. 使用鼠标滚轮或触控板进行缩放
4. 点击属性名可跳转到对应的 MDN 文档
5. 使用右上角的控制面板：
   - 重置视图：将视图恢复到初始状态
   - 添加自定义对象：添加新的对象到可视化图中
   - 导出 SVG：将当前视图导出为 SVG 文件

## 🎨 自定义主题

项目使用 CSS 变量定义主题颜色，可以轻松自定义：

```css
:root {
--bg-primary: #1a1a2e;
--neon-purple: #9d00ff;
--neon-cyan: #00f0ff;
--neon-yellow: #f0ff00;
}
```

## 🤝 贡献

欢迎提交 Issue 和 Pull Request！

## 📄 许可证

MIT License

## 🙏 致谢

- [D3.js](https://d3js.org/)
- [MDN Web Docs](https://developer.mozilla.org/)

## 📧 联系方式

如有问题或建议，欢迎通过以下方式联系：

- 提交 Issue
- 发送邮件到：[livestar2156@gmail.com]

---

如果这个项目对你有帮助，请给个 ⭐️ 支持一下！
