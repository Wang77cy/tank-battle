# 坦克大战 · Tank Battle

一个用原生 HTML + CSS + JavaScript 实现的经典「坦克大战（Battle City）」网页版小游戏，无需任何依赖，双击 `index.html` 即可在浏览器中游玩。

![坦克大战](https://img.shields.io/badge/HTML5-%E7%BA%AF%E5%89%8D%E7%AB%AF-red) ![License](https://img.shields.io/badge/license-MIT-blue)

## 🎮 玩法

- 控制你的坦克，在迷宫中穿梭并消灭所有敌方坦克；
- **保护你的基地（老鹰）**——基地被摧毁即游戏失败；
- 砖墙可被击穿摧毁，钢墙坚不可摧，水会阻挡坦克（子弹可穿过），草丛可以隐藏坦克。

## ⌨️ 操作

| 按键 | 功能 |
| --- | --- |
| `W` `A` `S` `D` 或 `↑` `←` `↓` `→` | 移动坦克 |
| `空格` | 发射炮弹 |
| `Enter` | 开始 / 暂停 / 重新开始 |

> 手机等触屏设备会显示屏幕上的方向键与开火按钮。

## ✨ 特性

- 经典 13×13 砖块地图，多关卡（3 关，敌人数量递增）
- 4 种地形：砖墙、钢墙、水、草丛
- 敌方坦克 AI：随机移动与射击
- 爆炸粒子特效、轻量音效（Web Audio）
- 计分系统、生命值、关卡进度
- 响应式布局，支持触屏操作

## 🚀 运行

直接用浏览器打开 `index.html`，或在当前目录启动任意静态服务器：

```bash
# Python
python -m http.server 8000
# Node.js
npx serve
```

然后访问 <http://localhost:8000>。

## 📁 项目结构

```
tank-battle/
└── index.html   # 游戏全部代码（HTML + CSS + JS 单文件）
```

## 📄 许可证

[MIT](LICENSE)
