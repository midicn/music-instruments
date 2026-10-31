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
 - chinafolk-002994 | 《算盘子》 —— 「算」：**声码器的本质是「算频谱」**——「**输入信号被分成多个频带，每个频带的信号电平给出频谱能量的瞬时表示**」——**算盘拨的不是账，是频谱的形状**（**C3 · 仅限学习研究**；库内无声码器录音，取民歌作意象参照）
 - chinafolk-000609 | 《五卷四书无心听》 —— 「无心听」：**Voder 需要专业操作员**——「**这是一台操作复杂的机器，但熟练的操作员能产生可辨认的语音**」——**无心听的人听不懂，有心的人才开得动**（**C3 · 仅限学习研究**）
 - chinafolk-002354 | 《开山修路通南北》 —— 「通南北」：**SIGSALY（1943）**——「用于二战期间的加密语音通讯」——**开山修路，把「语音」通到了大洋两岸的密线上**（**C3 · 仅限学习研究**）
sources:
 - **主线：一个发明，两种命运（本页最该记住的一条）** —— 「**声码器由 Bell Labs 的 Homer Dudley 于 1938 年发明，作为合成人类语音的手段**」；「**这项工作发展为通道声码器，用于电信的语音编码以在传输中节省带宽**」； **两条命运**：**电信世界（SIGSALY 战时加密 → LPC 语音压缩成为数字电话标准）与音乐世界（Moog/Carlos → Kraftwerk 的后人类美学）——同一个电路，两个世界的两种「名」**
 - **Voder（1939 世界博览会）与 Vocoder 的分工** —— 「**为了演示其解码器的语音合成能力，Voder（Voice Operation Demonstrator）在 1939–1940 年纽约世博会的 AT&T 馆向公众推出**」；「**Voder 由一个电子振荡器（有调音源）与噪声发生器（嘶声）组成、10 带共鸣滤波器（可变增益放大器）做声道、以及手动控制器（压力感应键控滤波 + 踏板控音高）**」； 「这是一台操作复杂的机器，但熟练的操作员能产生可辨认的语音」——**Voder 是「人来演的语音合成」，Vocoder 是「自动的语音编码」**——两个名字，两种自动化程度
 - **原理（两个阶段）** —— 「**分析：输入信号经多带滤波器，每带输出由包络跟随器测量，包络跟随器的信号被传送到解码器**」；「**合成：解码器把这些作为控制信号施加到输出滤波通道的相应放大器**」； **「原始语音信号的瞬时频率信息被丢弃了——对声码器作为加密辅助的原始用途而言这并不重要」**—— **「正是这个 dehumanizing（去人性化）的方面，使它在流行音乐与音频娱乐中成为有用的特殊声音效果**——**丢弃「音高」保住「形状」：音乐效果正来自工程的丢弃**
 - **音乐化的转折（Moog/Carlos/Kraftwerk）** —— 「**数十年后，Robert Moog 与 Wendy Carlos 造了一台耦合到 Moog 模块化合成器的声码器，把如今标志性的机器人嗓音引入音乐**」；「**Carlos 用它为 Stanley Kubrick 的电影 A Clockwork Orange 人声化贝多芬第九交响曲的第四乐章**」； **「德国电子先驱 Kraftwerk 在 1974 年专辑 Autobahn 上使用声码器，随后影响了一整代电子音乐家**——Herbie Hancock · Afrika Bambaataa……」
 - **vocoder / Auto-Tune / talkbox 三分（一页说清三种「机器唱歌」）** —— 「**声码器把一个信号的频谱特征施加到另一个信号——它不改音高，从两个输入创造新声音**」；「**Auto-Tune 是音高修正工具——分析演唱并把跑调的音符移到最近的正确音高——重度使用+快速修正产生 T-Pain 式的平滑阶梯效果**」； **「talkbox 是物理装置：把吉他音箱或合成器的声音经管子送进演奏者嘴里，演奏者用嘴唇舌头下颚塑造声音，麦克风拾取结果——滤波发生在演奏者口腔内而非电子滤波器组**」（**Peter Frampton 的 Show Me the Way · Zapp 的目录是 talkbox 地标**）
 - **电信世界的延续（LPC）** —— 「**早期数字电话系统使用脉冲编码调制，需要 64 kbps 传输一路语音——那是很大的带宽**」；「**基于线性预测编码（LPC）的声码器通过建模声道、只传输重建语音所需的参数而非完整音频波形，大幅降低带宽——美国政府标准 LPC-10 只用 2.4 kbps**」—— **「只传参数不传波形」——声码器的哲学成了整个数字通信的地基**
 - **CHER 1998 与 Auto-Tune 的滥用** —— 「**重度应用把人声锁到最近的半音太快，把歌手的音高规训到不自然的机器完美——常被误认为声码器效果，合成的 Auto-Tune 摆音由 Cher 的 1998 年金曲 Believe 推广，此后被 Kanye West · T-Pain · Will.i.am 使用（可以说过度使用）**」—— **对照 TB-303（缺陷成签名）：**「**Auto-Tune 的「过度修正」也是缺陷成签名——但它是「软件缺陷」而非「硬件缺陷」**
 - **Daft Punk** —— 「**Daft Punk 用声码器人格化他们的『唱歌机器人』形象，在音乐上融合人声与合成器——不过法国组合常用 talkbox——经管子说话的物理盒子来创造类声码器效果**」—— **连「机器人形象」本身都可以是 talkbox 演的：眼见耳听都未必为实**
 - 「声码器属**电鸣**系统的效果端（**不独立发声——寄生在音源上**）」依 Hornbostel–Sachs 分类
updated: 2026-10-15
---

::: zh

电台里那个声音，气声在，齿音在，辅音清清楚楚，可音高是平的，像有人躲在你嗓子里替你唱。这是声码器最容易被认出来的样子：形状是你的，音高不是。

| 项 | 内容 |
|---|---|
| HS 分类 | 电鸣 · 效果端（不独立发声，寄生在音源上）· 多带滤波加包络跟随 |
| 出身 | 贝尔实验室的 Homer Dudley，1938 年取得专利 |
| 八音： | 不适用 —— 周代八音是中国乐器的体系 |

## 把声音拆成频谱

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
 <text x="342" y="240" font-size="9" fill="#97C459"> Talkbox 口腔滤波 —— 最「身体」的效果器</text>

 <text x="20" y="272" font-size="10.5" fill="#E8C547"> 「瞬时频率信息被丢弃」—— 音乐效果正来自工程的丢弃</text>
 <text x="20" y="292" font-size="10" fill="#A9A49B"> 「只传参数不传波形」= 数字音频的根本思想（对照 Prophet-5 patch memory）</text>

 <g font-family="system-ui,sans-serif" font-size="10.5" fill="#A9A49B">
 <text x="20" y="318" fill="#E8C547"> Cher《Believe》（1998）：Auto-Tune 过度修正成签名 —— 软件版「缺陷成签名」（303 花 7 年，Believe 花 1 年）</text>
 <text x="20" y="338" font-size="10" fill="#A9A49B"> Daft Punk 的「唱歌机器人」常用 talkbox 演的 —— 眼见耳听都未必为实</text>
 <text x="20" y="358" fill="#6E6A64">⚠️ 示意图：按文字描述绘制，非实物比例。</text>
 </g>
</svg>
```

先分析一段人声：切成十几个频带，每个频带用一个包络跟随器盯着，记下这一带的能量此刻有多大。合成的时候，这些数值变成控制信号，去开合另一路声音（载波）的对应滤波器。

人声的瞬时频率被丢掉了，留下的是一张随时间变化的频谱轮廓。载波给音高，包络给形状，两者一合，出来的东西有元音、有辅音、有语气，却没有一个真正被唱出来的音。

对人声这是损失，对音乐这是资源。工程上为了省带宽丢掉的东西，正好是机器嗓音的来源。

## 音域由载波决定

```range
{"range":"C1–C5","common":"C1–C5","caption":"声码器的「音域」（频谱移植效果器 · 载波音源决定输出音域）","caption_en":"Vocoder 「range」 (spectral-transplant effect · the carrier's span decides the output)","note":"声码器属电鸣系统的效果端（不独立发声——寄生在音源上）。原理：调制信号（人声）经多带滤波（8–20 频带）+ 包络跟随器 → 控制信号施加到载波（合成器波形/噪声）的对应滤波通道——输出音域等于载波音源的音域（典型 C1–C5）。声码器不修正音高——它丢弃调制信号的瞬时频率、只保留频谱形状。Voder（1939 世博）为手动版本；SIGSALY（1943）为战时加密版本；LPC-10（2.4kbps）为现代数字电话地基。"}
```

声码器本身没有音域。它输出什么高度，取决于载波给什么：载波是合成器，就跟着合成器的音区走，通常 C1 到 C5；载波是噪声，出来的就是没有音高的气声。

它也从不修正音高。跑调的人声经它处理，跑调的形状还在，只是换了一副嗓子的皮。这一点常被记错：九十年代流行歌里那种阶梯式的电音，多半是修音软件干的，不是它。

## 一台机器，两份职业

1939 年纽约世博会上，贝尔实验室把 Voder 摆出来给人看：一台机器，一个人用手按键、用踏板控音高，当场合成出听得懂的句子。那是人在演机器说话。

同一个电路的另一半去了别处。1943 年的 SIGSALY 用它给跨洋电话加密，战后演化成线性预测编码，一路语音只要 2.4 kbps，而当时的标准是 64 kbps。今天你打的每一通数字电话，都还在用它的思路：**只传参数，不传波形**。

## 机器唱歌的三条路

音乐这边慢了一步，走得更远。六十年代末 Moog 与 Carlos 把声码器接到模块合成器上，机器人嗓子从此进入流行乐，Carlos 用它处理《发条橙》里的贝多芬第九。1974 年 Kraftwerk 在《Autobahn》里用它；Daft Punk 后来把它变成整套形象，虽然他们常用的是 talkbox——一根管子把声音送进嘴里，靠嘴唇塑形。

```audiolab
{"type":"instrument","gm":"Voice Oohs","synth":"bowed","phrase":["C3","E3","G3","C4","E4","G4","C5"],"label":"声码器的机器歌喉：频谱移植的人声（借人声嘟近似）","label_en":"The vocoder's machine voice — a transplanted spectrum (voice oohs stand in)","hint":"声码器的本质是「把人声的频谱形状移植到合成器的音色上」——这条人声嘟采样取其「人声质感」。真实声码器的三样特征这里听不出来：一是双输入结构（人声调制+合成器载波）；二是「丢弃音高保住形状」的哲学（音乐效果正来自工程的丢弃）；三是它与 Auto-Tune/talkbox 的三分——三种「机器唱歌」原理完全不同。","hint_en":"The vocoder's essence is 「transplanting the voice's spectral shape onto a synth」 — this voice-oohs sample takes the vocal texture. Three things are absent: the dual-input structure（voice modulates, synth carries）, the philosophy of discarding pitch while keeping shape（the musical effect born of engineering's discard）, and the three-way split from Auto-Tune and talkbox — three ways a machine sings, on entirely different principles."}
```

三条路的分别很清楚。声码器搬的是频谱，两个输入造一个新声音；修音软件只做一件事，把跑调的音拽回最近的半音；talkbox 的滤波发生在演奏者口腔里，是身体在替电路干活。九十年代那种阶梯式电音被记在声码器账上，其实是第二种。

:::

::: en

The voice on the radio has breath in it, teeth in it, clean consonants — and a flat pitch, as if someone were singing from inside your throat. That is the vocoder's signature: your shape, someone else's pitch.

| Item | Content |
|---|---|
| HS class | Electrophone · effects unit, no sound of its own; multiband filtering, envelope followers |
| Origin | Homer Dudley of Bell Labs, patented 1938 |
| Bayin | not applicable — a Chinese system |

## Cutting speech into a spectrum

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
 <text x="342" y="240" font-size="9" fill="#97C459"> Talkbox 口腔滤波 —— 最「身体」的效果器</text>

 <text x="20" y="272" font-size="10.5" fill="#E8C547"> 「瞬时频率信息被丢弃」—— 音乐效果正来自工程的丢弃</text>
 <text x="20" y="292" font-size="10" fill="#A9A49B"> 「只传参数不传波形」= 数字音频的根本思想（对照 Prophet-5 patch memory）</text>

 <g font-family="system-ui,sans-serif" font-size="10.5" fill="#A9A49B">
 <text x="20" y="318" fill="#E8C547"> Cher《Believe》（1998）：Auto-Tune 过度修正成签名 —— 软件版「缺陷成签名」（303 花 7 年，Believe 花 1 年）</text>
 <text x="20" y="338" font-size="10" fill="#A9A49B"> Daft Punk 的「唱歌机器人」常用 talkbox 演的 —— 眼见耳听都未必为实</text>
 <text x="20" y="358" fill="#6E6A64">⚠️ 示意图：按文字描述绘制，非实物比例。</text>
 </g>
</svg>
```

Analyse a voice: slice it into a dozen bands, each watched by an envelope follower noting its energy now. In synthesis those readings open the matching filters on a second sound, the carrier.

The voice's instantaneous frequency is thrown away; what survives is a spectral outline changing over time. The carrier supplies pitch, the envelope shape, and the result has vowels and inflection without a note being sung.

For speech a loss; for music a resource: what engineering discarded to save bandwidth is where the machine voice comes from.

## The carrier decides the range

```range
{"range":"C1–C5","common":"C1–C5","caption":"声码器的「音域」（频谱移植效果器 · 载波音源决定输出音域）","caption_en":"Vocoder 「range」 (spectral-transplant effect · the carrier's span decides the output)","note":"声码器属电鸣系统的效果端（不独立发声——寄生在音源上）。原理：调制信号（人声）经多带滤波（8–20 频带）+ 包络跟随器 → 控制信号施加到载波（合成器波形/噪声）的对应滤波通道——输出音域等于载波音源的音域（典型 C1–C5）。声码器不修正音高——它丢弃调制信号的瞬时频率、只保留频谱形状。Voder（1939 世博）为手动版本；SIGSALY（1943）为战时加密版本；LPC-10（2.4kbps）为现代数字电话地基。"}
```

It has no range of its own. Whatever height it outputs is the carrier's: a synth follows its own register, typically C1 to C5; noise gives breath without pitch.

Nor does it correct anything: a singer who goes flat still goes flat, the shape stays, only the throat is swapped. The stepped sound of late-nineties pop is mostly pitch-correction software, not the vocoder.

## One circuit, two careers

At the 1939 World's Fair, Bell Labs showed the Voder: a machine operated by hand, keys for the filters, a pedal for pitch, producing intelligible sentences on the spot. A human performing machine speech.

The other half went elsewhere. SIGSALY used it in 1943 to encrypt transatlantic calls; after the war it grew into linear predictive coding — one channel at 2.4 kbps where the standard was 64. Every digital call you make still sends **parameters, not waveforms**.

## Three ways a machine sings

Music arrived later and went further. In the late sixties Moog and Carlos wired a vocoder to a modular synth; Carlos used it on the Beethoven of A Clockwork Orange, and the robot voice entered pop. Kraftwerk used it on Autobahn in 1974; Daft Punk built an image on it, though they often use the talkbox, a tube into the mouth.

```audiolab
{"type":"instrument","gm":"Voice Oohs","synth":"bowed","phrase":["C3","E3","G3","C4","E4","G4","C5"],"label":"声码器的机器歌喉：频谱移植的人声（借人声嘟近似）","label_en":"The vocoder's machine voice — a transplanted spectrum (voice oohs stand in)","hint":"声码器的本质是「把人声的频谱形状移植到合成器的音色上」——这条人声嘟采样取其「人声质感」。真实声码器的三样特征这里听不出来：一是双输入结构（人声调制+合成器载波）；二是「丢弃音高保住形状」的哲学（音乐效果正来自工程的丢弃）；三是它与 Auto-Tune/talkbox 的三分——三种「机器唱歌」原理完全不同。","hint_en":"The vocoder's essence is 「transplanting the voice's spectral shape onto a synth」 — this voice-oohs sample takes the vocal texture. Three things are absent: the dual-input structure（voice modulates, synth carries）, the philosophy of discarding pitch while keeping shape（the musical effect born of engineering's discard）, and the three-way split from Auto-Tune and talkbox — three ways a machine sings, on entirely different principles."}
```

The three are distinct. The vocoder moves a spectrum: two inputs, one new sound. Pitch correction drags a stray note to the nearest semitone. The talkbox filters inside the mouth, the body doing the circuit's work. The stepped sound of the nineties, usually credited to it, belongs to the second.
:::
