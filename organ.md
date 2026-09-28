---
id: organ
site: inst
cat: I5
title: 管风琴
title_en: Organ
summary: 用键盘控制气阀、让气流进入音管的气鸣乐器，音可无限持续
summary_en: Keys open valves that admit air into pipes — an aerophone whose notes can sustain indefinitely
level: standard
tags: [乐器, 键盘, 西洋]
tags_en: [instrument, keyboard, western]
alias: [管风琴, organ, 教堂管风琴, 大风琴, pipe organ]
order: 82
links:
  - "[[concept:interval]]"
  - "[[concept:register]]"
  - "[[concept:timbre]]"
  - "[[concept:articulation]]"
  - "[[instrument:piano]]"
  - "[[instrument:harmonium]]"
  - "[[instrument:portative-organ]]"
  - "[[instrument:accordion]]"
instances:
  - pdmx-001939 | 六首圆号四重奏 Op.35 —— 多声部写作的范例，可对照管风琴"每声部独立"的特点
  - pdmx-000322 | 鲁特琴与竖笛的协奏曲 —— 巴洛克通奏低音的编制，管风琴常在其中
  - pdmx-002065 | 为竖笛与长笛而作的协奏曲 —— 巴洛克室内乐编制，管风琴可作通奏低音乐器
sources:
  - 结构依通行制琴资料：**键盘**控制**气阀**，气流由风箱（或电动鼓风）送入**音管**；音管按音高与音色分组，由**音栓（stops）**选择
  - 「管风琴属**气鸣**乐器 —— 振动的是音管内的空气柱」依 Hornbostel–Sachs 分类
  - 「音管分两大类：**哨管**（气流切过棱边）与**簧管**（气流使簧片振动）」依管风琴制作通识
  - 「音域随乐器差别极大，常见约 C2–C7；大型管风琴可超出此范围」依通行乐器资料
updated: 2026-09-26
---

::: zh
管风琴是键盘组里体量最大、也最特殊的一件：
**它不用手去"弹"一个发声体，而是用键盘去"开一扇门"，让气流自己发出声音。**

这带来两个别的键盘乐器都没有的结果：
**音可以无限持续**，以及**每个音都是独立的声部**。

| 分类 | 归属 |
|---|---|
| **HS 分类** | **气鸣**（Aerophone）—— **振动的是音管内的空气柱** |
| **次级类型** | 键盘控制气阀 · 气流送进音管 · **音栓**选择音管组 · 音可无限持续 |
| **所属族** | 西洋 · 键盘（气鸣支系） |
| **八音** | 不适用 —— 周代八音是中国乐器的体系，管风琴不在其中 |

> ⚠️ **一个概念上的要点**：**管风琴把"键盘"这个界面的性质讲得最清楚。**
> 在钢琴上，按键 = **击打**（一次动作对应一次发声）；
> 在管风琴上，按键 = **开阀**（按住多久，声音就持续多久）。
> 所以管风琴的键盘不是"打击装置"，而更像一组**开关** ——
> 这也意味着它**没有力度控制**（音管的响度由风压与音栓决定，不由触键决定）。
> **同一个界面，两种完全不同的操作语义。**

## 结构：键盘开阀，气流发声

```svg
<svg viewBox="0 0 640 340" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="管风琴的结构：键盘控制气阀、气流由风箱送入按音高排列的音管、音栓选择音管组">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">管风琴 · 结构（键盘开阀 → 气流 → 音管）</text>
  </g>
  <rect x="60" y="72" width="240" height="30" rx="4" fill="#17171A" stroke="#343439" stroke-width="1.4"/>
  <g stroke="#6E6A64" stroke-width="1.2">
    <path d="M76,72 L76,102"/><path d="M94,72 L94,102"/><path d="M112,72 L112,102"/>
    <path d="M130,72 L130,102"/><path d="M148,72 L148,102"/><path d="M166,72 L166,102"/>
    <path d="M184,72 L184,102"/><path d="M202,72 L202,102"/><path d="M220,72 L220,102"/>
    <path d="M238,72 L238,102"/><path d="M256,72 L256,102"/><path d="M274,72 L274,102"/>
  </g>
  <rect x="60" y="124" width="240" height="34" rx="4" fill="#17171A" stroke="#5B7FA8" stroke-width="1.6"/>
  <g fill="#5B7FA8">
    <rect x="112" y="132" width="10" height="18" rx="3"/>
    <rect x="166" y="132" width="10" height="18" rx="3"/>
    <rect x="220" y="132" width="10" height="18" rx="3"/>
  </g>
  <rect x="60" y="182" width="240" height="30" rx="4" fill="#17171A" stroke="#9C7A3C" stroke-width="1.5"/>
  <g stroke="#9C7A3C" stroke-width="2.4">
    <path d="M100,182 L100,140"/><path d="M150,182 L150,140"/><path d="M200,182 L200,140"/>
    <path d="M250,182 L250,140"/>
  </g>
  <g stroke="#E07A3F" stroke-width="1.8" fill="#17171A">
    <rect x="352" y="60" width="18" height="150" rx="8"/>
    <rect x="382" y="76" width="18" height="134" rx="8"/>
    <rect x="412" y="94" width="18" height="116" rx="8"/>
    <rect x="442" y="110" width="18" height="100" rx="8"/>
    <rect x="472" y="124" width="18" height="86" rx="8"/>
    <rect x="502" y="136" width="18" height="74" rx="8"/>
    <rect x="532" y="146" width="18" height="64" rx="8"/>
  </g>
  <path d="M340,210 L560,210" stroke="#343439" stroke-width="3"/>
  <g class="lead" stroke="#6E6A64" stroke-width=".9">
    <path d="M186,56 L186,66"/><path d="M186,124 L186,118"/>
    <path d="M186,232 L186,218"/><path d="M486,42 L486,54"/>
    <path d="M186,300 L280,214"/>
  </g>
  <g font-family="system-ui,sans-serif" font-size="11" fill="#A9A49B">
    <text x="180" y="53" text-anchor="end">键盘（开关，不是击打）</text>
    <text x="180" y="121" text-anchor="end" fill="#5B7FA8">气阀（按键开启）</text>
    <text x="180" y="235" text-anchor="end" fill="#9C7A3C">风箱 / 鼓风（送气）</text>
    <text x="492" y="39" fill="#E07A3F">音管（管越长音越低）</text>
    <text x="180" y="303" text-anchor="end">音栓（选择哪一组音管）</text>
  </g>
  <text x="20" y="266" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">气流持续送出，所以按住键就持续发声 —— 这是管风琴能"无限延长"一个音的原因。</text>
  <text x="20" y="288" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">音管的音高由管长决定：同一音高可以有多根不同长度与形状的管，对应不同音色 —— 这就是音栓。</text>
  <text x="20" y="316" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">所以管风琴的声音不是"一件乐器"，而是"一整组乐器"被一套键盘统一控制。</text>
</svg>
```

三处要点：

1. **键盘是开关，不是击打装置**。按住多久，音就持续多久 ——
   所以管风琴是唯一能**无限延长一个音**的键盘乐器。
2. **音管按音高与音色分组**。同一音高可以有多种管（长笛管、弦管、簧管…），
   由**音栓**选择 —— 这是它音色丰富的原因。
3. **它其实是一组乐器**。一台大管风琴可能有几千根音管、几十个音栓，
   由一套键盘统一控制。

## 音管的两大类

```svg
<svg viewBox="0 0 640 300" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="管风琴音管的两大类：哨管靠气流切过棱边发声，簧管靠气流使簧片振动">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">音管的两大类：哨管与簧管</text>
  </g>
  <text x="150" y="58" text-anchor="middle" font-size="11" fill="#5B7FA8">哨管 · 气流切过棱边</text>
  <rect x="110" y="76" width="80" height="130" rx="6" fill="#17171A" stroke="#5B7FA8" stroke-width="1.6"/>
  <path d="M110,140 L190,140" stroke="#5B7FA8" stroke-width="2.6"/>
  <path d="M150,152 C170,158 182,170 186,186" fill="none" stroke="#E07A3F" stroke-width="2.4"/>
  <path d="M178,180 L188,190 L176,192 Z" fill="#E07A3F"/>
  <text x="150" y="230" text-anchor="middle" font-size="10.5" fill="#A9A49B">气流切边发声，无簧片</text>
  <text x="150" y="252" text-anchor="middle" font-size="10.5" fill="#5B7FA8">长笛管 · 弦管 · 主音管</text>
  <text x="150" y="274" text-anchor="middle" font-size="10.5" fill="#6E6A64">管风琴音管的大多数</text>
  <text x="480" y="58" text-anchor="middle" font-size="11" fill="#9C7A3C">簧管 · 气流使簧片振动</text>
  <rect x="440" y="76" width="80" height="130" rx="6" fill="#17171A" stroke="#9C7A3C" stroke-width="1.6"/>
  <g stroke="#9C7A3C" stroke-width="3">
    <path d="M462,126 L462,170"/><path d="M474,126 L474,170"/>
    <path d="M486,126 L486,170"/><path d="M498,126 L498,170"/>
  </g>
  <path d="M440,110 L520,110" stroke="#9C7A3C" stroke-width="2.6"/>
  <text x="480" y="230" text-anchor="middle" font-size="10.5" fill="#A9A49B">气流使簧片振动，管身起共鸣</text>
  <text x="480" y="252" text-anchor="middle" font-size="10.5" fill="#9C7A3C">小号管 · 双簧管管 · 单簧管管</text>
  <text x="480" y="274" text-anchor="middle" font-size="10.5" fill="#6E6A64">与木管乐器同源的发声方式</text>
  <text x="20" y="292" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">管风琴把"边棱音"与"簧片发声"两种原理都装进了同一台乐器里 —— 这就是它音色极丰富的原因。</text>
</svg>
```

**这张图解释了管风琴为什么音色那么丰富**：
它把木管组的两种发声原理（边棱音与簧片）**都做成了音管** ——
所以它既能模仿长笛，也能模仿小号与双簧管。

## 音域

```range
{"range":"C2–C7","common":"C2–C6","caption":"管风琴的音域（以常见形制为例）","caption_en":"Organ range (a typical instrument)","note":"管风琴属气鸣乐器 —— 键盘控制气阀，气流进入音管使空气柱振动。音域随乐器差别极大，常见约 C2–C7；大型管风琴可超出此范围，也有仅一两个八度的小型乐器。"}
```

- **约 C2–C7**（视乐器），大型乐器可超出。
- **它没有统一的音域标准** —— 每台管风琴都是为所在建筑定制建造的。
  这与[[instrument:piano|钢琴]]（88 键统一）形成极端对照。
- **它的低音可以极低**（大管可达 32 英尺，对应极低的音）。

## 音色与听辨

四条线索：

1. **音可以无限持续**，且**持续期间没有任何衰减**。
   这是它与钢琴、击弦古钢琴最根本的听感差别 ——
   钢琴的音一出来就在衰减，管风琴的音则"立在原地"。
2. **音色随音栓变化极大**。同一台乐器可以像长笛、像小号、像弦乐组。
3. **没有力度层次**。触键不改变音量；音量靠音栓与"渐强箱"（swell box）。
4. **低频有压倒性的分量**。大型管风琴的低声足以震动整个建筑。

```audiolab
{"type":"instrument","gm":"Church Organ","synth":"blown","phrase":["C3","E3","G3","C4","E4","G4"],"label":"管风琴的常用区：C3 到 G4","label_en":"The organ's working register — C3 up to G4","hint":"注意音一旦发出就不再衰减 —— 这是管风琴独有的持续感","hint_en":"Hear that the sound never decays once it starts — an organ's unique sustain."}
```

## 演奏技法

- **触键不改变力度**。音量靠**音栓**与（部分乐器的）**渐强箱**（用踏板控制百叶窗的开合）。
- **连奏是它的核心**。因为音能持续，管风琴的乐句通常靠**手指的重叠**做成无缝隙的连奏。
- **踏板键盘（pedalboard）**：用脚演奏的低音键盘，是管风琴的标配 ——
  这让一个演奏者可以同时演奏三个甚至四个声部。
- **声部独立**。每个音都由独立的音管发声，所以**每个声部都能独立保持与呼吸** ——
  管风琴因此成为最接近"无伴奏合唱"的键盘乐器。

## 家族与近亲

| 乐器 | 发声体 | 键盘语义 | 延音 | 力度可控 |
|---|---|---|---|---|
| **管风琴** | **音管内的空气柱** | **开阀（按住即持续）** | **无限** | 不可（靠音栓） |
| [[instrument:piano\|钢琴]] | 弦 | 击打 | 衰减 | 可 |
| [[instrument:celesta\|钢片琴]] | 钢片 | 击打 | 短 | 可 |
| [[instrument:harmonium\|簧风琴]] | **自由簧** | 气流（脚踏风箱） | 持续 | 部分可 |
| [[instrument:portative-organ\|便携管风琴]] | 空气柱 | 开阀 | 无限 | 不可 |

**管风琴与它的"小型亲族"**（簧风琴 · 便携管风琴 · 手风琴）
构成了一个"**气流 + 键盘**"的家族 —— 它们的差别在**发声体**（音管 vs 自由簧）与**送气方式**。

## 历史演变

| 时期 | 状态 |
|---|---|
| 公元前 3 世纪 | 古希腊的**水压管风琴**已存在 —— 管风琴是键盘乐器的祖辈 |
| 中世纪 | 进入欧洲教堂；早期形制笨重、音域窄、音量大 |
| 14—17 世纪 | 音管与音栓系统逐步复杂化；出现便携与固定两类（见便携管风琴） |
| **17—18 世纪** | **巴洛克管风琴的黄金期**：巴赫等人的作品把它的复调能力推到极致 |
| 19 世纪 | 电动鼓风取代人力；管风琴体型与音量进一步扩大 |
| 20 世纪 | 管风琴复兴运动（回到巴洛克形制）与现代大型管风琴并存 |
| 20 世纪后期至今 | 教堂、音乐厅与音乐学院的固定乐器；也有当代作品 |

**它是键盘乐器里历史最久的一件**（比钢琴早约两千年），
也是唯一一件**与建筑绑定**的乐器 —— 大多数管风琴在建造时就是为那座建筑设计的。
**乐器与空间的关系，在它身上最紧密。**

## 常见误解

- **"管风琴是键盘乐器，所以和钢琴一类。"** 它是**气鸣**（空气柱振动），
  钢琴是**弦鸣**（弦振动）—— 分属两个大类。
- **"它能像钢琴那样控制力度。"** **不能**。触键不改变音量；
  音量靠音栓与渐强箱。这与大键琴的处境类似，但原因不同（一个是拨弦固定，一个是气流固定）。
- **"管风琴很笨重，所以不好用。"** 它确实不可移动，但这正是它的优势：
  它可以按建筑声学定制，得到别处得不到的规模与低频。
- **"它只是教堂乐器。"** 它也是音乐厅与音乐学院的固定乐器，
  且有大量非宗教的独奏与协奏曲目。
- **"它的音色都是"管风琴味"。"** 一台大管风琴的音色范围极广 ——
  它可以接近长笛、弦乐、小号、双簧管等等。

## 下一步

键盘组还剩 3 条，全部属于"**自由簧**"一类：
[[instrument:harmonium|簧风琴]] · [[instrument:accordion|手风琴]] · [[instrument:harmonica|口琴]]。
它们与管风琴同属气鸣，但**发声体从"空气柱"换成了"簧片"** ——
这一换，带来了一整套不同的乐器（也与木管的簧片形成区分）。
:::

::: en
The organ is the largest and most particular member of the keyboard group: **you do not strike a sound-maker
with the keys — you open a door and let the air do the sounding.**

That produces two results no other keyboard instrument has: **a note can sustain indefinitely**, and **every
note is an independent voice.**

| Classification | Value |
|---|---|
| **HS class** | **Aerophone** — **the air columns inside the pipes vibrate** |
| **Sub-type** | Keys open valves · air is fed to pipes · **stops** select pipe sets · unlimited sustain |
| **Family** | Western · Keyboard (aerophone branch) |
| **Bayin** | Not applicable — a Chinese system; the organ is outside it |

> ⚠️ **One conceptual point**: **the organ explains the "keyboard" interface most clearly.**
> On a piano, a key = **a strike** (one action, one sound);
> on an organ, a key = **a valve** (hold it and the sound lasts as long as you hold).
> So an organ keyboard is not a percussion device but a set of **switches** — which also means it **has no
> dynamic control** (loudness comes from wind pressure and stops, not from touch).
> **One interface, two completely different operating semantics.**

## Structure: keys open valves, air sounds

```svg
<svg viewBox="0 0 640 340" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Organ structure: keys open valves, air is fed from the bellows into pipes arranged by pitch, and stops select pipe ranks">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">Organ — structure (keys open valves → air → pipes)</text>
  </g>
  <rect x="60" y="72" width="240" height="30" rx="4" fill="#17171A" stroke="#343439" stroke-width="1.4"/>
  <g stroke="#6E6A64" stroke-width="1.2">
    <path d="M76,72 L76,102"/><path d="M94,72 L94,102"/><path d="M112,72 L112,102"/>
    <path d="M130,72 L130,102"/><path d="M148,72 L148,102"/><path d="M166,72 L166,102"/>
    <path d="M184,72 L184,102"/><path d="M202,72 L202,102"/><path d="M220,72 L220,102"/>
    <path d="M238,72 L238,102"/><path d="M256,72 L256,102"/><path d="M274,72 L274,102"/>
  </g>
  <rect x="60" y="124" width="240" height="34" rx="4" fill="#17171A" stroke="#5B7FA8" stroke-width="1.6"/>
  <g fill="#5B7FA8">
    <rect x="112" y="132" width="10" height="18" rx="3"/>
    <rect x="166" y="132" width="10" height="18" rx="3"/>
    <rect x="220" y="132" width="10" height="18" rx="3"/>
  </g>
  <rect x="60" y="182" width="240" height="30" rx="4" fill="#17171A" stroke="#9C7A3C" stroke-width="1.5"/>
  <g stroke="#9C7A3C" stroke-width="2.4">
    <path d="M100,182 L100,140"/><path d="M150,182 L150,140"/><path d="M200,182 L200,140"/>
    <path d="M250,182 L250,140"/>
  </g>
  <g stroke="#E07A3F" stroke-width="1.8" fill="#17171A">
    <rect x="352" y="60" width="18" height="150" rx="8"/>
    <rect x="382" y="76" width="18" height="134" rx="8"/>
    <rect x="412" y="94" width="18" height="116" rx="8"/>
    <rect x="442" y="110" width="18" height="100" rx="8"/>
    <rect x="472" y="124" width="18" height="86" rx="8"/>
    <rect x="502" y="136" width="18" height="74" rx="8"/>
    <rect x="532" y="146" width="18" height="64" rx="8"/>
  </g>
  <path d="M340,210 L560,210" stroke="#343439" stroke-width="3"/>
  <g class="lead" stroke="#6E6A64" stroke-width=".9">
    <path d="M186,56 L186,66"/><path d="M186,124 L186,118"/>
    <path d="M186,232 L186,218"/><path d="M486,42 L486,54"/>
    <path d="M186,300 L280,214"/>
  </g>
  <g font-family="system-ui,sans-serif" font-size="11" fill="#A9A49B">
    <text x="180" y="53" text-anchor="end">Keys (switches, not hammers)</text>
    <text x="180" y="121" text-anchor="end" fill="#5B7FA8">Valves (opened by keys)</text>
    <text x="180" y="235" text-anchor="end" fill="#9C7A3C">Bellows / blower</text>
    <text x="492" y="39" fill="#E07A3F">Pipes (longer = lower)</text>
    <text x="180" y="303" text-anchor="end">Stops (which ranks sound)</text>
  </g>
  <text x="20" y="266" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">Air is delivered continuously, so holding a key sustains the note — why an organ can hold a note forever.</text>
  <text x="20" y="288" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">Pitch is set by pipe length; one pitch can have several pipes of different lengths and shapes — that is a stop.</text>
  <text x="20" y="316" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">So an organ is not one instrument but a whole group of them controlled by one keyboard.</text>
</svg>
```

Three points:

1. **Keys are switches, not hammers.** Hold the key and the note lasts — the only keyboard instrument that can
   **sustain a note indefinitely**.
2. **Pipes are grouped by pitch and colour.** One pitch may have several kinds of pipe (flute, string, reed) —
   selected by **stops**, the source of its huge colour range.
3. **It is really a group of instruments.** A large organ may hold thousands of pipes and dozens of stops,
   controlled from one keyboard.

## Two great classes of pipe

```svg
<svg viewBox="0 0 640 300" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="The two classes of organ pipe: flue pipes sound by an air jet cutting an edge, reed pipes by air vibrating a reed">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">Two classes of pipe: flue and reed</text>
  </g>
  <text x="150" y="58" text-anchor="middle" font-size="11" fill="#5B7FA8">Flue pipe · jet cuts an edge</text>
  <rect x="110" y="76" width="80" height="130" rx="6" fill="#17171A" stroke="#5B7FA8" stroke-width="1.6"/>
  <path d="M110,140 L190,140" stroke="#5B7FA8" stroke-width="2.6"/>
  <path d="M150,152 C170,158 182,170 186,186" fill="none" stroke="#E07A3F" stroke-width="2.4"/>
  <path d="M178,180 L188,190 L176,192 Z" fill="#E07A3F"/>
  <text x="150" y="230" text-anchor="middle" font-size="10.5" fill="#A9A49B">no reed; the jet itself sounds</text>
  <text x="150" y="252" text-anchor="middle" font-size="10.5" fill="#5B7FA8">flute · string · principal</text>
  <text x="150" y="274" text-anchor="middle" font-size="10.5" fill="#6E6A64">the majority of organ pipes</text>
  <text x="480" y="58" text-anchor="middle" font-size="11" fill="#9C7A3C">Reed pipe · air vibrates a reed</text>
  <rect x="440" y="76" width="80" height="130" rx="6" fill="#17171A" stroke="#9C7A3C" stroke-width="1.6"/>
  <g stroke="#9C7A3C" stroke-width="3">
    <path d="M462,126 L462,170"/><path d="M474,126 L474,170"/>
    <path d="M486,126 L486,170"/><path d="M498,126 L498,170"/>
  </g>
  <path d="M440,110 L520,110" stroke="#9C7A3C" stroke-width="2.6"/>
  <text x="480" y="230" text-anchor="middle" font-size="10.5" fill="#A9A49B">the reed sounds; the pipe resonates</text>
  <text x="480" y="252" text-anchor="middle" font-size="10.5" fill="#9C7A3C">trumpet · oboe · clarinet stops</text>
  <text x="480" y="274" text-anchor="middle" font-size="10.5" fill="#6E6A64">the same principle as woodwinds</text>
  <text x="20" y="292" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">An organ builds both woodwind principles — edge-tone and reed — into pipes. Hence its enormous colour range.</text>
</svg>
```

**This diagram explains why an organ's colours are so wide**: it turns **both** woodwind sound-producing
principles (edge-tone and reed) into pipes — so it can imitate a flute, a trumpet or an oboe.

## Range

```range
{"range":"C2–C7","common":"C2–C6","caption":"管风琴的音域（以常见形制为例）","caption_en":"Organ range (a typical instrument)","note":"管风琴属气鸣乐器 —— 键盘控制气阀，气流进入音管使空气柱振动。音域随乐器差别极大，常见约 C2–C7；大型管风琴可超出此范围，也有仅一两个八度的小型乐器。"}
```

- **About C2–C7** depending on the instrument; large organs exceed it.
- **There is no standard range** — every organ is built to fit its building, the exact opposite of the
  [[instrument:piano|piano]]'s uniform 88 keys.
- **Its bass can go extremely low** (32-foot pipes reach the bottom of the audible range).

## Timbre, and how to hear it

Four cues:

1. **A note can sustain indefinitely with no decay.** The most fundamental difference from a piano or
   clavichord: a piano's note decays the moment it starts, an organ's "stands still".
2. **Colour varies enormously with the stops.** One instrument can sound like flutes, trumpets or a string
   section.
3. **No dynamic layering.** Touch does not change volume; that comes from stops and (on some instruments) a
   swell box.
4. **Overwhelming low-frequency weight.** A large organ's bass can shake a building.

```audiolab
{"type":"instrument","gm":"Church Organ","synth":"blown","phrase":["C3","E3","G3","C4","E4","G4"],"label":"管风琴的常用区：C3 到 G4","label_en":"The organ's working register — C3 up to G4","hint":"注意音一旦发出就不再衰减 —— 这是管风琴独有的持续感","hint_en":"Hear that the sound never decays once it starts — an organ's unique sustain."}
```

## Playing techniques

- **Touch does not change dynamics.** Volume comes from **stops** and (where fitted) a **swell box**
  (pedal-controlled shutters).
- **Legato is central.** Because notes sustain, organ phrasing is usually built by **overlapping fingers** to
  make a seamless line.
- **The pedalboard**: a keyboard played with the feet, standard on organs — letting one player perform three or
  even four parts at once.
- **Independent voices**: every note comes from its own pipes, so **each voice can sustain and breathe on its
  own** — making the organ the keyboard instrument closest to unaccompanied choral singing.

## The family

| Instrument | Vibrating body | Key semantics | Sustain | Dynamics |
|---|---|---|---|---|
| **Organ** | **air columns in pipes** | **valve (hold = sustain)** | **unlimited** | no (stops instead) |
| [[instrument:piano\|Piano]] | strings | strike | decaying | yes |
| [[instrument:celesta\|Celesta]] | steel plates | strike | short | yes |
| [[instrument:harmonium\|Harmonium]] | **free reeds** | air (foot bellows) | sustained | partly |
| [[instrument:portative-organ\|Portative organ]] | air columns | valve | unlimited | no |

**The organ and its smaller relatives** (harmonium, portative organ, accordion) form a "**air + keyboard**"
family — distinguished by **the vibrating body** (pipes versus free reeds) and **how the air is supplied**.

## History

| Period | State |
|---|---|
| 3rd c. BCE | the Greek **water organ** already exists — the organ is the ancestor of keyboard instruments |
| Middle Ages | enters European churches; early forms are bulky, narrow-ranged and very loud |
| 14th–17th c. | pipes and stop systems grow complex; portable and fixed types diverge (see portative organ) |
| **17th–18th c.** | **the golden age of the Baroque organ**: Bach and others push its polyphony to the limit |
| 19th c. | electric blowers replace manual pumping; organs grow larger and louder |
| 20th c. | the organ reform movement (back to Baroque models) coexists with modern large instruments |
| Late 20th c. onward | a fixed instrument of churches, halls and conservatories; also contemporary works |

**It is the oldest keyboard instrument** (some two thousand years older than the piano), and the only one
**bound to a building** — most organs are designed for the space they stand in.
**Nowhere else is the relationship between instrument and architecture so close.**

## Common misconceptions

- **"The organ is a keyboard instrument, so it is like a piano."** It is an **aerophone** (air columns vibrate);
  the piano is a **chordophone** (strings) — two different classes.
- **"It can control dynamics like a piano."** It **cannot**. Touch does not change volume; that comes from stops
  and the swell box. A situation comparable to the harpsichord's, though the cause differs (plucking is fixed;
  so is wind).
- **"Being immovable makes it impractical."** That immobility is its advantage: it can be built to a building's
  acoustics, achieving scale and low frequency nothing else can.
- **"It is only a church instrument."** It is also a fixture of concert halls and conservatories, with a large
  non-religious solo and concerto repertoire.
- **"It has only one organ sound."** A large organ's range is enormous — close to flutes, strings, trumpets,
  oboes and more.

## Next

Three keyboard entries remain, all in the **free-reed** family: the [[instrument:harmonium|harmonium]], the
[[instrument:accordion|accordion]] and the [[instrument:harmonica|harmonica]]. Like the organ they are
aerophones — but **the vibrating body changes from an air column to a reed**, and that one change produces a
whole different set of instruments (also distinguishing them from woodwind reeds).
:::


