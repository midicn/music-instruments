---
id: virtual-instruments
site: inst
cat: I11
title: 虚拟乐器与插件
title_en: Virtual instruments and plug-ins
summary: 内存杀死硬件，开放赢得生态 —— 采样库与插件的四插座时代
summary_en: RAM killed the hardware, openness won the ecosystem — sample libraries and the four sockets
level: standard
tags: [乐器, 电子, 电鸣, 西洋, 效果器, 虚拟乐器, 采样库, 插件, Kontakt]
tags_en: [instrument, electronic, electrophone, western, effects, virtual-instruments, sample-libraries, plugins, kontakt]
alias: [虚拟乐器, virtual instrument, VSTi, 采样器插件, 管弦乐库, Kontakt, 音色库]
order: 198
links:
  - "[[instrument:software-synth]]"
  - "[[instrument:samplers]]"
  - "[[instrument:music-workstation]]"
  - "[[instrument:eurorack]]"
  - "[[instrument:midi-controller]]"
  - "[[concept:timbre]]"
instances:
  - chinafolk-002600 | 《抗旱修水库》 —— ⭐⭐「抗旱」：虚拟乐器革命的真正原因是「抗旱」——硬件采样器死于物理内存天花板（EastWest 2003 年那套管弦乐音源要 32GB 硬盘，而硬件采样器大多只有 128MB 内存）——抗旱修库，修的是声音的水库（C3 · 仅限学习研究；库内无虚拟乐器录音，取民歌作意象参照）
  - chinafolk-001952 | 《高低农民开水库》 —— ⭐⭐「水库」：采样库就是声音的水库——VSL 的 Vienna Instruments「超过 280 万采样，世界上最大的管弦乐声音集合」——高低农民开水库，开的是一座声音的水（C3 · 仅限学习研究）
  - chinafolk-000986 | 《蜘蛛架得半天桥》 —— ⭐⭐「架桥」：Kontakt 的开放生态是一座桥——NI 交出 KSP 脚本语言，「2010 年前后几乎没有任何商业虚拟乐器敢不提供 Kontakt 版本」——蜘蛛架得半天桥，第三方厂商都从这桥上过（C3 · 仅限学习研究）
sources:
  - ⭐⭐ **主线：内存杀死硬件，开放赢得生态（本页最该记住的一条）** —— 「硬件采样器的崩溃并非因为音质，而是死于物理内存的天花板——当 EastWest 在 2003 年推出那套需要 32GB 硬盘空间的管弦乐音源时，所有硬件都哑火了——彼时大多数硬件采样器只能塞下 128MB 内存」；⭐⭐ **一场革命的原因常常很无聊：内存**；「Kontakt 抓住了这个缝隙，但真正聪明的布局在别处：Native Instruments 没有选择把采样器锁死成一个封闭产品，而是把开发工具交了出去——KSP 脚本语言允许第三方开发者创建极为复杂的乐器逻辑」；⭐⭐ **「NI 卖的不是一个采样器，而是一个采样器开发平台」——内存给了软件机会，开放把机会变成了生态（对照全站：Moog 的电压控制开放标准 vs Buchla 的封闭——同一个选择，赢的方式不同）**
  - ⭐⭐ **网络效应：兼容性是最大的护城河** —— 「作曲家们积累了上百套 Kontakt 音源库，更新到 Kontakt 8 之后照样能加载十几年前买的旧音色——厂商那边，整个生产管线都围绕 Kontakt 的脚本规范和压缩格式运转」；⭐⭐ **对照 midi-controller 条：MIDI 1.0 保持 viable 近四十年（1983–2020）——Kontakt 旧库二十年照样加载——两个「活得比公司久」的标准/平台，赢的是同一件事：不扔下用户**；⭐⭐ **围墙的另一面：免费 Kontakt Player 是「护城河也是围墙」——它只能加载预授权库，full 版才能导入编辑自有采样——开放是面向开发者的，对用户始终是分层的**
  - ⭐⭐ **VSL：从 DVD 到 Synchron Stage** —— 「2002 年 12 月 First Edition（Strings / Brass & Woodwinds / Percussion / Performance Set 四模块）——格式是 TASCAM GigaStudio 与 Apple Logic EXS24」；「2003 Pro Edition 采样翻倍；2005 Vienna Instruments Collections 含免费 player（AU/VST/AAX Native/RTAS 四格式）」；「Vienna Instruments 系列超过 280 万采样，是世界上最大的管弦乐声音集合」；「2016 Synchron Stage Vienna 开放（Hans Zimmer 的 Remote Control Productions 在此录音）；2017 年第一个 Auro-3D 采样库」；⭐⭐ **用户谱系：Hans Zimmer · Danny Elfman · A.R. Rahman · Alan Silvestri · Alexandre Desplat · Beyoncé——虚拟管弦乐先成了电影工业的草稿纸（mock-ups），再进终混——「先用虚拟乐团排练，再雇真乐团录制」成了行业工序**
  - ⭐⭐ **四插座：插件格式简史** —— 「VST（Steinberg · 1996 与 Cubase 3.7）→ 1999 VST 2.0 加 MIDI 输入（VSTi 诞生）→ 2008 VST 3（side-chaining · 可缩放 GUI）→ 2011 VST 3.5 per-note expression（复音触后 on steroids）→ 2025 VST 3.8 以 MIT 许可完全开源」；「AU（Apple · macOS/iOS）· AAX（Avid · Pro Tools · HDX 的 DSP 加速）· CLAP（u-he & Bitwig · per-note automation）」；⭐⭐ **对照 midi-controller 条的 1983 NAMM：MIDI 是「对手们共建一个标准」；插件格式是「各建各的插座+适配器」——声音的 USB 与 Lightning 之争，四十年后来到了软件世界**
  - ⭐⭐ **管弦乐库的民主化与技术** —— 「democratizing access to orchestral sounds——让独立作曲人以 modest 预算创作大规模作品」；技术三件套：「multi-sampling（每个音多力度层录制）· velocity layers（捕捉强弱带来的音色变化）· round-robin（重复音的多个版本，减少 machine gun 效应）」；「Kontakt 脚本实现了智能连奏过渡、真实动态交叉淡化、自适应奏法切换」；⭐⭐ **「$200 笔记本 + 免费插件就能给独立电影配乐」——对照 DX7 的预设分发（声音像唱片一样被复制）：虚拟乐器把「整个乐团」变成了可下载的东西——一个 bedroom producer 与 Hans Zimmer 之间，曾经隔着一整个音乐厅**
  - ⭐⭐ **AI 的入口** —— 「Kontakt 7（2023）引入 AI 辅助采样清理」——⭐⭐ **从 Fairlight 的光笔画波形，到 AI 清理采样——「做声音」的工具本身也在被自动化（对照 Schaeffer 的具体音乐：剪辑的自动化是半个世纪前开始的）**
updated: 2026-10-21
---

::: zh

## ⭐⭐ 主线：内存杀死硬件，开放赢得生态

> 「**硬件采样器的崩溃并非因为音质，而是死于物理内存的天花板——
> 当 EastWest 在 2003 年推出那套需要 32GB 硬盘空间的管弦乐音源时，
> 所有硬件都哑火了——彼时大多数硬件采样器只能塞下 128MB 内存**」.

⭐⭐ **一场革命的原因常常很无聊：内存。** 硬件采样器不是被打败的，
是**装不下**了——128MB 的内存遇到 32GB 的管弦乐。

⭐⭐ **而 Kontakt 抓住了缝隙之后，做了全站最熟悉的一个选择**：
「NI 没有选择把采样器锁死成一个封闭产品，而是把开发工具交了出去——
KSP 脚本语言允许第三方开发者创建极为复杂的乐器逻辑」。
⭐⭐ **「NI 卖的不是一个采样器，而是一个采样器开发平台。」**
（对照 Moog 的电压控制开放标准 vs Buchla 的封闭——
同一个选择，赢的方式不同。）

| HS 分类 | 归属 |
|---|---|
| **HS 分类** | **电鸣系统的效果端 / 宿主端**（**不独立发声——插件寄生在 DAW 或独立宿主里**）· **采样回放 + 脚本行为建模** |
| **出身** | ⭐⭐ **两条母线**：EastWest 2003 的 32GB 管弦乐音源（内存墙）＋ Kontakt 2002 的 KSP 开放脚本（生态位） |
| **八音注** | 八音之外——**它把全站的乐器都装进了一个「库」：这是「乐器」第一次以「库」为单位被买卖** |

## ⭐⭐ 网络效应：兼容性是最大的护口河

⭐⭐ **「作曲家们积累了上百套 Kontakt 音源库，更新到 Kontakt 8 之后
照样能加载十几年前买的旧音色」**——对照 MIDI 1.0 活近四十年：
两个「活得比公司久」的平台，赢的是同一件事：**不扔下用户。**

⭐⭐ **围墙的另一面**：免费 Kontakt Player 只能加载预授权库，
full 版才能导入编辑自有采样——⭐⭐ **开放是面向开发者的，对用户始终是分层的
——护城河也是围墙。**（对照 eurorack 的模块民主：那条河里没有守门人。）

## ⭐⭐ VSL：从 DVD 到 Synchron Stage

| 年 | 事件 |
|---|---|
| 2002.12 | First Edition（Strings / Brass & Woodwinds / Percussion / Performance Set）——GigaStudio 与 EXS24 格式 |
| 2003 | Pro Edition——采样翻倍 |
| 2005 | Vienna Instruments Collections——免费 player（AU/VST/AAX/RTAS 四格式） |
| 2016 | Synchron Stage Vienna 开放（Hans Zimmer 的 Remote Control Productions 在此录音） |
| 2017 | 第一个 Auro-3D 采样库 |

⭐⭐ **「超过 280 万采样，世界上最大的管弦乐声音集合」**；
用户谱系：Hans Zimmer · Danny Elfman · A.R. Rahman · Beyoncé。
⭐⭐ **虚拟管弦乐先成了电影工业的草稿纸（mock-ups），再进终混——
「先用虚拟乐团排练，再雇真乐团录制」成了行业工序。**

## ⭐⭐ 四插座：插件格式简史

| 插座 | 主人 | 年表 |
|---|---|---|
| **VST** | Steinberg | 1996 → 1999 VSTi → 2008 VST 3 → 2011 per-note expression → **2025 VST 3.8 MIT 开源** |
| **AU** | Apple | macOS / iOS（Logic · GarageBand） |
| **AAX** | Avid | Pro Tools · HDX 的 DSP 加速 |
| **CLAP** | u-he & Bitwig | per-note automation |

⭐⭐ **对照 midi-controller 条的 1983 NAMM：MIDI 是「对手们共建一个标准」；
插件格式是「各建各的插座 + 适配器」——声音的 USB 与 Lightning 之争，
四十年后来到了软件世界。**

## ⭐⭐ 民主化：一个卧室与一个音乐厅

⭐⭐ **技术三件套**：「multi-sampling（每音多力度层）· velocity layers
（捕捉强弱的音色变化）· round-robin（重复音的多个版本——
减少 machine gun 效应）」＋ Kontakt 脚本的「智能连奏过渡 ·
真实动态交叉淡化 · 自适应奏法切换」。

⭐⭐ **「$200 笔记本 + 免费插件就能给独立电影配乐」**——对照 DX7 的
预设分发：**虚拟乐器把「整个乐团」变成了可下载的东西——
一个 bedroom producer 与 Hans Zimmer 之间，曾经隔着一整个音乐厅。**

## ⭐ AI 的入口

⭐⭐ **Kontakt 7（2023）引入 AI 辅助采样清理**——从 Fairlight 的光笔画波形
到 AI 清理采样：**「做声音」的工具本身也在被自动化**
（对照 Schaeffer 的具体音乐——剪辑的自动化，半个世纪前就开始了）。

```svg
<svg viewBox="0 0 640 380" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="RAM killed the hardware, openness won the ecosystem: the 128MB wall versus the 32GB orchestra, and Kontakt's open scripting bridge with its network effects">
  <rect x="0" y="0" width="640" height="380" fill="#0D0C0A"/>
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">虚拟乐器 · 内存杀死硬件，开放赢得生态</text>
    <text x="20" y="44" font-size="11" fill="#6E6A64">一场革命的原因常常很无聊：内存</text>

    <!-- 内存墙 -->
    <rect x="20" y="62" width="290" height="112" rx="6" fill="none" stroke="#3A3733" stroke-width="1"/>
    <text x="32" y="82" font-size="10.5" fill="#A9A49B" font-weight="600">内存墙（2003）</text>
    <rect x="32" y="94" width="80" height="14" rx="2" fill="#6E6A64"/>
    <text x="32" y="120" font-size="9.5" fill="#A9A49B">硬件采样器 128MB</text>
    <rect x="32" y="132" width="264" height="14" rx="2" fill="#E07A3F"/>
    <text x="32" y="164" font-size="9.5" fill="#E07A3F">EastWest 管弦乐音源 32GB</text>
    <path d="M116 101 L296 101" stroke="#E8C547" stroke-width="0.8" stroke-dasharray="3 3"/>
    <text x="122" y="98" font-size="9" fill="#E8C547">250 倍</text>

    <!-- 生态位 -->
    <rect x="330" y="62" width="290" height="112" rx="6" fill="none" stroke="#E8C547" stroke-width="1.2"/>
    <text x="342" y="82" font-size="10.5" fill="#E8C547" font-weight="600">生态位（2002 →）</text>
    <text x="342" y="104" font-size="10" fill="#A9A49B">NI 交出 KSP 脚本语言</text>
    <text x="342" y="122" font-size="10" fill="#A9A49B">→ 第三方在 Kontakt 上造乐器</text>
    <text x="342" y="140" font-size="10" fill="#E07A3F">→ 网络效应：旧库照样加载</text>
    <text x="342" y="160" font-size="9.5" fill="#6E6A64">「卖的不是采样器，是开发平台」</text>

    <!-- 四插座 -->
    <text x="20" y="204" font-size="11" fill="#A9A49B" font-weight="600">四插座（插件格式之争 · 1996–2025）</text>
    <g font-size="9.5">
      <rect x="20" y="216" width="140" height="52" rx="5" fill="none" stroke="#E8C547" stroke-width="1.2"/>
      <text x="30" y="234" fill="#E8C547" font-weight="600">VST · Steinberg</text>
      <text x="30" y="250" font-size="9" fill="#6E6A64">1996 → VSTi 1999 → 开源 2025</text>
      <rect x="170" y="216" width="140" height="52" rx="5" fill="none" stroke="#3A3733" stroke-width="1"/>
      <text x="180" y="234" fill="#A9A49B" font-weight="600">AU · Apple</text>
      <text x="180" y="250" font-size="9" fill="#6E6A64">macOS / iOS</text>
      <rect x="320" y="216" width="140" height="52" rx="5" fill="none" stroke="#3A3733" stroke-width="1"/>
      <text x="330" y="234" fill="#A9A49B" font-weight="600">AAX · Avid</text>
      <text x="330" y="250" font-size="9" fill="#6E6A64">Pro Tools · DSP 加速</text>
      <rect x="470" y="216" width="150" height="52" rx="5" fill="none" stroke="#3A3733" stroke-width="1"/>
      <text x="480" y="234" fill="#A9A49B" font-weight="600">CLAP · u-he/Bitwig</text>
      <text x="480" y="250" font-size="9" fill="#6E6A64">per-note automation</text>
    </g>

    <!-- 民主化 -->
    <rect x="20" y="290" width="600" height="44" rx="6" fill="none" stroke="#E07A3F" stroke-width="1"/>
    <text x="32" y="310" font-size="10.5" fill="#E07A3F" font-weight="600">民主化：$200 笔记本 + 免费插件 = 独立电影配乐</text>
    <text x="32" y="328" font-size="9.5" fill="#6E6A64">一个 bedroom producer 与 Hans Zimmer 之间，曾经隔着一整个音乐厅。</text>

    <!-- AI 入口 -->
    <text x="20" y="356" font-size="10" fill="#A9A49B">2023 · Kontakt 7 引入 AI 辅助采样清理 —— 从光笔画波形到 AI 清理采样：做声音的工具也在被自动化。</text>
  </g>
</svg>
```

```range
{"range":"C0–C8","common":"C0–C8","caption":"虚拟乐器的「音域」（采样库/插件 · 所载乐器决定音域）","caption_en":"Virtual instruments 「range」 (sample libraries / plug-ins · the hosted instrument decides the span)","note":"虚拟乐器属电鸣系统的宿主/效果端（不独立发声——插件寄生在 DAW 或独立宿主里）。音域由所载乐器决定：采样库通常覆盖所录乐器的全音域（管弦乐库从低音提琴到短笛，取合幅约 C0–C8）。原理：multi-sampling（每音多力度层）+ velocity layers（捕捉强弱的音色变化）+ round-robin（重复音的多个版本，减少 machine gun 效应）+ 脚本行为建模（智能连奏过渡、动态交叉淡化、自适应奏法切换）。格式四插座：VST（Steinberg）/ AU（Apple）/ AAX（Avid）/ CLAP（u-he & Bitwig）；Kontakt Player 免费但只加载预授权库。","note_en":"Virtual instruments sit at the host/effects end of the electrophone system (they make no sound of their own — plug-ins are parasitic on a DAW or standalone host). The range is set by the hosted instrument: sample libraries typically span the recorded instrument's full compass (orchestral libraries from double bass to piccolo, roughly C0–C8 combined). Principle: multi-sampling (each note at multiple velocity layers) + velocity layers (timbre change with loudness) + round-robin (multiple takes of each note, reducing the machine-gun effect) + scripted behaviour modelling (intelligent legato transitions, dynamic crossfading, adaptive articulation switching). Four sockets: VST (Steinberg) / AU (Apple) / AAX (Avid) / CLAP (u-he & Bitwig); Kontakt Player is free but loads only pre-authorised libraries."}
```

```audiolab
{"type":"instrument","gm":"Orchestra Hit","phrase":["C3","E3","G3","C4","E4","G4","C5"],"label":"虚拟乐器的管弦一击：采样库的齐奏（借管弦乐 hit 近似）","label_en":"The virtual orchestra's hit — a library tutti (orchestra hit stands in)","hint":"虚拟乐器的本质是「把整个乐团变成可下载的东西」——这条管弦乐 hit 取其「齐奏意象」，但它最标志的特征在这里听不出来：一是 multi-sampling + round-robin——每个音按力度层录多遍，重复音不重样（消除 machine gun 效应）；二是脚本行为建模——智能连奏与奏法切换是「行为」不是「采样」；三是内存杀死硬件——2003 年 EastWest 32GB 管弦乐音源遇到硬件采样器的 128MB 天花板，硬件不是被打败，是装不下了；而 Kontakt 的开放（KSP 脚本）把机会变成了生态——「卖的不是采样器，是开发平台」。","hint_en":"The virtual instrument's essence is 「turning the whole orchestra into something downloadable」 — this orchestra hit takes the tutti image, but the signature is absent: multi-sampling plus round-robin — each note recorded at multiple velocity layers, no two repeats alike (killing the machine-gun effect); scripted behaviour modelling — intelligent legato and articulation switching are behaviour, not samples; and RAM killed the hardware — EastWest's 32GB orchestral library of 2003 met the hardware samplers' 128MB ceiling: the hardware wasn't beaten, it couldn't fit; and Kontakt's openness (KSP scripting) turned the opening into an ecosystem — 「not a sampler, a sampler development platform」."}
```

:::

::: en

## ⭐⭐ The main line: RAM killed the hardware, openness won the ecosystem

> 「**The hardware samplers' collapse was not about sound quality — they died
> at the ceiling of physical RAM: when EastWest released that orchestral
> library needing 32GB of disk space in 2003, all the hardware went dumb —
> most hardware samplers of the era could hold only 128MB**」.

⭐⭐ **A revolution's cause is often boring: RAM.** The hardware samplers weren't
beaten — **they couldn't fit** — 128MB of RAM met a 32GB orchestra.

⭐⭐ **And after Kontakt seized the opening, it made the choice this site knows
best**: 「Native Instruments did not lock the sampler into a closed product but
handed out the development tools — the KSP scripting language lets third-party
developers build extraordinarily complex instrument logic」.
⭐⭐ **「What NI sells is not a sampler but a sampler development platform.」**
(Against Moog's open volt-control standard versus Buchla's closed system —
the same choice, won a different way.)

| HS class | Assignment |
|---|---|
| **HS class** | **the host/effects end of the electrophone system**（**makes no sound of its own; plug-ins are parasitic on a DAW or standalone host**）· **sample playback + scripted behaviour modelling** |
| **Origin** | ⭐⭐ **two lines**: EastWest's 32GB orchestral library (2003 · the RAM wall) ＋ Kontakt's open KSP scripting (2002 · the ecological niche) |
| **Bayin note** | Outside the bayin — **it put the whole site's instruments into a 「library」: the first time instruments were bought and sold by the library** |

## ⭐⭐ Network effects: compatibility is the widest moat

⭐⭐ **「Composers accumulated hundreds of Kontakt libraries, and after upgrading
to Kontakt 8 they could still load sound colours bought more than a decade
earlier」** — against MIDI 1.0 staying viable for nearly four decades:
two platforms that 「outlived their companies」 win the same thing: **never
dropping their users.**

⭐⭐ **The other face of the wall**: the free Kontakt Player loads only
pre-authorised libraries; the full version alone can import and edit your own
samples — ⭐⭐ **the openness faces developers; for users it is always tiered —
the moat is also a wall.** (Against eurorack's module democracy: that river
has no gatekeeper.)

## ⭐⭐ VSL: from DVD to Synchron Stage

| Year | Event |
|---|---|
| 2002.12 | First Edition (Strings / Brass & Woodwinds / Percussion / Performance Set) — in GigaStudio and EXS24 formats |
| 2003 | Pro Edition — twice the samples |
| 2005 | Vienna Instruments Collections — free player (AU / VST / AAX Native / RTAS) |
| 2016 | Synchron Stage Vienna opens (Hans Zimmer's Remote Control Productions records there) |
| 2017 | the first Auro-3D sample library |

⭐⭐ **「Over 2.8 million samples, by far the largest collection of orchestral
sounds in the world」**; users: Hans Zimmer · Danny Elfman · A.R. Rahman ·
Beyoncé. ⭐⭐ **Virtual orchestras first became the film industry's drafting
paper (mock-ups), then entered the final mix — 「rehearse with the virtual
orchestra, then hire the real one」 became an industrial step.**

## ⭐⭐ Four sockets: a brief history of plug-in formats

| Socket | Owner | Timeline |
|---|---|---|
| **VST** | Steinberg | 1996 → VSTi 1999 → VST 3 in 2008 → per-note expression 2011 → **VST 3.8 MIT open-source 2025** |
| **AU** | Apple | macOS / iOS (Logic · GarageBand) |
| **AAX** | Avid | Pro Tools · DSP acceleration on HDX |
| **CLAP** | u-he & Bitwig | per-note automation |

⭐⭐ **Against the midi-controller entry's 1983 NAMM: MIDI was 「rivals building
one standard together」; plug-in formats are 「everyone builds their own socket,
plus adapters」 — the USB-versus-Lightning fight for sound arrived in the
software world forty years later.**

## ⭐⭐ Democratisation: one bedroom and one concert hall

⭐⭐ **The technical trio**: 「multi-sampling (each note at multiple velocity
layers) · velocity layers (timbre change with loudness) · round-robin (multiple
takes of each note — reducing the machine-gun effect)」 plus Kontakt scripting's
「intelligent legato transitions, true dynamic crossfading, adaptive
articulation switching」.

⭐⭐ **「A $200 laptop and free plugins could score an indie film」** — against the
DX7's preset distribution: **virtual instruments turned the 「whole orchestra」
into something downloadable — between one bedroom producer and Hans Zimmer there
was once an entire concert hall.**

## ⭐ The AI entrance

⭐⭐ **Kontakt 7 (2023) introduced AI-assisted sample cleanup** — from the
Fairlight's light pen drawing waveforms to AI cleaning samples: **the tools for
「making sound」 are themselves being automated** (against Schaeffer's musique
concrète — the automation of editing began half a century ago).

```svg
<svg viewBox="0 0 640 380" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="RAM killed the hardware, openness won the ecosystem: the 128MB wall versus the 32GB orchestra, and Kontakt's open scripting bridge with its network effects">
  <rect x="0" y="0" width="640" height="380" fill="#0D0C0A"/>
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">Virtual instruments · RAM killed the hardware, openness won the ecosystem</text>
    <text x="20" y="44" font-size="11" fill="#6E6A64">A revolution's cause is often boring: RAM</text>

    <rect x="20" y="62" width="290" height="112" rx="6" fill="none" stroke="#3A3733" stroke-width="1"/>
    <text x="32" y="82" font-size="10.5" fill="#A9A49B" font-weight="600">The RAM wall (2003)</text>
    <rect x="32" y="94" width="80" height="14" rx="2" fill="#6E6A64"/>
    <text x="32" y="120" font-size="9.5" fill="#A9A49B">hardware samplers: 128MB</text>
    <rect x="32" y="132" width="264" height="14" rx="2" fill="#E07A3F"/>
    <text x="32" y="164" font-size="9.5" fill="#E07A3F">EastWest orchestral library: 32GB</text>
    <path d="M116 101 L296 101" stroke="#E8C547" stroke-width="0.8" stroke-dasharray="3 3"/>
    <text x="122" y="98" font-size="9" fill="#E8C547">×250</text>

    <rect x="330" y="62" width="290" height="112" rx="6" fill="none" stroke="#E8C547" stroke-width="1.2"/>
    <text x="342" y="82" font-size="10.5" fill="#E8C547" font-weight="600">The niche (2002 →)</text>
    <text x="342" y="104" font-size="10" fill="#A9A49B">NI hands out the KSP scripting language</text>
    <text x="342" y="122" font-size="10" fill="#A9A49B">→ third parties build instruments on Kontakt</text>
    <text x="342" y="140" font-size="10" fill="#E07A3F">→ network effects: old libraries still load</text>
    <text x="342" y="160" font-size="9.5" fill="#6E6A64">「not a sampler, a development platform」</text>

    <text x="20" y="204" font-size="11" fill="#A9A49B" font-weight="600">Four sockets (the plug-in format fight · 1996–2025)</text>
    <g font-size="9.5">
      <rect x="20" y="216" width="140" height="52" rx="5" fill="none" stroke="#E8C547" stroke-width="1.2"/>
      <text x="30" y="234" fill="#E8C547" font-weight="600">VST · Steinberg</text>
      <text x="30" y="250" font-size="9" fill="#6E6A64">1996 → VSTi 1999 → open 2025</text>
      <rect x="170" y="216" width="140" height="52" rx="5" fill="none" stroke="#3A3733" stroke-width="1"/>
      <text x="180" y="234" fill="#A9A49B" font-weight="600">AU · Apple</text>
      <text x="180" y="250" font-size="9" fill="#6E6A64">macOS / iOS</text>
      <rect x="320" y="216" width="140" height="52" rx="5" fill="none" stroke="#3A3733" stroke-width="1"/>
      <text x="330" y="234" fill="#A9A49B" font-weight="600">AAX · Avid</text>
      <text x="330" y="250" font-size="9" fill="#6E6A64">Pro Tools · DSP acceleration</text>
      <rect x="470" y="216" width="150" height="52" rx="5" fill="none" stroke="#3A3733" stroke-width="1"/>
      <text x="480" y="234" fill="#A9A49B" font-weight="600">CLAP · u-he/Bitwig</text>
      <text x="480" y="250" font-size="9" fill="#6E6A64">per-note automation</text>
    </g>

    <rect x="20" y="290" width="600" height="44" rx="6" fill="none" stroke="#E07A3F" stroke-width="1"/>
    <text x="32" y="310" font-size="10.5" fill="#E07A3F" font-weight="600">Democratisation: a $200 laptop + free plugins = an indie film score</text>
    <text x="32" y="328" font-size="9.5" fill="#6E6A64">Between one bedroom producer and Hans Zimmer there was once an entire concert hall.</text>

    <text x="20" y="356" font-size="10" fill="#A9A49B">2023 · Kontakt 7: AI-assisted sample cleanup — the tools for making sound are automated.</text>
  </g>
</svg>
```

```range
{"range":"C0–C8","common":"C0–C8","caption":"虚拟乐器的「音域」（采样库/插件 · 所载乐器决定音域）","caption_en":"Virtual instruments 「range」 (sample libraries / plug-ins · the hosted instrument decides the span)","note":"虚拟乐器属电鸣系统的宿主/效果端（不独立发声——插件寄生在 DAW 或独立宿主里）。音域由所载乐器决定：采样库通常覆盖所录乐器的全音域（管弦乐库从低音提琴到短笛，取合幅约 C0–C8）。原理：multi-sampling（每音多力度层）+ velocity layers（捕捉强弱的音色变化）+ round-robin（重复音的多个版本，减少 machine gun 效应）+ 脚本行为建模（智能连奏过渡、动态交叉淡化、自适应奏法切换）。格式四插座：VST（Steinberg）/ AU（Apple）/ AAX（Avid）/ CLAP（u-he & Bitwig）；Kontakt Player 免费但只加载预授权库。","note_en":"Virtual instruments sit at the host/effects end of the electrophone system (they make no sound of their own — plug-ins are parasitic on a DAW or standalone host). The range is set by the hosted instrument: sample libraries typically span the recorded instrument's full compass (orchestral libraries from double bass to piccolo, roughly C0–C8 combined). Principle: multi-sampling (each note at multiple velocity layers) + velocity layers (timbre change with loudness) + round-robin (multiple takes of each note, reducing the machine-gun effect) + scripted behaviour modelling (intelligent legato transitions, dynamic crossfading, adaptive articulation switching). Four sockets: VST (Steinberg) / AU (Apple) / AAX (Avid) / CLAP (u-he & Bitwig); Kontakt Player is free but loads only pre-authorised libraries."}
```

```audiolab
{"type":"instrument","gm":"Orchestra Hit","phrase":["C3","E3","G3","C4","E4","G4","C5"],"label":"虚拟乐器的管弦一击：采样库的齐奏（借管弦乐 hit 近似）","label_en":"The virtual orchestra's hit — a library tutti (orchestra hit stands in)","hint":"虚拟乐器的本质是「把整个乐团变成可下载的东西」——这条管弦乐 hit 取其「齐奏意象」，但它最标志的特征在这里听不出来：一是 multi-sampling + round-robin——每个音按力度层录多遍，重复音不重样（消除 machine gun 效应）；二是脚本行为建模——智能连奏与奏法切换是「行为」不是「采样」；三是内存杀死硬件——2003 年 EastWest 32GB 管弦乐音源遇到硬件采样器的 128MB 天花板，硬件不是被打败，是装不下了；而 Kontakt 的开放（KSP 脚本）把机会变成了生态——「卖的不是采样器，是开发平台」。","hint_en":"The virtual instrument's essence is 「turning the whole orchestra into something downloadable」 — this orchestra hit takes the tutti image, but the signature is absent: multi-sampling plus round-robin — each note recorded at multiple velocity layers, no two repeats alike (killing the machine-gun effect); scripted behaviour modelling — intelligent legato and articulation switching are behaviour, not samples; and RAM killed the hardware — EastWest's 32GB orchestral library of 2003 met the hardware samplers' 128MB ceiling: the hardware wasn't beaten, it couldn't fit; and Kontakt's openness (KSP scripting) turned the opening into an ecosystem — 「not a sampler, a sampler development platform」."}
```

:::
