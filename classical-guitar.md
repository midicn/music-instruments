---
id: classical-guitar
site: inst
cat: I1
title: 古典吉他
title_en: Classical Guitar
summary: 六根尼龙弦、扇形音梁，用指甲拨弦的抱持式拨弦乐器
summary_en: Six nylon strings, fan bracing, and a plucking hand that uses the fingernails
level: core
tags: [乐器, 弦乐, 西洋]
tags_en: [instrument, strings, western]
alias: [古典吉他, classical guitar, 尼龙弦吉他, 西班牙吉他, guitar]
order: 14
links:
  - "[[concept:register]]"
  - "[[concept:clef]]"
  - "[[concept:concert-pitch]]"
  - "[[concept:timbre]]"
  - "[[concept:articulation]]"
  - "[[concept:harmonic-series]]"
  - "[[instrument:acoustic-guitar]]"
  - "[[instrument:ukulele]]"
  - "[[instrument:mandolin]]"
  - "[[instrument:lute]]"
instances:
  - giantmidi-003765 | Sor 的吉他教程曲 —— 古典吉他教学传统的源头之一，织体清楚、一句一个句法
  - giantmidi-004331 | Molitor 的吉他奏鸣曲 —— 把吉他当独奏乐器写的作品，能听出低音与旋律同时在走
  - giantmidi-000144 | Barrios 的 G 小调练习曲 —— 南美一路的吉他写作，泛音与轮指前的准备
  - giantmidi-006958 | Kreutzer 以莫扎特主题写的吉他变奏曲，可听主题如何在吉他上被拆成低音加旋律
  - giantmidi-003738 | Carulli 的小二重奏 —— 两把吉他对话，对照单把吉他时的声部处理
sources:
  - 琴体尺寸取通行制琴数据：琴体长 480 毫米、上腰宽 285、腰宽 225、下腰宽 355 毫米，弦长 650 毫米
  - 定弦 E–A–D–G–B–E（除三度外均为四度）与「记谱比实音高一个八度」属通行乐器学常识，本文为原创表述
  - 扇形音梁（fan bracing）为尼龙弦吉他常用结构、X 形音梁为钢弦吉他常用结构，依通行制琴工艺叙述
  - 音域数据依通行乐谱与乐器词典，本文为原创表述
updated: 2026-09-25
---

::: zh
古典吉他是**抱在怀里、用指尖拨弦**的六弦乐器。它的全部特征都指向同一个目的：
用一个不大的木箱子，把六根弦的振动变成**能同时听清几个声部**的声音。

它也是吉他族里最"传统"的一件：尼龙弦、扇形音梁、用指甲而不是拨片发音、
按实音高一个八度记谱。

| 分类 | 归属 |
|---|---|
| **HS 分类** | **弦鸣**（Chordophone）—— 发声体是弦本身 |
| **次级类型** | 拨奏（手指拨弦）· 有颈、有板腔共鸣箱、有品 |
| **所属族** | 西洋 · 弦乐（弹拨支系） |
| **八音** | 不适用 —— 周代八音是中国乐器的体系，古典吉他不在其中 |

## 结构：吉他的腰为什么这么浅

```svg
<svg viewBox="0 0 640 430" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="古典吉他外形与主要部件：琴头、弦轴、指板与品、音孔、琴码、面板、音梁位置与琴桥">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">古典吉他 · 外形与主要部件（六根尼龙弦）</text>
  </g>
  <!-- 琴颈与指板 -->
  <path d="M306,86 L334,86 L343,224 L297,224 Z" fill="#0E0E10"/>
  <g stroke="#343439" stroke-width=".9">
    <path d="M298,116 L342,116"/><path d="M299,146 L341,146"/><path d="M300,176 L340,176"/>
    <path d="M301,206 L339,206"/>
  </g>
  <!-- 琴头与弦轴 -->
  <path d="M306,44 L334,44 L336,86 L304,86 Z" fill="#17171A" stroke="#343439" stroke-width="1.2"/>
  <g fill="#343439">
    <rect x="286" y="50" width="18" height="6" rx="1"/><rect x="336" y="50" width="18" height="6" rx="1"/>
    <rect x="286" y="64" width="18" height="6" rx="1"/><rect x="336" y="64" width="18" height="6" rx="1"/>
    <rect x="286" y="78" width="18" height="6" rx="1"/><rect x="336" y="78" width="18" height="6" rx="1"/>
  </g>
  <!-- 琴体 -->
  <path d="M320,120 C329.3,121.3 362.7,123.2 375.6,127.8 C388.4,132.3 394.9,137.8 397.2,147.3 C399.5,156.8 392.2,172.4 389.5,185 C386.8,197.6 381,209 380.9,222.7 C380.9,236.3 383.4,252.2 389.2,266.9 C395.1,281.6 416.1,296.6 416.1,311.1 C416.1,325.6 400.4,343.6 389.2,354 C378,364.4 360.4,369.2 348.8,373.5 C337.3,377.8 324.8,378.9 320,380 M320,380 C315.2,378.9 302.7,377.8 291.2,373.5 C279.6,369.2 262,364.4 250.8,354 C239.6,343.6 223.9,325.6 223.9,311.1 C223.9,296.6 244.9,281.6 250.8,266.9 C256.6,252.2 259.1,236.3 259.1,222.7 C259,209 253.2,197.6 250.5,185 C247.8,172.4 240.5,156.8 242.8,147.3 C245.1,137.8 251.6,132.3 264.4,127.8 C277.3,123.2 310.7,121.3 320,120 Z"
        fill="#17171A" stroke="#343439" stroke-width="1.4"/>
  <!-- 内部：扇形音梁（虚线标位置）-->
  <g stroke="#9C7A3C" stroke-width="1.3" stroke-dasharray="3 3" fill="none" opacity=".9">
    <path d="M320,300 L262,344"/>
    <path d="M320,300 L286,352"/>
    <path d="M320,300 L320,356"/>
    <path d="M320,300 L354,352"/>
    <path d="M320,300 L378,344"/>
  </g>
  <!-- 音孔 -->
  <circle cx="320" cy="272" r="24" fill="#0E0E10" stroke="#343439" stroke-width="1.4"/>
  <!-- 琴码与琴桥 -->
  <path d="M296,300 L344,300 L344,308 L296,308 Z" fill="#111113" stroke="#343439" stroke-width="1.1"/>
  <path d="M300,300 L340,300" stroke="#A9A49B" stroke-width="1.6"/>
  <!-- 六根弦 -->
  <g stroke="#C9A227" opacity=".85">
    <path d="M309,88 L309,302" stroke-width="1.3"/><path d="M313.4,88 L313.4,302" stroke-width="1.2"/>
    <path d="M317.8,88 L317.8,302" stroke-width="1.1"/><path d="M322.2,88 L322.2,302" stroke-width=".9"/>
    <path d="M326.6,88 L326.6,302" stroke-width=".8"/><path d="M331,88 L331,302" stroke-width=".7"/>
  </g>
  <!-- 标注 -->
  <g class="lead" stroke="#6E6A64" stroke-width=".9">
    <path d="M496,52 L340,56"/><path d="M528,72 L340,72"/><path d="M491,104 L304,106"/>
    <path d="M186,150 L244,152"/><path d="M186,196 L272,196"/>
    <path d="M528,258 L350,262"/><path d="M528,304 L348,304"/><path d="M528,340 L392,340"/>
    <path d="M186,356 L316,330"/>
  </g>
  <g font-family="system-ui,sans-serif" font-size="11" fill="#A9A49B">
    <text x="600" y="55" text-anchor="end">琴头（弦轴各三个）</text>
    <text x="600" y="75" text-anchor="end">弦轴 · 六枚</text>
    <text x="600" y="107" text-anchor="end">指板与品丝（19 品）</text>
    <text x="180" y="153" text-anchor="end">上腰</text>
    <text x="180" y="199" text-anchor="end">腰（很浅）</text>
    <text x="180" y="359" text-anchor="end" fill="#9C7A3C">扇形音梁（在面板内侧）</text>
    <text x="610" y="261" text-anchor="end">音孔</text>
    <text x="610" y="307" text-anchor="end">琴码与琴桥</text>
    <text x="610" y="343" text-anchor="end">下腰</text>
  </g>
  <text x="20" y="416" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">对照：小提琴的「腰宽 ÷ 琴体长」是 0.32，吉他是 0.47 —— 吉他的腰浅得多，所以看起来"胖"。</text>
</svg>
```

最后那行小字是这一节最要紧的事实。把三件拿来一比（数据来自实测尺寸）：

| 件 | 上腰/长 | **腰/长** | 下腰/长 |
|---|---|---|---|
| 小提琴 | 0.472 | **0.315** | 0.584 |
| 吉他（古典 / 民谣） | 0.59 | **0.47–0.54** | 0.74–0.79 |
| [[instrument:viol\|维奥尔琴]] | 0.471 | **0.382** | 0.618 |

小提琴的腰被"掐"得很深（0.32），因为它**用弓**，弓要在腰那里进出；
吉他的腰浅（0.47），因为它**用手拨**，只需要让手腕能扫过琴弦 ——
于是它把多出来的面积全给了面板。**面积就是音量。**

## 发声原理：扇形音梁是给尼龙弦定做的

吉他与小提琴的声学路径同构：弦 → 琴码 → 面板 → 箱内空气 → 音孔辐射出去。
真正不同的地方在**面板内侧那几根木头**。

尼龙弦的张力比钢弦低得多（六根合起来约 40 公斤，只有钢弦的一半）。
张力小，面板被"推"的力就小，所以古典吉他用**扇形音梁**：几根细木条从音孔下方向外呈扇形铺开，
把力分散到面板的一大片区域上，让整块面板尽量均匀地振动。

```svg
<svg viewBox="0 0 640 300" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="古典吉他面板内侧的扇形音梁俯视示意：七根木条从音孔下方呈扇形铺开，琴桥板横向加强">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">面板内侧 · 扇形音梁（俯视，把面板翻过来看）</text>
  </g>
  <!-- 面板轮廓（简化：只画外形，不画腰的细节）-->
  <path d="M320,44 C356,46 396,54 412,76 C428,98 420,128 412,150 C404,172 396,190 396,208 C396,228 404,246 416,262 C428,278 424,296 404,306 C376,318 340,320 320,320"
        fill="#111113" stroke="#343439" stroke-width="1.4"/>
  <path d="M320,44 C284,46 244,54 228,76 C212,98 220,128 228,150 C236,172 244,190 244,208 C244,228 236,246 224,262 C212,278 216,296 236,306 C264,318 300,320 320,320 Z"
        fill="#111113" stroke="#343439" stroke-width="1.4"/>
  <!-- 音孔 -->
  <circle cx="320" cy="150" r="30" fill="#0E0E10" stroke="#5B7FA8" stroke-width="1.5"/>
  <text x="320" y="154" text-anchor="middle" font-size="11" fill="#5B7FA8">音孔</text>
  <!-- 琴桥板（横向）-->
  <rect x="256" y="192" width="128" height="16" rx="2" fill="#9C7A3C" opacity=".55"/>
  <text x="392" y="204" font-size="11" fill="#9C7A3C">琴桥板（横向加强）</text>
  <!-- 扇形音梁七根 -->
  <g stroke="#9C7A3C" stroke-width="5" stroke-linecap="round">
    <path d="M320,182 L232,250"/>
    <path d="M320,182 L258,268"/>
    <path d="M320,182 L290,282"/>
    <path d="M320,182 L320,290"/>
    <path d="M320,182 L350,282"/>
    <path d="M320,182 L382,268"/>
    <path d="M320,182 L408,250"/>
  </g>
  <text x="230" y="280" font-size="11" fill="#9C7A3C" text-anchor="end">扇形音梁 · 七根</text>
  <text x="20" y="292" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">扇形把力摊到整块面板上 —— 这是"张力小"的尼龙弦所需要的结构。</text>
</svg>
```

（对照：钢弦吉他用的是 **X 形音梁** —— 交叉的两根主梁。钢弦张力大一倍，
面板更需要"抗拉"而不是"被摊开"。见 [[instrument:acoustic-guitar|民谣吉他]] 一节。）

**音孔不是装饰，是开口**：箱内空气通过它成为一个**亥姆霍兹共振器**，
频率约在 100 Hz 附近。吉他最低的空弦 E2 是 82 Hz —— 比共振点还低，
所以吉他的最低几个音天生偏薄。这是**任何**吉他（不论多贵）都逃不掉的物理限制。

## 音域

```range
{"range":"E2–E6","written":"E3–E7","common":"E2–C5","caption":"古典吉他的记谱音域与实音音域","caption_en":"Classical guitar: notated range above, sounding range below","note":"吉他是移调乐器 —— 记谱比实音高一个八度。上面一行是记谱，下面一行是实际听到的音高。"}
```

四根弦的定弦是 **E2–A2–D3–G3–B3–E4**：除了 G 到 B 是三度，其余相邻弦都是四度。
这个"三度例外"是吉他的历史包袱 —— 它是为了让和弦指型能横向移动而留下的，
代价是音阶指型在 G–B 之间要换一次形状。

三度例外带来的一个直接好处：**最低四根弦（E A D G）正好是四度关系，
与小提琴族的定弦同一套逻辑**，所以吉他手转弹贝斯时，最低四根弦的指型可以直接搬。

## 音色与听辨

古典吉他的听辨要点：

1. **音头是"指甲"而不是"拨片"**。拨弦的瞬间有一小段高频的"啵"，
   但比钢弦吉他圆、比拨片软。这个音头是它的第一识别特征。
2. **余音衰减得比钢弦快、但更干净**。尼龙弦的内阻尼大，
   所以声音不会像钢弦那样拖着长长的金属泛音尾巴。
3. **低音弦不"炸"**。E2 与 A2 这两个音偏薄（前面说的音孔共振问题），
   好的演奏会用靠弦（apoyando）去补，但补不回来 —— 这是设计上的特点，不是缺陷。
4. **泛音位置清晰**。因为面板整体在振动，吉他的自然泛音（第 12、7、5 品）
   非常容易听出，音色通透得像另一种乐器。

下面的试听件给的是六根空弦，从最低到最高。**注意最低两根（E2、A2）比其余四根薄**
—— 那就是音孔共振频率在下方的结果。

```audiolab
{"type":"instrument","gm":"Acoustic Guitar (nylon)","synth":"plucked","phrase":["E2","A2","D3","G3","B3","E4"],"label":"六根空弦：从 E2 到 E4","label_en":"Six open strings — E2 up to E4","hint":"注意最低两根弦比其他四根薄；这是共鸣箱共振频率落在它们上方造成的","hint_en":"Notice how the two lowest strings sound thinner than the rest — the box resonance sits above them."}
```

> 本页「在库中听例子」里的曲子是**乐谱与演奏的骨架**（转写或雕版 MIDI），
> 音色由上面的试听件负责。

## 演奏技法

古典吉他的右手**不用拨片**，用拇指（p）与食指、中指、无名指（i、m、a）四种分工。
这是它名称里"古典"的实际含义：**右手的指法是成体系的**。

- **靠弦（apoyando）与勾弦（tirando）**：靠弦是拨完后手指停在下一根弦上，
  声音更厚、更适合旋律；勾弦是手指离弦，声音更轻、更适合快速音型。
  这两件事是古典吉他右手的底层语法。
- **轮指（tremolino）**：拇指弹低音，i、m、a 依次弹同一个高音 ——
  听起来像"长音"，其实是同音重复。这是古典吉他的招牌技巧之一。
- **击弦与滑音**（左手）：不用右手拨，靠左手手指敲在品丝上发音（锤弦），
  或滑过去带出下一个音。
- **自然泛音与人工泛音**：右手虚按第 12、7、5 品产生泛音；
  左手按弦、右手在指定等分点虚触则为人工泛音。
- **回声与消音**：靠右手掌侧轻触琴桥附近的弦，得到闷住的音或短促的断音。

因为不用拨片，古典吉他的**音量普遍小于钢弦吉他**，但**动态层次更细** ——
它能做到非常弱的渐弱，这是拨片不容易做到的。

## 家族与近亲

吉他族与**拨片族**是两条线，容易混：

| 乐器 | 弦 | 定弦 | 发音方式 | 记谱 |
|---|---|---|---|---|
| **古典吉他** | 6 根单弦（尼龙） | E A D G B E | 指甲拨弦 | 移调（高八度） |
| [[instrument:acoustic-guitar\|民谣吉他]] | 6 根单弦（钢） | E A D G B E | 拨片 / 指弹 | 移调（高八度） |
| [[instrument:ukulele\|尤克里里]] | 4 根单弦（尼龙） | G C E A（高音 G） | 指甲 / 指腹 | 实音 |
| [[instrument:mandolin\|曼陀林]] | 4 组**复弦**（钢） | G D A E | 拨片 | 实音 |
| [[instrument:lute\|鲁特琴]] | 6 组及以上**复弦**（羊肠） | G C F A D G | 指腹 / 指甲 | 实音 |

**两组关键差异**：① 拨弦还是拨片；② 单弦还是复弦。
复弦（曼陀林、鲁特琴）每两根弦同音，声音更厚、余音更长，代价是调音与换弦的工作量翻倍。

吉他一族往上追，共同的祖先是 [[instrument:lute|鲁特琴]]。
从鲁特琴到吉他，最本质的变化是**把复弦改成单弦**：更少的弦、更大的音量、更容易调音。

## 历史演变

吉他族的根在**鲁特琴**。16 世纪西班牙出现了一种更小、用四组复弦的**比维拉琴**
（vihuela），它用吉他的定弦逻辑（四度加三度）取代了鲁特琴的定弦 ——
这个选择一直留到今天：**吉他的定弦是西班牙的，不是欧洲通用的**。

之后三百年是加弦的过程：四组 → 五组 → 五根单弦（16 世纪）→ 六根单弦（约 18 世纪末）。

真正的定型发生在 **19 世纪的西班牙**。制琴师 **Torres** 把琴体尺寸加大到一个新的比例
（今天说的"古典吉他尺寸"就是他那时的），并确立了**扇形音梁**。
从那以后，古典吉他的形制基本没有再变 —— 现在做的琴和 150 年前的琴，
外观与内部结构几乎一样。

20 世纪它走出了两条路：一条是**演奏传统**（Segovia 把古典吉他推上独奏舞台），
另一条是**写作传统**（从 Tárrega、Barrios 到今天的作曲家）。
今天古典吉他是少数**既有完整教学体系、又有当代作品**的拨弦乐器之一。

## 常见误解

- **"古典吉他只能弹古典音乐。"** → "古典"指的是**持琴与右手技法体系**，
  不是曲目范围。当代作品、爵士改编、民间音乐都在弹，只是用同一套手。
- **"尼龙弦不如钢弦，音量小就是差。"** → 两种弦是为两种结构配的：
  尼龙弦张力小 → 面板要扇形梁摊力；钢弦张力大 → 面板要 X 形梁抗拉。
  音量小是"用更小的张力换更细的动态"的代价，不是等级差别。
- **"六根弦，所以能弹的比小提琴多。"** → 弦多不等于音域宽。吉他实音音域 E2–E6（约四个八度），
  小提琴 G3–E7 —— **小提琴的上限更高**。吉他多的是**同时发音的能力**（六根弦可以一起响）。
- **"品丝让音准完全没问题。"** → 品丝只把音高**量化到十二平均律的固定格子**上。
  想弹出别的律制（或做出滑音）就做不到了 —— 这正是无品乐器（比如
  [[instrument:violin|小提琴]]）存在的理由。
- **"吉他谱上的音就是实际听到的音。"** → 反了。吉他是**移调乐器**，
  记谱比实音高一个八度。看音域图上的两行就清楚。
- **"弦越多越好。"** → 从六弦到七弦、八弦确实扩展了低音，但复弦（如曼陀林）
  并不意味着更大音量 —— 那是另一种取舍，见 [[instrument:mandolin|曼陀林]]。

## 下一步

想继续听：先听 [[instrument:acoustic-guitar|民谣吉他]] —— 同一个形状、换了一套弦和一套音梁，
两件对照能把"**结构跟着弦走**"这件事听得很明白；
再往上追到 [[instrument:lute|鲁特琴]]，看吉他的复弦祖先长什么样。
:::

::: en
The classical guitar is a six-string instrument **held in the lap and plucked with the fingertips**.
Everything about it serves one purpose: to turn the vibration of six strings into a sound in which
**several voices can be heard at once**.

It is also the most traditional member of the guitar family: nylon strings, fan bracing, fingernails
rather than a pick, and notation an octave above sounding pitch.

| Classification | Value |
|---|---|
| **HS class** | **Chordophone** — the vibrating body is the string itself |
| **Sub-type** | Plucked (by finger) · necked, with a box resonator, fretted |
| **Family** | Western · Strings (plucked branch) |
| **Bayin** | Not applicable — the eight categories are a Chinese system; the classical guitar is outside it |

## Structure: why a guitar's waist is so shallow

```svg
<svg viewBox="0 0 640 430" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Classical guitar parts: headstock, tuning machines, fretted fingerboard, soundhole, bridge, top plate and the fan bracing inside">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">Classical guitar — outer form and principal parts (six nylon strings)</text>
  </g>
  <path d="M306,86 L334,86 L343,224 L297,224 Z" fill="#0E0E10"/>
  <g stroke="#343439" stroke-width=".9">
    <path d="M298,116 L342,116"/><path d="M299,146 L341,146"/><path d="M300,176 L340,176"/>
    <path d="M301,206 L339,206"/>
  </g>
  <path d="M306,44 L334,44 L336,86 L304,86 Z" fill="#17171A" stroke="#343439" stroke-width="1.2"/>
  <g fill="#343439">
    <rect x="286" y="50" width="18" height="6" rx="1"/><rect x="336" y="50" width="18" height="6" rx="1"/>
    <rect x="286" y="64" width="18" height="6" rx="1"/><rect x="336" y="64" width="18" height="6" rx="1"/>
    <rect x="286" y="78" width="18" height="6" rx="1"/><rect x="336" y="78" width="18" height="6" rx="1"/>
  </g>
  <path d="M320,120 C329.3,121.3 362.7,123.2 375.6,127.8 C388.4,132.3 394.9,137.8 397.2,147.3 C399.5,156.8 392.2,172.4 389.5,185 C386.8,197.6 381,209 380.9,222.7 C380.9,236.3 383.4,252.2 389.2,266.9 C395.1,281.6 416.1,296.6 416.1,311.1 C416.1,325.6 400.4,343.6 389.2,354 C378,364.4 360.4,369.2 348.8,373.5 C337.3,377.8 324.8,378.9 320,380 M320,380 C315.2,378.9 302.7,377.8 291.2,373.5 C279.6,369.2 262,364.4 250.8,354 C239.6,343.6 223.9,325.6 223.9,311.1 C223.9,296.6 244.9,281.6 250.8,266.9 C256.6,252.2 259.1,236.3 259.1,222.7 C259,209 253.2,197.6 250.5,185 C247.8,172.4 240.5,156.8 242.8,147.3 C245.1,137.8 251.6,132.3 264.4,127.8 C277.3,123.2 310.7,121.3 320,120 Z"
        fill="#17171A" stroke="#343439" stroke-width="1.4"/>
  <g stroke="#9C7A3C" stroke-width="1.3" stroke-dasharray="3 3" fill="none" opacity=".9">
    <path d="M320,300 L262,344"/>
    <path d="M320,300 L286,352"/>
    <path d="M320,300 L320,356"/>
    <path d="M320,300 L354,352"/>
    <path d="M320,300 L378,344"/>
  </g>
  <circle cx="320" cy="272" r="24" fill="#0E0E10" stroke="#343439" stroke-width="1.4"/>
  <path d="M296,300 L344,300 L344,308 L296,308 Z" fill="#111113" stroke="#343439" stroke-width="1.1"/>
  <path d="M300,300 L340,300" stroke="#A9A49B" stroke-width="1.6"/>
  <g stroke="#C9A227" opacity=".85">
    <path d="M309,88 L309,302" stroke-width="1.3"/><path d="M313.4,88 L313.4,302" stroke-width="1.2"/>
    <path d="M317.8,88 L317.8,302" stroke-width="1.1"/><path d="M322.2,88 L322.2,302" stroke-width=".9"/>
    <path d="M326.6,88 L326.6,302" stroke-width=".8"/><path d="M331,88 L331,302" stroke-width=".7"/>
  </g>
  <g class="lead" stroke="#6E6A64" stroke-width=".9">
    <path d="M463,52 L340,56"/><path d="M485,72 L340,72"/><path d="M426,104 L304,106"/>
    <path d="M185,150 L244,152"/><path d="M185,196 L272,196"/>
    <path d="M528,258 L350,262"/><path d="M496,304 L348,304"/><path d="M185,340 L392,340"/>
    <path d="M185,356 L316,330"/>
  </g>
  <g font-family="system-ui,sans-serif" font-size="11" fill="#A9A49B">
    <text x="600" y="55" text-anchor="end">Headstock (three a side)</text>
    <text x="600" y="75" text-anchor="end">Six tuning machines</text>
    <text x="600" y="107" text-anchor="end">Fretted fingerboard (19 frets)</text>
    <text x="180" y="153" text-anchor="end">Upper bout</text>
    <text x="180" y="199" text-anchor="end">Waist (shallow)</text>
    <text x="180" y="343" text-anchor="end">Lower bout</text>
    <text x="180" y="359" text-anchor="end" fill="#9C7A3C">Fan bracing (inside)</text>
    <text x="610" y="261" text-anchor="end">Soundhole</text>
    <text x="610" y="307" text-anchor="end">Bridge and saddle</text>
  </g>
  <text x="20" y="400" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">For scale: a violin's waist is 0.32 of its body length, a guitar's is 0.47 —</text>
  <text x="20" y="416" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">the guitar's waist is far shallower, which is why it looks stocky.</text>
</svg>
```

That last line is the key fact of this section. Set the three side by side (measured data):

| Instrument | Upper/body | **Waist/body** | Lower/body |
|---|---|---|---|
| Violin | 0.472 | **0.315** | 0.584 |
| Guitar (nylon or steel) | 0.59 | **0.47–0.54** | 0.74–0.79 |
| [[instrument:viol\|Viol]] | 0.471 | **0.382** | 0.618 |

A violin's waist is cut deep (0.32) because it is **bowed** — the bow has to pass through the waist.
A guitar's waist is shallow (0.47) because it is **plucked by hand**, and the hand only needs room to
sweep across the strings. The area it saves goes straight into the top plate.
**Area is volume.**

## How it sounds: fan bracing is built for nylon

The acoustic path is the same as a violin's: string → bridge → top plate → air in the box → out
through the soundhole. What differs is **the wood on the inside of the top plate**.

Nylon strings pull far less than steel — about 40 kg for all six, roughly half of a steel set.
Less tension means less force pushing the top plate, so a classical guitar uses **fan bracing**:
several thin struts spreading outwards from below the soundhole, distributing the force over a wide
area so the whole plate vibrates as evenly as possible.

```svg
<svg viewBox="0 0 640 300" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Looking at the inside of the classical guitar top plate: seven struts fanning out from below the soundhole, with a transverse bridge plate">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">Inside the top plate · fan bracing (seen from inside)</text>
  </g>
  <path d="M320,44 C356,46 396,54 412,76 C428,98 420,128 412,150 C404,172 396,190 396,208 C396,228 404,246 416,262 C428,278 424,296 404,306 C376,318 340,320 320,320"
        fill="#111113" stroke="#343439" stroke-width="1.4"/>
  <path d="M320,44 C284,46 244,54 228,76 C212,98 220,128 228,150 C236,172 244,190 244,208 C244,228 236,246 224,262 C212,278 216,296 236,306 C264,318 300,320 320,320 Z"
        fill="#111113" stroke="#343439" stroke-width="1.4"/>
  <circle cx="320" cy="150" r="30" fill="#0E0E10" stroke="#5B7FA8" stroke-width="1.5"/>
  <text x="320" y="154" text-anchor="middle" font-size="11" fill="#5B7FA8">soundhole</text>
  <rect x="256" y="192" width="128" height="16" rx="2" fill="#9C7A3C" opacity=".55"/>
  <text x="392" y="204" font-size="11" fill="#9C7A3C">bridge plate</text>
  <g stroke="#9C7A3C" stroke-width="5" stroke-linecap="round">
    <path d="M320,182 L232,250"/>
    <path d="M320,182 L258,268"/>
    <path d="M320,182 L290,282"/>
    <path d="M320,182 L320,290"/>
    <path d="M320,182 L350,282"/>
    <path d="M320,182 L382,268"/>
    <path d="M320,182 L408,250"/>
  </g>
  <text x="214" y="268" font-size="11" fill="#9C7A3C" text-anchor="end">Seven fan struts</text>
  <text x="20" y="292" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">The fan spreads the force across the whole plate — which is what low-tension nylon requires.</text>
</svg>
```

(For comparison, steel-string guitars use **X-bracing** — two main braces crossing. Steel pulls twice
as hard, so the plate needs to resist rather than spread. See [[instrument:acoustic-guitar|acoustic guitar]].)

**The soundhole is an opening, not decoration**: the air inside acts as a **Helmholtz resonator**,
at roughly 100 Hz. The guitar's lowest open string, E2, is 82 Hz — below the resonance.
So the guitar's lowest notes are inherently thin. No guitar escapes this; it is a physical limit,
not a matter of price.

## Range

```range
{"range":"E2–E6","written":"E3–E7","common":"E2–C5","caption":"古典吉他的记谱音域与实音音域","caption_en":"Classical guitar: notated range above, sounding range below","note":"吉他是移调乐器 —— 记谱比实音高一个八度。上面一行是记谱，下面一行是实际听到的音高。"}
```

The six strings are tuned **E2–A2–D3–G3–B3–E4**: every adjacent pair is a fourth **except G to B**,
which is a third. That exception is a historical inheritance — it was kept because it lets chord
shapes move across the neck, and the price is that scale patterns change shape at the G–B boundary.

One useful consequence: **the lowest four strings (E A D G) are all a fourth apart**, the same logic
the violin family uses — so a guitarist picking up a bass can transfer those fingerings directly.

## Timbre, and how to hear it

How to recognise a classical guitar:

1. **The attack is fingernail, not pick.** There is a small high-frequency click at the pluck, but
   rounder and softer than a steel string's or a pick's. It is the first identifying feature.
2. **The decay is faster but cleaner than steel.** Nylon has higher internal damping, so the sound
   does not trail the long metallic overtone tail that steel strings do.
3. **The bass strings do not boom.** E2 and A2 are thin (the soundhole-resonance issue above). A good
   player compensates with rest strokes, but only partly — it is a design characteristic, not a fault.
4. **Harmonics are clear.** Because the whole plate vibrates, the natural harmonics at frets 12, 7
   and 5 ring out very cleanly, sounding almost like another instrument.

The player below gives the six open strings, lowest to highest. **Notice that the bottom two (E2, A2)
sound thinner than the rest** — that is the box resonance sitting above them.

```audiolab
{"type":"instrument","gm":"Acoustic Guitar (nylon)","synth":"plucked","phrase":["E2","A2","D3","G3","B3","E4"],"label":"六根空弦：从 E2 到 E4","label_en":"Six open strings — E2 up to E4","hint":"注意最低两根弦比其他四根薄；这是共鸣箱共振频率落在它们上方造成的","hint_en":"Notice how the two lowest strings sound thinner than the rest — the box resonance sits above them."}
```

> The tracks under “Listen in the library” are the **skeleton of the music** — transcription or
> engraving MIDI — while timbre is handled by the player above.

## Playing techniques

The right hand uses **no pick**: the thumb (p) and the index, middle and ring fingers (i, m, a) divide
the work. That is the practical meaning of "classical" in the name — **the right hand is a system**.

- **Rest stroke (apoyando) and free stroke (tirando)**: in a rest stroke the finger comes to rest on
  the next string — fuller, better for melody; in a free stroke it lifts away — lighter, better for
  fast figures. These two are the grammar of the right hand.
- **Tremolo**: the thumb plays the bass while i, m and a repeat the same high note, so it sounds like
  one long note. A signature technique.
- **Hammer-ons and slides** (left hand): sounding a note by hammering a finger onto the fret, or
  sliding into it, without plucking.
- **Natural and artificial harmonics**: touch the string lightly at fret 12, 7 or 5; or stop with the
  left hand and touch a node with the right.
- **Muting**: the side of the right palm near the bridge gives a damped or staccato sound.

Because there is no pick, a classical guitar is generally **quieter than a steel-string**, but it has
**finer dynamic shading** — it can fade to a very soft pianissimo, which a pick makes difficult.

## The family

The guitar line and the pick line are easy to confuse:

| Instrument | Strings | Tuning | Sound produced by | Notation |
|---|---|---|---|---|
| **Classical guitar** | 6 single (nylon) | E A D G B E | fingernails | transposing (octave up) |
| [[instrument:acoustic-guitar\|Acoustic guitar]] | 6 single (steel) | E A D G B E | pick or fingers | transposing (octave up) |
| [[instrument:ukulele\|Ukulele]] | 4 single (nylon) | G C E A (high G) | nails or fingertips | at pitch |
| [[instrument:mandolin\|Mandolin]] | 4 doubled **courses** (steel) | G D A E | pick | at pitch |
| [[instrument:lute\|Lute]] | 6+ doubled **courses** (gut) | G C F A D G | fingertips/nails | at pitch |

**Two decisive differences**: plucked by finger or by pick; single strings or doubled courses.
Doubled courses (mandolin, lute) make each note thicker and longer, at the cost of twice the tuning
and restringing work.

Chasing the guitar's ancestry leads to the [[instrument:lute|lute]]. The essential change from lute to
guitar was **replacing doubled courses with single strings**: fewer strings, more volume, easier tuning.

## History

The guitar family's root is the **lute**. In 16th-century Spain a smaller instrument with four doubled
courses appeared — the **vihuela** — and it replaced the lute's tuning with the guitar logic
(fourths plus one third). That choice survives today: **the guitar's tuning is Spanish, not general
European practice**.

Three centuries of adding strings followed: four courses → five courses → five single strings
(16th c.) → six single strings (around the end of the 18th c.).

The decisive fixing happened in **19th-century Spain**. The maker **Torres** enlarged the body to a new
proportion — today's "classical guitar size" is his — and established **fan bracing**. Since then the
instrument has barely changed: a guitar built now has almost the same outside shape and inside
structure as one built 150 years ago.

The 20th century split it into two traditions: **performing** (Segovia put the classical guitar on the
solo stage) and **writing** (from Tárrega and Barrios to composers working today). It is one of the
few plucked instruments with both a complete teaching method and a living contemporary repertoire.

## Common misconceptions

- **"A classical guitar can only play classical music."** "Classical" names the **hold and the
  right-hand technique**, not a repertoire. Contemporary works, jazz arrangements and folk music all
  get played — with the same hand.
- **"Nylon is inferior to steel; less volume means worse."** The two string types match two structures:
  low tension needs fan bracing to spread the force; high tension needs X-bracing to resist it. Lower
  volume is the price of trading tension for finer dynamics, not a rank.
- **"Six strings means it covers more than a violin."** More strings is not more range. A guitar sounds
  E2–E6 (about four octaves); a violin is G3–E7 — **the violin goes higher**. What the guitar adds is
  **the ability to sound several notes at once**.
- **"Frets make intonation a solved problem."** Frets **quantise** pitch onto the twelve-tone grid. You
  cannot play another temperament, or slide — exactly why unfretted instruments such as the
  [[instrument:violin|violin]] exist.
- **"What you read is what sounds."** Backwards. The guitar is a **transposing** instrument, notated an
  octave above sounding pitch. The two rows on the range chart show it.
- **"More strings is simply better."** Seven- and eight-string guitars do extend the bass, but doubled
  courses (as on a mandolin) do not mean more volume — that is a different trade-off, see
  [[instrument:mandolin|mandolin]].

## Next

To keep listening: go to the [[instrument:acoustic-guitar|acoustic guitar]] — same shape, a different
set of strings and a different bracing pattern. Hearing the two side by side makes
**"structure follows the strings"** audible. Then trace the ancestry to the [[instrument:lute|lute]]
and see what the guitar's doubled-course ancestor looked like.
:::
