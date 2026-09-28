---
id: timpani
site: inst
cat: I4
title: 定音鼓
title_en: Timpani
summary: 可调音高的膜鸣鼓，管弦乐打击乐的核心
summary_en: The tunable membranophone drum — the core of orchestral percussion
level: standard
tags: [乐器, 打击, 西洋]
tags_en: [instrument, percussion, western]
alias: [定音鼓, timpani, 罐鼓, 铜鼓（误称）, kettledrum]
order: 55
links:
  - "[[concept:interval]]"
  - "[[concept:register]]"
  - "[[concept:timbre]]"
  - "[[concept:articulation]]"
  - "[[instrument:snare-drum]]"
  - "[[instrument:bass-drum]]"
  - "[[instrument:tuba]]"
  - "[[instrument:trumpet]]"
instances:
  - pdmx-002820 | 为三支小号与定音鼓而作的协奏曲 TWV 54:D4 —— 巴洛克时期定音鼓与小号的标准配对
  - pdmx-000062 | 管乐五重奏（长笛 · 双簧管 · 单簧管 · 圆号 · 巴松）—— 无打击乐的编制，可作对照
  - pdmx-002528 | 霍尔斯特《第二军乐组曲》Op.28 No.2 —— 管乐团编制里定音鼓的实际用法
sources:
  - 结构依通行制琴资料：铜制半球形鼓身，鼓皮蒙在顶端，靠**踏板**（或手柄、螺杆）改变鼓皮张力以调音；配软头定音鼓槌
  - 「定音鼓属**膜鸣**乐器 —— 鼓皮本身是振源，鼓身起共鸣作用」依 Hornbostel–Sachs 分类
  - 「单支定音鼓音域约一个六度；常见一套四支合起来约 D2–A3」依通行配器资料
  - 「管弦乐里通常配二至四支，现代作品可更多」依通行配器惯例
updated: 2026-09-26
---

::: zh
定音鼓是打击乐组的核心，因为它解决了打击乐最大的一个难题：**音高**。
它是**可调音高**的鼓 —— 靠踏板改变鼓皮的张力，从而改变音高。

它也是理解打击乐分类最好的起点。打击乐分两大类，而这条界线与木管、铜管的分法**完全不同**。

| 分类 | 归属 |
|---|---|
| **HS 分类** | **膜鸣**（Membranophone）—— **鼓皮本身是振源**，鼓身只是共鸣体 |
| **次级类型** | 单面蒙皮 · **可调音高**（踏板改变张力） · 用槌击奏 |
| **所属族** | 西洋 · 打击（膜鸣支系 · 有音高） |
| **八音** | 不适用 —— 周代八音是中国乐器的体系，定音鼓不在其中 |

> ⚠️ **一个概念上的要点**：**打击乐的两大类不是按材料分的，而是按"什么在振动"分的。**
> - **膜鸣**（Membranophone）：**一张膜**是振源 → 所有鼓类（定音鼓、小鼓、大鼓、铃鼓…）
> - **体鸣**（Idiophone）：**材料本身**振动 → 锣、钹、三角铁、木琴、钟琴…
>
> 这与[[instrument:flute|木管]]（气柱振动）和[[instrument:trumpet|铜管]]（嘴唇振动）
> 构成 HS 五分法里的三条不同判据。**"打击"是演奏方式，"膜鸣/体鸣"才是分类。**

## 打击乐怎么分：先看什么在振动

```svg
<svg viewBox="0 0 640 340" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="打击乐的两大类：膜鸣乐器以鼓皮为振源，体鸣乐器以材料本身为振源">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">打击乐的两大类：膜鸣与体鸣</text>
  </g>
  <text x="160" y="62" text-anchor="middle" font-size="11" fill="#E07A3F">膜鸣 · 一张膜在振动</text>
  <ellipse cx="160" cy="132" rx="80" ry="30" fill="#17171A" stroke="#E07A3F" stroke-width="1.7"/>
  <path d="M80,132 C104,116 216,116 240,132" fill="none" stroke="#E07A3F" stroke-width="2.4"/>
  <path d="M80,132 L80,196 C80,214 240,214 240,196 L240,132" fill="none" stroke="#343439" stroke-width="1.6"/>
  <circle cx="160" cy="96" r="5" fill="#E07A3F"/>
  <path d="M160,104 L160,118" stroke="#E07A3F" stroke-width="2" stroke-dasharray="3 2"/>
  <text x="160" y="238" text-anchor="middle" font-size="10.5" fill="#A9A49B">鼓皮 = 振源，鼓身 = 共鸣体</text>
  <text x="160" y="260" text-anchor="middle" font-size="10.5" fill="#E07A3F">定音鼓 · 小鼓 · 大鼓 · 铃鼓</text>
  <text x="480" y="62" text-anchor="middle" font-size="11" fill="#5B7FA8">体鸣 · 材料本身在振动</text>
  <rect x="404" y="118" width="150" height="28" rx="14" fill="#17171A" stroke="#5B7FA8" stroke-width="1.7"/>
  <path d="M404,132 C440,120 518,120 554,132" fill="none" stroke="#5B7FA8" stroke-width="2.4"/>
  <circle cx="479" cy="92" r="5" fill="#5B7FA8"/>
  <path d="M479,100 L479,116" stroke="#5B7FA8" stroke-width="2" stroke-dasharray="3 2"/>
  <text x="480" y="238" text-anchor="middle" font-size="10.5" fill="#A9A49B">整块材料在工作，没有膜</text>
  <text x="480" y="260" text-anchor="middle" font-size="10.5" fill="#5B7FA8">三角铁 · 铙钹 · 锣 · 木琴 · 钟琴</text>
  <text x="20" y="296" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">"打击"说的是「怎么演奏」（敲、摇、擦），"膜鸣/体鸣"说的是「什么在振动」 —— 后者才是分类。</text>
  <text x="20" y="318" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">所以铃鼓同时是膜鸣（鼓皮）与体鸣（框架上的一圈小钹片）—— 一件乐器可以横跨两类。</text>
</svg>
```

**这张图是打击乐全批的骨架**。下面 23 条都会落在两栏之一：

| | 膜鸣（膜是振源） | 体鸣（材料是振源） |
|---|---|---|
| **有音高** | **定音鼓** | 木琴 · 马林巴 · 颤音琴 · 钟琴 · 管钟 · 钢片琴 · 手碟 |
| **无固定音高** | 小鼓 · 大鼓 · 铃鼓 · 爵士鼓组 · 拉丁打击组 | 三角铁 · 铙钹 · 锣 · 响板 · 敲击棒 · 鞭响器 · 乐砧 · 风铃 · 砂槌 · 雨棍 · 木鱼 |

**四个格子** —— 上排 8 件有明确音高（能画音域图），下排 16 件没有。

## 结构：半球鼓身 + 踏板调音

```svg
<svg viewBox="0 0 640 340" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="定音鼓的结构：铜制半球形鼓身、顶端鼓皮、调音螺杆与踏板以及定音鼓槌">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">定音鼓 · 结构（踏板改变鼓皮张力即改变音高）</text>
  </g>
  <path d="M170,140 C170,232 240,268 300,268 C360,268 430,232 430,140 Z" fill="#17171A" stroke="#343439" stroke-width="1.6"/>
  <ellipse cx="300" cy="140" rx="130" ry="34" fill="#0E0E10" stroke="#9C7A3C" stroke-width="2.2"/>
  <ellipse cx="300" cy="140" rx="112" ry="26" fill="#17171A" stroke="#343439" stroke-width="1.2"/>
  <g stroke="#6E6A64" stroke-width="2.6" stroke-linecap="round">
    <path d="M178,148 L172,172"/><path d="M212,164 L204,188"/>
    <path d="M250,176 L244,200"/><path d="M300,180 L300,204"/>
    <path d="M350,176 L356,200"/><path d="M388,164 L396,188"/>
    <path d="M422,148 L428,172"/>
  </g>
  <path d="M300,268 L300,300 L360,306" fill="none" stroke="#5B7FA8" stroke-width="7" stroke-linecap="round"/>
  <rect x="352" y="296" width="46" height="12" rx="4" fill="#5B7FA8"/>
  <path d="M420,120 L462,96" stroke="#9C7A3C" stroke-width="5" stroke-linecap="round"/>
  <ellipse cx="468" cy="92" rx="12" ry="9" fill="#9C7A3C"/>
  <g class="lead" stroke="#6E6A64" stroke-width=".9">
    <path d="M186,190 L230,168"/><path d="M186,262 L244,262"/>
    <path d="M186,318 L292,306"/><path d="M186,116 L240,124"/>
    <path d="M486,86 L482,90"/>
  </g>
  <g font-family="system-ui,sans-serif" font-size="11" fill="#A9A49B">
    <text x="180" y="193" text-anchor="end" fill="#9C7A3C">鼓皮（振源）</text>
    <text x="180" y="265" text-anchor="end">铜制半球形鼓身（共鸣体）</text>
    <text x="180" y="321" text-anchor="end" fill="#5B7FA8">踏板（改变张力 → 改变音高）</text>
    <text x="180" y="113" text-anchor="end">调音螺杆（张紧鼓皮）</text>
    <text x="492" y="83">软头鼓槌</text>
  </g>
  <text x="20" y="336" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">鼓身呈半球形并封闭 —— 这样低频不会被"漏掉"，所以定音鼓能发出有明确音高的低沉音。</text>
</svg>
```

三处要点：

1. **鼓身是封闭的半球**。这是它能有明确音高的关键 —— 封闭腔体让基频突出，
   而开口的鼓（如小鼓）低频发散、音高不明确。
2. **踏板是调音装置**。踩下踏板改变鼓皮的张力 → 改变音高。
   一套鼓在乐曲进行中可以**实时换音**，这是它在管弦乐里不可替代的原因。
3. **用软头鼓槌**。槌头的软硬直接决定音色（软 → 圆厚，硬 → 清晰），
   所以定音鼓手会根据乐句**换槌**，这是它的重要表现手段。

## 音域

```range
{"range":"D2–A3","common":"D2–F3","caption":"定音鼓（一套）的总音域","caption_en":"Timpani (a set) — combined range","note":"定音鼓是「可调音高」的膜鸣乐器：靠踏板改变鼓皮张力。单支鼓约一个六度；常见的一套四支合起来约 D2–A3。记谱即实音。"}
```

- **一套四支合起来约 D2–A3**，但**单支鼓只有约一个六度的调节范围** ——
  所以它的音高能力是"多支鼓各覆盖一段"。
- **常用区 D2–F3**：管弦乐里绝大多数定音鼓声部都在这里。
- **它只负责低音**。定音鼓从来不是旋律乐器，但它**决定了低频的节奏感**。

## 音色与听辨

四条线索：

1. **有明确音高，但音高不是它最突出的特征**。听感上"轰鸣的雷声"往往先于"具体的音"。
2. **余音长**。敲一下会响一段时间，所以快速连击时声音会叠起来 ——
   需要鼓手用**止音**（手按鼓皮）控制。
3. **槌头决定音色**。同一支鼓换槌就像换了半件乐器，这是它表现力最大的来源。
4. **力度范围极宽**。从极弱的"远处雷声"到能压过整个乐队的强击。

```audiolab
{"type":"instrument","gm":"Timpani","synth":"perc","phrase":["D2","A2","D3","A3","D2"],"label":"定音鼓的常用音区：D2 到 A3","label_en":"The timpani's working range — D2 up to A3","hint":"注意有音高但更像「轰鸣」—— 以及余音如何叠在一起","hint_en":"Hear a definite pitch that still reads as thunder — and how the notes ring into each other."}
```

## 演奏技法

- **双手各持一槌**，所以它能**同时敲两个音**（甚至三、四个，视鼓数）。
- **止音（damping）**：用手按住鼓皮停止余音 —— 干净的收尾靠它。
- **换槌**：软、中、硬三种以上，按乐句需要即时更换。
- **滚奏（roll）**：双槌快速交替，得到持续的轰鸣 ——
  定音鼓的滚奏是管弦乐里最有效的"张力"手段之一。
- **踏板滑音**：踩踏板在敲击后改变音高，得到滑音效果 —— 现代作品常用。

## 家族与近亲

| 乐器 | 膜鸣 / 体鸣 | 有音高？ | 在乐队里的角色 |
|---|---|---|---|
| **定音鼓** | 膜鸣 | **有（可调）** | 低频节奏与张力 |
| [[instrument:snare-drum\|小鼓]] | 膜鸣 | 无 | 节奏骨架、军乐核心 |
| [[instrument:bass-drum\|大鼓]] | 膜鸣 | 无 | 强拍与低频厚度 |
| [[instrument:marimba\|马林巴]] | 体鸣 | **有** | 旋律与和声 |
| [[instrument:glockenspiel\|钟琴]] | 体鸣 | **有** | 高音加亮 |

**定音鼓与马林巴是"有音高打击乐"的两端**：
一个在最低（膜鸣），一个在中高（体鸣的木质琴条）。

## 历史演变

| 时期 | 状态 |
|---|---|
| 古代—中世纪 | 各地有蒙皮鼓；中东与欧洲的**罐鼓**是定音鼓的直接前身 |
| 15—16 世纪 | 随军乐队进入欧洲；此时靠螺杆调音，换音很慢 |
| 17 世纪 | 进入管弦乐；常与小号配对（两者都只有少数几个音可用） |
| 18—19 世纪 | 调音机构逐步改良；贝多芬等把定音鼓从"节奏"提升到"表现手段" |
| 19 世纪末—20 世纪 | **踏板调音**普及 → 可在乐曲中实时换音；定音鼓的写法大幅解放 |
| 20 世纪至今 | 成为管弦乐与管乐团的标准配置；现代作品要求更复杂的换音与音色变化 |

**一个常被引用的例子**：贝多芬《第九交响曲》的谐谑曲里，
定音鼓有一段独奏式的写法（定音鼓奏出主题的节奏）—— 在 1824 年这是很不寻常的做法。

## 常见误解

- **"定音鼓是体鸣乐器。"** 它是**膜鸣** —— 鼓皮是振源，鼓身只是共鸣体。
- **"它没有音高。"** 它**有明确音高**，而且可以靠踏板调节，是管弦乐里少数有音高的打击乐器。
- **"它是铜做的所以像铜管。"** 材料不判类。它属**打击 · 膜鸣**，
  与靠嘴唇振动的铜管毫无关系。
- **"一套定音鼓音域很宽。"** **单支**鼓只有约一个六度；总音域靠**多支鼓各覆盖一段**拼出来。
- **"打鼓不需要技巧。"** 定音鼓的止音、换槌、滚奏与踏板控制都是专门技术，
  音准（踏板定位）也要求听辨能力。

## 下一步

打击乐这条线从"膜鸣"出发，接下来会分两条走：
**鼓类**（[[instrument:snare-drum|小鼓]] · [[instrument:bass-drum|大鼓]]）
与**体鸣**（木琴一族 · 金属一族）。

先看**小鼓** —— 它是军乐与爵士鼓组的心脏，也是"膜鸣如何变得没有音高"的最好例子。
:::

::: en
The timpani are the core of the percussion group because they solve percussion's hardest problem: **pitch**.
They are **tunable** — a pedal changes the tension of the head, and the tension changes the pitch.

They are also the best starting point for understanding how percussion is classified, because that line is
drawn on a **completely different basis** from woodwind or brass.

| Classification | Value |
|---|---|
| **HS class** | **Membranophone** — **the head itself is the source**, the bowl only resonates |
| **Sub-type** | Single head · **tunable** (pedal changes tension) · struck with mallets |
| **Family** | Western · Percussion (membranophone branch, with pitch) |
| **Bayin** | Not applicable — a Chinese system; the timpani are outside it |

> ⚠️ **One conceptual point**: **percussion's two great classes are not separated by material but by what
> vibrates.**
> - **Membranophone**: **a head** is the source → all drums (timpani, snare, bass drum, tambourine…)
> - **Idiophone**: **the material itself** vibrates → gongs, cymbals, triangles, xylophones, bells…
>
> Along with the [[instrument:tuba|aerophone's air column]] and the brass player's lips, that makes three
> distinct criteria inside the Hornbostel–Sachs scheme. **"Percussion" describes how it is played; "membrane
> or idiophone" is the classification.**

## How percussion divides: first ask what vibrates

```svg
<svg viewBox="0 0 640 340" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Percussion's two classes: membranophones whose head is the source, and idiophones whose material itself vibrates">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">Percussion's two classes: membranophone and idiophone</text>
  </g>
  <text x="160" y="62" text-anchor="middle" font-size="11" fill="#E07A3F">Membranophone · a head vibrates</text>
  <ellipse cx="160" cy="132" rx="80" ry="30" fill="#17171A" stroke="#E07A3F" stroke-width="1.7"/>
  <path d="M80,132 C104,116 216,116 240,132" fill="none" stroke="#E07A3F" stroke-width="2.4"/>
  <path d="M80,132 L80,196 C80,214 240,214 240,196 L240,132" fill="none" stroke="#343439" stroke-width="1.6"/>
  <circle cx="160" cy="96" r="5" fill="#E07A3F"/>
  <path d="M160,104 L160,118" stroke="#E07A3F" stroke-width="2" stroke-dasharray="3 2"/>
  <text x="160" y="238" text-anchor="middle" font-size="10.5" fill="#A9A49B">head = source, bowl = resonator</text>
  <text x="160" y="260" text-anchor="middle" font-size="10.5" fill="#E07A3F">timpani · snare · bass drum · tambourine</text>
  <text x="480" y="62" text-anchor="middle" font-size="11" fill="#5B7FA8">Idiophone · the material vibrates</text>
  <rect x="404" y="118" width="150" height="28" rx="14" fill="#17171A" stroke="#5B7FA8" stroke-width="1.7"/>
  <path d="M404,132 C440,120 518,120 554,132" fill="none" stroke="#5B7FA8" stroke-width="2.4"/>
  <circle cx="479" cy="92" r="5" fill="#5B7FA8"/>
  <path d="M479,100 L479,116" stroke="#5B7FA8" stroke-width="2" stroke-dasharray="3 2"/>
  <text x="480" y="238" text-anchor="middle" font-size="10.5" fill="#A9A49B">a solid body does the work, no head</text>
  <text x="480" y="260" text-anchor="middle" font-size="10.5" fill="#5B7FA8">triangle · cymbals · gong · xylophone · bells</text>
  <text x="20" y="296" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">"Percussion" says how it is played (struck, shaken, scraped); "membrane or idiophone" says what vibrates.</text>
  <text x="20" y="318" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">A tambourine is both — a membrane and a ring of small cymbals. One instrument can straddle the line.</text>
</svg>
```

**This diagram is the skeleton of the whole percussion batch.** The next 23 entries all fall into one of
four cells:

| | Membranophone (head) | Idiophone (material) |
|---|---|---|
| **With pitch** | **Timpani** | xylophone · marimba · vibraphone · glockenspiel · tubular bells · celesta · handpan |
| **Without fixed pitch** | snare · bass drum · tambourine · drum kit · Latin percussion | triangle · cymbals · gong · castanets · claves · whip · anvil · wind chimes · maracas · rainstick · woodblock |

**Four cells** — eight instruments with definite pitch (they can carry a range chart), sixteen without.

## Structure: a hemispherical bowl and pedal tuning

```svg
<svg viewBox="0 0 640 340" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Timpani structure: a copper hemispherical bowl, a head on top, tuning rods and a pedal, plus a soft mallet">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">Timpani — structure (the pedal changes head tension, hence pitch)</text>
  </g>
  <path d="M170,140 C170,232 240,268 300,268 C360,268 430,232 430,140 Z" fill="#17171A" stroke="#343439" stroke-width="1.6"/>
  <ellipse cx="300" cy="140" rx="130" ry="34" fill="#0E0E10" stroke="#9C7A3C" stroke-width="2.2"/>
  <ellipse cx="300" cy="140" rx="112" ry="26" fill="#17171A" stroke="#343439" stroke-width="1.2"/>
  <g stroke="#6E6A64" stroke-width="2.6" stroke-linecap="round">
    <path d="M178,148 L172,172"/><path d="M212,164 L204,188"/>
    <path d="M250,176 L244,200"/><path d="M300,180 L300,204"/>
    <path d="M350,176 L356,200"/><path d="M388,164 L396,188"/>
    <path d="M422,148 L428,172"/>
  </g>
  <path d="M300,268 L300,300 L360,306" fill="none" stroke="#5B7FA8" stroke-width="7" stroke-linecap="round"/>
  <rect x="352" y="296" width="46" height="12" rx="4" fill="#5B7FA8"/>
  <path d="M420,120 L462,96" stroke="#9C7A3C" stroke-width="5" stroke-linecap="round"/>
  <ellipse cx="468" cy="92" rx="12" ry="9" fill="#9C7A3C"/>
  <g class="lead" stroke="#6E6A64" stroke-width=".9">
    <path d="M186,190 L230,168"/><path d="M186,262 L244,262"/>
    <path d="M186,318 L292,306"/><path d="M186,116 L240,124"/>
    <path d="M486,86 L482,90"/>
  </g>
  <g font-family="system-ui,sans-serif" font-size="11" fill="#A9A49B">
    <text x="180" y="193" text-anchor="end" fill="#9C7A3C">Head (the source)</text>
    <text x="180" y="265" text-anchor="end">Copper bowl (resonator)</text>
    <text x="180" y="321" text-anchor="end" fill="#5B7FA8">Pedal (tension → pitch)</text>
    <text x="180" y="113" text-anchor="end">Tuning rods</text>
    <text x="492" y="83">Soft mallet</text>
  </g>
  <text x="20" y="336" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">The bowl is closed and hemispherical, so no low frequency leaks away — hence a definite, deep pitch.</text>
</svg>
```

Three points:

1. **The bowl is a closed hemisphere.** That is the key to a definite pitch: a closed cavity favours the
   fundamental, while an open drum (like a snare) scatters its low frequencies and blurs the pitch.
2. **The pedal is the tuning mechanism.** Pressing it changes head tension and therefore pitch, so a set can
   **retune during a piece** — why timpani are irreplaceable in an orchestra.
3. **Soft-headed mallets.** Head hardness decides the colour (soft = round and deep, hard = clear), so
   timpanists **change mallets** by phrase — a major expressive device.

## Range

```range
{"range":"D2–A3","common":"D2–F3","caption":"定音鼓（一套）的总音域","caption_en":"Timpani (a set) — combined range","note":"定音鼓是「可调音高」的膜鸣乐器：靠踏板改变鼓皮张力。单支鼓约一个六度；常见的一套四支合起来约 D2–A3。记谱即实音。"}
```

- **A set of four spans about D2–A3**, but **each drum tunes over only about a sixth** — so the total comes
  from several drums each covering a stretch.
- **The working area is D2–F3**; almost all orchestral writing lives there.
- **It carries the bass only.** Timpani are never a melodic instrument, but they **decide the rhythm of the
  low end**.

## Timbre, and how to hear it

Four cues:

1. **A definite pitch that does not read as one.** The impression of "distant thunder" usually arrives before
   the actual note.
2. **A long ring**, so fast strikes overlap — players damp with the hand to control it.
3. **The mallet decides the colour.** Changing mallets is like changing half the instrument, and is its
   greatest source of expression.
4. **A huge dynamic range**, from a distant rumble to a strike that can dominate the orchestra.

```audiolab
{"type":"instrument","gm":"Timpani","synth":"perc","phrase":["D2","A2","D3","A3","D2"],"label":"定音鼓的常用音区：D2 到 A3","label_en":"The timpani's working range — D2 up to A3","hint":"注意有音高但更像「轰鸣」—— 以及余音如何叠在一起","hint_en":"Hear a definite pitch that still reads as thunder — and how the notes ring into each other."}
```

## Playing techniques

- **One mallet in each hand**, so a player can strike **two notes at once** (more with more drums).
- **Damping** by hand stops the ring — the basis of a clean release.
- **Mallet changes**: at least soft, medium and hard, swapped by phrase.
- **Rolls**: alternating strokes produce a sustained thunder — one of the orchestra's most effective ways
  to build tension.
- **Pedal glissando**: changing pitch after the strike, a modern technique.

## The family

| Instrument | Class | Pitch? | Role in the ensemble |
|---|---|---|---|
| **Timpani** | membranophone | **yes (tunable)** | low rhythm and tension |
| [[instrument:snare-drum\|Snare drum]] | membranophone | no | rhythmic skeleton, military core |
| [[instrument:bass-drum\|Bass drum]] | membranophone | no | downbeats and low weight |
| [[instrument:marimba\|Marimba]] | idiophone | **yes** | melody and harmony |
| [[instrument:glockenspiel\|Glockenspiel]] | idiophone | **yes** | brightening the top |

**Timpani and marimba are the two ends of "pitched percussion"**: one the lowest (membrane), one in the
middle-high (idiophone wooden bars).

## History

| Period | State |
|---|---|
| Antiquity–Middle Ages | skin drums everywhere; the Middle Eastern and European **kettledrum** is the direct ancestor |
| 15th–16th c. | enters Europe with military bands; tuning is by rods at this point and slow |
| 17th c. | enters the orchestra, often paired with trumpets (both have only a few notes) |
| 18th–19th c. | tuning mechanisms improve; Beethoven and others raise the timpani from rhythm to expression |
| Late 19th–20th c. | **pedal tuning** spreads → retuning during a piece becomes possible, and the writing is freed |
| 20th c. onward | standard in orchestra and band; contemporary works demand complex retuning and colour changes |

**A commonly cited example**: in the scherzo of Beethoven's Ninth the timpani have a soloistic passage
playing the theme's rhythm — highly unusual for 1824.

## Common misconceptions

- **"Timpani are idiophones."** They are **membranophones** — the head is the source, the bowl only
  resonates.
- **"They have no pitch."** They **do**, tunably, and are among the few pitched instruments in orchestral
  percussion.
- **"They are copper, so they are like brass instruments."** Material settles nothing. They belong to
  **percussion · membranophone**, unrelated to lip-driven brass.
- **"A set has a wide range."** **Each drum** tunes over only about a sixth; the total is assembled from
  several drums.
- **"Drumming needs no technique."** Damping, mallet choice, rolls and pedal tuning are specialist skills,
  and tuning by pedal demands a good ear.

## Next

From "membranophones" the line now splits: **drums** ([[instrument:snare-drum|snare]] ·
[[instrument:bass-drum|bass drum]]) and **idiophones** (the xylophone family, the metal family).

Start with the **snare drum** — the heart of military music and the drum kit, and the best example of how a
membranophone becomes pitchless.
:::
