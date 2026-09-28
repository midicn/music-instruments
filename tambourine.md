---
id: tambourine
site: inst
cat: I4
title: 铃鼓
title_en: Tambourine
summary: 框架鼓加一圈小钹片 —— 一件乐器同时横跨膜鸣与体鸣
summary_en: A frame drum with a ring of jingles — one instrument straddling both percussion classes
level: standard
tags: [乐器, 打击, 西洋]
tags_en: [instrument, percussion, western]
alias: [铃鼓, tambourine, 手鼓（误称）, 摇鼓]
order: 59
links:
  - "[[concept:interval]]"
  - "[[concept:register]]"
  - "[[concept:timbre]]"
  - "[[concept:articulation]]"
  - "[[instrument:cymbals]]"
  - "[[instrument:triangle]]"
  - "[[instrument:snare-drum]]"
  - "[[instrument:latin-percussion]]"
instances:
  - pdmx-002528 | 霍尔斯特《第二军乐组曲》Op.28 No.2 —— 管乐团编制里铃鼓的实际用法
  - pdmx-000510 | Drake's Drum —— 标题指向打击乐的曲目，可作时代语汇的参照
  - norbeck-001125 | Yakety Sax —— 流行音乐里打击乐与节奏组的配合，可作场景对照
sources:
  - 结构依通行制琴资料：木质或塑料**圆形框架**，一面蒙皮（单面框鼓）；框架侧壁开槽，嵌**一圈小金属钹片（jingles）**
  - 「铃鼓主体属**膜鸣**（框架鼓），同时其钹片属**体鸣** —— 一件乐器同时包含两类振动体」依 Hornbostel–Sachs 分类与乐器声学
  - 「无固定音高」依分类
  - 「两种基本用法：摇动（钹片发声）与击打鼓面（膜发声）」依通行打击乐惯例
updated: 2026-09-26
---

::: zh
铃鼓是打击乐里唯一一件**同时横跨两大类**的乐器：
它的**框架鼓**是**膜鸣**（鼓皮是振源），
装在框架侧壁的那**一圈小钹片**是**体鸣**（金属片自身振动）。

所以它有两种完全不同的声音来源 —— 而这两种声音在音乐里各有用处。

| 分类 | 归属 |
|---|---|
| **HS 分类** | **膜鸣**（框架鼓为主体）· **同时含体鸣组件**（钹片）· **无固定音高** |
| **次级类型** | 单面框鼓 · 框架侧壁嵌一圈钹片 · 摇奏或击奏 |
| **所属族** | 西洋 · 打击（**横跨膜鸣与体鸣**） |
| **八音** | 不适用 —— 周代八音是中国乐器的体系，铃鼓不在其中 |

> ⚠️ **一个概念上的要点**：**分类是按"主要振源"定的，但乐器可以同时具备多种振源。**
> 铃鼓在 HS 分类里归**膜鸣**（主体是框架鼓），但它身上**确实装着一套体鸣的钹片**。
> 这与[[instrument:timpani|定音鼓]]那页画的两大类图并不矛盾 ——
> 恰恰说明**分类是给乐器的主属性贴标签，而不是否认它的其他属性**。
> 演奏时，你可以选择"只让钹片响"（摇）或"让鼓面响"（击），
> **这等于在两类之间自由切换。**

## 结构：框架 + 鼓皮 + 一圈钹片

```svg
<svg viewBox="0 0 640 300" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="铃鼓的结构：圆形木质框架、单面鼓皮，框架侧壁嵌着一圈小金属钹片">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">铃鼓 · 结构（一层鼓皮 + 一圈钹片）</text>
  </g>
  <circle cx="300" cy="158" r="108" fill="#17171A" stroke="#9C7A3C" stroke-width="1.8"/>
  <circle cx="300" cy="158" r="88" fill="#0E0E10" stroke="#9C7A3C" stroke-width="3.4"/>
  <circle cx="300" cy="158" r="60" fill="none" stroke="#343439" stroke-width="1.1"/>
  <g fill="#E07A3F" stroke="#E07A3F" stroke-width="1">
    <circle cx="300" cy="50" r="6"/><circle cx="368" cy="70" r="6"/>
    <circle cx="408" cy="128" r="6"/><circle cx="408" cy="188" r="6"/>
    <circle cx="368" cy="246" r="6"/><circle cx="300" cy="266" r="6"/>
    <circle cx="232" cy="246" r="6"/><circle cx="192" cy="188" r="6"/>
    <circle cx="192" cy="128" r="6"/><circle cx="232" cy="70" r="6"/>
  </g>
  <g class="lead" stroke="#6E6A64" stroke-width=".9">
    <path d="M186,78 L262,86"/><path d="M186,158 L252,158"/>
    <path d="M186,262 L252,250"/><path d="M486,120 L390,138"/>
  </g>
  <g font-family="system-ui,sans-serif" font-size="11" fill="#A9A49B">
    <text x="180" y="75" text-anchor="end">木质或塑料框架</text>
    <text x="180" y="161" text-anchor="end">单面鼓皮（膜鸣）</text>
    <text x="180" y="265" text-anchor="end" fill="#E07A3F">框架侧壁嵌的小钹片</text>
    <text x="492" y="117" fill="#E07A3F">钹片 = 体鸣振源</text>
  </g>
  <text x="20" y="292" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">摇动时鼓皮几乎不响，钹片"沙沙"；击鼓面时鼓皮"嗒"一声 —— 两种声音来源各管一半。</text>
</svg>
```

三处要点：

1. **一层鼓皮 + 一圈钹片**。这就是它的全部构造，也是它横跨两类的物理原因。
2. **摇与击是两种用法**。摇动让钹片响（体鸣），击鼓面让膜响（膜鸣）——
   演奏者可以只用一种，也可以叠在一起。
3. **框架的材质与制作影响很大**。木框与塑料框音色不同，钹片的数量与厚度也各厂不同。

## 两个声音来源

```svg
<svg viewBox="0 0 640 280" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="铃鼓的两个振源对比：钹片的体鸣产生沙沙声，鼓面的膜鸣产生嗒声">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">一件乐器，两个振源</text>
  </g>
  <text x="160" y="62" text-anchor="middle" font-size="11" fill="#E07A3F">钹片 · 体鸣</text>
  <ellipse cx="160" cy="132" rx="70" ry="30" fill="#17171A" stroke="#E07A3F" stroke-width="1.7"/>
  <g stroke="#E07A3F" stroke-width="3" stroke-linecap="round">
    <path d="M120,132 L120,104"/><path d="M150,132 L150,96"/>
    <path d="M180,132 L180,104"/><path d="M210,132 L210,112"/>
  </g>
  <text x="160" y="192" text-anchor="middle" font-size="10.5" fill="#A9A49B">摇动时金属片互撞</text>
  <text x="160" y="214" text-anchor="middle" font-size="10.5" fill="#E07A3F">沙沙（高频、颗粒密）</text>
  <text x="160" y="236" text-anchor="middle" font-size="10.5" fill="#6E6A64">用于：持续节奏、气氛</text>
  <text x="480" y="62" text-anchor="middle" font-size="11" fill="#5B7FA8">鼓面 · 膜鸣</text>
  <ellipse cx="480" cy="132" rx="70" ry="30" fill="#17171A" stroke="#5B7FA8" stroke-width="1.7"/>
  <path d="M410,132 C440,116 520,116 550,132" fill="none" stroke="#5B7FA8" stroke-width="2.4"/>
  <circle cx="480" cy="96" r="6" fill="#5B7FA8"/>
  <text x="480" y="192" text-anchor="middle" font-size="10.5" fill="#A9A49B">敲击时鼓皮振动</text>
  <text x="480" y="214" text-anchor="middle" font-size="10.5" fill="#5B7FA8">嗒（短、有音头）</text>
  <text x="480" y="236" text-anchor="middle" font-size="10.5" fill="#6E6A64">用于：重音、切分</text>
  <text x="20" y="264" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">两个振源可以在一次动作里同时激发 —— 那是铃鼓最有代表性的声音（"沙"里带"嗒"）。</text>
</svg>
```

**这就是铃鼓的全部技巧基础**：

| 动作 | 振源 | 声音 |
|---|---|---|
| **摇动** | 钹片（体鸣） | 沙沙，持续 |
| **击鼓面** | 鼓皮（膜鸣） | 嗒，一次 |
| **击框架** | 钹片 + 木框 | 短促、干脆 |
| **摇 + 击** | 两者同时 | 沙里带嗒 |

## 音域

铃鼓属于**无固定音高**乐器，本站不为其生成音域图。它的表现手段在**动作类型与力度**：

| 动作 | 用途 |
|---|---|
| **轻摇** | 背景的持续节奏 |
| **重摇** | 高潮气氛的推进 |
| **击鼓面** | 切分重音 |
| **拇指滚（thumb roll）** | 一串连续的"沙" —— 铃鼓最标志性的技法 |
| **框架击** | 干脆的短点 |

**拇指滚是它的招牌**：用拇指在鼓面上快速摩擦，让钹片连续不断地响 ——
听起来像持续的沙沙声，实际上没有一次是"打"出来的。

## 音色与听辨

四条线索：

1. **高频为主，颗粒细密**。钹片的声音比[[instrument:cymbals|吊镲]]更小更密 ——
   像是很多极小的镲一起响。
2. **"沙"与"嗒"可以叠加**。这是它区别于其他打击乐的地方：
   两种完全不同性质的音可以在一个动作里同时出现。
3. **控制难度在于"稳"**。持续摇动要保持均匀，否则节奏会抖。
4. **力度层次宽**。从背景的轻沙到能穿透乐队的高潮推进。

```audiolab
{"type":"instrument","drum":54,"synth":"perc","phrase":[54,54,54,54,54,54],"label":"铃鼓的摇奏与击奏","label_en":"Tambourine — shaken and struck","hint":"注意两种声音：钹片的持续「沙」与鼓面的「嗒」","hint_en":"Two sounds to hear: the continuous shiver of the jingles and the tap of the head."}
```

## 演奏技法

- **摇（shake）**：手腕或手臂转动，让钹片连续碰撞 —— 基础功，要求均匀。
- **拇指滚（thumb roll）**：拇指在鼓面上摩擦带动钹片 —— 得到连续的"沙"。
- **击（strike）**：用另一只手的指节或膝盖击鼓面 —— 重音与切分。
- **框架击**：直接击木框，得到更干脆、更"木"的音。
- **膝上/手上**：铃鼓可以拿在手里或架在支架上，两种方式技法不同。

## 家族与近亲

| 乐器 | 膜鸣 / 体鸣 | 特征 | 用途 |
|---|---|---|---|
| **铃鼓** | **两者都有** | 框鼓 + 一圈钹片 | 节奏与气氛 |
| [[instrument:cymbals\|铙钹]] | 体鸣 | 大片金属 | 强调、高潮 |
| [[instrument:triangle\|三角铁]] | 体鸣 | 钢棒 | 穿透性重点 |
| [[instrument:snare-drum\|小鼓]] | 膜鸣 | 响弦 | 节奏骨架 |
| [[instrument:latin-percussion\|拉丁打击组]] | 膜鸣为主 | 康加、邦戈等 | 拉丁节奏层 |

**铃鼓是这份表里唯一"两类都有"的一件** —— 这也让它在配器上特别灵活：
需要"沙"就用摇，需要"点"就用击。

## 历史演变

| 时期 | 状态 |
|---|---|
| 古代 | 框鼓在世界多地出现（中东、地中海、印度）；带钹片的形制在中东与欧洲逐步成型 |
| 中世纪—文艺复兴 | 在欧洲民间舞蹈与宗教场景使用 |
| 18—19 世纪 | 随土耳其军乐进入管弦乐；成为管弦乐与管乐团的标准打击乐器 |
| 20 世纪 | 在爵士、拉丁、摇滚与流行里广泛使用；成为歌曲伴奏的常备乐器 |
| 20 世纪后期至今 | 与[[instrument:latin-percussion|拉丁打击组]]一起构成流行音乐的节奏层 |

## 常见误解

- **"铃鼓是小孩子玩的。"** 它是管弦乐、管乐团与流行音乐的标准打击乐器，
  拇指滚与均匀摇奏都是需要长期练习的技术。
- **"它属于体鸣。"** HS 分类里它归**膜鸣**（主体是框架鼓），
  但它**同时带有一套体鸣的钹片** —— 这才是它最特别的地方。
- **"它只能摇。"** 击鼓面、击框架、拇指滚都是独立的技术，各得到不同的音色。
- **"它和中国的鼓一样。"** 中国的**手鼓**（如维吾尔手鼓）与铃鼓在形制上有相近之处，
  但各自有独立的传统与技法 —— **相似不等于同源**。
- **"铃鼓有音高。"** 无固定音高。

## 下一步

体鸣里还有一件与它、与[[instrument:triangle|三角铁]]都不同的乐器：
[[instrument:gong|锣]] —— 同样是金属整体振动，但能量更低、余音更长。

再往后就进入"有音高的体鸣"一族：从 [[instrument:xylophone|木琴]] 开始的木质琴条，
到 [[instrument:glockenspiel|钟琴]] 一类的金属琴条。
:::

::: en
The tambourine is the one percussion instrument that **straddles both great classes**: its **frame drum** is
a **membranophone** (the head is the source), while the **ring of small jingles** set into the frame is an
**idiophone** (the metal plates vibrate themselves).

So it has two entirely different sound sources — and each does its own work in music.

| Classification | Value |
|---|---|
| **HS class** | **Membranophone** (the frame drum is the main body) · **with idiophone components** (jingles) · **unpitched** |
| **Sub-type** | Single-headed frame drum · a ring of jingles in the rim · shaken or struck |
| **Family** | Western · Percussion (**straddling membrane and idiophone**) |
| **Bayin** | Not applicable — a Chinese system; the tambourine is outside it |

> ⚠️ **One conceptual point**: **classification labels an instrument by its *primary* source — but an
> instrument can have more than one.** The tambourine is classified as a **membranophone** (the frame drum is
> the body), yet it **really does carry a set of idiophone jingles**.
> This does not contradict the two-class diagram on the [[instrument:timpani|timpani]] page — it shows that
> **classification tags a main property without denying the others.**
> In playing you may choose to sound **only the jingles** (shake) or **only the head** (strike) —
> effectively switching between the two classes.

## Structure: a frame, a head and a ring of jingles

```svg
<svg viewBox="0 0 640 300" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Tambourine structure: a round wooden frame with a single head and a ring of small jingles set into the rim">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">Tambourine — structure (one head plus a ring of jingles)</text>
  </g>
  <circle cx="300" cy="158" r="108" fill="#17171A" stroke="#9C7A3C" stroke-width="1.8"/>
  <circle cx="300" cy="158" r="88" fill="#0E0E10" stroke="#9C7A3C" stroke-width="3.4"/>
  <circle cx="300" cy="158" r="60" fill="none" stroke="#343439" stroke-width="1.1"/>
  <g fill="#E07A3F" stroke="#E07A3F" stroke-width="1">
    <circle cx="300" cy="50" r="6"/><circle cx="368" cy="70" r="6"/>
    <circle cx="408" cy="128" r="6"/><circle cx="408" cy="188" r="6"/>
    <circle cx="368" cy="246" r="6"/><circle cx="300" cy="266" r="6"/>
    <circle cx="232" cy="246" r="6"/><circle cx="192" cy="188" r="6"/>
    <circle cx="192" cy="128" r="6"/><circle cx="232" cy="70" r="6"/>
  </g>
  <g class="lead" stroke="#6E6A64" stroke-width=".9">
    <path d="M186,78 L262,86"/><path d="M186,158 L252,158"/>
    <path d="M186,262 L252,250"/><path d="M486,120 L390,138"/>
  </g>
  <g font-family="system-ui,sans-serif" font-size="11" fill="#A9A49B">
    <text x="180" y="75" text-anchor="end">Wooden or plastic frame</text>
    <text x="180" y="161" text-anchor="end">Single head (membrane source)</text>
    <text x="180" y="265" text-anchor="end" fill="#E07A3F">Jingles set into the rim</text>
    <text x="492" y="117" fill="#E07A3F">Jingles = idiophone source</text>
  </g>
  <text x="20" y="292" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">Shaken, the head barely sounds and the jingles shiver; struck, the head taps. Two sources, half each.</text>
</svg>
```

Three points:

1. **One head plus a ring of jingles** — the whole construction, and the physical reason it straddles two
   classes.
2. **Shake and strike are two techniques**: shaking sounds the jingles (idiophone), striking sounds the head
   (membranophone), and both can be combined.
3. **Frame material and workmanship matter a lot**: wood and plastic differ, and jingle count and weight vary
   between makers.

## Two sound sources

```svg
<svg viewBox="0 0 640 280" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="The tambourine's two sources compared: jingles (idiophone) shiver, the head (membranophone) taps">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">One instrument, two sources</text>
  </g>
  <text x="160" y="62" text-anchor="middle" font-size="11" fill="#E07A3F">Jingles · idiophone</text>
  <ellipse cx="160" cy="132" rx="70" ry="30" fill="#17171A" stroke="#E07A3F" stroke-width="1.7"/>
  <g stroke="#E07A3F" stroke-width="3" stroke-linecap="round">
    <path d="M120,132 L120,104"/><path d="M150,132 L150,96"/>
    <path d="M180,132 L180,104"/><path d="M210,132 L210,112"/>
  </g>
  <text x="160" y="192" text-anchor="middle" font-size="10.5" fill="#A9A49B">metal plates collide when shaken</text>
  <text x="160" y="214" text-anchor="middle" font-size="10.5" fill="#E07A3F">a shiver (high, dense grains)</text>
  <text x="160" y="236" text-anchor="middle" font-size="10.5" fill="#6E6A64">used for: sustain, atmosphere</text>
  <text x="480" y="62" text-anchor="middle" font-size="11" fill="#5B7FA8">Head · membranophone</text>
  <ellipse cx="480" cy="132" rx="70" ry="30" fill="#17171A" stroke="#5B7FA8" stroke-width="1.7"/>
  <path d="M410,132 C440,116 520,116 550,132" fill="none" stroke="#5B7FA8" stroke-width="2.4"/>
  <circle cx="480" cy="96" r="6" fill="#5B7FA8"/>
  <text x="480" y="192" text-anchor="middle" font-size="10.5" fill="#A9A49B">the head vibrates when struck</text>
  <text x="480" y="214" text-anchor="middle" font-size="10.5" fill="#5B7FA8">a tap (short, with an attack)</text>
  <text x="480" y="236" text-anchor="middle" font-size="10.5" fill="#6E6A64">used for: accents, syncopation</text>
  <text x="20" y="264" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">Both can fire in one motion — the tambourine's signature sound: a tap inside a shiver.</text>
</svg>
```

**This is the basis of every tambourine technique**:

| Motion | Source | Sound |
|---|---|---|
| **Shake** | jingles (idiophone) | a sustained shiver |
| **Strike the head** | head (membranophone) | a single tap |
| **Strike the frame** | jingles + wood | short and crisp |
| **Shake + strike** | both | a tap inside a shiver |

## Range

The tambourine is **unpitched**, so no range chart is generated. Its means are **motion type and dynamics**:

| Motion | Use |
|---|---|
| **Light shake** | a sustained background rhythm |
| **Heavy shake** | driving a climax |
| **Strike the head** | syncopated accents |
| **Thumb roll** | a continuous shiver — its most identifiable technique |
| **Frame strike** | a crisp short point |

**The thumb roll is its signature**: rubbing the thumb across the head sets the jingles going continuously —
it sounds like an unbroken shiver, and not one stroke is actually "hit".

## Timbre, and how to hear it

Four cues:

1. **High and finely grained.** Smaller and denser than a [[instrument:cymbals|suspended cymbal]] — like many
   tiny cymbals at once.
2. **"Shiver" and "tap" can overlap**, which sets it apart from other percussion: two entirely different
   sound types in a single motion.
3. **The difficulty is steadiness** — a continuous shake must not wobble.
4. **A wide dynamic range**, from a light background shiver to a climax that cuts through a band.

```audiolab
{"type":"instrument","drum":54,"synth":"perc","phrase":[54,54,54,54,54,54],"label":"铃鼓的摇奏与击奏","label_en":"Tambourine — shaken and struck","hint":"注意两种声音：钹片的持续「沙」与鼓面的「嗒」","hint_en":"Two sounds to hear: the continuous shiver of the jingles and the tap of the head."}
```

## Playing techniques

- **Shake**: rotating the wrist or arm sets the jingles colliding continuously — the foundation, and it must
  be even.
- **Thumb roll**: rubbing the thumb on the head drives the jingles for a continuous shiver.
- **Strike**: knuckles or knee on the head for accents and syncopation.
- **Frame strike**: hitting the wooden rim directly for a drier, woodier sound.
- **Held or mounted**: hand-held and stand-mounted techniques differ.

## The family

| Instrument | Class | Feature | Use |
|---|---|---|---|
| **Tambourine** | **both** | frame drum + jingles | rhythm and atmosphere |
| [[instrument:cymbals\|Cymbals]] | idiophone | large metal sheets | accents, climaxes |
| [[instrument:triangle\|Triangle]] | idiophone | steel rod | penetrating emphasis |
| [[instrument:snare-drum\|Snare drum]] | membranophone | snares | rhythmic skeleton |
| [[instrument:latin-percussion\|Latin percussion]] | mostly membranophone | congas, bongos… | Latin rhythm layers |

**The tambourine is the only one in this table with both classes** — which is exactly what makes it so
flexible in a score: shake for a shiver, strike for a point.

## History

| Period | State |
|---|---|
| Antiquity | frame drums appear across the Middle East, the Mediterranean and India; the jingled form develops in the Middle East and Europe |
| Medieval–Renaissance | used in European folk dance and religious settings |
| 18th–19th c. | enters the orchestra with Turkish military music and becomes standard percussion |
| 20th c. | widely used in jazz, Latin, rock and pop; a regular in song accompaniment |
| Late 20th c. onward | with [[instrument:latin-percussion|Latin percussion]] it forms the rhythm layer of popular music |

## Common misconceptions

- **"A tambourine is a child's toy."** It is standard percussion in orchestra, band and pop, and both the
  thumb roll and an even shake take years to master.
- **"It is an idiophone."** In Hornbostel–Sachs it is a **membranophone** (the frame drum is the body), but it
  **also carries idiophone jingles** — its most particular feature.
- **"You can only shake it."** Striking the head, striking the frame and the thumb roll are separate
  techniques with separate sounds.
- **"It is the same as a Chinese hand drum."** Uyghur and other Chinese hand drums are similar in form but
  have their own traditions and techniques — **resemblance is not common origin**.
- **"It has pitch."** Unpitched.

## Next

Among the idiophones one more differs from both the tambourine and the [[instrument:triangle|triangle]]: the
[[instrument:gong|gong]] — also a metal body vibrating as a whole, but with lower energy and a longer tail.

After that come the **pitched** idiophones, from the wooden bars of the [[instrument:xylophone|xylophone]] to
the metal bars of the [[instrument:glockenspiel|glockenspiel]] family.
:::
