# Wolfzzzzz 模拟飞行个人主页

![模拟飞行](https://img.shields.io/badge/MSFS-爱好者-blue)
![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-部署成功-brightgreen)

这是我的个人介绍页面，专为**微软模拟飞行**爱好者设计。页面可根据东八区（UTC+8）的实时时间变换背景色，并在进入前执行网络与安全自检。内容聚焦于我最爱的两款机型：**波音 777-300ER (77W)** 和 **空客 A350-1000 (35K)**，并集成了 GitHub 与 iCloud 联系方式。

👉 **[在线预览](https://wolfzzzzz.github.io/ProfileWolfzzzzz)**

## ✨ 特性

- **智能加载自检**：进入页面前自动检测 IP 地址、网络信息、安全连接及浏览器环境，并显示进度条。
- **实时动态主题**：页面背景色随东八区小时变化（色相逐小时流转，亮度根据白天/夜晚自适应）。
- **模拟飞行主题界面**：
  - 毛玻璃卡片设计
  - 仪表盘装饰（空速、航向、高度、温度）
  - 个性化飞行偏好展示（77W 与 35K）
- **响应式布局**：完美适配桌面端与移动端。
- **一键联系**：GitHub 与 iCloud 邮箱链接。

## 🛠 技术栈

- HTML5
- CSS3（Flexbox、Grid、毛玻璃效果、动画）
- JavaScript（ES6+）
- [Font Awesome 6](https://fontawesome.com/)（图标库）
- [ip-api.com](https://ip-api.com/)（IP 地理位置查询）

## 🚀 部署到 GitHub Pages

1. **Fork 或下载本仓库**到你的本地。
2. 修改 `index.html` 中的个人信息（如邮箱、GitHub 链接、机型偏好等）。
3. 在 GitHub 上创建一个新仓库（例如 `example.github.io` 或任意名称）。
4. 将代码推送到该仓库的 `main` 分支。
5. 进入仓库设置 **Settings** → **Pages**，在 "Branch" 处选择 `main` 分支，点击保存。
6. 等待几分钟，访问 `https://example.github.io/example` 即可看到在线页面。

## 📁 文件结构
.
├── index.html # 主页面（包含样式与脚本）
├── README.md # 项目说明
├── LICENSE # 开源许可证
└── .gitignore # Git 忽略文件

## ⚙️ 自定义指南

- **修改机型/个人信息**：直接编辑 `index.html` 中对应卡片内容。
- **调整颜色规则**：修改 `applyColorByHour` 函数中的 `hue`、`lightness` 计算逻辑。
- **更换自检 API**：目前使用 `ip-api.com`，如需替换可在 `script.js` 的 `ipPromise` 部分修改。

## 📄 许可证

本项目采用 MIT 许可证，详情请参见 [LICENSE](LICENSE) 文件。

## 📬 联系方式

- GitHub: [@Wolfzzzzz](https://github.com/Wolfzzzzz)
- 邮箱: zhang429500@icloud.com

---

**Happy Flying! ✈️**