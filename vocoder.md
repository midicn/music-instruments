---
id: vocoder
site: inst
cat: I11
title: 声码器
title_en: The vocoder
summary: 从战时密码到机器人的歌喉 —— 一个发明在两个世界里的两种命运
summary_en: From wartime cipher to the robot's singing voice — one invention, two destinies
level: standard
tags: [乐器, 电子, 电鸣, 西洋, 效果器, 声码器, 人声处理, Kraftwerk]
tags_en: [instrument, electronic, electrophone, western, effects, vocoder, voice-processing, kraftwerk]
alias: [声码器, vocoder, Voder, 语音编码器, SIGSALY]
order: 194
links:
  - "[[instrument:theremin]]"
  - "[[instrument:hammond-organ]]"
  - "[[instrument:midi-controller]]"
  - "[[concept:timbre]]"
  - "[[concept:pitch]]"
instances:
  - chinafolk-002994 | 《算盘子》 —— ⭐⭐「算」：**声码器的本质是「算频谱」**——「**输入信号被分成多个频带，每个频带的信号电平给出频谱能量的瞬时表示**」——**算盘拨的不是账，是频谱的形状**（**C3 · 仅限学习研究**；库内无声码器录音，取民歌作意象参照）
  - chinafolk-000609 | 《五卷四书无心听》 —— ⭐⭐「无心听」：**Voder 需要专业操作员**——「**这是一台操作复杂的机器，但熟练的操作员能产生可辨认的语音**」——**无心听的人听不懂，有心的人才开得动**（**C3 · 仅限学习研究**）
  - chinafolk-002354 | 《开山修路通南北》 —— ⭐⭐「通南北」：**SIGSALY（1943）**——「用于二战期间的加密语音通讯」——**开山修路，把「语音」通到了大洋两岸的密线上**（**C3 · 仅限学习研究**）
sources:
  - ⭐⭐ **主线：一个发明，两种命运（本页最该记住的一条）** —— 「**声码器由 Bell Labs 的 Homer Dudley 于 1938 年发明，作为合成人类语音的手段**」；「**这项工作发展为通道声码器，用于电信的语音编码以在传输中节省带宽**」；⭐⭐ **两条命运**：**电信世界（SIGSALY 战时加密 → LPC 语音压缩成为数字电话标准）与音乐世界（Moog/Carlos → Kraftwerk 的后人类美学）——同一个电路，两个世界的两种「名」**
  - ⭐⭐ **Voder（1939 世界博览会）与 Vocoder 的分工** —— 「**为了演示其解码器的语音合成能力，Voder（Voice Operation Demonstrator）在 1939–1940 年纽约世博会的 AT&T 馆向公众推出**」；「**Voder 由一个电子振荡器（有调音源）与噪声发生器（嘶声）组成、10 带共鸣滤波器（可变增益放大器）做声道、以及手动控制器（压力感应键控滤波 + 踏板控音高）**」；⭐⭐ 「这是一台操作复杂的机器，但熟练的操作员能产生可辨认的语音」——**Voder 是「人来演的语音合成」，Vocoder 是「自动的语音编码」**——两个名字，两种自动化程度
  - ⭐⭐ **原理（两个阶段）** —— 「**分析：输入信号经多带滤波器，每带输出由包络跟随器测量，包络跟随器的信号被传送到解码器**」；「**合成：解码器把这些作为控制信号施加到输出滤波通道的相应放大器**」；⭐⭐ **「原始语音信号的瞬时频率信息被丢弃了——对声码器作为加密辅助的原始用途而言这并不重要」**——⭐⭐ **「正是这个 dehumanizing（去人性化）的方面，使它在流行音乐与音频娱乐中成为有用的特殊声音效果**——**丢弃「音高」保住「形状」：音乐效果正来自工程的丢弃**
  - ⭐⭐ **音乐化的转折（Moog/Carlos/Kraftwerk）** —— 「**数十年后，Robert Moog 与 Wendy Carlos 造了一台耦合到 Moog 模块化合成器的声码器，把如今标志性的机器人嗓音引入音乐**」；「**Carlos 用它为 Stanley Kubrick 的电影 A Clockwork Orange 人声化贝多芬第九交响曲的第四乐章**」；⭐⭐ **「德国电子先驱 Kraftwerk 在 1974 年专辑 Autobahn 上使用声码器，随后影响了一整代电子音乐家**——Herbie Hancock · Afrika Bambaataa……」
  - ⭐⭐ **vocoder / Auto-Tune / talkbox 三分（一页说清三种「机器唱歌」）** —— 「**声码器把一个信号的频谱特征施加到另一个信号——它不改音高，从两个输入创造新声音**」；「**Auto-Tune 是音高修正工具——分析演唱并把跑调的音符移到最近的正确音高——重度使用+快速修正产生 T-Pain 式的平滑阶梯效果**」；⭐⭐ **「talkbox 是物理装置：把吉他音箱或合成器的声音经管子送进演奏者嘴里，演奏者用嘴唇舌头下颚塑造声音，麦克风拾取结果——滤波发生在演奏者口腔内而非电子滤波器组**」（**Peter Frampton 的 Show Me the Way · Zapp 的目录是 talkbox 地标**）
  - ⭐⭐ **电信世界的延续（LPC）** —— 「**早期数字电话系统使用脉冲编码调制，需要 64 kbps 传输一路语音——那是很大的带宽**」；「**基于线性预测编码（LPC）的声码器通过建模声道、只传输重建语音所需的参数而非完整音频波形，大幅降低带宽——美国政府标准 LPC-10 只用 2.4 kbps**」——⭐⭐ **「只传参数不传波形」——声码器的哲学成了整个数字通信的地基**
  - ⭐⭐ **CHER 1998 与 Auto-Tune 的滥用** —— 「**重度应用把人声锁到最近的半音太快，把歌手的音高规训到不自然的机器完美——常被误认为声码器效果，合成的 Auto-Tune 摆音由 Cher 的 1998 年金曲 Believe 推广，此后被 Kanye West · T-Pain · Will.i.am 使用（可以说过度使用）**」——⭐⭐ **对照 TB-303（缺陷成签名）：**「**Auto-Tune 的「过度修正」也是缺陷成签名——但它是「软件缺陷」而非「硬件缺陷」**
  - **Daft Punk** —— 「**Daft Punk 用声码器人格化他们的『唱歌机器人』形象，在音乐上融合人声与合成器——不过法国组合常用 talkbox——经管子说话的物理盒子来创造类声码器效果**」——⭐ **连「机器人形象」本身都可以是 talkbox 演的：眼见耳听都未必为实**
  - 「声码器属**电鸣**系统的效果端（**不独立发声——寄生在音源上**）」依 Hornbostel–Sachs 分类
updated: 2026-10-15
---

::: zh
**前面几页的乐器都在「制造声音」——这一页的效果器在「改写声音的形状」。**

> 「**正是这个 dehumanizing（去人性化）的方面，
> 使它在流行音乐与音频娱乐中成为有用的特殊声音效果。**」

⭐⭐ **本页写声码器——效果第 1 条。主线一句话：一个发明，两种命运。**

| 分类 | 归属 |
|---|---|
| **HS 分类** | **电鸣系统的效果端**（**不独立发声——寄生在音源上**）· **滤波器组 + 包络跟随** |
| **出身** | ⭐⭐ **Homer Dudley（Bell Labs · 1938 专利 · 1939 世博 Voder 演示）**——**为电信带宽与战时加密而生** |
| **两个世界** | ⭐⭐ **电信：SIGSALY 战时加密 → LPC 2.4kbps** ｜ **音乐：Moog/Carlos → Kraftwerk 的后人类美学** |
| **八音对照** | 八音之外——**效果器的「乐器性」第一次被正名** |

## ⭐⭐ 主线：一个发明，两种命运

> 「**声码器由 Bell Labs 的 Homer Dudley 于 1938 年发明，作为合成人类语音的手段；
> 这项工作发展为通道声码器，用于电信的语音编码以在传输中节省带宽**」。

⭐⭐ **同一个电路，两个世界的两种「名」**：

| | ⭐ **电信世界** | ⭐ **音乐世界** |
|---|---|---|
| 名字 | **语音编码器（保密通信）** | **声码器效果（机器人歌喉）** |
| 目标 | **省带宽 · 加密** | **去人性化 · 未来感** |
| 里程碑 | **SIGSALY（1943）→ LPC-10（2.4kbps）** | **Moog/Carlos → Kraftwerk → Daft Punk** |

⭐⭐ **对照全站**：**Telharmonium 的技术「死于」时代，声码器的技术「活在」两个时代——**
**因为它同时握着两个世界的需求。**

## ⭐⭐ Voder（1939）：人来演的语音合成

> 「**为了演示其解码器的语音合成能力，Voder（Voice Operation Demonstrator）
> 在 1939–1940 年纽约世博会的 AT&T 馆向公众推出**」；
> 「**Voder 由一个电子振荡器（有调音源）与噪声发生器（嘶声）组成、
> 10 带共鸣滤波器（可变增益放大器）做声道、以及手动控制器
> （压力感应键控滤波 + 踏板控音高）**」。

⭐⭐ 「这是一台操作复杂的机器，但熟练的操作员能产生可辨认的语音」——
**Voder 是「人来演的语音合成」，Vocoder 是「自动的语音编码」**——两个名字，两种自动化程度。

⭐⭐ **Voder 与 Vocoder 的分工**：
**Voder 是「人来演的语音合成」（手动控制每个滤波器）；
Vocoder 是「自动的语音编码」（机器分析）——**
**两个名字，两种自动化程度。**

## ⭐⭐ 原理：丢弃音高，保住形状

> 「**分析：输入信号经多带滤波器，每带输出由包络跟随器测量；
> 合成：解码器把这些作为控制信号施加到输出滤波通道的相应放大器**」；
> ⭐⭐ **「原始语音信号的瞬时频率信息被丢弃了——对加密而言这并不重要」——**
> ⭐⭐ **「正是这个 dehumanizing（去人性化）的方面，使它在流行音乐中成为有用的
> 特殊声音效果**」。

⭐⭐ **这是全站最锋利的一次「工程与艺术的换位」**：
**对加密工程师，「丢掉音高」是压缩的代价；
对音乐家，「丢掉音高」正是机器唱歌的原因——**
**声音的「形状」可以与「音高」分离，这个认识同时诞生了保密电话与机器人歌喉。**

## ⭐⭐ 音乐化的转折

> 「**数十年后，Robert Moog 与 Wendy Carlos 造了一台耦合到 Moog 模块化合成器的声码器，
> 把如今标志性的机器人嗓音引入音乐**」；
> 「**Carlos 用它为 Stanley Kubrick 的电影 A Clockwork Orange 人声化
> 贝多芬第九交响曲的第四乐章**」；
> 「**德国电子先驱 Kraftwerk 在 1974 年专辑 Autobahn 上使用声码器，
> 随后影响了一整代电子音乐家**」。

⭐⭐ **对照 moog-modular 条的 Switched-On Bach（Carlos）——**
**Carlos 的两次「古典 × 电子」：一次用合成器弹巴赫（1968），
一次用声码器唱贝多芬（A Clockwork Orange）——**
**两次都改写了「电子乐器能做什么」。**

## ⭐⭐ 三分：vocoder / Auto-Tune / talkbox

一页说清三种「机器唱歌」：

| | ⭐ **Vocoder** | **Auto-Tune** | ⭐⭐ **Talkbox** |
|---|---|---|---|
| 原理 | **频谱移植**（两输入） | **音高修正**（单输入） | **口腔滤波**（物理） |
| 音高 | 不改 | **改** | 改（靠嘴唇） |
| 滤波在哪 | **电子滤波器组** | 软件算法 | **演奏者的口腔** |
| 地标 | Kraftwerk · Daft Punk | Cher《Believe》· T-Pain | **Frampton · Zapp** |

⭐⭐ **talkbox 的「滤波发生在演奏者口腔内」——**
**对照全站的「身体作为乐器」谱系（口弦/喉雕/卡林巴的共鸣腔）——**
**talkbox 是电子时代最「身体」的效果器。**

## ⭐⭐ 电信世界的延续：只传参数不传波形

> 「**早期数字电话系统使用脉冲编码调制，需要 64 kbps 传输一路语音——
> 那是很大的带宽**」；
> 「**基于线性预测编码（LPC）的声码器通过建模声道、只传输重建语音所需的参数
> 而非完整音频波形，大幅降低带宽——美国政府标准 LPC-10 只用 2.4 kbps**」。

⭐⭐ **「只传参数不传波形」——声码器的哲学成了整个数字通信的地基**：
**对照 Prophet-5 的 patch memory（「记住参数而非音频」）——**
**「参数化」是数字音频的根本思想，声码器是它的第一个大规模应用。**

## ⭐⭐ Cher 1998 与「缺陷成签名」的软件版

> 「**重度应用把人声锁到最近的半音太快，把歌手的音高规训到不自然的机器完美——
> 常被误认为声码器效果，合成的 Auto-Tune 摆音由 Cher 的 1998 年金曲 Believe 推广，
> 此后被 Kanye West · T-Pain · Will.i.am 使用（可以说过度使用）**」。

⭐⭐ **对照 TB-303（缺陷成签名）**——**Auto-Tune 的「过度修正」也是缺陷成签名——
但它是「软件缺陷」而非「硬件缺陷」**。
**两次都是「错误使用」被音乐收编——一次花了 7 年（303），一次只花了 1 年（Believe）。**

## 收口：三句记住声码器

| 问 | 答 |
|---|---|
| ⭐ 最要紧的一条 | ⭐⭐ **一个发明，两种命运**——电信（SIGSALY → LPC 2.4kbps）与音乐（Moog/Carlos → Kraftwerk）；⭐⭐ **「丢弃音高保住形状」的 dehumanizing 恰是音乐效果之源** |
| ⭐⭐ Voder | ⭐⭐ **1939 世博：人来演的语音合成**（压力键控滤波+踏板控音高）——**Voder（手动的）vs Vocoder（自动的）** |
| ⭐⭐ 原理 | **多带滤波 + 包络跟随 → 控制信号施加到载波滤波通道**；⭐⭐ **「瞬时频率信息被丢弃」**——**音乐效果正来自工程的丢弃** |
| ⭐⭐ 转折 | **Moog/Carlos（A Clockwork Orange 的贝多芬）→ Kraftwerk Autobahn（1974）**——**机器人歌喉进入音乐** |
| ⭐⭐ 三分 | **Vocoder 频谱移植｜Auto-Tune 音高修正｜Talkbox 口腔滤波**——⭐⭐ **talkbox 的滤波发生在演奏者口腔内（最「身体」的效果器）** |
| ⭐⭐ 电信延续 | **LPC-10 只用 2.4kbps（对照 PCM 64kbps）**——⭐⭐ **「只传参数不传波形」=数字音频的根本思想（对照 Prophet-5 patch memory）** |
| ⭐⭐ Cher 1998 | **Auto-Tune 过度修正成签名**——⭐⭐ **软件版「缺陷成签名」（303 花 7 年，Believe 花 1 年）** |
| ⭐ Daft Punk | **「唱歌机器人」形象——不过常用 talkbox 演的**——⭐ **眼见耳听都未必为实** |
| HS | **电鸣系统的效果端**（寄生在音源上） |

**声码器的故事是「一个电路的两次投胎」：**
**第一次投胎做保密电话，第二次投胎做机器人的歌喉。**
⭐⭐ **它的哲学「只传参数不传波形」至今统治着数字音频——**
**你以为你在听声音，其实你常常在听参数。**

```svg
<svg viewBox="0 0 640 380" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="The vocoder: one invention, two destinies — Homer Dudley's Bell Labs circuit of 1938 served telecom as SIGSALY wartime encryption and later LPC compression at 2.4 kilobits, and served music through Moog and Carlos, Kraftwerk's Autobahn and Daft Punk's singing robots; the principle discards pitch and keeps spectral shape, which is precisely why the dehumanising effect sings">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">声码器 · 一个发明，两种命运</text>
    <text x="20" y="44" font-size="11" fill="#6E6A64">丢弃音高，保住形状 —— 去人性化正是音乐效果之源</text>
  </g>

  <rect x="40" y="62" width="260" height="60" rx="8" fill="#26241F" stroke="#9C7A3C" stroke-width="1.3"/>
  <text x="170" y="84" text-anchor="middle" font-size="9.5" fill="#A9A49B">Bell Labs · Homer Dudley · 1938</text>
  <text x="170" y="104" text-anchor="middle" font-size="9" fill="#6E6A64">多带滤波 + 包络跟随 → 控制信号</text>

  <path d="M300,92 L340,92" stroke="#E8C547" stroke-width="2"/>
  <text x="306" y="84" font-size="9" fill="#E8C547">1943</text>

  <rect x="344" y="62" width="256" height="60" rx="8" fill="#26241F" stroke="#E8C547" stroke-width="1.4"/>
  <text x="472" y="84" text-anchor="middle" font-size="9.5" fill="#E8C547">SIGSALY（二战加密语音）</text>
  <text x="472" y="104" text-anchor="middle" font-size="9" fill="#6E6A64">→ LPC-10（2.4 kbps · 数字电话的地基）</text>

  <g font-family="system-ui,sans-serif" font-size="10" fill="#A9A49B">
    <text x="40" y="152" font-size="10" fill="#97C459">电信世界</text>
    <text x="120" y="152" font-size="9.5">省带宽 · 加密 · 「只传参数不传波形」</text>
    <text x="40" y="176" font-size="10" fill="#F0997B">音乐世界</text>
    <text x="120" y="176" font-size="9.5">去人性化 · 未来感 · 机器人的歌喉</text>
  </g>

  <rect x="30" y="190" width="286" height="56" rx="8" fill="none" stroke="#97C459" stroke-width="1.2"/>
  <text x="173" y="210" text-anchor="middle" font-size="9.5" fill="#97C459">音乐化转折</text>
  <text x="48" y="230" font-size="9" fill="#6E6A64">Moog/Carlos（A Clockwork Orange 贝多芬）</text>
  <text x="48" y="240" font-size="9" fill="#97C459">→ Kraftwerk Autobahn（1974）→ Daft Punk</text>

  <rect x="324" y="190" width="286" height="56" rx="8" fill="none" stroke="#6E6A64" stroke-width="1.1"/>
  <text x="467" y="210" text-anchor="middle" font-size="9.5" fill="#A9A49B">三分：机器唱歌的三条路</text>
  <text x="342" y="230" font-size="9" fill="#6E6A64">Vocoder 频谱移植 · Auto-Tune 音高修正</text>
  <text x="342" y="240" font-size="9" fill="#97C459">⭐ Talkbox 口腔滤波 —— 最「身体」的效果器</text>

  <text x="20" y="272" font-size="10.5" fill="#E8C547">⭐ 「瞬时频率信息被丢弃」—— 音乐效果正来自工程的丢弃</text>
  <text x="20" y="292" font-size="10" fill="#A9A49B">⭐⭐ 「只传参数不传波形」= 数字音频的根本思想（对照 Prophet-5 patch memory）</text>

  <g font-family="system-ui,sans-serif" font-size="10.5" fill="#A9A49B">
    <text x="20" y="318" fill="#E8C547">⭐ Cher《Believe》（1998）：Auto-Tune 过度修正成签名 —— 软件版「缺陷成签名」（303 花 7 年，Believe 花 1 年）</text>
    <text x="20" y="338" font-size="10" fill="#A9A49B">⭐ Daft Punk 的「唱歌机器人」常用 talkbox 演的 —— 眼见耳听都未必为实</text>
    <text x="20" y="358" fill="#6E6A64">⚠️ 示意图：按文字描述绘制，非实物比例。</text>
  </g>
</svg>
```

```range
{"range":"C1–C5","common":"C1–C5","caption":"声码器的「音域」（频谱移植效果器 · 载波音源决定输出音域）","caption_en":"Vocoder 「range」 (spectral-transplant effect · the carrier's span decides the output)","note":"声码器属电鸣系统的效果端（不独立发声——寄生在音源上）。原理：调制信号（人声）经多带滤波（8–20 频带）+ 包络跟随器 → 控制信号施加到载波（合成器波形/噪声）的对应滤波通道——输出音域等于载波音源的音域（典型 C1–C5）。声码器不修正音高——它丢弃调制信号的瞬时频率、只保留频谱形状。Voder（1939 世博）为手动版本；SIGSALY（1943）为战时加密版本；LPC-10（2.4kbps）为现代数字电话地基。"}
```

```audiolab
{"type":"instrument","gm":"Voice Oohs","synth":"bowed","phrase":["C3","E3","G3","C4","E4","G4","C5"],"label":"声码器的机器歌喉：频谱移植的人声（借人声嘟近似）","label_en":"The vocoder's machine voice — a transplanted spectrum (voice oohs stand in)","hint":"声码器的本质是「把人声的频谱形状移植到合成器的音色上」——这条人声嘟采样取其「人声质感」。真实声码器的三样特征这里听不出来：一是双输入结构（人声调制+合成器载波）；二是「丢弃音高保住形状」的哲学（音乐效果正来自工程的丢弃）；三是它与 Auto-Tune/talkbox 的三分——三种「机器唱歌」原理完全不同。","hint_en":"The vocoder's essence is 「transplanting the voice's spectral shape onto a synth」 — this voice-oohs sample takes the vocal texture. Three things are absent: the dual-input structure（voice modulates, synth carries）, the philosophy of discarding pitch while keeping shape（the musical effect born of engineering's discard）, and the three-way split from Auto-Tune and talkbox — three ways a machine sings, on entirely different principles."}
```
:::

::: en
Every instrument in the previous pages 「made」 sound — this page's effect 「rewrites」 the shape
of sound.

> 「**正是这个 dehumanizing（去人性化）的方面，
> 使它在流行音乐与音频娱乐中成为有用的特殊声音效果**」.

⭐⭐ **This page is the vocoder — first of the effects family. One line: one invention, two
destinies.**

| Class | Assignment |
|---|---|
| **HS class** | **the effects end of the electrophone system**（**makes no sound of its own; parasitic on sound sources**）· **filter banks + envelope followers** |
| **Origin** | ⭐⭐ **Homer Dudley（Bell Labs · patent 1938 · Voder demo at the 1939 World's Fair）** — born for telecom bandwidth and wartime encryption |
| **Two worlds** | ⭐⭐ **telecom: SIGSALY → LPC at 2.4kbps** ｜ **music: Moog/Carlos → Kraftwerk's post-human aesthetics** |
| **Bayin note** | Outside the bayin — **the first time an effect's 「instrumentality」 was named** |

## ⭐⭐ The main line: one invention, two destinies

> 「**声码器由 Bell Labs 的 Homer Dudley 于 1938 年发明，作为合成人类语音的手段；
> 这项工作发展为通道声码器，用于电信的语音编码以在传输中节省带宽**」.

⭐⭐ **One circuit, two names in two worlds**:

| | ⭐ **Telecom world** | ⭐ **Music world** |
|---|---|---|
| Name | **voice encoder（secure comms）** | **vocoder effect（robot voice）** |
| Goal | **bandwidth · encryption** | **dehumanisation · futurism** |
| Milestones | **SIGSALY（1943）→ LPC-10（2.4kbps）** | **Moog/Carlos → Kraftwerk → Daft Punk** |

⭐⭐ **Against the site**: **the Telharmonium's technology 「died」 of its era; the vocoder's
「lives」 in two eras — because it held the needs of two worlds at once.**

## ⭐⭐ The Voder（1939）: speech synthesis played by a human

> 「**为了演示其解码器的语音合成能力，Voder（Voice Operation Demonstrator）
> 在 1939–1940 年纽约世博会的 AT&T 馆向公众推出**」;
> 「**Voder 由一个电子振荡器（有调音源）与噪声发生器（嘶声）组成、
> 10 带共鸣滤波器（可变增益放大器）做声道、以及手动控制器
> （压力感应键控滤波 + 踏板控音高）**」.

⭐⭐ **「这是一台操作复杂的机器，但熟练的操作员能产生可辨认的语音」—**

⭐⭐ **The Voder/Vocoder division**:
**the Voder was 「speech synthesis played by a human」（hand-controlled filters）;
the Vocoder was 「automatic speech encoding」（machine analysis）—**
**two names, two degrees of automation.**

## ⭐⭐ The principle: discard the pitch, keep the shape

> 「**分析：输入信号经多带滤波器，每带输出由包络跟随器测量；
> 合成：解码器把这些作为控制信号施加到输出滤波通道的相应放大器**」;
> ⭐⭐ **「原始语音信号的瞬时频率信息被丢弃了——对加密而言这并不重要」—**
> ⭐⭐ **「正是这个 dehumanizing（去人性化）的方面，使它在流行音乐中成为有用的
> 特殊声音效果」**.

⭐⭐ **The sharpest 「engineering-art swap」 on the site**:
**to the encryption engineer, 「discarding pitch」 was the price of compression;
to the musician, 「discarding pitch」 is why the machine sings —**
**the insight that sound's 「shape」 can be separated from its 「pitch」 gave birth to both the
secure phone and the robot's singing voice.**

## ⭐⭐ The musical turn

> 「**数十年后，Robert Moog 与 Wendy Carlos 造了一台耦合到 Moog 模块化合成器的声码器，
> 把如今标志性的机器人嗓音引入音乐**」;
> 「**Carlos 用它为 Stanley Kubrick 的电影 A Clockwork Orange 人声化
> 贝多芬第九交响曲的第四乐章**」;
> 「**德国电子先驱 Kraftwerk 在 1974 年专辑 Autobahn 上使用声码器，
> 随后影响了一整代电子音乐家**」.

⭐⭐ **Against the moog-modular page's Switched-On Bach（Carlos）—**
**Carlos's two 「classical × electronic」 crossings: playing Bach on a synthesizer（1968）,
singing Beethoven through a vocoder（A Clockwork Orange）—**
**each rewrote what electronic instruments could do.**

## ⭐⭐ Three ways a machine sings: vocoder / Auto-Tune / talkbox

| | ⭐ **Vocoder** | **Auto-Tune** | ⭐⭐ **Talkbox** |
|---|---|---|---|
| Principle | **spectral transplant**（two inputs） | **pitch correction**（one input） | **acoustic filtering**（physical） |
| Pitch | untouched | **changed** | changed（by lips） |
| Where filtered | **electronic filter banks** | software | **the performer's mouth** |
| Landmarks | Kraftwerk · Daft Punk | Cher《Believe》· T-Pain | **Frampton · Zapp** |

⭐⭐ **The talkbox's 「filtering happens inside the performer's mouth」 —**
**against the site's 「body as instrument」 lineage（jaw harp/throat carvings/kalimba
resonators）—**
**the talkbox is the most 「bodily」 effect of the electronic age.**

## ⭐⭐ The telecom continuation: parameters, not waveforms

> 「**早期数字电话系统使用脉冲编码调制，需要 64 kbps 传输一路语音——
> 那是很大的带宽**」;
> 「**基于线性预测编码（LPC）的声码器通过建模声道、只传输重建语音所需的参数
> 而非完整音频波形，大幅降低带宽——美国政府标准 LPC-10 只用 2.4 kbps**」.

⭐⭐ **「只传参数不传波形」 — the vocoder's philosophy became the foundation of digital
communication**:
**against the Prophet-5's patch memory（「remember parameters, not audio」）—**
**「parameterisation」 is the fundamental idea of digital audio, and the vocoder was its first
massive application.**

## ⭐⭐ Cher 1998 and the software version of flaw-into-signature

> 「**重度应用把人声锁到最近的半音太快，把歌手的音高规训到不自然的机器完美——
> 常被误认为声码器效果，合成的 Auto-Tune 摆音由 Cher 的 1998 年金曲 Believe 推广，
> 此后被 Kanye West · T-Pain · Will.i.am 使用（可以说过度使用）**」.

⭐⭐ **Against the TB-303（flaw into signature）** — **Auto-Tune's 「over-correction」 is also a
flaw become signature — but a 「software flaw」, not a 「hardware flaw」**.
**Twice the 「wrong use」 was adopted by music: the 303 took 7 years, Believe took 1.**

## Recap: three sentences on the vocoder

| Q | A |
|---|---|
| ⭐ The key point | ⭐⭐ **one invention, two destinies** — telecom（SIGSALY → LPC at 2.4kbps）and music（Moog/Carlos → Kraftwerk）; ⭐⭐ **「discarding pitch, keeping shape」 — the dehumanising IS the musical effect** |
| ⭐⭐ The Voder | ⭐⭐ **1939 World's Fair: speech synthesis played by a human**（pressure-keyed filters + pitch pedal）— **Voder（manual）vs Vocoder（automatic）** |
| ⭐⭐ The principle | **multiband filters + envelope followers → control signals onto the carrier's filter channels**; ⭐⭐ **「instantaneous frequency information was discarded」** — **the musical effect comes from the engineering's discard** |
| ⭐⭐ The turn | **Moog/Carlos（Beethoven in A Clockwork Orange）→ Kraftwerk Autobahn（1974）** — **the robot voice enters music** |
| ⭐⭐ The three-way split | **Vocoder spectral-transplant｜Auto-Tune pitch-correction｜Talkbox mouth-filtering** — ⭐⭐ **the talkbox filters inside the performer's mouth（the most 「bodily」 effect）** |
| ⭐⭐ Telecom continuation | **LPC-10 at 2.4kbps（vs PCM 64kbps）** — ⭐⭐ **「parameters, not waveforms」= the fundamental idea of digital audio（against the Prophet-5's patch memory）** |
| ⭐⭐ Cher 1998 | **Auto-Tune over-correction as signature** — ⭐⭐ **the software version of flaw-into-signature（303 took 7 years, Believe took 1）** |
| ⭐ Daft Punk | **the 「singing robot」 image — often performed on a talkbox** — ⭐ **what you see and hear is not what it is** |
| HS | **the effects end of the electrophone system**（parasitic on sound sources） |

**The vocoder's story is 「one circuit, two reincarnations」:**
**first born as the secure phone, reborn as the robot's singing voice.**
⭐⭐ **Its philosophy — 「parameters, not waveforms」 — still governs digital audio:**
**you think you are listening to sound; often you are listening to parameters.**

```svg
<svg viewBox="0 0 640 380" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="The vocoder: one invention, two destinies — Homer Dudley's Bell Labs circuit of 1938 served telecom as SIGSALY wartime encryption and later LPC compression at 2.4 kilobits, and served music through Moog and Carlos, Kraftwerk's Autobahn and Daft Punk's singing robots; the principle discards pitch and keeps spectral shape, which is precisely why the dehumanising effect sings">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">声码器 · 一个发明，两种命运</text>
    <text x="20" y="44" font-size="11" fill="#6E6A64">丢弃音高，保住形状 —— 去人性化正是音乐效果之源</text>
  </g>

  <rect x="40" y="62" width="260" height="60" rx="8" fill="#26241F" stroke="#9C7A3C" stroke-width="1.3"/>
  <text x="170" y="84" text-anchor="middle" font-size="9.5" fill="#A9A49B">Bell Labs · Homer Dudley · 1938</text>
  <text x="170" y="104" text-anchor="middle" font-size="9" fill="#6E6A64">多带滤波 + 包络跟随 → 控制信号</text>

  <path d="M300,92 L340,92" stroke="#E8C547" stroke-width="2"/>
  <text x="306" y="84" font-size="9" fill="#E8C547">1943</text>

  <rect x="344" y="62" width="256" height="60" rx="8" fill="#26241F" stroke="#E8C547" stroke-width="1.4"/>
  <text x="472" y="84" text-anchor="middle" font-size="9.5" fill="#E8C547">SIGSALY（二战加密语音）</text>
  <text x="472" y="104" text-anchor="middle" font-size="9" fill="#6E6A64">→ LPC-10（2.4 kbps · 数字电话的地基）</text>

  <g font-family="system-ui,sans-serif" font-size="10" fill="#A9A49B">
    <text x="40" y="152" font-size="10" fill="#97C459">电信世界</text>
    <text x="120" y="152" font-size="9.5">省带宽 · 加密 · 「只传参数不传波形」</text>
    <text x="40" y="176" font-size="10" fill="#F0997B">音乐世界</text>
    <text x="120" y="176" font-size="9.5">去人性化 · 未来感 · 机器人的歌喉</text>
  </g>

  <rect x="30" y="190" width="286" height="56" rx="8" fill="none" stroke="#97C459" stroke-width="1.2"/>
  <text x="173" y="210" text-anchor="middle" font-size="9.5" fill="#97C459">音乐化转折</text>
  <text x="48" y="230" font-size="9" fill="#6E6A64">Moog/Carlos（A Clockwork Orange 贝多芬）</text>
  <text x="48" y="240" font-size="9" fill="#97C459">→ Kraftwerk Autobahn（1974）→ Daft Punk</text>

  <rect x="324" y="190" width="286" height="56" rx="8" fill="none" stroke="#6E6A64" stroke-width="1.1"/>
  <text x="467" y="210" text-anchor="middle" font-size="9.5" fill="#A9A49B">三分：机器唱歌的三条路</text>
  <text x="342" y="230" font-size="9" fill="#6E6A64">Vocoder 频谱移植 · Auto-Tune 音高修正</text>
  <text x="342" y="240" font-size="9" fill="#97C459">⭐ Talkbox 口腔滤波 —— 最「身体」的效果器</text>

  <text x="20" y="272" font-size="10.5" fill="#E8C547">⭐ 「瞬时频率信息被丢弃」—— 音乐效果正来自工程的丢弃</text>
  <text x="20" y="292" font-size="10" fill="#A9A49B">⭐⭐ 「只传参数不传波形」= 数字音频的根本思想（对照 Prophet-5 patch memory）</text>

  <g font-family="system-ui,sans-serif" font-size="10.5" fill="#A9A49B">
    <text x="20" y="318" fill="#E8C547">⭐ Cher《Believe》（1998）：Auto-Tune 过度修正成签名 —— 软件版「缺陷成签名」（303 花 7 年，Believe 花 1 年）</text>
    <text x="20" y="338" font-size="10" fill="#A9A49B">⭐ Daft Punk 的「唱歌机器人」常用 talkbox 演的 —— 眼见耳听都未必为实</text>
    <text x="20" y="358" fill="#6E6A64">⚠️ 示意图：按文字描述绘制，非实物比例。</text>
  </g>
</svg>
```

```range
{"range":"C1–C5","common":"C1–C5","caption":"声码器的「音域」（频谱移植效果器 · 载波音源决定输出音域）","caption_en":"Vocoder 「range」 (spectral-transplant effect · the carrier's span decides the output)","note":"声码器属电鸣系统的效果端（不独立发声——寄生在音源上）。原理：调制信号（人声）经多带滤波（8–20 频带）+ 包络跟随器 → 控制信号施加到载波（合成器波形/噪声）的对应滤波通道——输出音域等于载波音源的音域（典型 C1–C5）。声码器不修正音高——它丢弃调制信号的瞬时频率、只保留频谱形状。Voder（1939 世博）为手动版本；SIGSALY（1943）为战时加密版本；LPC-10（2.4kbps）为现代数字电话地基。"}
```

```audiolab
{"type":"instrument","gm":"Voice Oohs","synth":"bowed","phrase":["C3","E3","G3","C4","E4","G4","C5"],"label":"声码器的机器歌喉：频谱移植的人声（借人声嘟近似）","label_en":"The vocoder's machine voice — a transplanted spectrum (voice oohs stand in)","hint":"声码器的本质是「把人声的频谱形状移植到合成器的音色上」——这条人声嘟采样取其「人声质感」。真实声码器的三样特征这里听不出来：一是双输入结构（人声调制+合成器载波）；二是「丢弃音高保住形状」的哲学（音乐效果正来自工程的丢弃）；三是它与 Auto-Tune/talkbox 的三分——三种「机器唱歌」原理完全不同。","hint_en":"The vocoder's essence is 「transplanting the voice's spectral shape onto a synth」 — this voice-oohs sample takes the vocal texture. Three things are absent: the dual-input structure（voice modulates, synth carries）, the philosophy of discarding pitch while keeping shape（the musical effect born of engineering's discard）, and the three-way split from Auto-Tune and talkbox — three ways a machine sings, on entirely different principles."}
```
:::