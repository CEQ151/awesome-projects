# 📚 awesome-projects（分类规范版）

A collection of awesome GitHub projects, categorized for easy lookup.
按项目类型分类整理，便于快速检索。

## 🛠️ 一、工具类项目

### 📥 1.1 下载与录屏工具

#### 🖥️ Mac 录屏开源神器 - OpenScreen

高颜值录屏工具，可实现丝滑鼠标跟随、自动放大特写、自定义背景等功能，是付费软件 Screen Studio 的开源替代。
支持全屏/指定窗口录制、添加标注、裁剪修剪、多格式导出，适配抖音、B站、公众号等多平台发布需求。
[openscreen](https://github.com/siddharthvaddem/openscreen)

#### 📥 开源下载器 - Motrix

功能全面的开源下载工具，支持多种协议，满足日常各类下载需求。
[Motrix](https://github.com/agalwood/Motrix)

#### 📥 微信公众号下载神器

这个开源项目能把公众号文章批量下载下来。软件运行起来后能把文章的正文、配图以及底部的精选评论全部抓取下来。
文件格式方面支持得很全面，你可以选择存成网页格式、Markdown 或者更便于打印阅读的 PDF 文件。这些格式方便
后续导入到各类笔记软件中进行二次整理。使用这个工具不需要太复杂的编程知识，配置好参数后就能自动运行。
[wechat-article-exporter](https://github.com/wechat-article/wechat-article-exporter)

### 📄 1.2 PDF 处理工具

#### 📄 PDF 工具包 - BentoPDF

像精致便当盒一样集成多种 PDF 实用工具，开箱即用。所有文件处理均在本地完成，无需上传服务器，保障隐私安全。
该项目开源不久即获得 6K+ Star，是轻量高效的 PDF 处理解决方案。
[BentoPDF](https://github.com/alam00000/bentopdf)

#### 📐 PDF 数学公式翻译 - PDFMathTranslate

开源 PDF 文件翻译与双语对照项目，底层基于 AI 大模型能力，支持 DeepSeek/Ollama/OpenAI 等服务，完整保留文档排版，GitHub 已获 20K+ Star。
**核心特性**：

1. 数学公式识别与提取，保留图表、目录和注释：自动定位提取公式，支持公式中符号/函数/变量名的多语言替换
（如英文"sin"替换为中文"正弦"）；
2. 多语言&多翻译服务支持：兼容 Google、Bing、DeepL、Ollama、OpenAI、Zhipu、DeepSeek、Qwen Translation 等翻译服务，提供环境变量配置指引；
3. 多使用方式：在线体验、Windows 客户端、pip 安装、Docker/uv 部署等。

**使用入口**：

- 在线体验1：[Click](https://www.modelscope.cn/studios/AI-ModelScope/PDFMathTranslate)
- 在线体验2：[Click](https://huggingface.co/spaces/reycn/PDFMathTranslate-Docker)
- Windows 客户端：[Click](https://github.com/Byaidu/PDFMathTranslate/releases)
- pip 安装：Python 3.10 环境下执行 `pip install pdf2zh`，后输入 `pdf2zh -i`，访问 http://localhost:7860 使用
[PDFMathTranslate](https://github.com/Byaidu/PDFMathTranslate)

#### 🌐 多语言电子书&PDF翻译 - PolyglotPDF

专注于多语言电子书处理和 PDF 翻译的开源项目（近期开源），GitHub 已获 1.7K Star，支持保留原始文档布局的格式转换。

**核心特性**：

1. 高效处理：1秒内完成文字/表格/公式处理，10秒内完成整份PDF翻译；
2. 格式兼容：完整保留原版排版，支持扫描版文档（OCR）、基于文本的PDF（无需GPU），兼容EPUB、MOBI等电子书格式；
3. 灵活扩展：支持离线翻译（轻量模型），可对接 Doubao、Qwen、deepseek v3、gpt4-o-mini 等 AI 大模型，提供 API 集成能力；
4. 交互友好：提供网页版原文-译文并排对比界面。

**技术实现**：基于 PyMuPDF 库实现高效 PDF 解析和布局提取，确保翻译后格式与原版一致。

#### 📑 Zotero文献PDF翻译插件 - zotero-pdf-translate

专为文献管理软件 Zotero 设计的开源翻译插件（开发者 @windingwind 维护），提升外文文献阅读效率。

**核心特性**：

1. 全场景翻译：支持划词/拼接翻译、标题/摘要翻译、批注/注释翻译，覆盖PDF、EPub、网页内容、元数据等；
2. 多引擎兼容：集成 Google Translate、百度、DeepL、OpenAI 等 20+ 翻译服务，支持多引擎同时使用对比结果；
3. 适配科研场景：专为科研人员/学生设计，是处理外文学术文献的高效工具。
[zotero-pdf-translate](https://github.com/windingwind/zotero-pdf-translate)

### 🎵🎬 1.3 音视频处理工具

#### 🎤 语音转文本 - Handy

完全离线、免费开源的语音转文本桌面应用，秉持隐私优先原则，所有处理均在本地完成，语音数据不出域。
基于 Tauri 框架构建，保证轻量级和高性能；集成 OpenAI Whisper 和 CPU 优化的 Parakeet 模型，支持 Windows、macOS、Linux 多系统，具备全局快捷键听写功能。
[Handy](https://github.com/cjpais/Handy)

#### 🗣️ 文本转语音模型 - Chatterbox

由 Resemble AI 开源的 TTS 模型，提供高质量、低延迟语音生成能力。
包含 3.5 亿参数的 Chatterbox-Turbo 模型，通过压缩解码过程降低显存占用和计算需求；支持多语言生成、原生副语言标签（笑声/咳嗽等），生成音频含 PerTh 水印防止滥用。
[chatterbox](https://github.com/resemble-ai/chatterbox)

#### 🔊 音频分割模型 - sam-audio

Meta 推出的专业音频分割模型，可实现精准的音频内容分割，适用于音频处理场景。
[sam-audio](https://github.com/facebookresearch/sam-audio)

### 🖥️ 1.4 系统工具

#### 🖨️ 远程桌面软件 - CrossDesk

开源远程桌面软件，GitHub 拥有 3.3K+ Star，主打轻量级和跨平台，核心代码基于 C++ 编写，运行效率高、资源占用低。
支持 Windows、macOS、Ubuntu 主流桌面系统，且提供 Web 客户端，可通过浏览器（如 iOS Safari）直接控制远程电脑。
技术层面基于 MiniRTC 实时音视频传输库，具备网络透传、音视频软硬编解码、网络拥塞控制、传输加密等能力，保障画面流畅且安全。
[crossdesk](https://github.com/kunkundi/crossdesk)

## 🤖️ 二、AI 相关项目

### 🎨 2.1 AI 生成与创作

#### 🎬 视频转手绘故事 - clipsketch-ai

纯前端项目，支持输入 B站/小红书视频链接生成带打点功能的播放器，可快速截取视频帧。
核心亮点是集成 Google Gemini 大模型，能将截图转为手绘风格分镜草图，并自动生成小红书文案；采用 React + Tailwind CSS，数据本地存储，适配竖屏/宽屏视频。
[clipsketch-ai](https://github.com/RanFeng/clipsketch-ai)

#### 🎨 图层 AI 生成模型 - Qwen-Image-Layered

阿里推出的 AI 生成模型，区别于普通图片生成，可直接生成自带图层的图像，等效于获取 PSD 源文件，大幅提升设计工作效率。
[Qwen-Image-Layered](https://github.com/QwenLM/Qwen-Image-Layered)

#### 📊 AI 画流程图 - next-ai-draw-io

基于 Next.js 构建，融合 AI 与 draw.io 能力的 Web 应用。
支持通过自然语言生成/修改图表，也可上传手绘草图/截图，通过多模态视觉能力复刻为可编辑的 draw.io 图表，适用于白板会议记录数字化。
[next-ai-draw-io](https://github.com/DayuanJiang/next-ai-draw-io)

#### 📑 AI制作PPT - PPT Agent

中科院计算所开源项目，支持根据一句话生成PPT，或读取长文档自动提炼重点生成幻灯片。
区别于简单的文本转PPT工具，采用多智能体（Multi-Agent）流程，模拟人类制作PPT的完整思考过程。
[ppt-agent](https://github.com/icip-cas/PPTAgent)

### 🧠 2.2 AI 智能体

#### 🖥️ AI 接管系统 - TuriX-CUA

让 AI 模拟人类操作电脑的智能体，具备视觉感知和键鼠控制能力，像人一样操作屏幕、执行任务。
引入多模型架构，测试集通过率超 80%，可自动完成各类电脑操作任务。
[TuriX-CUA](https://github.com/TurixAI/TuriX-CUA)

#### 📚 读论文 Agent - Paper Burner X

集文献识别、翻译、阅读与智能分析于一体的纯前端工具，浏览器打开即可使用。
支持 PDF/Word/PPT/EPUB 等格式导入，极速并发翻译且保留公式/图表格式；具备智能分析、自动生成思维导图/流程图、原译文对比标注等功能。
[paper-burner-x](https://github.com/Feather-2/paper-burner-x)

#### 🧩 Everywhere Agent

可读取屏幕内容的 AI 智能助手，按下快捷键即可在鼠标位置调出输入框，自动读取光标附近/当前窗口内容作为上下文，快速解答问题（如代码报错修复、代码解释、文本润色）。
支持 OpenAI、Claude、Gemini、DeepSeek、Kimi 等主流模型 API，也兼容 Ollama 本地开源模型；集成 MCP 工具，可安全连接本地文件系统、浏览器、终端。
[Everywhere](https://github.com/DearVa/Everywhere)

## 💻 三、开发与学习相关

### 🧮 3.1 算法学习

#### 🧑‍💻 JS 算法与数据结构 - javascript-algorithms

专为 JavaScript 开发者打造的算法学习项目，累计 195K+ Star。
用现代 JavaScript 代码实现各类计算机科学算法和数据结构，通俗易懂，适合初级工程师进阶、大厂算法面试准备。
[javascript-algorithms](https://github.com/trekhleb/javascript-algorithms)

### 🌐 3.2 免费域名开源项目

#### 🌐 FreeDomain

宗旨是让每个人都能拥有免费域名，提供 DPDNS.ORG、US.KG、XX.KG 等后缀，可在官方控制面板直接注册，全程免费且无需支付验证。
核心亮点是支持第三方 DNS 服务（Cloudflare、FreeDNS 等），可零成本搭建具备 CDN 加速/DDoS 防护的网站。
目前已有数十万个域名通过该平台注册，项目持续维护，计划新增更多域名后缀和免费主机服务；适合学生党、开发者练习建站/部署应用（需遵守规定，滥用会封禁账户）。
[FreeDomain](https://github.com/DigitalPlatDev/FreeDomain)

## 📊 四、效率与办公相关

### 📝 4.1 简历相关

#### 📄 YAML 写简历 - rendercv

通过 YAML 配置文件填写经历、技能，自动生成排版精美的 PDF/Markdown 简历。
基于 LaTeX 专业排版引擎，无需编写复杂 LaTeX 代码；提供多种内置主题，修改一行配置即可切换风格，适合频繁更新简历的场景。
[rendercv](https://github.com/rendercv/rendercv)

#### 🔍 简历匹配器 - Resume-Matcher

24.7K+ Star 的求职辅助工具，解决简历投出无回应的问题。
可分析简历与职位描述的匹配度，识别缺失的关键词，避免因关键词不足/格式问题被系统初筛淘汰。
[Resume-Matcher](https://github.com/srbhr/Resume-Matcher)

### 🏡 4.2 生活服务

#### 📍 约会地点推荐 - MeetSpot

用于推荐约会地点的开源项目，助力解决约会选址难题，提升生活便捷性。
[MeetSpot](https://github.com/JasonRobertDestiny/MeetSpot)

## 🎮 五、娱乐休闲

### 🎵 高颜值歌词工具 - BetterLyrics

Windows 平台颜值极高的歌词可视化工具（兼音乐播放功能），基于 WinUI3 开发，界面贴合 Windows 11 现代风格，支持毛玻璃特效、流体背景。
提供全屏沉浸（屏保）、桌面悬浮、屏幕边缘停靠等多种显示模式；可播放本地音乐，支持 SMB/WebDAV 连接 NAS 听歌，且能自动识别 Spotify、Apple Music、网易云音乐、QQ 音乐等主流软件正在播放的歌曲并同步显示歌词。
[BetterLyrics](https://github.com/jayfunc/BetterLyrics)
