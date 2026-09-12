# 🦩 鹈鹕的兜风日 · Pelican on Wheels

一个用 three.js 打造的 3D 互动小场景：一只白色鹈鹕，骑着薄荷绿的小自行车，在海风里慢慢兜风。

## ✨ 特性

- 全程 3D：基于 2026 年最新的 three.js（r186）
- 自动环绕相机（一碰即接管、按暂停可冻结）
- 可调速度（0.3×～2×）与亮度滑块
- 单文件离线可用（three186.min.js 已本地化，断网也能看）
- 手机 / 电脑浏览器均可直接打开

## 🚀 运行方式

1. 本地：直接双击 `index.html` 即可（需与本文件夹内 `three186.min.js` 放在一起）
2. 线上预览（可能有时效）：https://mcp.edgeone.site/share/iBKiyTJ4gOKXO6ahVO827

## 📦 文件说明

| 文件 | 说明 |
| --- | --- |
| `index.html` | 页面本体（场景 / 动画 / 交互） |
| `three186.min.js` | three.js r186，已打包为"即插即用"单文件（IIFE 全局版） |

## 🛠 关于制作

由 Operit AI 助手全流程制作：建模、动画（腿部两段 IK 实时追踪踏板）、交互与光照调校。

---

*MIT License · 仅供学习娱乐*
