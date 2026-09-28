---
id: ocarina
site: inst
cat: I2
title: 陶笛
title_en: Ocarina
summary: 闭腔乐器，音高由腔体容积与开孔面积决定，因此形状极自由
summary_en: A closed-vessel flute whose pitch comes from cavity volume and hole area — hence its free shape
level: standard
tags: [乐器, 木管, 西洋]
tags_en: [instrument, woodwind, western]
alias: [陶笛, ocarina, 洋埙, 奥卡利那笛]
order: 40
links:
  - "[[concept:interval]]"
  - "[[concept:register]]"
  - "[[concept:timbre]]"
  - "[[concept:articulation]]"
  - "[[instrument:recorder]]"
  - "[[instrument:pan-flute]]"
  - "[[instrument:flute]]"
instances:
  - pdmx-001402 | G 大调竖笛奏鸣曲 —— **竖笛**演奏；同为哨嘴驱动的无簧木管，音色可互相参照
  - pdmx-002065 | 为竖笛与长笛而作的协奏曲 —— 对照"哨嘴"与"嘴唇"两种边棱音
  - giantmidi-000507 | C 小调竖笛协奏曲 —— 同类激振的独奏写法
sources:
  - 结构依通行制琴资料：多为陶制（也有塑料、木、金属），呈**闭腔**形状，带哨嘴风道与若干指孔；无键
  - 「陶笛属闭腔气鸣乐器，音高由腔体容积与开孔总面积决定，而非有效管长」依 Hornbostel–Sachs 分类与管乐器声学
  - 「十二孔陶笛（中音 C 调）音域约 A4–F6」依通行乐器资料；不同型号差异较大
  - 「19 世纪意大利由 Donati 等人改良定型为现代陶笛；同类闭腔乐器在世界多地古已有之」依乐器史
  - ⚠️ 库内没有标题可确认为陶笛的曲目 —— 本条给出的是**同为哨嘴驱动的竖笛**曲目作音色参照，音色由试听件负责
updated: 2026-09-26
---

::: zh
陶笛在所有木管里是个"异类"：**它的音高不是由管子长度决定的。**
它是**闭腔乐器**（vessel flute）—— 一个封闭的腔体，音高由**腔体容积**与**开孔总面积**共同决定。

这一条解释了它最显眼的特点：**形状可以做得千奇百怪**。因为约束它的不是"必须有多长"，
而是"必须有多大容积"。

| 分类 | 归属 |
|---|---|
| **HS 分类** | **气鸣**（Aerophone）· 边棱音（哨嘴 / 风道驱动）· **闭腔** |
| **次级类型** | 竖吹 · 无簧片 · 哨嘴风道 · 指孔，无键 · 多为陶制 |
| **所属族** | 西洋 · 木管（哨嘴族 · 闭腔支系） |
| **八音** | 不适用 —— 周代八音是中国乐器的体系；中国的同类乐器是埙（属土），见中国乐器部分 |

> ⚠️ **一个概念上的要点**：管乐器（如[[instrument:flute|长笛]]）的音高由**有效管长**决定 ——
> 所以它必须是"一个长条"。
> **闭腔乐器**（陶笛）的音高由**容积 + 开孔面积**决定 —— 所以它可以是圆的、椭圆的、动物的、星形的。
> **判断一件气鸣乐器属于哪一类，看的是"什么在决定音高"，而不是它长什么样。**
> 这条判据在木管里只有两三个例外，陶笛是最典型的一个。

## 结构：一个腔，几个孔

```svg
<svg viewBox="0 0 640 320" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="陶笛的闭腔结构：椭圆形腔体、哨嘴风道、前方的方形指孔与侧面的音孔">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">陶笛 · 闭腔结构（腔体容积决定音区，开孔面积决定音高）</text>
  </g>
  <ellipse cx="330" cy="180" rx="118" ry="86" fill="#17171A" stroke="#343439" stroke-width="1.6"/>
  <ellipse cx="330" cy="180" rx="98" ry="68" fill="#0E0E10" stroke="#5B7FA8" stroke-width="1.2"/>
  <path d="M232,116 C210,104 206,86 214,74 L244,74 C238,88 242,102 254,110 Z" fill="#17171A" stroke="#343439" stroke-width="1.4"/>
  <rect x="212" y="70" width="36" height="8" rx="2.4" fill="#E8C547"/>
  <g fill="#070706" stroke="#9C7A3C" stroke-width="1.4">
    <rect x="286" y="206" width="20" height="20" rx="9"/>
    <rect x="318" y="212" width="20" height="20" rx="9"/>
    <rect x="350" y="206" width="20" height="20" rx="9"/>
    <rect x="300" y="176" width="20" height="20" rx="9"/>
    <rect x="336" y="176" width="20" height="20" rx="9"/>
    <rect x="368" y="182" width="18" height="18" rx="8"/>
    <rect x="264" y="180" width="18" height="18" rx="8"/>
  </g>
  <g fill="#070706" stroke="#9C7A3C" stroke-width="1.2">
    <circle cx="368" cy="140" r="6"/><circle cx="396" cy="212" r="6"/>
  </g>
  <g class="lead" stroke="#6E6A64" stroke-width=".9">
    <path d="M186,64 L230,64"/><path d="M186,124 L216,124"/>
    <path d="M186,216 L256,216"/><path d="M186,290 L300,252"/>
    <path d="M486,180 L446,182"/><path d="M486,266 L428,238"/>
  </g>
  <g font-family="system-ui,sans-serif" font-size="11" fill="#A9A49B">
    <text x="180" y="67" text-anchor="end">哨嘴 + 风道</text>
    <text x="180" y="127" text-anchor="end" fill="#E8C547">棱边</text>
    <text x="180" y="219" text-anchor="end">指孔（方形或圆形）</text>
    <text x="180" y="293" text-anchor="end">体积决定基础音区</text>
    <text x="492" y="183">音孔（用于高音）</text>
    <text x="492" y="269">开孔总面积决定音高</text>
  </g>
  <text x="20" y="308" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">没有"管长"这回事 —— 所以同一容积的陶笛可以做成圆、椭圆、动物或任何形状，音准不受影响。</text>
</svg>
```

三处要点：

1. **驱动方式与[[instrument:recorder|竖笛]]相同**（哨嘴风道 + 边棱音），
   但**共鸣的方式不同**：一个用管，一个用腔。
2. **音高与"开孔总面积"有关**，所以孔的大小和数量都很关键 ——
   这也是陶笛的孔常做成**方形**（方便精确控制面积）的原因之一。
3. **没有"管长"这个约束**，所以外形完全自由 —— 动物造型、星星造型都能做成乐器。

## 管 vs 腔：为什么形状能自由

```svg
<svg viewBox="0 0 640 300" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="管乐器与闭腔乐器的对比：管乐器的音高由有效管长决定，闭腔乐器由容积与开孔面积决定">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">音高由什么决定，决定了乐器必须长什么样</text>
  </g>
  <text x="160" y="62" text-anchor="middle" font-size="11" fill="#6E6A64">管乐器（长笛 · 竖笛 · 单簧管）</text>
  <rect x="60" y="96" width="200" height="30" rx="4" fill="#17171A" stroke="#5B7FA8" stroke-width="1.5"/>
  <g fill="#070706" stroke="#9C7A3C" stroke-width="1.2">
    <circle cx="110" cy="111" r="6"/><circle cx="140" cy="111" r="6"/>
    <circle cx="170" cy="111" r="6"/><circle cx="200" cy="111" r="6"/>
  </g>
  <path d="M60,152 L260,152" stroke="#343439" stroke-width="1"/>
  <text x="160" y="176" text-anchor="middle" font-size="10.5" fill="#5B7FA8">音高 ← 有效管长</text>
  <text x="160" y="200" text-anchor="middle" font-size="10.5" fill="#A9A49B">必须是一个长条</text>
  <text x="480" y="62" text-anchor="middle" font-size="11" fill="#6E6A64">闭腔乐器（陶笛）</text>
  <ellipse cx="420" cy="140" rx="66" ry="54" fill="#17171A" stroke="#E07A3F" stroke-width="1.5"/>
  <circle cx="480" cy="140" r="48" fill="none" stroke="#242427" stroke-width="1" stroke-dasharray="3 3"/>
  <ellipse cx="530" cy="140" rx="46" ry="54" fill="#17171A" stroke="#E07A3F" stroke-width="1.5"/>
  <text x="480" y="216" text-anchor="middle" font-size="10.5" fill="#E07A3F">音高 ← 容积 + 开孔面积</text>
  <text x="480" y="240" text-anchor="middle" font-size="10.5" fill="#A9A49B">形状随意，容积一致即可</text>
  <text x="20" y="272" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">左边必须"长"，右边只要"够大" —— 所以陶笛能被做成动物、星星或任何造型，音准不受外形影响。</text>
</svg>
```

**这条差别还带来一个音域上的后果**：闭腔乐器的音域通常**比同体积的管乐器窄** ——
因为管内可以靠开孔不断改变有效长度，而腔体一旦定了容积，能变化的余量就有限。
陶笛的典型音域因此只有**一个半八度左右**。

## 音域

```range
{"range":"A4–F6","common":"C5–C6","caption":"十二孔陶笛（中音 C 调）的音域","caption_en":"Twelve-hole C ocarina range","note":"陶笛是闭腔乐器，音域随型号差异很大；这里以常见的十二孔中音 C 调陶笛为例，约 A4–F6（一个半八度）。记谱即实音，不移调。"}
```

- **约 A4–F6**，一个半八度 —— **比同体积的管乐器窄**，这是闭腔的代价。
- **常用区 C5–C6**：中音区最稳，也是旋律主要活动的地方。
- **不同型号差异极大**：从很小的哨子形陶笛（几个音）到较大的低音陶笛（一个八度多），
  尺寸与音域不成简单比例。

## 音色与听辨

四条线索：

1. **圆润、清亮、带一点"哨音"**。它比[[instrument:recorder|竖笛]]更"圆"，
   泛音更少，接近一个近乎纯音的音色。
2. **音域窄，所以很"统一"**。整件乐器里没有一个音区是特别暗或特别亮的。
3. **音量小、投射弱**。它适合独奏、录音与小场合，很难在大编制里担当声部。
4. **高音靠小孔与气息**。上方几个音需要精确的气流控制，音量也会明显变小。

```audiolab
{"type":"instrument","gm":"Ocarina","synth":"blown","phrase":["C5","E5","G5","C6","E6","F6"],"label":"陶笛的常用区：C5 到 F6","label_en":"The ocarina's working register — C5 up to F6","hint":"注意音色的圆润与近乎纯音的干净 —— 闭腔乐器泛音少，所以听起来「没有棱角」","hint_en":"Hear how round and nearly pure it is — a closed vessel has few harmonics, so the sound has no edges."}
```

## 演奏技法

- **指法密集**。因为音孔少、音域窄，跨音域常常要靠**交叉指法**与气息配合。
- **半孔与滑音**。用手指在孔上滑入滑出可以得到滑音 —— 陶笛上很常用。
- **俯吹（bending）**：靠改变吹气角度压低音高，可以得到约一个半音的滑动。
- **持握方式多样**。十二孔陶笛常用双手十指按孔，所以它的持握姿势与竖笛差别很大。

## 家族与近亲

| 乐器 | 驱动 | 共鸣 | 音高由什么定 | 音域 |
|---|---|---|---|---|
| [[instrument:recorder\|竖笛]] | 哨嘴风道 | 管 | 有效管长 | 约两个八度 |
| **陶笛** | 哨嘴风道 | **闭腔** | **容积 + 开孔面积** | 约一个半八度 |
| [[instrument:pan-flute\|排箫]] | 嘴唇 | 多根**闭管** | 每根管的长度 | 视管数 |
| [[instrument:flute\|长笛]] | 嘴唇 | 管 | 有效管长 | 超过三个八度 |

**注意陶笛与[[instrument:pan-flute|排箫]]都是"闭"的，但闭的方式不同**：
陶笛闭的是**腔**（音高看容积），排箫闭的是**管**（音高看管长，且只能产生奇次泛音）。
**"闭"这个字在这两件乐器上指的不是同一件事。**

## 历史演变

| 时期 | 状态 |
|---|---|
| 古代 | 世界多地都有闭腔陶制吹奏乐器：中国的**埙**、中美洲的陶哨、非洲的陶制吹器 —— 独立出现 |
| 19 世纪（意大利） | **Donati** 等人把这类乐器改良定型为「ocarina」（意大利语"小鹅"，因形似），十二孔、可吹完整音阶的现代形制由此成立 |
| 19 世纪末—20 世纪 | 作为普及型乐器在欧洲与美洲流传；也进入军乐队（陶笛乐队曾一度流行） |
| 20 世纪后期至今 | 因电子游戏与影视配乐的使用而重新流行；同时成为世界范围内常见的普及乐器 |

## 常见误解

- **"陶笛和竖笛是一样的，只是材质不同。"** 材质不是关键 ——
  **共鸣方式不同**：竖笛是**管**（音高看管长），陶笛是**闭腔**（音高看容积）。
- **"陶笛是玩具。"** 它是**完整的闭腔气鸣乐器**，有明确的分类地位与成体系的指法；
  作为普及乐器只是它的一种使用场景。
- **"形状做成动物会影响音准。"** 只要**容积**与**开孔面积**不受影响，外形怎么变都不影响音准 ——
  这正是闭腔乐器的特点。
- **"它的音域和长笛差不多。"** 陶笛典型音域只有约**一个半八度**，
  闭腔限制了它可变化的空间。
- **"中国的埙就是陶笛。"** 两者**都是闭腔陶制吹奏乐器**，属同类思路，
  但形制、指法与历史传统各自独立 —— **相似不等于同源**（见中国乐器部分）。

## 下一步

木管这条线的最后一条是 [[instrument:pan-flute|排箫]] ——
它也是"闭"的，但闭的是**管**而不是腔；而且它是**世界性的乐器**，
从古希腊到安第斯山脉都有它的身影。

这三件（[[instrument:recorder|竖笛]] · 陶笛 · 排箫）讲完，木管组就正式收口了。
:::

::: en
The ocarina is the odd one out among woodwinds: **its pitch is not set by the length of a tube.** It is a
**closed-vessel flute** — an enclosed cavity, with pitch determined by the **volume of the cavity** and the
**total area of the open holes**.

That single fact explains its most obvious trait: **its shape can be anything.** What constrains it is not
"how long must it be" but "how large must the volume be".

| Classification | Value |
|---|---|
| **HS class** | **Aerophone** · edge-tone (duct drive) · **closed vessel** |
| **Sub-type** | Vertical · reedless · duct head · finger holes, keyless · usually ceramic |
| **Family** | Western · Woodwinds (duct family, vessel branch) |
| **Bayin** | Not applicable — a Chinese system; the Chinese relative is the *xun* (an earth instrument), covered with Chinese instruments |

> ⚠️ **One conceptual point**: a tube instrument such as the [[instrument:flute|flute]] has its pitch set by
> **effective tube length**, so it must be a long shape. A **vessel** instrument has its pitch set by
> **volume plus hole area**, so it can be round, oval, animal-shaped or star-shaped.
> **To place an aerophone, ask what determines the pitch — not what it looks like.**
> There are only a few exceptions in the woodwind group, and the ocarina is the classic one.

## Structure: one cavity, a few holes

```svg
<svg viewBox="0 0 640 320" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="The ocarina's closed-vessel structure: an oval cavity, duct head, square finger holes on the front and small tone holes at the side">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">Ocarina — a closed vessel (volume sets the register, hole area sets the pitch)</text>
  </g>
  <ellipse cx="330" cy="180" rx="118" ry="86" fill="#17171A" stroke="#343439" stroke-width="1.6"/>
  <ellipse cx="330" cy="180" rx="98" ry="68" fill="#0E0E10" stroke="#5B7FA8" stroke-width="1.2"/>
  <path d="M232,116 C210,104 206,86 214,74 L244,74 C238,88 242,102 254,110 Z" fill="#17171A" stroke="#343439" stroke-width="1.4"/>
  <rect x="212" y="70" width="36" height="8" rx="2.4" fill="#E8C547"/>
  <g fill="#070706" stroke="#9C7A3C" stroke-width="1.4">
    <rect x="286" y="206" width="20" height="20" rx="9"/>
    <rect x="318" y="212" width="20" height="20" rx="9"/>
    <rect x="350" y="206" width="20" height="20" rx="9"/>
    <rect x="300" y="176" width="20" height="20" rx="9"/>
    <rect x="336" y="176" width="20" height="20" rx="9"/>
    <rect x="368" y="182" width="18" height="18" rx="8"/>
    <rect x="264" y="180" width="18" height="18" rx="8"/>
  </g>
  <g fill="#070706" stroke="#9C7A3C" stroke-width="1.2">
    <circle cx="368" cy="140" r="6"/><circle cx="396" cy="212" r="6"/>
  </g>
  <g class="lead" stroke="#6E6A64" stroke-width=".9">
    <path d="M186,64 L230,64"/><path d="M186,124 L216,124"/>
    <path d="M186,216 L256,216"/><path d="M186,290 L300,252"/>
    <path d="M486,180 L446,182"/><path d="M486,266 L428,238"/>
  </g>
  <g font-family="system-ui,sans-serif" font-size="11" fill="#A9A49B">
    <text x="180" y="67" text-anchor="end">Duct head</text>
    <text x="180" y="127" text-anchor="end" fill="#E8C547">Edge</text>
    <text x="180" y="219" text-anchor="end">Finger holes (square or round)</text>
    <text x="180" y="293" text-anchor="end">Volume sets the register</text>
    <text x="492" y="183">Small holes for the top</text>
    <text x="492" y="269">Hole area sets the pitch</text>
  </g>
  <text x="20" y="308" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">There is no tube length — so one volume can be a ball, an egg, an animal, and still play in tune.</text>
</svg>
```

Three points:

1. **The drive matches the [[instrument:recorder|recorder]]** (duct plus edge), but the **resonance differs**:
   one uses a tube, the other a vessel.
2. **Pitch relates to the total open hole area**, so the size and number of holes matter — part of why
   ocarina holes are often **square**, to control area precisely.
3. **There is no "tube length" constraint**, so the body shape is entirely free — animals and stars included.

## Tube versus vessel: why the shape is free

```svg
<svg viewBox="0 0 640 300" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Tube instrument versus vessel instrument: the tube's pitch comes from effective length, the vessel's from volume and hole area">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">What sets the pitch also sets what the instrument must look like</text>
  </g>
  <text x="160" y="62" text-anchor="middle" font-size="11" fill="#6E6A64">Tube (flute · recorder · clarinet)</text>
  <rect x="60" y="96" width="200" height="30" rx="4" fill="#17171A" stroke="#5B7FA8" stroke-width="1.5"/>
  <g fill="#070706" stroke="#9C7A3C" stroke-width="1.2">
    <circle cx="110" cy="111" r="6"/><circle cx="140" cy="111" r="6"/>
    <circle cx="170" cy="111" r="6"/><circle cx="200" cy="111" r="6"/>
  </g>
  <path d="M60,152 L260,152" stroke="#343439" stroke-width="1"/>
  <text x="160" y="176" text-anchor="middle" font-size="10.5" fill="#5B7FA8">pitch ← effective length</text>
  <text x="160" y="200" text-anchor="middle" font-size="10.5" fill="#A9A49B">so it must be long</text>
  <text x="480" y="62" text-anchor="middle" font-size="11" fill="#6E6A64">Vessel (ocarina)</text>
  <ellipse cx="420" cy="140" rx="66" ry="54" fill="#17171A" stroke="#E07A3F" stroke-width="1.5"/>
  <circle cx="480" cy="140" r="48" fill="none" stroke="#242427" stroke-width="1" stroke-dasharray="3 3"/>
  <ellipse cx="530" cy="140" rx="46" ry="54" fill="#17171A" stroke="#E07A3F" stroke-width="1.5"/>
  <text x="480" y="216" text-anchor="middle" font-size="10.5" fill="#E07A3F">pitch ← volume + hole area</text>
  <text x="480" y="240" text-anchor="middle" font-size="10.5" fill="#A9A49B">any shape, one volume</text>
  <text x="20" y="272" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">Left must be long; right only needs to be big enough — so an ocarina can look like anything, in tune.</text>
</svg>
```

**One further consequence for range**: a vessel instrument is usually **narrower in range than a tube of
similar bulk** — a tube keeps changing its effective length as holes open, while a cavity of fixed volume
offers only limited variation. A typical ocarina therefore spans about **an octave and a half**.

## Range

```range
{"range":"A4–F6","common":"C5–C6","caption":"十二孔陶笛（中音 C 调）的音域","caption_en":"Twelve-hole C ocarina range","note":"陶笛是闭腔乐器，音域随型号差异很大；这里以常见的十二孔中音 C 调陶笛为例，约 A4–F6（一个半八度）。记谱即实音，不移调。"}
```

- **About A4–F6**, an octave and a half — **narrower than a tube of similar bulk**, the vessel's price.
- **The working register is C5–C6**, the steadiest part and where melodies mostly live.
- **Different sizes vary widely**: from tiny whistle-shaped instruments with a few notes to large bass
  ocarinas with a little over an octave; size and range are not simply proportional.

## Timbre, and how to hear it

Four cues:

1. **Round, clear, faintly whistling.** Rounder than a [[instrument:recorder|recorder]] and with fewer
   harmonics — close to a near-pure tone.
2. **One uniform colour.** A narrow range means no register is notably dark or bright.
3. **Quiet and weakly projecting.** Good for solo, recording and small rooms; hard to give it a part in a
   large ensemble.
4. **The top comes from small holes and fine air control**, and it turns noticeably softer up there.

```audiolab
{"type":"instrument","gm":"Ocarina","synth":"blown","phrase":["C5","E5","G5","C6","E6","F6"],"label":"陶笛的常用区：C5 到 F6","label_en":"The ocarina's working register — C5 up to F6","hint":"注意音色的圆润与近乎纯音的干净 —— 闭腔乐器泛音少，所以听起来「没有棱角」","hint_en":"Hear how round and nearly pure it is — a closed vessel has few harmonics, so the sound has no edges."}
```

## Playing techniques

- **Dense fingering.** With few holes and a narrow range, crossing registers often needs **cross
  fingerings** plus air control.
- **Half-holes and slides.** Sliding a finger on and off a hole gives a glissando, much used on ocarinas.
- **Bending**: changing the blowing angle lowers the pitch by roughly a semitone.
- **Varied holds.** A twelve-hole ocarina is held with all ten fingers, quite unlike a recorder.

## The family

| Instrument | Drive | Resonator | Pitch set by | Range |
|---|---|---|---|---|
| [[instrument:recorder\|Recorder]] | duct head | tube | effective length | about two octaves |
| **Ocarina** | duct head | **closed vessel** | **volume + hole area** | about 1.5 octaves |
| [[instrument:pan-flute\|Pan flute]] | lips | several **closed tubes** | each tube's length | depends on tube count |
| [[instrument:flute\|Flute]] | lips | tube | effective length | over three octaves |

**Note that the ocarina and the [[instrument:pan-flute|pan flute]] are both "closed", but differently**:
the ocarina closes a **cavity** (pitch by volume), the pan flute closes **tubes** (pitch by length, and only
odd harmonics). **"Closed" does not mean the same thing for the two.**

## History

| Period | State |
|---|---|
| Antiquity | closed ceramic wind instruments appear independently worldwide: the Chinese **xun**, Mesoamerican clay whistles, African ceramic pipes |
| 19th c. (Italy) | **Donati** and others refine the type into the modern "ocarina" (Italian for "little goose", from its shape): twelve holes and a full scale |
| Late 19th–20th c. | spreads as a popular instrument in Europe and the Americas; also used in military bands (ocarina bands were once a fashion) |
| Late 20th c. onward | revived by video-game and film scores; also a widely played instrument worldwide |

## Common misconceptions

- **"An ocarina is a recorder made of clay."** Material is not the point — the **resonance differs**: a
  recorder is a **tube** (pitch by length), an ocarina a **closed vessel** (pitch by volume).
- **"An ocarina is a toy."** It is a **complete closed-vessel aerophone** with a real classification and a
  systematic fingering; being popular is only one of its uses.
- **"An animal shape would ruin the tuning."** As long as **volume and hole area** are unaffected, the
  outline can be anything — that is precisely the vessel's property.
- **"Its range is about the same as a flute's."** A typical ocarina spans about **an octave and a half**;
  the vessel limits how much can vary.
- **"The Chinese xun is an ocarina."** Both are **closed ceramic wind instruments** and share the same idea,
  but their forms, fingerings and traditions are independent — **resemblance is not common origin** (see
  Chinese instruments).

## Next

The last entry on this line is the [[instrument:pan-flute|pan flute]] — also "closed", but as a set of
**tubes** rather than a cavity, and a genuinely **worldwide** instrument, from ancient Greece to the Andes.

With the [[instrument:recorder|recorder]], the ocarina and the pan flute, the woodwind group closes.
:::
