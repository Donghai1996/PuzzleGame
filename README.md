game/
│
├── assets/
│   ├── bg/             场景背景
│   ├── characters/     角色立绘
│   ├── items/          道具图片
│   └── ui/             UI素材
│
├── css/
│   ├── variables.css   UI变量 / 主题配置
│   ├── base.css        基础框架布局
│   ├── components.css  通用组件样式
│   │
│   └── scenes/
│       ├── clinicGate.css
│       ├── courtyard.css
│       └── sceneTemplate.css
│
├── js/
│   ├── core/
│   │   ├── items.js
│   │   ├── state.js
│   │   ├── helpers.js
│   │   └── ui.js
│   │
│   ├── scenes/
│   │   ├── clinicGate.js
│   │   ├── courtyard.js
│   │   └── sceneTemplate.js
│   │
│   └── main.js
│
├── templates/
│   └── sceneTemplate.html
│
├── docs/
│   └── ui-tokens.md
│
├── index.html
└── courtyard.html

CSS 结构
- `css/variables.css`
UI变量配置文件，用于修改：主题颜色/字体/面板颜色/按钮样式/对话框尺寸/头像大小

- `css/base.css`
基础布局框架，负责：游戏整体布局/场景容器/页面结构/面板基础样式

- `css/components.css`
通用组件样式，例如：对话框组件/头像区/物品栏/按钮样式/标签/通用UI

- `css/scenes/*.css`
场景专属样式，包括：场景背景/角色位置/热点位置/特殊谜题

JS结构
- `js/core/state.js`
场景状态，负责：创建场景状态/重置场景/管理当前状态

- `js/core/helpers.js`
通用工具函数，例如：UI辅助/动画/道具处理/选择逻辑

- `js/core/ui.js`
统一UI渲染系统，负责：对话框显示/角色头像/当前相关人/物品栏渲染/UI刷新

- `js/scene/*.js`
场景逻辑，负责：场景剧情/交互逻辑/解密流程/事件处理

Scene Template
- `templates/sceneTemplate.html`
- `css/scenes/sceneTemplate.css`
- `js/scenes/sceneTemplate.js`
新建场景

使用方式：
直接打开 index.html
这他妈也要问

