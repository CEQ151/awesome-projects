# awesome-projects（分类规范版）

A collection of awesome GitHub projects, categorized for easy lookup.
按项目类型分类整理，便于快速检索。

## 一、工具类项目

### 1.1 下载与录屏工具

#### Mac 录屏开源神器 - OpenScreen

高颜值录屏工具，可实现丝滑鼠标跟随、自动放大特写、自定义背景等功能，
是付费软件 Screen Studio 的开源替代。

支持全屏/指定窗口录制、添加标注、裁剪修剪、多格式导出，适配抖音、B 站、
公众号等多平台发布需求。

[openscreen](https://github.com/siddharthvaddem/openscreen)

#### 开源下载器 - Motrix

功能全面的开源下载工具，支持多种协议，满足日常各类下载需求。

[Motrix](https://github.com/agalwood/Motrix)

### 1.2 PDF 处理工具

#### PDF 工具包 - BentoPDF

像精致便当盒一样集成多种 PDF 实用工具，开箱即用。所有文件处理均在本地完成，
无需上传服务器，保障隐私安全。

该项目开源不久即获得 6K+ Star，是轻量高效的 PDF 处理解决方案。

[BentoPDF](https://github.com/alam00000/bentopdf)

### 1.3 音视频处理工具

#### 语音转文本 - Handy

完全离线、免费开源的语音转文本桌面应用，秉持隐私优先原则，所有处理均在本地完成，
语音数据不出域。

基于 Tauri 框架构建，保证轻量级和高性能；集成 OpenAI Whisper 和 CPU 优化的
Parakeet 模型，支持 Windows、macOS、Linux 多系统，具备全局快捷键听写功能。

[Handy](https://github.com/cjpais/Handy)

#### 文本转语音模型 - Chatterbox

由 Resemble AI 开源的 TTS 模型，提供高质量、低延迟语音生成能力。

包含 3.5 亿参数的 Chatterbox-Turbo 模型，通过压缩解码过程降低显存占用和计算需求；
支持多语言生成、原生副语言标签（笑声/咳嗽等），生成音频含 PerTh 水印防止滥用。

[chatterbox](https://github.com/resemble-ai/chatterbox)

#### 音频分割模型 - sam-audio

Meta 推出的专业音频分割模型，可实现精准的音频内容分割，适用于音频处理场景。

[sam-audio](https://github.com/facebookresearch/sam-audio)

### 1.4 系统工具

#### 远程桌面软件

CrossDesk 是一款开源的远程桌面软件。现在在 GitHub 上有 3.3K 的 Star 了。
它主打轻量级和跨平台，我看了一下它的代码仓库，主要使用 C++ 编写，占比很高，
它的运行效率和资源占用控制得相当不错。  

它支持主流的桌面操作系统。Windows、macOS、Ubuntu 都能运行。
重点是它支持 Web 客户端，很多时候我们在外面 CrossDesk 的
优势就能出来。你只需要打开浏览器，输入被控端的 ID 和密码，
就能直接在网页里控制远程电脑。比如用你 iOS 的 Safari 
浏览器去控制一台 Windows 11 的电脑。  

在技术实现上，CrossDesk 基于 MiniRTC 这个实时音视频传输库。
它具备很多成熟的基础能力，比如网络透传、视频软硬编解码、
音频编解码、网络拥塞控制以及传输加密。这些特性保证了在使用过
程中画面流畅且安全。

[crossdesk](https://github.com/kunkundi/crossdesk)

## 二、AI 相关项目

### 2.1 AI 生成与创作

#### 视频转手绘故事 - clipsketch-ai

纯前端项目，支持输入 B 站/小红书视频链接生成带打点功能的播放器，可快速截取视频帧。

核心亮点是集成 Google Gemini 大模型，能将截图转为手绘风格分镜草图，并自动生成
小红书文案；采用 React + Tailwind CSS，数据本地存储，适配竖屏/宽屏视频。

[clipsketch-ai](https://github.com/RanFeng/clipsketch-ai)

#### 图层 AI 生成模型 - Qwen-Image-Layered

阿里推出的 AI 生成模型，区别于普通图片生成，可直接生成自带图层的图像，
等效于获取 PSD 源文件，大幅提升设计工作效率。

[Qwen-Image-Layered](https://github.com/QwenLM/Qwen-Image-Layered)

#### AI 画流程图 - next-ai-draw-io

基于 Next.js 构建，融合 AI 与 draw.io 能力的 Web 应用。

支持通过自然语言生成/修改图表，也可上传手绘草图/截图，通过多模态视觉能力复刻为
可编辑的 draw.io 图表，适用于白板会议记录数字化。

[next-ai-draw-io](https://github.com/DayuanJiang/next-ai-draw-io)

#### AI制作PPT

PPT Agent  
PPTAgent 是中科院计算所开源的项目。它不仅能根据一句话生成PPT，
还能直接读懂长文档，自动提炼重点生成幻灯片。与市面上简单的文本转Markdown转PPT不同，
PPTAgent 采用了一种更加智能的多智能体（Multi-Agent） 流程，
模拟了人类制作 PPT 的完整思考过程。

[ppt-agent](https://github.com/icip-cas/PPTAgent)

### 2.2 AI 智能体

#### AI 接管系统 - TuriX-CUA

让 AI 模拟人类操作电脑的智能体，具备视觉感知和键鼠控制能力，像人一样操作屏幕、
执行任务。

引入多模型架构，测试集通过率超 80%，可自动完成各类电脑操作任务。

[TuriX-CUA](https://github.com/TurixAI/TuriX-CUA)

#### 读论文 Agent - Paper Burner X

集文献识别、翻译、阅读与智能分析于一体的纯前端工具，浏览器打开即可使用。

支持 PDF/Word/PPT/EPUB 等格式导入，极速并发翻译且保留公式/图表格式；具备智能分析、
自动生成思维导图/流程图、原译文对比标注等功能。

[paper-burner-x](https://github.com/Feather-2/paper-burner-x)

#### Everywhere Agent

Everywhere 这个项目就是为了解决这个问题诞生的，它能看懂你屏幕上正在显
示的内容。比如你写代码的时候报错了，不需要截图也不需要复制。直接按下快捷键
，Everywhere 的输入框就会出现在你当前鼠标的位置。它会自动读取光标附近的文
本或者当前窗口的内容作为上下文。你只需要直接问它：这个错误怎么修？这几行代
码什么意思？这段话帮我润色一下。它就能立刻结合你屏幕上的内容给出答案。这就
把原本割裂的 AI 交互完全融入到了你的操作流里。  

对于模型支持方面，它非常全面。不仅支持 OpenAI、Claude、Gemini 这些主流大
厂的 API，国内的 DeepSeek、Kimi 也都在支持列表里。也支持 Ollama，配合本地
运行的开源模型使用。还有一个值得一提的技术点是它集成了 MCP 工具，让 AI 可
以更安全地连接本地文件系统、浏览器甚至终端。这让它不仅仅是一个聊天机器人，更
像是一个能帮你操作电脑的智能助手。  

[Everywhere](https://github.com/DearVa/Everywhere)



## 三、开发与学习相关

### 3.1 算法学习

#### JS 算法与数据结构 - javascript-algorithms

专为 JavaScript 开发者打造的算法学习项目，累计 195K+ Star。

用现代 JavaScript 代码实现各类计算机科学算法和数据结构，通俗易懂，适合初级工程师
进阶、大厂算法面试准备。

[javascript-algorithms](https://github.com/trekhleb/javascript-algorithms)

### 3.2 免费域名开源项目

FreeDomain 的宗旨是让每个人都能拥有免费的域名。它提供 DPDNS.ORG 和 US.KG 以及 
XX.KG 等多种后缀。用户可以在其官方控制面板中直接注册。整个过程完全免费且无需繁琐
的支付验证。  

该项目最大的亮点在于对第三方 DNS 服务的支持。你注册的域名可以托管到 Cloudflare 
或 FreeDNS 等平台。这对于需要 CDN 加速或 DDoS 防护的用户来说非常实用。配合 
Cloudflare 的免费计划，你可以零成本搭建一个具备完整功能的网站。  

目前已有数十万个域名通过该平台注册。这在一定程度上证明了服务的可用性。项目团队也
在持续维护和更新，未来还有计划增加更多域名后缀和免费主机服务。对于学生党和开发者而
言，这是一个练习建站和部署应用的绝佳资源。你可以利用这些免费域名部署博客或测试新的代
码框架。不过使用时请务必遵守相关规定。任何滥用行为都会导致账户被封禁。  

[FreeDomain](https://github.com/DigitalPlatDev/FreeDomain)

## 四、效率与办公相关

### 4.1 简历相关

#### YAML 写简历 - rendercv

通过 YAML 配置文件填写经历、技能，自动生成排版精美的 PDF/Markdown 简历。

基于 LaTeX 专业排版引擎，无需编写复杂 LaTeX 代码；提供多种内置主题，修改一行配置
即可切换风格，适合频繁更新简历的场景。

[rendercv](https://github.com/rendercv/rendercv)

#### 简历匹配器 - Resume-Matcher

24.7K+ Star 的求职辅助工具，解决简历投出无回应的问题。

可分析简历与职位描述的匹配度，识别缺失的关键词，避免因关键词不足/格式问题被系统
初筛淘汰。

[Resume-Matcher](https://github.com/srbhr/Resume-Matcher)

### 4.2 生活服务

#### 约会地点推荐 - MeetSpot

用于推荐约会地点的开源项目，助力解决约会选址难题，提升生活便捷性。

[MeetSpot](https://github.com/JasonRobertDestiny/MeetSpot)  

## 五、娱乐休闲

这是一个 Windows 上颜值极高的歌词工具。基于 WinUI3 开发的歌词可视
化工具，同时也具备音乐播放功能。第一眼看到它，你会被它的颜值吸引。
它的界面设计完全贴合 Windows 11 的现代风格，毛玻璃特效和流体背景非
常漂亮。  

它提供了多种显示模式。你可以选择全屏沉浸模式，把它当做一个精美的屏保
。也可以选择桌面模式，让歌词悬浮在所有窗口之上。还有一个停靠模式，
能在屏幕边缘显示一个简洁的歌词栏。

它自己可以播放本地音乐，也支持 SMB 和 WebDAV 协议连接 NAS 听歌。更
重要的是，它能完美配合其他主流音乐软件使用。无论你用的是 Spotify、
Apple Music，还是网易云音乐、QQ 音乐，它都能自动识别正在播放的歌
曲并同步显示歌词。  

[BetterLyrics](https://github.com/jayfunc/BetterLyrics)


