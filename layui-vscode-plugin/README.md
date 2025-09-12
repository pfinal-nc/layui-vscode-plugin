# layui-snippets-pfinal

🎉 **Layui VSCode 插件 - 支持最新 2.11.6 版本**

为 VSCode 提供 Layui 框架的代码片段自动补全，方便快速开发。

## ✨ 主要特性

- 🚀 **支持最新版本**: 完全支持 Layui 2.11.6 最新版本
- 📦 **丰富组件库**: 包含 50+ 个常用 Layui 组件代码片段
- 🆕 **新增组件**: 支持 2.10+ 新增的组件构建器、新标签页等
- 💡 **智能补全**: 输入前缀即可快速生成完整代码
- 🔧 **多语言支持**: 支持 HTML、PHP、JavaScript 三种语言

## 🆕 新增组件 (v0.1.0)

### 2.10+ 新组件
- **组件构建器** (`lay-component`) - 2.10+ 新增的重要模块
- **新标签页** (`lay-tabs`) - 替代旧的 tab 组件
- **颜色选择器** (`lay-colorpicker`)
- **穿梭框** (`lay-transfer`)
- **滑块** (`lay-slider`)
- **轮播** (`lay-carousel`)
- **流加载** (`lay-flow`)
- **代码预览** (`lay-code`)
- **徽章** (`lay-badge`)
- **下拉菜单** (`lay-dropdown`)
- **上传** (`lay-upload`)
- **日期选择器** (`lay-laydate`)

### 基础组件
- **CDN 引用** (`lay-cdn:2.11.6`) - 最新版本 CDN
- **容器布局** (`lay-con`, `lay-row`)
- **按钮组件** (`lay-btn` 系列)
- **表单组件** (`lay-form` 系列)
- **导航组件** (`lay-nav` 系列)
- **表格组件** (`lay-table`)
- **弹出层** (`lay-layer` 系列)
- **树组件** (`lay-tree`)
- **更多...**

## 🚀 使用方式

1. 在 VSCode 中安装本插件
2. 在 HTML/PHP/JavaScript 文件中输入组件前缀
3. 选择对应的代码片段即可快速生成代码

### 示例

```html
<!-- 输入 lay-cdn:2.11.6 生成最新版本 CDN -->
<link rel="stylesheet" media="screen" href="https://cdn.staticfile.org/layui/2.11.6/css/layui.min.css">
<script src="https://cdn.staticfile.org/layui/2.11.6/layui.min.js"></script>

<!-- 输入 lay-tabs 生成新标签页组件 -->
<div id="test-tabs"></div>
<script>
layui.use('tabs', function(){
  var tabs = layui.tabs;
  tabs.render({
    elem: '#test-tabs',
    header: [
      { title: 'Tab1' },
      { title: 'Tab2' }
    ],
    body: [
      { content: 'Tab content 1' },
      { content: 'Tab content 2' }
    ]
  });
});
</script>
```

## 📝 更新日志

### v0.1.0 (2025-01-27)
- 🎉 重大更新：支持 Layui 2.11.6 最新版本
- 新增 12 个 2.10+ 新组件代码片段
- 优化现有代码片段，提升开发体验
- 更新插件版本号和描述信息

### v0.0.6
- 支持 Layui 2.8.18 版本
- 新增登录面板、注册面板等组件

## 🔗 相关链接

- **GitHub**: [https://github.com/pfinal-nc/layui-vscode-plugin](https://github.com/pfinal-nc/layui-vscode-plugin)
- **Layui 官网**: [https://layui.dev/](https://layui.dev/)
- **Layui 文档**: [https://layui.dev/docs/2/](https://layui.dev/docs/2/)

## 📄 许可证

MIT License

---

**让 Layui 开发更高效！** 🚀

