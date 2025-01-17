![image](https://github.com/user-attachments/assets/0c08e94e-138b-4e99-94c4-8804e089ee12)
# ChromeLivetext

> **Language:** [English](#) | [简体中文](#)

---

## Introduction

ChromeLivetext is a Chrome extension that brings real-time image OCR and translation functionality to Chrome, similar to what Safari offers on macOS. This feature represents Apple's elegant interaction design: imagine watching a YouTube video and being able to pause and directly copy the text from the video screen without needing clunky third-party OCR tools. Or reading a comic where Safari can utilize macOS's Vision framework for ultra-fast and accurate OCR and translation on the device, far surpassing other open-source OCR solutions. Safari can process ten or more pages of comics in just one or two seconds.

### Current Limitations of Safari
While Safari's implementation is impressive, it still has issues. For example, when translating vertically arranged Japanese text into Chinese, the character direction is incorrect.

### Core Technology
The core of ChromeLivetext is based on:
1. Apple's built-in Vision framework for OCR.
2. A seamless front-end design that aligns recognized text with its original position on images.

### Current Progress
Currently, ChromeLivetext is **50% complete**:
- The front-end sends images from web pages to the back-end.
- The back-end utilizes Apple's Vision OCR framework but only supports English recognition at the moment.
- The alignment between recognized text and its position on the image is still suboptimal.

### How to Use
1. Install the extension on Chrome (requires enabling Developer Mode to load third-party extensions).
2. Launch `chromelivetext.app`.

### Call for Contributions
We welcome contributions from developers to help refine and expand this project. While Google has the resources to implement such a feature effortlessly, they have yet to do so. Let's make it happen together!

---

## 项目介绍

ChromeLivetext 是一个 Chrome 扩展，旨在为 Chrome 带来类似 macOS Safari 的实时图片 OCR 和翻译功能。这是一项非常棒的功能，充分体现了苹果优雅的交互设计：想象一下，你在 YouTube 上观看视频时，只需暂停即可直接复制屏幕上的文字，而无需再笨拙地打开第三方 OCR 工具。或者当你在阅读漫画时，Safari 可以实时调用 macOS 的 Vision 框架进行超快速、超精准的 OCR 和翻译，基于本地算力，速度远远超越其他开源 OCR 方案。Safari 能在一两秒内完成十多页漫画的快速 OCR 和翻译。

### Safari 的局限性
虽然 Safari 的实现令人印象深刻，但它也存在一些问题。例如，对于竖排的日语文字翻译成中文时，字符方向往往不正确。

### 核心技术
ChromeLivetext 的核心包括：
1. 苹果内置的 Vision 框架实现 OCR 功能。
2. 优雅的前端设计，能够将识别的文本完美地对齐到图片上的原始文本位置。

### 当前进展
目前，ChromeLivetext 已实现 **50%** 的功能：
- 前端能够将网页图片发送到后端。
- 后端调用了苹果内置的 Vision OCR 框架，但目前仅支持英文识别。
- 文本与图片位置的匹配仍不够理想。

### 使用方法
1. 在 Chrome 中安装扩展（需开启开发者模式加载第三方扩展）。
2. 启动 `chromelivetext.app`。

### 欢迎贡献
我们欢迎开发者一起参与改进和完善这个项目。虽然谷歌完全有能力轻松实现此功能，但他们至今未做出类似尝试。让我们一同努力，让它成为现实！
