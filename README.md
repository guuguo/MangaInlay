<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://hub.guuguo.top/assets/mangainlay-banner-dark.png?v=20261123v3" />
  <source media="(prefers-color-scheme: light)" srcset="https://hub.guuguo.top/assets/mangainlay-banner-light.png?v=20261123v3" />
  <img src="https://hub.guuguo.top/assets/mangainlay-banner-light.png?v=20261123v3" alt="漫嵌 MangaInlay — 生肉漫画与条漫原位气泡嵌字翻译插件" width="100%" />
</picture>

# 漫嵌 MangaInlay

**生肉漫画与条漫实时原位气泡嵌字翻译浏览器插件 — 不贴白膏药，译文直接嵌进原本的气泡里**

[![Chrome Web Store](https://img.shields.io/badge/Chrome%20Web%20Store-v0.1.2-0ea5e9?style=flat-square&logo=googlechrome&logoColor=white)](https://chromewebstore.google.com/detail/jchdohdejkkonpocnjipingjgagfeibn)
[![Edge Add-ons](https://img.shields.io/badge/Edge%20Add--ons-v0.1.2-0078d4?style=flat-square&logo=microsoftedge&logoColor=white)](https://microsoftedge.microsoft.com/addons/detail/iioeeclifijdikhefbihncbdngmlkmci)
[![Official Website](https://img.shields.io/badge/%E5%AE%98%E7%BD%91-hub.guuguo.top-e5432d?style=flat-square)](https://hub.guuguo.top/mangainlay)
[![Store Release](https://img.shields.io/badge/%E5%95%86%E5%BA%97%E7%BA%BF%E4%B8%8A%E7%89%88-v0.1.2%20%E5%B7%B2%E4%B8%8A%E7%BA%BF-16a34a?style=flat-square)](https://chromewebstore.google.com/detail/jchdohdejkkonpocnjipingjgagfeibn)

**简体中文** · [English](#english-summary)

<br />

<img src="https://hub.guuguo.top/assets/mangainlay-demo-github.gif?v=20261123v3" width="800" alt="漫嵌 MangaInlay 实机演示：滚动生肉页、墨迹浮现中文气泡、按住 Alt 看原图" />

</div>

---

## 安装

推荐直接从官方扩展商店安装，装完即用，自动更新（无需配置任何 API Key）：

- **Chrome 用户**：前往 [Chrome Web Store 安装 漫嵌 MangaInlay（v0.1.2）](https://chromewebstore.google.com/detail/jchdohdejkkonpocnjipingjgagfeibn)
- **Edge 用户（国内免梯直装）**：前往 [Microsoft Edge Add-ons 安装 漫嵌 MangaInlay（v0.1.2）](https://microsoftedge.microsoft.com/addons/detail/iioeeclifijdikhefbihncbdngmlkmci)
- **Android 手机 / 平板（直装正式版 v0.1.0）**：[官网直链下载 APK](https://hub.guuguo.top/downloads/MangaInlay-Android-v0.1.0.apk) · [GitHub Releases（支持 Obtainium 追更）](https://github.com/guuguo/MangaInlay/releases/tag/android-v0.1.0)
- **产品官网 & 在线演示**：[https://hub.guuguo.top/mangainlay](https://hub.guuguo.top/mangainlay)

<details>
<summary>开发者 / 离线手动安装（.zip）</summary>

1. 从官网下载打包归档：[mangainlay-extension.zip](https://hub.guuguo.top/downloads/mangainlay-extension.zip)（本地源码目录 `extension/` 也可直接加载）。
2. 解压到本地固定文件夹（请勿删除该文件夹）。
3. 在地址栏打开 `chrome://extensions`（或 `edge://extensions`），开启右上角 **开发者模式**。
4. 点击 **加载已解压的扩展程序**，选择解压后的目录即可。

</details>

---

## 能做什么

- **本地原位无痕嵌字**：后端只返回紧凑的气泡坐标与译文 JSON，扩展在浏览器本地离屏 `<canvas>` 吸取底色、擦除原文并按气泡轮廓自适应排版；支持高宽比 `> 1.65` 自动日漫竖排与多字体矩阵。
- **按住 `Alt` 秒看原图 & 流式预读**：读生肉时随时按住键盘 `Alt` 透出原文对照，松手恢复译文；条漫往下滑自动领先 2 屏并发预取。

| 爆炸气泡不糊（日漫竖排） | 拟声词与倾斜门牌保留原画 | 多色无框字重排（繁/日/韩 → 简体） |
| :---: | :---: | :---: |
| <img src="https://hub.guuguo.top/assets/compare-burst-before.png?v=20261123v3" width="200" alt="爆炸气泡生肉" /> <img src="https://hub.guuguo.top/assets/compare-burst-after.png?v=20261123v3" width="200" alt="爆炸气泡中文嵌字" /> | <img src="https://hub.guuguo.top/assets/compare-sign-before.png?v=20261123v3" width="200" alt="倾斜门牌生肉" /> <img src="https://hub.guuguo.top/assets/compare-sign-after.png?v=20261123v3" width="200" alt="倾斜门牌平行旁注" /> | <img src="https://hub.guuguo.top/assets/compare-caption-before.png?v=20261123v3" width="220" alt="红黑无框生肉" /> <img src="https://hub.guuguo.top/assets/compare-caption-after.png?v=20261123v3" width="220" alt="干净居中重排中文" /> |

---

## 额度与价格

所有口径与插件端、官网保持严格一致：

| 方案 | 价格 | 额度与权益 |
| --- | --- | --- |
| **免费体验** | `¥0` | 每日 **30 格**全新 AI 识别（约 1.5 话），首日首次使用额外加赠 **+30 格**（首日共 **60 格** ≈ 3 话）；免登录即用 |
| **7 天畅看卡（推荐）** | **¥6.9** / 7 天 | 7 天内全站生肉无限翻译、4× 并发预取；爱发电微信 / 支付宝扫码付完自动轮询秒激活 |
| **Pro 月卡** | **¥19** / 30 天（海外 **$4.9**/月） | 30 天无限畅读、跨设备账号同步（Google / LINUX DO）与优先调度通道 |

- **缓存 0 消耗承诺**：无论是你看过的**本地 IndexedDB 缓存**，还是其他漫迷已经翻好的**云端共享缓存**，命中时一律 **0 消耗（不扣每日额度，即使剩余 0 格也可秒开）**。
- **拦截保护**：极少数被 AI 安全策略跳过的画面直接标为未处理，**同样不扣额度、不写脏缓存**。

---

## 隐私

- 未命中缓存时，扩展仅对当前漫画长图做分段压缩并加密发送至后端（`https://mangainlay-api.guuguo.top`），交由 Gemini Vision 识别气泡 `box_2d` 与译文 JSON；**涂白与嵌字渲染全部在你的浏览器本地完成，不读取其他非漫画标签页**。
- 云端共享缓存仅以图片哈希保存识别出的坐标与译文 JSON，用于二次访问秒开，**不长期留存原始漫画图片**。
- 完整说明见 [隐私政策](https://mangainlay-api.guuguo.top/privacy)。

---

## 自部署后端

欢迎 Star 或参考 `backend/` 自建轻量无图片回传的 JSON 翻译服务端：

- **技术栈**：Node.js 22+ 原生 HTTP 服务（Cloud Run） + Vertex AI / Gemini Flash Vision JSON Schema + Firestore（可选）。
- **本地运行测试**：

```bash
cd backend && npm test
```

- 将扩展设置页开启开发者模式（`options.html?dev=1`），即可指向你自己的后端地址与 `X-Translator-Token`。

---

## English Summary

**MangaInlay** is an in-place Chrome & Edge extension that translates raw manga, manhwa, and long-strip webtoons directly inside their original speech bubbles without slapping opaque white boxes over artwork.

- **Install**: [Chrome Web Store (v0.1.2)](https://chromewebstore.google.com/detail/jchdohdejkkonpocnjipingjgagfeibn) · [Edge Add-ons (v0.1.2)](https://microsoftedge.microsoft.com/addons/detail/iioeeclifijdikhefbihncbdngmlkmci) · [Homepage](https://hub.guuguo.top/mangainlay)
- **Android App (v0.1.0)**: [Direct APK Download](https://hub.guuguo.top/downloads/MangaInlay-Android-v0.1.0.apk) · [GitHub Releases](https://github.com/guuguo/MangaInlay/releases/tag/android-v0.1.0)
- **Free Quota & Caching**: Free users get **30 uncached slices/day** (~1.5 chapters) plus a **+30 Day-1 welcome bonus** (60 slices on Day 1). **Both local IndexedDB cache and shared cloud cache hits deduct 0 quota**, and safety-blocked panels never deduct quota.
- **Passes**: ¥6.9 / 7 days, ¥19 / 30 days, or $4.9 / month globally.
- **Self-Hosting**: See `backend/` for the lightweight Google Cloud Run + Gemini Vision JSON service (`cd backend && npm test`).
