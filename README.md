# Rasso 官方官网

拉索（Rasso）— 键盘驱动的桌面插件启动器的官方网站。**单主页架构**：工程蓝图风格（Neobrutalism + Blueprint Sketch），纯白底方格网 + 黑白墨线硬阴影。

## 🌐 在线访问

**主页**: https://hanhanpig3.github.io/rasso-website/

> 插件仓库与官网分离：[hanhanpig3/rasso](https://github.com/hanhanpig3/rasso) 是产品主仓库，本仓库只承载官网。

## 📄 页面板块

| 板块 | 内容 |
|------|------|
| **FIG.01 系统结构图** | 微内核 + 8 插件星系画布，芯片点击引爆、便签可拖拽 |
| **FIG.02 命令工作流** | Alt+Space → 输入 → 选择 → 执行 → 收起，五步全键盘链路 |
| **极客控制台** | 打字机构建日志（真实运行数据回放）+ SVG 示波器（IPC 延迟量级） |
| **FIG.03 插件实机预览** | 可交互模拟启动器：输入过滤、回车打开；编码转换 / 变量命名面板**真实可用** |
| **FIG.04 快捷键清单** | 全局热键与窗口级快捷键一览 |
| **FIG.05 插件沙箱** | 主进程 / IPC 桥 / 插件沙箱三层隔离架构 |

全站支持 **中 / EN 一键切换**（Vue 响应式 i18n，切换带淡入淡出）。

## 🏗️ 技术栈

- **Vue 3 (CDN) + Tailwind CSS (CDN)** — 单文件实现，无构建步骤
- **原生交互动效** — 芯片引爆（弹性贝塞尔回弹）、Pointer 拖拽便签、rAF 手绘波形、打字机终端
- **GitHub Pages** — main 分支自动部署，HTTPS

## 📁 目录结构

```
rasso-website/
├── index.html            # 唯一主页（蓝图工程版）
├── animations/
│   └── demo.html         # 插件工作流动画演示（HyperFrames 思路的简化版）
├── server.js             # 本地预览服务器（node server.js，端口 3000）
└── README.md
```

## 🔗 相关链接

- **主仓库**: https://github.com/hanhanpig3/rasso
- **产品下载**: https://github.com/hanhanpig3/rasso/releases
