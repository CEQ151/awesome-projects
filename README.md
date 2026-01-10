# 📚 awesome-projects（分类规范版）

A collection of awesome GitHub projects, categorized for easy lookup.
按项目类型分类整理，便于快速检索。

## 🛠️ 一、工具类项目

### 📥 1.1 下载与录屏工具

#### 🖥️ Mac 录屏开源神器 - OpenScreen
高颜值录屏工具，可实现丝滑鼠标跟随、自动放大特写、自定义背景等功能，
是付费软件 Screen Studio 的开源替代。
支持全屏/指定窗口录制、添加标注、裁剪修剪、多格式导出，适配抖音、
B站、公众号等多平台发布需求。
[openscreen](https://github.com/siddharthvaddem/openscreen)

#### 📥 开源下载器 - Motrix
功能全面的开源下载工具，支持多种协议，满足日常各类下载需求。
[Motrix](https://github.com/agalwood/Motrix)

### 📄 1.2 PDF 处理工具

#### 📄 PDF 工具包 - BentoPDF
像精致便当盒一样集成多种 PDF 实用工具，开箱即用。所有文件处理均在本
地完成，无需上传服务器，保障隐私安全。
该项目开源不久即获得 6K+ Star，是轻量高效的 PDF 处理解决方案。
[BentoPDF](https://github.com/alam00000/bentopdf)

### 🎵🎬 1.3 音视频处理工具

#### 🎤 语音转文本 - Handy
完全离线、免费开源的语音转文本桌面应用，秉持隐私优先原则，所有处理均在本
地完成，语音数据不出域。
基于 Tauri 框架构建，保证轻量级和高性能；集成 OpenAI Whisper 和 CPU 优
化的 Parakeet 模型，支持 Windows、macOS、Linux 多系统，具备全局快捷键听写功能。
[Handy](https://github.com/cjpais/Handy)

#### 🗣️ 文本转语音模型 - Chatterbox
由 Resemble AI 开源的 TTS 模型，提供高质量、低延迟语音生成能力。
包含 3.5 亿参数的 Chatterbox-Turbo 模型，通过压缩解码过程降低显存占用和计
算需求；支持多语言生成、原生副语言标签（笑声/咳嗽等），生成音频含 PerTh 水
印防止滥用。
[chatterbox](https://github.com/resemble-ai/chatterbox)

#### 🔊 音频分割模型 - sam-audio
Meta 推出的专业音频分割模型，可实现精准的音频内容分割，适用于音频处理场景。
[sam-audio](https://github.com/facebookresearch/sam-audio)

### 🖥️ 1.4 系统工具

#### 🖨️ 远程桌面软件 - CrossDesk
开源远程桌面软件，GitHub 拥有 3.3K+ Star，主打轻量级和跨平台，核心代码基于 
C++ 编写，运行效率高、资源占用低。
支持 Windows、macOS、Ubuntu 主流桌面系统，且提供 Web 客户端，可通过浏览器（
如 iOS Safari）直接控制远程电脑。
技术层面基于 MiniRTC 实时音视频传输库，具备网络透传、音视频软硬编解码、网络
拥塞控制、传输加密等能力，保障画面流畅且安全。
[crossdesk](https://github.com/kunkundi/crossdesk)

## 🤖️ 二、AI 相关项目

### 🎨 2.1 AI 生成与创作

#### 🎬 视频转手绘故事 - clipsketch-ai
纯前端项目，支持输入 B站/小红书视频链接生成带打点功能的播放器，可快速截取视频帧。
核心亮点是集成 Google Gemini 大模型，能将截图转为手绘风格分镜草图，并自动生成
小红书文案；采用 React + Tailwind CSS，数据本地存储，适配竖屏/宽屏视频。
[clipsketch-ai](https://github.com/RanFeng/clipsketch-ai)

#### 🎨 图层 AI 生成模型 - Qwen-Image-Layered
阿里推出的 AI 生成模型，区别于普通图片生成，可直接生成自带图层的图像，等效于
获取 PSD 源文件，大幅提升设计工作效率。
[Qwen-Image-Layered](https://github.com/QwenLM/Qwen-Image-Layered)

#### 📊 AI 画流程图 - next-ai-draw-io
基于 Next.js 构建，融合 AI 与 draw.io 能力的 Web 应用。
支持通过自然语言生成/修改图表，也可上传手绘草图/截图，通过多模态视觉能力复刻为
可编辑的 draw.io 图表，适用于白板会议记录数字化。
[next-ai-draw-io](https://github.com/DayuanJiang/next-ai-draw-io)

#### 📑 AI制作PPT - PPT Agent
中科院计算所开源项目，支持根据一句话生成PPT，或读取长文档自动提炼重点生成幻灯片。
区别于简单的文本转PPT工具，采用多智能体（Multi-Agent）流程，模拟人类制作PPT的完整
思考过程。
[ppt-agent](https://github.com/icip-cas/PPTAgent)

### 🧠 2.2 AI 智能体

#### 🖥️ AI 接管系统 - TuriX-CUA
让 AI 模拟人类操作电脑的智能体，具备视觉感知和键鼠控制能力，像人一样操作屏幕、执行任务。
引入多模型架构，测试集通过率超 80%，可自动完成各类电脑操作任务。
[TuriX-CUA](https://github.com/TurixAI/TuriX-CUA)

#### 📚 读论文 Agent - Paper Burner X
集文献识别、翻译、阅读与智能分析于一体的纯前端工具，浏览器打开即可使用。
支持 PDF/Word/PPT/EPUB 等格式导入，极速并发翻译且保留公式/图表格式；具备智能分析、
自动生成思维导图/流程图、原译文对比标注等功能。
[paper-burner-x](https://github.com/Feather-2/paper-burner-x)

#### 🧩 Everywhere Agent
可读取屏幕内容的 AI 智能助手，按下快捷键即可在鼠标位置调出输入框，自动读取
光标附近/当前窗口内容作为上下文，快速解答问题（如代码报错修复、代码解释、文本润色）。
支持 OpenAI、Claude、Gemini、DeepSeek、Kimi 等主流模型 API，也兼容 Ollama 本地开源模型；
集成 MCP 工具，可安全连接本地文件系统、浏览器、终端。
[Everywhere](https://github.com/DearVa/Everywhere)

## 💻 三、开发与学习相关

### 🧮 3.1 算法学习

#### 🧑‍💻 JS 算法与数据结构 - javascript-algorithms
专为 JavaScript 开发者打造的算法学习项目，累计 195K+ Star。
用现代 JavaScript 代码实现各类计算机科学算法和数据结构，通俗易懂，适合初级工程师进阶、
大厂算法面试准备。
[javascript-algorithms](https://github.com/trekhleb/javascript-algorithms)

### 🌐 3.2 免费域名开源项目

#### 🌐 FreeDomain
宗旨是让每个人都能拥有免费域名，提供 DPDNS.ORG、US.KG、XX.KG 等后缀，可在官方控制面板
直接注册，全程免费且无需支付验证。
核心亮点是支持第三方 DNS 服务（Cloudflare、FreeDNS 等），可零成本搭建具备 CDN 加速/DDoS 
防护的网站。
目前已有数十万个域名通过该平台注册，项目持续维护，计划新增更多域名后缀和免费主机服务；
适合学生党、开发者练习建站/部署应用（需遵守规定，滥用会封禁账户）。
[FreeDomain](https://github.com/DigitalPlatDev/FreeDomain)

## 📊 四、效率与办公相关

### 📝 4.1 简历相关

#### 📄 YAML 写简历 - rendercv
通过 YAML 配置文件填写经历、技能，自动生成排版精美的 PDF/Markdown 简历。
基于 LaTeX 专业排版引擎，无需编写复杂 LaTeX 代码；提供多种内置主题，修改一行配置即可切换风格，
适合频繁更新简历的场景。
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

#### 🎵 高颜值歌词工具 - BetterLyrics
Windows 平台颜值极高的歌词可视化工具（兼音乐播放功能），基于 WinUI3 开发，界面贴合 
Windows 11 现代风格，支持毛玻璃特效、流体背景。
提供全屏沉浸（屏保）、桌面悬浮、屏幕边缘停靠等多种显示模式；可播放本地音乐，支持 SMB/WebDAV 
连接 NAS 听歌，且能自动识别 Spotify、Apple Music、网易云音乐、QQ 音乐等主流软件正在播放的
歌曲并同步显示歌词。
[BetterLyrics](https://github.com/jayfunc/BetterLyrics)