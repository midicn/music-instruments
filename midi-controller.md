---
id: midi-controller
site: inst
cat: I11
title: MIDI 控制器
title_en: The MIDI controller
summary: 发送音符、力度与控制消息，驱动外部或软件乐器
summary_en: Sending note, velocity and control messages to hardware or software instruments
level: standard
tags: [乐器, 电子, 电鸣, 西洋, 数字合成器, MIDI, 控制器, master keyboard]
tags_en: [instrument, electronic, electrophone, western, digital-synth, midi, controller, master-keyboard]
alias: [MIDI 控制器, midi-controller, MIDI 键盘, master keyboard, MIDI, 主控键盘]
order: 185
links:
 - "[[instrument:voltage-control]]"
 - "[[instrument:dx7-fm]]"
 - "[[instrument:music-workstation]]"
 - "[[instrument:prophet-5]]"
 - "[[concept:pitch]]"
 - "[[concept:articulation]]"
instances:
  - mutopia-000280 | 文件包含两个发音通道，所有起音力度均为127；可区分音符消息、通道与演奏力度三个维度 | The file uses two sounding channels and all note-on velocities are 127, separating note messages, channels and velocity as three dimensions
  - musicnet-000039 | 文件包含三个弦乐音色程序与音量等控制消息，可观察同一份MIDI怎样为多个声部分配接收音色 | Three string programs and control messages including volume show how one MIDI file assigns receiving sounds to multiple parts
  - giantmidi-006222 | 文件含延音踏板控制消息CC64，可把音符起止与踏板控制分开理解 | The file includes sustain-pedal controller CC64, allowing note timing and pedal control to be considered separately
sources:
  - "https://support.focusrite.com/hc/en-gb/articles/360001456045-Why-can-t-I-hear-my-MIDI-keyboard"
  - "https://midi.org/what-musicians-artists-need-to-know-about-midi-2-0"
  - "https://midi.org/specs"
 - **主线：乐器第一次只剩「控制」（本页最该记住的一条）** —— 「**1990 年代，随着声音模块与软件合成器的普及，键盘演化为**不含发声引擎**的专用控制器——优先便携与兼容**」→ **在 MIDI 控制器之前，「演奏」与「发声」从没分开过——这件乐器证明：按下的键可以只是「消息」，声音可以住在别处**（ **这是「控制与发声分离」的终极一步——电压控制条把控制变成信号，MIDI 把信号变成通用语**）
 - **MIDI 的双父（Kakehashi 与 Smith）** —— 「**Roland 总裁 Ikutaro Kakehashi 觉得缺乏标准化在限制电子音乐行业的成长**——1981 年 6 月向 Oberheim 的 Tom Oberheim 提议开发标准（觉得 Oberheim 系统太笨重），**又对 Sequential Circuits 总裁 Dave Smith 谈一个更简单便宜的替代**」；「**Smith 与 Sequential 工程师 Chet Wood 写出统一接口文档 Universal Synthesizer Interface，1981 年 10 月在 AES 展会发表**」；「**标准由 Roland · Yamaha · Korg · Kawai · Sequential 的代表讨论修改**」
 - **名字的诞生（UMI → MIDI）** —— 「**Kakehashi 喜欢叫它 Universal Musical Interface（UMI），发音 you-me——但 Smith 觉得这有点 corny（土）；不过他喜欢用 instrument 而不是 synthesizer，提议 Musical Instrument Digital Interface（MIDI）**」→ **一个名字的两个坚持：一个要「Universal」，一个要「Instrument」——最后「Musical Instrument」留在了每个 MIDI 文件的名字里**
 - **1983 NAMM：两台对手琴的第一次对话** —— 「**1983 年冬季 NAMM 展会上，Smith 演示了 Prophet-600 与 Roland JP-6 之间的 MIDI 连接**」→ **两台对手公司的琴第一次互相「听懂」**——**对照 1V/oct 的标准之争（voltage-control 条）：这次不是谁的标准赢，而是大家共建一个**
 - **MIDI 1.0 的近四十年（万年桥）** —— 「**原版 MIDI 1.0 协议在 2020 年 MIDI 2.0 引入前保持 viable 近四十年——音乐史上少有技术标准有如此普及的采用与持久的影响**」； **「Kakehashi 与 Smith 于 2013 年获 Technical Grammy Awards」**—— **对照 Telharmonium（技术被时代杀死）：MIDI 是技术「活得比公司久」的案例**（Sequential 1987 破产，MIDI 永生）
 - **MIDI 控制器的类型（只列形状，不发声）** —— 「**键盘控制器（keyboard controllers）是最常见的 MIDI 输入设备——25 键移动型到 88 键全配重**」；「**多数有力度感应键，许多有触后**——「**channel aftertouch（任何键的压力影响整个通道）或 polyphonic aftertouch（逐键控制）**」；「**pitch bend 与调制轮**」；「**synth-action 轻快适合电子乐 · weighted/semi-weighted 更有钢琴的阻力感**」
 - **USB MIDI（1999）：另一座桥** —— 「**1999 年 USB-IF 与 MMA 合作引入 USB MIDI——把 MIDI 传输嵌入 USB Audio Device Class，免去专用串行接口**」→ 「**2000 年代平价 MIDI 控制器崛起——如 2002 年的 M-Audio Keystation 49e**」；「**Akai MPK Mini 低于 $200——专业级特性对初学者与爱好者可及**」
 - **MIDI 2.0（2019/2020）** —— 「**MIDI 2.0 增强了双向通信与表现力，同时支持便携无线型号**」—— **双向：MIDI 1.0 是「我发你收」，MIDI 2.0 的设备可以互相「介绍自己」**
 - **意大利的独奏传奇（Baglioni 1986）** —— 「**在意大利，MIDI 因 1986 年 Claudio Baglioni 的体育场巡演而获得特别知名度——艺术家以创新方式利用这项技术独自在舞台上表演，没有乐队也没有伴奏**」—— **一个人 + 一套 MIDI = 一支乐队：控制与发声分离的最早大规模舞台证明**
 - 「MIDI 控制器属**电鸣**系统的控制端（本身不发声——**HS 分类之外的「元乐器」**）」依 Hornbostel–Sachs 分类
updated: 2026-11-02
---

::: zh

## 一件不发声的乐器

1990 年代，键盘开始拆成两半：一半是键，一半是声音。按下不发声音，只发一条消息——哪个音、多用力、按了多久。声音住在别处，可能是一台音源，也可能是另一台电脑。

在这之前，演奏与发声从没分开过。琴键连着弦、连着簧片、连着振荡器，按下去声音必须发生。控制器把它拆开了，键变成电话键：只负责拨号。

八音：不在其列——它自己不发声，没有可振动的部件。

## 两个人握手，才有这门通用语

1981 年，Roland 总裁梯郁太郎觉得各家标准不一正在拖住整个行业。他先找 Oberheim，嫌对方系统太笨重；又找 Sequential Circuits 的 Dave Smith，谈一个更简单便宜的方案。

Smith 与工程师 Chet Wood 写出 Universal Synthesizer Interface，1981 年 10 月在 AES 发表。定名时两人各让一步：梯郁太郎喜欢 Universal Musical Interface，缩写念作 you-me，Smith 嫌土；Smith 坚持用 instrument 而不是 synthesizer，最后留下的是 Musical Instrument Digital Interface。

发明常是一个人的事，标准必须是一群人的事。

## 1983 年冬天，两台对手琴第一次对话

1983 年冬季 NAMM 展会上，Smith 让 Prophet-600 与 Roland JP-6 通过 MIDI 连了起来。两家对手公司的琴第一次互相听懂。同年 8 月，MIDI 1.0 规范发布。

MIDI 2.0 在2020年推出，并继续重视与MIDI 1.0设备的兼容。协议版本和USB、五针DIN等传输接口是不同层面，不能把2020年当作MIDI 1.0的终止年份。

## 形状：25 到 88 键，和两只轮子

纯 MIDI 控制器发送音符、力度和控制消息，本身通常不带发声引擎。连接电脑后，要让宿主接收 MIDI、把消息送到虚拟乐器，再把音频送到正确输出，才会听到声音。USB 与五针 DIN 是不同的传输方式，二者仍可并存；接口是否供电、设备是否传音频，也要分别确认。

1986 年，Claudio Baglioni 在意大利的体育场巡演里一个人带一套 MIDI 上台，没有乐队也没有伴奏。那是控制与发声分离之后最早的大规模舞台证明。

### HS 分类

| 项 | 内容 |
|---|---|
| HS 分类 | 电鸣系统的控制端（本身不发声 ·「元乐器」） |
| 出身 | 1981–83 · 梯郁太郎（Roland）与 Smith（Sequential）双父 |
| 名字 | UMI 被弃 · MIDI = Musical Instrument Digital Interface |
| 键位 | 25–88 键 · 力度 · 触后（整通道 / 逐键）· 弯音与调制轮 |
| 寿命 | MIDI 1.0 自 1983 年发布，至今仍在使用· 2013 年两人同获 Technical Grammy |
| 八音：不在其列 | 没有振动的部件 |

```svg
<svg viewBox="0 0 640 380" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="The MIDI controller: an instrument reduced to control alone — a keyboard sending messages through a five-pin DIN cable to sound modules of rival makers; the two fathers Kakehashi of Roland and Smith of Sequential shaking hands over the 1981 proposal; MIDI 1.0 introduced in 1983 and still in use">
 <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
 <text x="20" y="22">MIDI 控制器 · 乐器第一次只剩「控制」</text>
 <text x="20" y="44" font-size="11" fill="#6E6A64">键是消息 · 声音住在别处 · 消息触发接收端发声</text>
 </g>

 <rect x="40" y="70" width="240" height="80" rx="8" fill="#26241F" stroke="#E8C547" stroke-width="1.5"/>
 <g stroke="#E8C547" stroke-width="1">
 <path d="M64,84 L64,134 M88,84 L88,134 M112,84 L112,134 M136,84 L136,134 M160,84 L160,134 M184,84 L184,134 M208,84 L208,134 M232,84 L232,134"/>
 </g>
 <text x="160" y="168" text-anchor="middle" font-size="9.5" fill="#E8C547">MIDI 控制器（不发声）</text>
 <text x="160" y="184" text-anchor="middle" font-size="8.5" fill="#6E6A64">键=消息 · velocity · aftertouch · 弯音/调制轮</text>

 <path d="M284,110 L356,110" stroke="#E8C547" stroke-width="2"/>
 <text x="292" y="102" font-size="9" fill="#E8C547">五针 DIN · 31.25 kbps</text>

 <g font-size="9.5" fill="#97C459">
 <rect x="360" y="70" width="120" height="34" rx="4" fill="none" stroke="#97C459" stroke-width="1.2"/>
 <text x="420" y="91" text-anchor="middle">Roland 音源</text>
 <rect x="360" y="112" width="120" height="34" rx="4" fill="none" stroke="#97C459" stroke-width="1.2"/>
 <text x="420" y="133" text-anchor="middle">Yamaha 音源</text>
 <rect x="500" y="70" width="120" height="34" rx="4" fill="none" stroke="#97C459" stroke-width="1.2"/>
 <text x="560" y="91" text-anchor="middle">Korg 音源</text>
 <rect x="500" y="112" width="120" height="34" rx="4" fill="none" stroke="#97C459" stroke-width="1.2"/>
 <text x="560" y="133" text-anchor="middle">Sequential 音源</text>
 </g>

 <text x="20" y="216" font-size="10.5" fill="#E8C547"> 双父握手：Kakehashi（Roland）主动找 Smith（Sequential）—— 发明是一个人的事，标准是一群人的事</text>
 <text x="20" y="238" font-size="10" fill="#A9A49B">UMI（you-me）被嫌 corny → Smith 坚持用 instrument → Musical Instrument Digital Interface</text>

 <rect x="30" y="250" width="286" height="56" rx="8" fill="none" stroke="#6E6A64" stroke-width="1.1"/>
 <text x="173" y="270" text-anchor="middle" font-size="9.5" fill="#A9A49B">1983 NAMM：第一次对话</text>
 <text x="48" y="290" font-size="9" fill="#6E6A64">Prophet-600 ↔ Roland JP-6（对手琴互相听懂）</text>
 <text x="48" y="300" font-size="9" fill="#97C459">这次不是谁的标准赢，是大家共建一个</text>

 <rect x="324" y="250" width="286" height="56" rx="8" fill="none" stroke="#6E6A64" stroke-width="1.1"/>
 <text x="467" y="270" text-anchor="middle" font-size="9.5" fill="#A9A49B">MIDI 1.0：自1983年发布并延续使用</text>
 <text x="342" y="290" font-size="9" fill="#6E6A64">近四十年 viable · Sequential 1987 破产 · MIDI 永生</text>
 <text x="342" y="300" font-size="9" fill="#97C459">2013 双父 Technical Grammy · 技术活得比公司久</text>

 <g font-family="system-ui,sans-serif" font-size="10.5" fill="#A9A49B">
 <text x="20" y="330" fill="#E8C547"> USB MIDI（1999）嵌入 Audio Class → 平价控制器崛起（Keystation · MPK Mini <$200）</text>
 <text x="20" y="350" font-size="10" fill="#A9A49B"> Baglioni 1986 意大利体育场巡演：一个人 + 一套 MIDI = 一支乐队（分离的最早舞台证明）</text>
 <text x="20" y="370" fill="#6E6A64">⚠️ 示意图：按文字描述绘制，非实物比例。</text>
 </g>
</svg>
```

```range
{"range":"C1–C8","common":"C1–C8","caption":"MIDI 控制器的「音域」（本身不发声 · 键位映射由接收端决定 · 图示为 25–88 键范围）","caption_en":"MIDI controller 「range」 (silent by itself · key mapping decided by the receiver · 25–88 keys shown)","note":"MIDI 控制器属电鸣系统的控制端（元乐器——本身不发声）。25/49/61/88 键规格，力度感应与触后（channel/polyphonic aftertouch）；输出 MIDI 消息（note on/off · velocity · pitch bend · control change）经五针 DIN（31.25 kbps）或 USB。音域取决于接收端的音源——同一台控制器今天可驱动钢琴明天可驱动鼓机。键位映射即「音域」。记谱按接收端音源实音。"}
```

```audiolab
{"type":"instrument","gm":"Lead 8 (bass + lead)","synth":"bowed","phrase":["C4","E4","G4","C5","G4","E4","C4"],"label":"同一组音符触发的合成音色","label_en":"A synthesizer sound triggered by one note sequence","hint":"本例用C–E–G的音名短句触发接收端音色。MIDI负责传递音符等消息，接收端才把消息变成声音；实际连接还要分别检查输入路由和音频输出。","hint_en":"A C–E–G-based phrase triggers the receiving sound. MIDI carries note and other messages; the receiver turns them into audio. In a real setup, check MIDI routing and audio output separately."}
```

::: en

## An instrument that makes no sound

In the 1990s the keyboard split in two: one half keys, the other half sound. You press and nothing sounds; a message leaves instead, saying which note, how hard, how long. Before that, playing and sounding had never been separate: keys were tied to strings, reeds, oscillators, and the sound had to happen at the press. The controller cut the tie and turned keys into telephone keys. It sits outside the bayin: there is no vibrating body to sort.

## Two men shake hands, and a language appears

In 1981 Ikutaro Kakehashi, president of Roland, decided incompatible standards were holding the industry back. He approached Oberheim first, found the system too bulky, then Dave Smith of Sequential Circuits with a simpler, cheaper proposal. Smith and the engineer Chet Wood wrote the Universal Synthesizer Interface, presented at the AES convention that October.

The naming cost each man something: Kakehashi liked Universal Musical Interface, pronounced you-me; Smith thought it corny and insisted on instrument. What survived was Musical Instrument Digital Interface. Invention is usually one person's work; a standard has to be a crowd's.

## Winter 1983: two rival instruments talk

At the winter NAMM show of 1983, Smith connected a Prophet-600 to a Roland JP-6 over MIDI. Instruments from rival companies understood each other for the first time. The 1.0 specification followed that August.

MIDI 2.0 appeared in 2020 with continued emphasis on compatibility with MIDI 1.0 equipment. Protocol versions and transports such as USB and five-pin DIN are different layers; 2020 is not an end date for MIDI 1.0.

## Shaped like 25 to 88 keys, and two wheels

A dedicated MIDI controller sends note, velocity and control messages and usually has no sound engine. A computer must route its MIDI to an instrument and the resulting audio to an output. USB and five-pin DIN are different transports that coexist; power delivery and audio transmission are separate capabilities to check.

In 1986 Claudio Baglioni toured Italian stadiums alone with a MIDI rig, no band and no backing track: the first large-scale proof on stage that control and sound could live apart.

### HS class

| Item | Content |
|---|---|
| HS class | the control end of the electrophone system (silent · a meta-instrument) |
| Origin | 1981–83 · Kakehashi (Roland) and Smith (Sequential) |
| Name | UMI dropped · MIDI = Musical Instrument Digital Interface |
| Keys | 25–88 · velocity · aftertouch · pitch and mod wheels |
| Lifespan | MIDI 1.0, introduced in 1983 and still in use · Technical Grammy in 2013 |
| Bayin | outside it — no vibrating body |

```svg
<svg viewBox="0 0 640 380" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="The MIDI controller: an instrument reduced to control alone — a keyboard sending messages through a five-pin DIN cable to sound modules of rival makers; the two fathers Kakehashi of Roland and Smith of Sequential shaking hands over the 1981 proposal; MIDI 1.0 introduced in 1983 and still in use">
 <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
 <text x="20" y="22">MIDI 控制器 · 乐器第一次只剩「控制」</text>
 <text x="20" y="44" font-size="11" fill="#6E6A64">键是消息 · 声音住在别处 · 消息触发接收端发声</text>
 </g>

 <rect x="40" y="70" width="240" height="80" rx="8" fill="#26241F" stroke="#E8C547" stroke-width="1.5"/>
 <g stroke="#E8C547" stroke-width="1">
 <path d="M64,84 L64,134 M88,84 L88,134 M112,84 L112,134 M136,84 L136,134 M160,84 L160,134 M184,84 L184,134 M208,84 L208,134 M232,84 L232,134"/>
 </g>
 <text x="160" y="168" text-anchor="middle" font-size="9.5" fill="#E8C547">MIDI 控制器（不发声）</text>
 <text x="160" y="184" text-anchor="middle" font-size="8.5" fill="#6E6A64">键=消息 · velocity · aftertouch · 弯音/调制轮</text>

 <path d="M284,110 L356,110" stroke="#E8C547" stroke-width="2"/>
 <text x="292" y="102" font-size="9" fill="#E8C547">五针 DIN · 31.25 kbps</text>

 <g font-size="9.5" fill="#97C459">
 <rect x="360" y="70" width="120" height="34" rx="4" fill="none" stroke="#97C459" stroke-width="1.2"/>
 <text x="420" y="91" text-anchor="middle">Roland 音源</text>
 <rect x="360" y="112" width="120" height="34" rx="4" fill="none" stroke="#97C459" stroke-width="1.2"/>
 <text x="420" y="133" text-anchor="middle">Yamaha 音源</text>
 <rect x="500" y="70" width="120" height="34" rx="4" fill="none" stroke="#97C459" stroke-width="1.2"/>
 <text x="560" y="91" text-anchor="middle">Korg 音源</text>
 <rect x="500" y="112" width="120" height="34" rx="4" fill="none" stroke="#97C459" stroke-width="1.2"/>
 <text x="560" y="133" text-anchor="middle">Sequential 音源</text>
 </g>

 <text x="20" y="216" font-size="10.5" fill="#E8C547"> 双父握手：Kakehashi（Roland）主动找 Smith（Sequential）—— 发明是一个人的事，标准是一群人的事</text>
 <text x="20" y="238" font-size="10" fill="#A9A49B">UMI（you-me）被嫌 corny → Smith 坚持用 instrument → Musical Instrument Digital Interface</text>

 <rect x="30" y="250" width="286" height="56" rx="8" fill="none" stroke="#6E6A64" stroke-width="1.1"/>
 <text x="173" y="270" text-anchor="middle" font-size="9.5" fill="#A9A49B">1983 NAMM：第一次对话</text>
 <text x="48" y="290" font-size="9" fill="#6E6A64">Prophet-600 ↔ Roland JP-6（对手琴互相听懂）</text>
 <text x="48" y="300" font-size="9" fill="#97C459">这次不是谁的标准赢，是大家共建一个</text>

 <rect x="324" y="250" width="286" height="56" rx="8" fill="none" stroke="#6E6A64" stroke-width="1.1"/>
 <text x="467" y="270" text-anchor="middle" font-size="9.5" fill="#A9A49B">MIDI 1.0：自1983年发布并延续使用</text>
 <text x="342" y="290" font-size="9" fill="#6E6A64">近四十年 viable · Sequential 1987 破产 · MIDI 永生</text>
 <text x="342" y="300" font-size="9" fill="#97C459">2013 双父 Technical Grammy · 技术活得比公司久</text>

 <g font-family="system-ui,sans-serif" font-size="10.5" fill="#A9A49B">
 <text x="20" y="330" fill="#E8C547"> USB MIDI（1999）嵌入 Audio Class → 平价控制器崛起（Keystation · MPK Mini <$200）</text>
 <text x="20" y="350" font-size="10" fill="#A9A49B"> Baglioni 1986 意大利体育场巡演：一个人 + 一套 MIDI = 一支乐队（分离的最早舞台证明）</text>
 <text x="20" y="370" fill="#6E6A64">⚠️ 示意图：按文字描述绘制，非实物比例。</text>
 </g>
</svg>
```

```range
{"range":"C1–C8","common":"C1–C8","caption":"MIDI 控制器的「音域」（本身不发声 · 键位映射由接收端决定 · 图示为 25–88 键范围）","caption_en":"MIDI controller 「range」 (silent by itself · key mapping decided by the receiver · 25–88 keys shown)","note":"MIDI 控制器属电鸣系统的控制端（元乐器——本身不发声）。25/49/61/88 键规格，力度感应与触后（channel/polyphonic aftertouch）；输出 MIDI 消息（note on/off · velocity · pitch bend · control change）经五针 DIN（31.25 kbps）或 USB。音域取决于接收端的音源——同一台控制器今天可驱动钢琴明天可驱动鼓机。键位映射即「音域」。记谱按接收端音源实音。"}
```

```audiolab
{"type":"instrument","gm":"Lead 8 (bass + lead)","synth":"bowed","phrase":["C4","E4","G4","C5","G4","E4","C4"],"label":"同一组音符触发的合成音色","label_en":"A synthesizer sound triggered by one note sequence","hint":"本例用C–E–G的音名短句触发接收端音色。MIDI负责传递音符等消息，接收端才把消息变成声音；实际连接还要分别检查输入路由和音频输出。","hint_en":"A C–E–G-based phrase triggers the receiving sound. MIDI carries note and other messages; the receiver turns them into audio. In a real setup, check MIDI routing and audio output separately."}
```
:::
