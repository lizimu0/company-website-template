# Company Website Template

一套现代简约风格的科技公司官网模板，纯 HTML/CSS/JS 实现，零外部依赖，开箱即用。

## 预览

在线预览：https://lizimu0.github.io/company-website-template/

## 特性

- 现代简约设计，白底大留白 + 蓝色主色调
- 响应式布局，适配桌面 / 平板 / 手机
- 滚动渐入动画（Intersection Observer）
- 导航吸顶 + 毛玻璃效果
- 纯静态实现，无需构建工具，无 CDN 依赖

## 页面结构

| 模块 | 说明 |
|------|------|
| Hero | 首屏大标题 + CTA 按钮 + 数据指标栏 |
| Products | 6 张产品卡片网格 |
| About | 公司简介 + 资质列表 |
| Contact | 联系方式 + 咨询表单 |
| Footer | 多栏导航 + 版权信息 |

## 快速使用

1. 克隆仓库：
   ```bash
   git clone https://github.com/lizimu0/company-website-template.git
   ```
2. 打开 `index.html`，全局搜索替换以下内容：
   - `云启科技` → 你的公司名
   - `XX市XX区XX路XX号` → 实际地址
   - `contact@yourcompany.com` → 实际邮箱
   - `400-XXX-XXXX` → 实际电话
3. 修改 `:root` 中的 `--accent` 变量可一键换主题色。

## 技术栈

- HTML5 / CSS3 / Vanilla JavaScript
- CSS Custom Properties（主题变量）
- Intersection Observer API（滚动动画）
- Flexbox + Grid（响应式布局）

## License

MIT
