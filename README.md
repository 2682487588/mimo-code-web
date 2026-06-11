# MiMo Code Landing Page

MiMo Code 官方产品页的静态复刻版本，包含完整的交互动效和响应式布局。

## 在线预览

[查看在线效果](https://master-frank.github.io/mimo-code-web/)

## 功能特性

- **Canvas 墨迹揭示效果** — 鼠标 hover 时用不规则墨点"擦除"遮罩，露出底部飞天壁画
- **打字机动画** — 副标题逐字显示 + 光标闪烁，卡片标题进入视口时触发
- **中英文切换** — 所有文案实时切换，语言选择即时生效
- **复制命令** — 一键复制安装命令，带 tooltip 反馈动画
- **响应式布局** — 640px 以下自适应移动端
- **导航下拉菜单** — 产品下拉 + 语言切换，hover 展开

## 技术栈

- 纯 HTML / CSS / JavaScript，无框架依赖
- Canvas 2D API 实现墨迹揭示动效
- IntersectionObserver 驱动卡片标题入场动画
- Google Fonts (Questrial + Noto Serif SC)

## 本地运行

```bash
git clone https://github.com/Master-Frank/mimo-code-web.git
cd mimo-code-web
# 用任意静态服务器打开
npx serve .
```

## 项目结构

```
├── index.html              # 页面主体（HTML + CSS + JS）
├── logo.png                # MiMo Logo
├── icon-translate.svg      # 语言切换图标
├── icon-copy.svg           # 复制按钮图标
├── 飞天4.png               # Hero 区域背景图
├── feature-model.png       # 特性卡片 1
├── feature-agent.png       # 特性卡片 2
├── feature-context.png     # 特性卡片 3
├── feature-evolution.png   # 特性卡片 4
└── feature-compose.png     # 特性卡片 5
```

## 致谢

原始设计来自 [MiMo Code 官网](https://mimo.xiaomi.com/coder)，仅供学习参考。
