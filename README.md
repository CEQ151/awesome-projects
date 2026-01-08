# awesome-projects

A collection of awesome GitHub projects.

## Turning Video into Hand-drawn stories

这个开源项目挺有意思，你把B站或者小红书的视频链接丢进去，它就能变身成一个带打点功能的播放器。看到哪个画面有感觉，按个快捷键就能把那一帧截下来，不用你自己再去截图工具里折腾。但这玩意儿最核心的其实是AI脑补能力。它接Google Gemini的大模型，能把你截下来的那些视频画面瞬间变成手绘风格的分镜草图，甚至还能根据画面内容自动帮你写好发小红书的文案。

技术上它是个纯前端项目，用了 React 和 Tailwind CSS，数据也是存在浏览器本地的，不用担心隐私泄露。作者把交互做得挺细，针对竖屏视频和宽屏视频都有适配，甚至还考虑了批量生成来省 API 的钱，看得出是懂内容创作者痛点的。

开源地址：<https://github.com/RanFeng/clipsketch-ai>

## 哪里约会？MeetSpot

开源地址：<https://github.com/JasonRobertDestiny/MeetSpot>

## Meta 推出音频分割模型

开源地址：<https://github.com/facebookresearch/sam-audio>

## 阿里推出图层 AI 生成模型

Qwen-Image-Layered 生成的不是一张图，而是自带图层的图像，就像是你直接得到了一个 PSD 源文件。

开源地址：<https://github.com/QwenLM/Qwen-Image-Layered>

## 让 AI 接管 Windows 和 MacOS

这个叫 TuriX-CUA 的开源项目也是一个让 AI 替你玩电脑的 AI 智能体。它也是给 AI 装上眼睛和手，让它像人一样看着屏幕，动鼠标、敲键盘，帮你把活儿干了。前两天，TuriX-CUA 刚更新了一波大的，引入了多模型架构，在测试集通过率超过 了 80%，确实有点东西。

开源地址：<https://github.com/TurixAI/TuriX-CUA>

## 用 YAML 去写简历

你只需要把你的经历、技能像填表一样写在配置文件里，它就能自动帮你生成各种排版精美的 PDF 和 Markdown。

这个开源项目把内容和表现分离了。它底层走的是 LaTeX 那套专业排版引擎，但你完全不需要去写那些晦涩的 LaTeX 代码。它还贴心地提供了一些内置的主题，基本涵盖了程序员和学术界主流的审美。如果

# awesome-projects

A collection of awesome GitHub projects.

## Turning Video into Hand-drawn stories

这个开源项目挺有意思，你把B站或者小红书的视频链接丢进去，它就能变身成一个带打点功能的播放器。
看到哪个画面有感觉，按个快捷键就能把那一帧截下来，不用你自己再去截图工具里折腾。
但这玩意儿最核心的其实是AI脑补能力。它接Google Gemini的大模型，能把你截下来的那些视频画面
瞬间变成手绘风格的分镜草图，甚至还能根据画面内容自动帮你写好发小红书的文案。

技术上它是个纯前端项目，用了 React 和 Tailwind CSS，数据也是存在浏览器本地的，不用担心隐私泄露。
作者把交互做得挺细，针对竖屏视频和宽屏视频都有适配，甚至还考虑了批量生成来省 API 的钱，
看得出是懂内容创作者痛点的。

[clipsketch-ai](https://github.com/RanFeng/clipsketch-ai)

## 哪里约会？MeetSpot

[MeetSpot](https://github.com/JasonRobertDestiny/MeetSpot)

## Meta 推出音频分割模型

[sam-audio](https://github.com/facebookresearch/sam-audio)

## 阿里推出图层 AI 生成模型

Qwen-Image-Layered 生成的不是一张图，而是自带图层的图像，就像是你直接得到了一个 PSD 源文件。

[Qwen-Image-Layered](https://github.com/QwenLM/Qwen-Image-Layered)

## 让 AI 接管 Windows 和 MacOS

这个叫 TuriX-CUA 的开源项目也是一个让 AI 替你玩电脑的 AI 智能体。它也是给 AI 装上眼睛和手，
让它像人一样看着屏幕，动鼠标、敲键盘，帮你把活儿干了。前两天，TuriX-CUA 刚更新了一波大的，
引入了多模型架构，在测试集通过率超过了 80%，确实有点东西。

[TuriX-CUA](https://github.com/TurixAI/TuriX-CUA)

## 用 YAML 去写简历

你只需要把你的经历、技能像填表一样写在配置文件里，它就能自动帮你生成各种排版精美的 PDF 和 Markdown。

这个开源项目把内容和表现分离了。它底层走的是 LaTeX 那套专业排版引擎，但你完全不需要去写那些晦涩的
LaTeX 代码。它还贴心地提供了一些内置的主题，基本涵盖了程序员和学术界主流的审美。
如果你想换个风格，改一行配置就能生成一套全新的排版。对于那些每年都要更新几次简历的人来说，
这玩意儿可以研究研究。

[rendercv](https://github.com/rendercv/rendercv)

## 文本转语音模型

Chatterbox 是由 Resemble AI 开源的文本转语音（TTS）模型。

它提供高质量、低延迟的语音生成能力，包含了 Chatterbox-Turbo 模型，这是一个拥有 3.5 亿参数的高效模型，
通过将解码过程压缩至一步，显著降低了显存占用和计算需求。该开源项目不仅支持多语言生成，
还原生支持副语言标签。在文本里面插入如笑声、咳嗽等标签，让生成的语音更加生动自然，
语音合成的表现力和真实感还是挺不错的。

Chatterbox 生成的音频默认包含 Resemble AI 的 PerTh 水印。这种水印在经过 MP3 压缩或音频编辑后
依然可以被高精度检测出来，防止语音克隆技术的滥用。

[chatterbox](https://github.com/resemble-ai/chatterbox)

## AI 画流程图

这是一个基于 Next.js 构建的 Web 应用程序，巧妙地将 AI 的能力与 draw.io 相结合。
通过自然语言对话来生成和修改图表，将手动拖拽转变为意图驱动的绘图模式。

比如你说：画一个登录流程图。AI 就会自动分析意图并生成符合 draw.io 标准的 XML 数据，
直接在画布上渲染出完整的图表。

而且还支持上传一张手绘草图、截图或现有的图表图片，AI 利用多模态视觉能力会识别图片中的元素与结构，
并将其复刻为可编辑的 draw.io 图表。这对于将白板会议记录数字化非常有用。
改天单独写一篇文章，介绍一下这个开源项目。

[next-ai-draw-io](https://github.com/DayuanJiang/next-ai-draw-io)

## 简历匹配器

这个叫 Resume-Matcher 的开源项目现在已经 24.7K 的 Star 了。如果你最近在找工作，简历投出去石沉大海，
从来没有回音，可以了解一下这个开源项目。

现在很多公司初筛简历，都会看你的简历里没有包含职位描述里的关键词。如果没有相关关键词或者格式机器读不懂，
你就不会被初筛选中。这个 Resume Matcher 就是专门为了解决这个问题，它能分析你的简历，
提前告诉你：你的简历如果不改这几个词，系统就会把你刷掉。

[Resume-Matcher](https://github.com/srbhr/Resume-Matcher)

## Mac 录屏开源神器

大家刷 B 站的时候，可能注意到过一种很流行的视频风格：丝滑的鼠标跟随、自动放大的特写镜头、
美观的渐变背景。这种高颜值的录屏视频会极大地提升产品演示的质感。

很多都是用 macOS 软件：Screen Studio 搞出来的，它虽然极其好用，但价格也相当感人。
OpenScreen 是这个产品的开源替代，刚刚在 GitHub 上崭露头角。虽然是开源的，核心功能一点也不含糊。
它支持全屏录制，或指定单个应用窗口，避免无关内容干扰。而且还能手动添加缩放效果，
还能调整深度、时长和位置，让重点内容更突出。

还能设置壁纸、纯色、渐变背景，或上传自定义图片，告别单调黑边。自带运动模糊，让平移、缩放效果更丝滑，
提升视频质感。除此之外，还有标注工具：支持添加文字、箭头、图片标注，讲解重点一目了然。

还能裁剪画面隐藏多余部分、修剪冗余片段，无需额外剪辑软件；多格式导出，支持不同宽高比和分辨率，
适配抖音、B 站、公众号等多平台发布。

[openscreen](https://github.com/siddharthvaddem/openscreen)

## 开源下载器

[Motrix](https://github.com/agalwood/Motrix)

## PDF 工具包

没开源几天，在 GitHub 上就获得 6K 的 Star 了。BentoPDF 像一个精致的便当盒（Bento），
把你需要的所有 PDF 工具都打包在一起，开箱即用。与传统的在线工具不同，虽然你在浏览器中使用它，
但所有的文件处理逻辑都在你的本地电脑上完成，文件永远不会被上传到任何服务器。

[BentoPDF](https://github.com/alam00000/bentopdf)

## JS 算法

想要冲击大厂，或者从初级工程师进阶到高级工程师时，算法面试是必考题。而市面上大多数算法教程，
要么是用 Java/C++ 写的，看着头大，要么是枯燥的理论，看完就忘。这个叫 javascript-algorithms
的开源项目专门为 JavaScript 开发者打造，目前已经狂揽 195K+ Star，你没看错，是19万。

用最纯粹、最现代的 JavaScript 代码，把计算机科学里那些晦涩难懂的算法和数据结构，
一个个敲出来给你看。

[javascript-algorithms](https://github.com/trekhleb/javascript-algorithms)

## 读论文 Agent

阅读国外专业的学术论文，光理解内容就挺费劲了，如果还要总结内容、生成思维导图，更是让人头疼。
可以试下，Paper Burner X 这个开源工具，集文献识别、翻译、阅读与智能分析于一体，在浏览器上打开就能用。

一个纯前端实现的 Agent 智能分析系统，可自主调用工具进行多步推理，还能翻译长论文，
保留公式、图表等复杂格式。主要功能：

> 支持 PDF、Word、PPT、EPUB 等多种格式导入和处理；
> 极速并发翻译，长论文仅需数十秒，保留原文格式；
> 前端 Agent 智能分析，支持复杂问答和信息提取；
> 自动生成思维导图、流程图和结构化文献矩阵；
> 原译文智能对齐对比，支持高亮标注和目录导航。

[paper-burner-x](https://github.com/Feather-2/paper-burner-x)

## 语音转文本：Handy

Handy 是一款完全离线、免费且开源的语音转文本（Speech-to-Text）桌面应用程序，
现在已经 7.4K+ 的 Star 了。这是一个简单、隐私优先的听写工具。与依赖云服务的语音助手不同，
Handy 所有的处理都在用户本地电脑上完成，确保语音数据不出域。

基于 Tauri 框架构建，保证了软件的轻量级和高性能。在核心语音识别引擎上，它集成了 OpenAI 的 Whisper 模型
以及 CPU 优化的 Parakeet 模型，能够在 Windows、macOS 和 Linux 上流畅运行。
它还具备全局快捷键功能，用户按下快捷键说话，文字即可直接输入到当前的文本框中。

[Handy](https://github.com/cjpais/Handy)
