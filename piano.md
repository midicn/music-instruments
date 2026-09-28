---
id: piano
site: inst
cat: I5
title: 钢琴
title_en: Piano
summary: 键盘击弦的弦鸣乐器，能靠触键控制力度，全音域乐器之一
summary_en: A keyboard-struck chordophone with touch-sensitive dynamics — one of the few full-range instruments
level: standard
tags: [乐器, 键盘, 西洋]
tags_en: [instrument, keyboard, western]
alias: [钢琴, piano, 三角钢琴, 立式钢琴, pianoforte]
order: 79
links:
  - "[[concept:interval]]"
  - "[[concept:register]]"
  - "[[concept:timbre]]"
  - "[[concept:articulation]]"
  - "[[instrument:harpsichord]]"
  - "[[instrument:clavichord]]"
  - "[[instrument:celesta]]"
  - "[[instrument:organ]]"
instances:
  - pdmx-000071 | 贝多芬 F 大调圆号奏鸣曲 Op.17 —— 原是圆号与钢琴的作品，可听钢琴在室内乐里的角色
  - pdmx-002479 | 为圆号与钢琴的四首小品 Op.35 —— 同为"独奏乐器 + 钢琴"的编制
  - pdmx-000062 | 管乐五重奏（长笛 · 双簧管 · 单簧管 · 圆号 · 巴松）—— 无钢琴的编制，可作对照
sources:
  - 结构依通行制琴资料：**键盘**经**击弦机**驱动包毡木槌击弦；每音由**一至三根弦**构成，弦的振动经**音板**放大；**制音器**在离键时止音，右踏板可整体解除
  - 「钢琴属**弦鸣**乐器 —— 振源是弦；键盘只是操作界面」依 Hornbostel–Sachs 分类
  - 「标准音域 A0–C8（88 键）」依通行制琴规格
  - 「击弦机使音量与音色随触键力度变化 —— 这是它与大键琴最根本的区别」依乐器史与乐器声学
updated: 2026-09-26
---

::: zh
钢琴是键盘乐器里最"全能"的一件，也是**全站唯一一件音域覆盖键盘全部 88 键的乐器**。
它能把整个乐队的总谱浓缩到一双手上 —— 这件事只有它和[[instrument:organ|管风琴]]做得到。

它身上还有一个必须讲清的分类问题：
**它由键盘演奏，却属弦鸣乐器** —— 因为**振动的是弦**，键盘只是操作界面。

| 分类 | 归属 |
|---|---|
| **HS 分类** | **弦鸣**（Chordophone）—— **振动的是弦** |
| **次级类型** | 键盘经击弦机驱动包毡木槌击弦 · 每音一至三根弦 · 音板放大 · 制音器止音 |
| **所属族** | 西洋 · 键盘（击弦支系） |
| **八音** | 不适用 —— 周代八音是中国乐器的体系，钢琴不在其中 |

> ⚠️ **一个概念上的要点**：**"键盘"回答的是"怎么操作"，"弦鸣/气鸣/体鸣"回答的是"什么在振动"。**
> 键盘组里四件乐器正好把这条讲透：
> - **钢琴**：键盘 → 击弦 → **弦鸣**
> - [[instrument:harpsichord|大键琴]]：键盘 → 拨弦 → **弦鸣**
> - [[instrument:organ|管风琴]]：键盘 → 气流 → **气鸣**
> - [[instrument:celesta|钢片琴]]：键盘 → 击钢片 → **体鸣**
>
> 四种键盘，三个大类。**所以"键盘乐器"是一个操作界面上的归类，不是声学上的归类。**

## 三个机制：力度、余音、音量

钢琴之所以能取代[[instrument:harpsichord|大键琴]]，靠的是**三个机制**同时成立。

```svg
<svg viewBox="0 0 640 320" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="钢琴的三个核心机制：击弦机带来力度控制、制音器与踏板控制余音、音板放大音量">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">三个机制，决定了钢琴能做而大键琴做不到的事</text>
  </g>
  <rect x="40" y="52" width="168" height="150" rx="6" fill="#17171A" stroke="#5B7FA8" stroke-width="1.6"/>
  <text x="124" y="76" text-anchor="middle" font-size="11" fill="#5B7FA8">机制一 · 击弦机</text>
  <path d="M72,130 L140,104" stroke="#5B7FA8" stroke-width="4" stroke-linecap="round"/>
  <ellipse cx="148" cy="100" rx="12" ry="9" fill="#5B7FA8"/>
  <path d="M60,150 L100,150" stroke="#5B7FA8" stroke-width="3" stroke-linecap="round"/>
  <text x="124" y="172" text-anchor="middle" font-size="10.5" fill="#A9A49B">按键 → 木槌击弦</text>
  <text x="124" y="192" text-anchor="middle" font-size="10.5" fill="#5B7FA8">力度可控制</text>
  <rect x="236" y="52" width="168" height="150" rx="6" fill="#17171A" stroke="#9C7A3C" stroke-width="1.6"/>
  <text x="320" y="76" text-anchor="middle" font-size="11" fill="#9C7A3C">机制二 · 制音器</text>
  <path d="M300,128 L356,112" stroke="#9C7A3C" stroke-width="3.4" stroke-linecap="round"/>
  <rect x="352" y="104" width="16" height="12" rx="3" fill="#9C7A3C"/>
  <path d="M280,144 L360,144" stroke="#9C7A3C" stroke-width="2.6"/>
  <text x="320" y="172" text-anchor="middle" font-size="10.5" fill="#A9A49B">离键即止音</text>
  <text x="320" y="192" text-anchor="middle" font-size="10.5" fill="#9C7A3C">踏板解除限制</text>
  <rect x="432" y="52" width="168" height="150" rx="6" fill="#17171A" stroke="#E07A3F" stroke-width="1.6"/>
  <text x="516" y="76" text-anchor="middle" font-size="11" fill="#E07A3F">机制三 · 音板</text>
  <path d="M462,140 C492,120 540,120 570,140" fill="none" stroke="#E07A3F" stroke-width="3"/>
  <path d="M462,150 C492,170 540,170 570,150" fill="none" stroke="#E07A3F" stroke-width="2" stroke-dasharray="4 3"/>
  <text x="516" y="172" text-anchor="middle" font-size="10.5" fill="#A9A49B">弦的振动经音板放大</text>
  <text x="516" y="192" text-anchor="middle" font-size="10.5" fill="#E07A3F">音量足以填满厅堂</text>
  <text x="20" y="234" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">三者缺一不可：只有力度没有音量，就是击弦古钢琴；只有音量没有力度，就是大键琴；</text>
  <text x="20" y="256" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">只有力度与音量而没有余音控制，就没有"踩住踏板"这件事 —— 那样音乐的语言会完全不同。</text>
  <text x="20" y="284" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">钢琴之所以成为 19 世纪音乐的"通用乐器"，正是因为它三项俱全。</text>
  <text x="20" y="306" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">所以你听到的"钢琴的表现力"，背后是三条具体的机械设计。</text>
</svg>
```

**这张图给出了钢琴存在的技术理由**（详见下节的对照表）。

## 键盘组三种触发方式的对照

```svg
<svg viewBox="0 0 640 300" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="钢琴、大键琴与击弦古钢琴三种触发方式的对照：击弦可控制力度、拨弦不能、击弦但音量极小">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">同样是键盘，三种触发方式</text>
  </g>
  <g font-family="system-ui,sans-serif" font-size="10.5">
    <text x="20" y="66" fill="#5B7FA8">钢琴 · 击弦</text>
    <text x="20" y="88" fill="#A9A49B">木槌击弦，击完即离</text>
    <text x="20" y="110" fill="#6E6A64">力度可控制 ✓ 音量可大 ✓ 余音可控 ✓</text>
    <text x="20" y="146" fill="#9C7A3C">大键琴 · 拨弦</text>
    <text x="20" y="168" fill="#A9A49B">羽管拨弦，拨完即回</text>
    <text x="20" y="190" fill="#6E6A64">力度不可控制 ✗ 音量固定 余音可控 ✓</text>
    <text x="20" y="226" fill="#E07A3F">击弦古钢琴 · 击弦</text>
    <text x="20" y="248" fill="#A9A49B">铜片击弦，击后仍触弦</text>
    <text x="20" y="270" fill="#6E6A64">力度可控制 ✓ 音量极小 ✗（还可用触键做颤音）</text>
  </g>
  <g stroke="#343439" stroke-width="1">
    <path d="M316,50 L316,276"/>
  </g>
  <g font-family="system-ui,sans-serif" font-size="10.5" fill="#A9A49B">
    <text x="332" y="66">触发方式的差别只有一点：</text>
    <text x="332" y="88">击弦的"接触时间"极短，但击弦的速度</text>
    <text x="332" y="110">可以随按键的速度改变 → 这就是"力度"。</text>
    <text x="332" y="146">拨弦的接触由机械固定，按键快慢</text>
    <text x="332" y="168">不影响拨动的力度 → 因此没有力度层次。</text>
    <text x="332" y="204">击弦古钢琴用铜片，击后铜片继续</text>
    <text x="332" y="226">压在弦上 → 演奏者可以在按键后继续</text>
    <text x="332" y="248">加压，做出颤音（Bebung）——</text>
    <text x="332" y="270" fill="#E07A3F">这是键盘乐器里极少见的一种"后触"效果。</text>
  </g>
  <text x="20" y="292" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">"能不能控制力度"不是风格问题，而是「机械结构决定的」。</text>
</svg>
```

**这条"机械结构决定可控范围"是键盘组的核心线索**：
乐器能做什么，先由它的机构决定，然后才轮到作曲家的想象。

## 音域

```range
{"range":"A0–C8","common":"A0–C7","caption":"钢琴的音域（88 键）","caption_en":"Piano range (88 keys)","note":"钢琴属弦鸣乐器 —— 键盘只是操作界面，振源是弦。标准 88 键，音域 A0–C8，是本站键盘条目的参照尺度：其他键盘乐器的音域都可以在这上面标出位置。"}
```

- **A0–C8（88 键）**，覆盖本站音域图的**全部键盘范围** ——
  所以它是键盘组里唯一不需要"超钢琴延伸区"的乐器。
- **常用区 A0–C7**：最高一个八度主要在独奏与炫技段落使用。
- **它的音域宽度是键盘组的标尺**。看[[instrument:harpsichord|大键琴]]、
  [[instrument:clavichord|击弦古钢琴]]、[[instrument:organ|管风琴]]时，
  都可以在 88 键上直接看到它们占哪一段。

## 音色与听辨

四条线索：

1. **音头清晰、余音长而可控**。木槌的击弦给一个明确的音头，随后的余音由制音器与踏板管理。
2. **力度层次是它的语言**。同一件乐器可以从几乎听不见做到极强 ——
   这是它在 19 世纪成为"通用乐器"的核心理由。
3. **低音厚、高音亮，中间最"歌"**。不同音区的音色差异很大，作曲家常利用这一点。
4. **它是一件"和声乐器"**。十指能同时按下十个音，所以它天然适合承担和声骨架。

```audiolab
{"type":"instrument","gm":"Acoustic Grand Piano","synth":"struck","phrase":["A0","A2","A4","C6","C8"],"label":"钢琴的音域：从最低 A0 到最高 C8","label_en":"The piano's range — from A0 up to C8","hint":"注意低音的厚与高音的亮 —— 这个跨度是它成为「通用乐器」的原因","hint_en":"Hear the depth at the bottom and the brightness at the top — this span is why it became the universal instrument."}
```

## 演奏技法

- **触键**：力度、时值、连断都由按键控制。
- **三个踏板**（现代钢琴）：**右踏板（延音）**把制音器整体抬起 → 余音叠加；
  **左踏板（弱音）**改变弦数或缩短击弦距离；**中踏板**视乐器而定（选择性延音）。
- **连奏与断奏**：击弦机允许极细腻的连断控制，这是钢琴语言的基础。
- **特殊的"预备"效果**：先按下琴键不发声（让制音器抬起），再击弦 —— 可以得到更长的余音。

## 家族与近亲

| 乐器 | 触发方式 | 振源 | 力度可控 | 音量 | 音域 |
|---|---|---|---|---|---|
| **钢琴** | 击弦 | 弦 | **可** | **大** | **A0–C8** |
| [[instrument:harpsichord\|大键琴]] | **拨弦** | 弦 | **不可** | 中 | F1–F6 |
| [[instrument:clavichord\|击弦古钢琴]] | 击弦（铜片） | 弦 | 可（可做颤音） | **极小** | C2–C6 |
| [[instrument:organ\|管风琴]] | 气流 | **空气柱** | 不可（靠音栓） | 极大 | C2–C7 |
| [[instrument:celesta\|钢片琴]] | 击片 | **钢片** | 可 | 小 | C3–C8 |

**这张表把"键盘"这个界面下的四条技术路线并排摆开了** ——
它们共用一只手，却分属三个 HS 大类、四种可控范围。

## 历史演变

| 时期 | 状态 |
|---|---|
| 1700 年前后 | 意大利的 **Cristofori** 做出第一台能靠触键控制力度的键盘击弦乐器 —— 钢琴的起点 |
| 18 世纪 | 与**大键琴**长期并存；击弦机的改良（维也纳式与英国式两种）逐步推进 |
| 19 世纪 | 金属框架、交叉弦列、毡槌等技术成熟 → 音量与音域大幅扩展；**成为家庭与音乐厅的通用乐器** |
| 19 世纪后期 | 88 键（A0–C8）成为标准；三角与立式两种形制定型 |
| 20 世纪 | 成为作曲、教学与表演的中心乐器；录音与流行音乐也以它为基础 |
| 20 世纪后期至今 | 与电子键盘并存；在古典、爵士、流行、影视里全面通用 |

**它的胜利有一个很实际的原因**：**能控制力度**。
与大键琴相比，它多出来的那一点"可控性"，
让音乐第一次能在键盘上做出渐强渐弱 —— 而这正是 18 世纪末音乐语言的核心需求。

## 常见误解

- **"钢琴是键盘乐器，所以属键盘类。"** HS 分类里它属**弦鸣** —— 振动的是弦。
  "键盘"是操作界面，不是分类（同组的管风琴属气鸣、钢片琴属体鸣）。
- **"钢琴和大键琴差不多。"** 触发方式不同（击弦 vs 拨弦）→ **大键琴不能控制力度**，
  这是两者最根本的差别。
- **"踏板只是把声音变大。"** 延音踏板改变的是**和声的叠加方式**，是配器与演奏语言的一部分。
- **"立式钢琴是"小一号的三角"。"** 弦的排列方向不同（竖 vs 横），
  击弦机结构也不同 → 手感与声音都有差别。
- **"钢琴音域很宽所以能演奏任何音乐。"** 它音域宽，但**不能延长音**（击弦后余音自然衰减）——
  这一点与管风琴、弦乐完全不同，也是"钢琴化写作"之所以特别的原因。

## 下一步

键盘组的下一站是它的"前任"：[[instrument:harpsichord|大键琴]] ——
同样用键盘、同样用弦，但**拨弦**带来了完全不同的音乐语言。
再往后是 [[instrument:clavichord|击弦古钢琴]]（力度可控但极小）与
[[instrument:organ|管风琴]]（键盘下的气鸣）。
:::

::: en
The piano is the most "complete" of the keyboard instruments, and **the only instrument on this site whose
range spans the entire 88-key compass.** It can compress a full orchestral score into two hands — something
only it and the [[instrument:organ|organ]] can do.

It also poses a classification question that has to be stated clearly: **it is played from a keyboard, yet it
belongs to the chordophones** — because **the strings vibrate**; the keyboard is only the interface.

| Classification | Value |
|---|---|
| **HS class** | **Chordophone** — **the strings vibrate** |
| **Sub-type** | Keyboard drives a felt hammer action against strings · one to three strings per note · soundboard amplifies · dampers stop the sound |
| **Family** | Western · Keyboard (struck branch) |
| **Bayin** | Not applicable — a Chinese system; the piano is outside it |

> ⚠️ **One conceptual point**: **"keyboard" answers "how it is operated"; "chordophone / aerophone /
> idiophone" answers "what vibrates".**
> The keyboard group's four instruments make this plain:
> - **Piano**: keyboard → struck strings → **chordophone**
> - [[instrument:harpsichord|Harpsichord]]: keyboard → plucked strings → **chordophone**
> - [[instrument:organ|Organ]]: keyboard → air → **aerophone**
> - [[instrument:celesta|Celesta]]: keyboard → struck steel plates → **idiophone**
>
> Four keyboards, three great classes. **"Keyboard instrument" is a grouping by interface, not by acoustics.**

## Three mechanisms: dynamics, ring, volume

The piano replaced the [[instrument:harpsichord|harpsichord]] because **three mechanisms** came together.

```svg
<svg viewBox="0 0 640 320" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="The piano's three core mechanisms: hammer action gives dynamic control, dampers and pedal manage the ring, the soundboard amplifies">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">Three mechanisms — what the piano can do and a harpsichord cannot</text>
  </g>
  <rect x="40" y="52" width="168" height="150" rx="6" fill="#17171A" stroke="#5B7FA8" stroke-width="1.6"/>
  <text x="124" y="76" text-anchor="middle" font-size="11" fill="#5B7FA8">1 · Hammer action</text>
  <path d="M72,130 L140,104" stroke="#5B7FA8" stroke-width="4" stroke-linecap="round"/>
  <ellipse cx="148" cy="100" rx="12" ry="9" fill="#5B7FA8"/>
  <path d="M60,150 L100,150" stroke="#5B7FA8" stroke-width="3" stroke-linecap="round"/>
  <text x="124" y="172" text-anchor="middle" font-size="10.5" fill="#A9A49B">key → hammer → string</text>
  <text x="124" y="192" text-anchor="middle" font-size="10.5" fill="#5B7FA8">dynamics controllable</text>
  <rect x="236" y="52" width="168" height="150" rx="6" fill="#17171A" stroke="#9C7A3C" stroke-width="1.6"/>
  <text x="320" y="76" text-anchor="middle" font-size="11" fill="#9C7A3C">2 · Dampers</text>
  <path d="M300,128 L356,112" stroke="#9C7A3C" stroke-width="3.4" stroke-linecap="round"/>
  <rect x="352" y="104" width="16" height="12" rx="3" fill="#9C7A3C"/>
  <path d="M280,144 L360,144" stroke="#9C7A3C" stroke-width="2.6"/>
  <text x="320" y="172" text-anchor="middle" font-size="10.5" fill="#A9A49B">release stops the sound</text>
  <text x="320" y="192" text-anchor="middle" font-size="10.5" fill="#9C7A3C">pedal lifts the limit</text>
  <rect x="432" y="52" width="168" height="150" rx="6" fill="#17171A" stroke="#E07A3F" stroke-width="1.6"/>
  <text x="516" y="76" text-anchor="middle" font-size="11" fill="#E07A3F">3 · Soundboard</text>
  <path d="M462,140 C492,120 540,120 570,140" fill="none" stroke="#E07A3F" stroke-width="3"/>
  <path d="M462,150 C492,170 540,170 570,150" fill="none" stroke="#E07A3F" stroke-width="2" stroke-dasharray="4 3"/>
  <text x="516" y="172" text-anchor="middle" font-size="10.5" fill="#A9A49B">strings amplified by the board</text>
  <text x="516" y="192" text-anchor="middle" font-size="10.5" fill="#E07A3F">enough volume for a hall</text>
  <text x="20" y="234" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">All three matter: dynamics without volume is a clavichord; volume without dynamics is a harpsichord;</text>
  <text x="20" y="256" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">and without control of the ring there would be no such thing as holding the pedal down.</text>
  <text x="20" y="284" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">The piano became the 19th century's universal instrument precisely because it has all three.</text>
  <text x="20" y="306" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">So "the piano's expressiveness" rests on three concrete mechanical designs.</text>
</svg>
```

**This diagram gives the piano its technical reason to exist** (see the comparison below).

## Three keyboard trigger types compared

```svg
<svg viewBox="0 0 640 300" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Piano, harpsichord and clavichord compared by trigger: struck strings allow dynamics, plucked strings do not, struck copper tangents allow dynamics but are very quiet">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">One keyboard, three ways of setting a string going</text>
  </g>
  <g font-family="system-ui,sans-serif" font-size="10.5">
    <text x="20" y="66" fill="#5B7FA8">Piano · struck</text>
    <text x="20" y="88" fill="#A9A49B">felt hammer strikes, then leaves</text>
    <text x="20" y="110" fill="#6E6A64">dynamics YES · loud YES · ring control YES</text>
    <text x="20" y="146" fill="#9C7A3C">Harpsichord · plucked</text>
    <text x="20" y="168" fill="#A9A49B">a quill plucks and returns</text>
    <text x="20" y="190" fill="#6E6A64">dynamics NO · fixed volume · ring control YES</text>
    <text x="20" y="226" fill="#E07A3F">Clavichord · struck (tangent)</text>
    <text x="20" y="248" fill="#A9A49B">a brass tangent strikes and stays in contact</text>
    <text x="20" y="270" fill="#6E6A64">dynamics YES · very quiet NO · can even add vibrato</text>
  </g>
  <g stroke="#343439" stroke-width="1">
    <path d="M316,50 L316,276"/>
  </g>
  <g font-family="system-ui,sans-serif" font-size="10.5" fill="#A9A49B">
    <text x="332" y="66">The trigger difference is one thing:</text>
    <text x="332" y="88">a strike touches the string for an instant, but</text>
    <text x="332" y="110">its speed follows the key → that is "dynamics".</text>
    <text x="332" y="146">A pluck's force is fixed by the mechanism, so key</text>
    <text x="332" y="168">speed changes nothing → no dynamic layering.</text>
    <text x="332" y="204">The clavichord's tangent stays pressed against</text>
    <text x="332" y="226">the string, so the player can keep adding</text>
    <text x="332" y="248">pressure after the key is down (Bebung) —</text>
    <text x="332" y="270" fill="#E07A3F">a rare "after-touch" effect in keyboard playing.</text>
  </g>
  <text x="20" y="292" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">"Can it control dynamics" is not a matter of taste but of 「mechanism」.</text>
</svg>
```

**"Mechanism decides the range of control" is the keyboard group's key thread**: what an instrument can do is
settled by its mechanism first, and only then by a composer's imagination.

## Range

```range
{"range":"A0–C8","common":"A0–C7","caption":"钢琴的音域（88 键）","caption_en":"Piano range (88 keys)","note":"钢琴属弦鸣乐器 —— 键盘只是操作界面，振源是弦。标准 88 键，音域 A0–C8，是本站键盘条目的参照尺度：其他键盘乐器的音域都可以在这上面标出位置。"}
```

- **A0–C8 (88 keys)**, covering the site's **entire keyboard range** — the only keyboard instrument here that
  never needs a "beyond the piano" extension.
- **The working range is A0–C7**; the top octave belongs mostly to solo and virtuoso writing.
- **Its span is the keyboard group's ruler.** Reading the [[instrument:harpsichord|harpsichord]],
  [[instrument:clavichord|clavichord]] or [[instrument:organ|organ]] entries, you can see directly where they
  sit on these 88 keys.

## Timbre, and how to hear it

Four cues:

1. **A clear attack and a long, controllable tail** — the hammer gives the attack, the dampers and pedal manage
   what follows.
2. **Dynamic layering is its language**: from almost inaudible to very loud on one instrument — the core reason
   it became the 19th century's universal instrument.
3. **Thick low, bright high, most "vocal" in the middle** — composers exploit the differing registers.
4. **It is a harmonic instrument**: ten fingers can press ten notes, so it naturally carries harmony.

```audiolab
{"type":"instrument","gm":"Acoustic Grand Piano","synth":"struck","phrase":["A0","A2","A4","C6","C8"],"label":"钢琴的音域：从最低 A0 到最高 C8","label_en":"The piano's range — from A0 up to C8","hint":"注意低音的厚与高音的亮 —— 这个跨度是它成为「通用乐器」的原因","hint_en":"Hear the depth at the bottom and the brightness at the top — this span is why it became the universal instrument."}
```

## Playing techniques

- **Touch** controls dynamics, duration and legato.
- **Three pedals** (modern pianos): **right (sustain)** lifts all dampers so notes accumulate; **left (soft)**
  changes the number of strings or shortens the hammer's travel; **middle** varies by instrument (selective
  sustain).
- **Legato and staccato**: the action allows very fine control of connection — the basis of piano language.
- **The "prepared" effect**: pressing keys silently first (lifting dampers), then striking, yields a longer
  ring.

## The family

| Instrument | Trigger | Source | Dynamics | Volume | Range |
|---|---|---|---|---|---|
| **Piano** | struck | strings | **yes** | **large** | **A0–C8** |
| [[instrument:harpsichord\|Harpsichord]] | **plucked** | strings | **no** | medium | F1–F6 |
| [[instrument:clavichord\|Clavichord]] | struck (tangent) | strings | yes (with vibrato) | **tiny** | C2–C6 |
| [[instrument:organ\|Organ]] | air | **air columns** | no (stops instead) | huge | C2–C7 |
| [[instrument:celesta\|Celesta]] | struck plates | **steel plates** | yes | small | C3–C8 |

**This table lays out the four technical routes behind the word "keyboard"** — one hand, three HS classes,
four ranges of control.

## History

| Period | State |
|---|---|
| Around 1700 | **Cristofori** in Italy builds the first keyboard instrument whose touch controls dynamics — the piano begins |
| 18th c. | coexists with the **harpsichord** for decades; actions improve (Viennese and English types) |
| 19th c. | iron frames, overstringing and felt hammers mature → far more volume and range; **it becomes the household and concert-hall universal instrument** |
| Later 19th c. | 88 keys (A0–C8) become standard; grand and upright forms settle |
| 20th c. | central to composition, teaching and performance; recording and popular music are built around it |
| Late 20th c. onward | coexists with electronic keyboards; universal in classical, jazz, pop and film |

**Its victory has a very practical cause: it can control dynamics.** That extra bit of controllability over the
harpsichord let music make crescendos and diminuendos at a keyboard for the first time — exactly what the
language of the late 18th century required.

## Common misconceptions

- **"The piano is a keyboard instrument, so it is classed as a keyboard instrument."** In Hornbostel–Sachs it
  is a **chordophone** — the strings vibrate. "Keyboard" is an interface (the organ in the same group is an
  aerophone, the celesta an idiophone).
- **"The piano and the harpsichord are much the same."** Different triggers (struck versus plucked) → **a
  harpsichord cannot control dynamics**, the fundamental difference.
- **"The pedal just makes it louder."** The sustain pedal changes **how harmonies stack** — part of the
  language of writing and playing.
- **"An upright is a small grand."** The strings run in different directions (vertical versus horizontal) and
  the action differs → different feel and sound.
- **"A wide range means it can play anything."** The range is wide, but **it cannot sustain** (a struck note
  decays) — unlike the organ or strings, and the reason "piano writing" is so distinctive.

## Next

The keyboard group's next stop is the piano's predecessor: the [[instrument:harpsichord|harpsichord]] — the
same keyboard and the same strings, but **plucked**, which produces an entirely different musical language.
Beyond it come the [[instrument:clavichord|clavichord]] (dynamic but tiny) and the
[[instrument:organ|organ]] (aerophone under a keyboard).
:::
