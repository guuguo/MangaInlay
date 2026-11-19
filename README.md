<div align="center">

# MangaInlay (漫嵌)

**In-Place AI Manga & Webtoon Bubble Translator Chrome Extension**

*生肉漫画与条漫原位气泡嵌字翻译 Chrome 扩展 — 不加方框遮挡画面，译文直接嵌进原本的气泡里*

[![Official Website](https://img.shields.io/badge/Website-hub.guuguo.top%2Fmangainlay-0ea5e9?style=flat-square)](https://hub.guuguo.top/mangainlay)
[![Latest Release](https://img.shields.io/badge/Download-v0.1.1%20(.zip)-22c55e?style=flat-square)](https://github.com/guuguo/MangaInlay/releases/latest)

</div>

---

![MangaInlay Before vs After](https://hub.guuguo.top/assets/mangainlay-hero.png)

## Why MangaInlay?

Most comic translation extensions slap opaque boxes over speech bubbles—covering up radial spikes, sound effects, and background artwork.

**MangaInlay** ([hub.guuguo.top/mangainlay](https://hub.guuguo.top/mangainlay)) keeps full-resolution image processing off the network: the backend returns only compact bubble coordinates and translated JSON, while the Chrome extension samples surrounding bubble colors and renders translated text directly on an offscreen HTML5 Canvas.

### Key Features

- **In-Place Canvas Erasure & Typesetting**: Samples bubble background colors locally, erases original text, and wraps translations to fit the actual bubble contour.
- **Artwork & SFX Protection**:
  - **Radial Starbursts**: Preserves spiky shout-bubble borders instead of clipping them with rectangles.
  - **Tilted Signs & Handwritten SFX**: Keeps the original artwork intact and adds a perspective-matched parallel note beside the sign.
- **Long-Strip Webtoon Streaming**: Slices tall webtoons into chunks, translates concurrently, and streams bubbles onto the page without blocking your screen.
- **Scroll & Carousel Sync**: Tracks dynamic image transforms and horizontal page-turn transitions smoothly.
- **17+ Languages & Cross-Device Sync**: Supports Google Sign-In, Email OTP, and LINUX DO Connect.

![Radial Burst and Tilted Sign Protection](https://hub.guuguo.top/assets/mangainlay-artwork.png)

![Non-Blocking Workflow](https://hub.guuguo.top/assets/mangainlay-workflow.png)

---

## Install & Try (v0.1.1)

While Chrome Web Store review is pending, you can load the extension directly:

1. Download **`MangaInlay-v0.1.1.zip`** from [GitHub Releases](https://github.com/guuguo/MangaInlay/releases/latest) or [hub.guuguo.top/mangainlay](https://hub.guuguo.top/mangainlay) and unzip it to a permanent folder.
2. Open `chrome://extensions` in Chrome or Edge.
3. Enable **Developer mode** (top-right toggle).
4. Click **Load unpacked** and select the unzipped folder.

Includes **20 free uncached pages per day** (cached community pages do not consume quota).

---

## 中文简介（漫嵌 MangaInlay）

平时追日漫、韩漫、美漫生肉时，传统翻译工具常常直接在画面上盖一个方框，挡住人物和特效。

**漫嵌（MangaInlay）** 在浏览器本地离屏 Canvas 完成底色取样、原文擦除和自适应排版，尽量还原汉化组嵌字效果：

- **本地无痕嵌字**：自动取气泡周边底色修补，连体气泡拆瓣填字，支持日漫竖排和白边描边字。
- **保护原画与拟声词**：保留爆炸气泡放射刺，手绘拟声词与倾斜门牌按原角度和颜色旁注。
- **长条漫流式渲染**：边滑边翻，不遮罩屏幕；命中云端共享缓存不扣每日免费次数。
- **官网与社区**：[https://hub.guuguo.top/mangainlay](https://hub.guuguo.top/mangainlay)
