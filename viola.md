---
id: viola
site: inst
cat: I1
title: 中提琴
title_en: Viola
summary: 比小提琴低纯五度的同族乐器，音色偏暗，乐队里负责内声部的黏合
summary_en: The violin's family sibling a fifth lower — darker in tone, and the glue of the inner parts in an ensemble
level: core
tags: [乐器, 弦乐, 西洋]
tags_en: [instrument, strings, western]
alias: [中提琴, viola, 中音提琴]
order: 11
links:
  - "[[concept:interval]]"
  - "[[concept:register]]"
  - "[[concept:timbre]]"
  - "[[concept:clef]]"
  - "[[concept:articulation]]"
  - "[[concept:harmonic-series]]"
  - "[[instrument:violin]]"
  - "[[instrument:cello]]"
  - "[[instrument:double-bass]]"
instances:
  - pdmx-000957 | 标题就写明是中提琴协奏曲（TWV 51 G9）—— 中提琴当独奏主角的作品在 19 世纪以前很少，这一首是最常被引用的那个
  - pdmx-000415 | 小提琴与中提琴的二重帕萨卡利亚 —— 两种音色在同一段音乐里交替，家族内部的差别听得最清楚
  - giantmidi-006159 | 中提琴奏鸣曲（钢琴演奏转写）—— 听它在中低音区的持续线条如何铺底
  - musicnet-000069 | 弦乐四重奏的慢乐章 —— 中提琴在四重奏里的典型职责，填满内声部、接住旋律的尾巴
  - musicnet-000068 | 同一首四重奏的快板乐章，可与上一条对照内声部在快速织体里的"黏合"作用
sources:
  - 琴体尺寸取通行制琴数据：琴体长 410 毫米（常见 40–42 厘米），上琴腰宽 195、腰宽 130、下琴腰宽 240 毫米
  - 定弦 C–G–D–A（比小提琴低纯五度）与音域范围属通行乐器学常识，各版乐器词典表述一致，本文为原创表述
  - 「低五度需要约 21 英寸（≈534 毫米）琴体」这一比例推算依弦长—频率关系（弦长加长 1.5 倍降纯五度）与乐器学通行说法
  - 谱号用法（中音谱号为主，高把位转高音谱号）依通行记谱规范
updated: 2026-09-25
---

::: zh
中提琴是小提琴家族里最容易"听漏"的一件。它比小提琴低整整一个纯五度，琴体只大一圈 ——
却因此背上了一个别的乐器没有的麻烦：**按声学比例它该更大得多，而人的手臂够不到**。

| 分类 | 归属 |
|---|---|
| **HS 分类** | **弦鸣**（Chordophone）—— 发声体是弦本身 |
| **次级类型** | 摩擦激励（用弓擦弦）· 有颈、有板腔共鸣箱 |
| **所属族** | 西洋 · 弦乐 |
| **八音** | 不适用 —— 周代八音是中国乐器的体系，中提琴不在其中 |

## 结构：和小提琴几乎一样，除了尺寸

```svg
<svg viewBox="0 0 640 430" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="中提琴外形与主要部件，并叠加小提琴的虚线轮廓以显示两者尺寸差">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">中提琴 · 外形与主要部件（虚线 = 小提琴，叠加在同一顶端）</text>
  </g>
  <!-- 小提琴虚线轮廓（尺寸参照） -->
  <path d="M320,120 C325.8,121.1 346.1,123.4 355,126.8 C363.9,130.2 368.2,132.4 373.3,140.3 C378.5,148.2 389,161.8 386,174.2 C383.1,186.7 355.6,202.1 355.6,214.9 C355.6,227.7 380.9,239.8 386,251.1 C391.1,262.4 386,271.4 386,282.7 C386,294 391.8,309.7 386,318.9 C380.3,328.1 362.6,333.6 351.6,338.1 C340.6,342.6 325.3,344.7 320,346 M320,346 C314.7,344.7 299.4,342.6 288.4,338.1 C277.4,333.6 259.7,328.1 254,318.9 C248.2,309.7 254,294 254,282.7 C254,271.4 248.9,262.4 254,251.1 C259.1,239.8 284.4,227.7 284.4,214.9 C284.4,202.1 256.9,186.7 254,174.2 C251,161.8 261.5,148.2 266.7,140.3 C271.8,132.4 276.1,130.2 285,126.8 C293.9,123.4 314.2,121.1 320,120 Z"
        fill="none" stroke="#5B7FA8" stroke-width="1.3" stroke-dasharray="4 3"/>
  <!-- 琴颈与指板（比小提琴长） -->
  <path d="M305,92 L335,92 L343,256 L297,256 Z" fill="#0E0E10"/>
  <!-- 琴头与弦轴 -->
  <path d="M306,50 L334,50 L336,92 L304,92 Z" fill="#17171A" stroke="#343439" stroke-width="1.2"/>
  <path d="M320,48 C309,48 302,39 306,29 C310,19 322,15 330,21 C338,26 337,37 328,40 C322,42 317,38 318,33"
        fill="none" stroke="#A9A49B" stroke-width="2.4" stroke-linecap="round"/>
  <g fill="#343439">
    <rect x="288" y="58" width="16" height="6" rx="1"/>
    <rect x="336" y="58" width="16" height="6" rx="1"/>
    <rect x="290" y="76" width="14" height="6" rx="1"/>
    <rect x="336" y="76" width="14" height="6" rx="1"/>
  </g>
  <!-- 中提琴琴体 -->
  <path d="M320,120 C326.7,121.3 350,123.9 360.3,127.8 C370.6,131.7 375.9,134.3 381.8,143.4 C387.8,152.5 399.5,168.1 396.1,182.4 C392.7,196.7 361.2,214.5 361.2,229.2 C361.2,243.9 390.3,257.8 396.1,270.8 C401.9,283.8 396.1,294.2 396.1,307.2 C396.1,320.2 402.7,338.2 396.1,348.8 C389.5,359.4 369.1,365.7 356.4,370.9 C343.7,376.1 326.1,378.5 320,380 M320,380 C313.9,378.5 296.3,376.1 283.6,370.9 C270.9,365.7 250.5,359.4 243.9,348.8 C237.3,338.2 243.9,320.2 243.9,307.2 C243.9,294.2 238.1,283.8 243.9,270.8 C249.7,257.8 278.8,243.9 278.8,229.2 C278.8,214.5 247.3,196.7 243.9,182.4 C240.5,168.1 252.2,152.5 258.2,143.4 C264.1,134.3 269.4,131.7 279.7,127.8 C290,123.9 313.3,121.3 320,120 Z"
        fill="#17171A" stroke="#343439" stroke-width="1.4"/>
  <!-- f 孔 -->
  <g stroke="#0E0E10" stroke-width="7" stroke-linecap="round" fill="none">
    <path d="M285,182 C277,207 293,239 285,263"/>
    <path d="M355,182 C363,207 347,239 355,263"/>
  </g>
  <!-- 琴桥 -->
  <path d="M292,248 L348,248 L344,255 L296,255 Z" fill="#A9A49B"/>
  <!-- 系弦板与尾钮 -->
  <path d="M306,312 L334,312 L328,362 L312,362 Z" fill="#0E0E10" stroke="#343439" stroke-width="1"/>
  <circle cx="320" cy="370" r="3" fill="#A9A49B"/>
  <!-- 腮托 -->
  <path d="M298,330 C282,334 268,348 270,362 C272,374 288,379 300,370 Z" fill="#111113" stroke="#343439" stroke-width="1.1"/>
  <!-- 四根弦（C G D A）-->
  <g stroke="#C9A227" stroke-width="1" opacity=".85">
    <path d="M311,94 L311,318"/><path d="M316.5,94 L316.5,318"/>
    <path d="M322,94 L322,318"/><path d="M327.5,94 L327.5,318"/>
  </g>
  <!-- 标注 -->
  <g class="lead" stroke="#6E6A64" stroke-width=".9">
    <path d="M528,58 L340,64"/><path d="M528,78 L340,80"/><path d="M484,108 L306,110"/>
    <path d="M484,166 L388,166"/><path d="M478,196 L382,196"/>
    <path d="M186,150 L262,152"/><path d="M186,188 L276,190"/><path d="M186,232 L276,232"/>
    <path d="M186,300 L246,300"/><path d="M186,360 L268,360"/>
    <path d="M572,248 L350,248"/><path d="M528,290 L392,290"/><path d="M529,330 L340,328"/>
  </g>
  <g font-family="system-ui,sans-serif" font-size="11" fill="#A9A49B">
    <text x="600" y="61" text-anchor="end">琴头（涡卷）</text>
    <text x="600" y="81" text-anchor="end">弦轴 · 四个</text>
    <text x="600" y="111" text-anchor="end">指板（比小提琴更长）</text>
    <text x="600" y="169" text-anchor="end" fill="#5B7FA8">虚线 ＝ 小提琴 356 mm</text>
    <text x="600" y="199" text-anchor="end" fill="#9C7A3C">中提琴 410 mm（1.15×）</text>
    <text x="180" y="153" text-anchor="end">上琴腰</text>
    <text x="180" y="191" text-anchor="end">f 孔</text>
    <text x="180" y="235" text-anchor="end">腰（C 部）</text>
    <text x="180" y="303" text-anchor="end">下琴腰</text>
    <text x="180" y="363" text-anchor="end">腮托（近代加装）</text>
    <text x="610" y="251" text-anchor="end">琴桥</text>
    <text x="610" y="293" text-anchor="end">面板（云杉）</text>
    <text x="610" y="333" text-anchor="end">系弦板 · 尾钮</text>
  </g>
  <text x="20" y="416" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">四件是几何相似体：中提琴的轮廓基本就是小提琴按 1.15 倍放大 —— 所以指法能互迁。真正的差别在弦。</text>
</svg>
```

指板的长度、琴弦的粗细、琴桥的高度都随尺寸一起放大，**做琴的工艺几乎不用改**。
这正是[[instrument:violin|小提琴]]、中提琴、[[instrument:cello|大提琴]]三件能由同一位制琴师
用同一套手艺做出来的原因，也是演奏者能在这三件之间转移指法的原因。

## 「尺寸困境」：它本该更大

中提琴的全部麻烦都在这一节。

弦的频率与弦长成反比：**弦长加长到 1.5 倍，音就低一个纯五度**。
要让中提琴在声学上与「小提琴放大版」等效，琴体长应该是 356 × 1.5 ≈ **534 毫米**
（约 21 英寸）。而实际上，它停在 **410 毫米** —— 差了近四分之一：

```svg
<svg viewBox="0 0 640 356" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="按同一比例尺推算的理想中提琴尺寸 534 毫米，与市场上实际尺寸 410 毫米的对比，两者顶端对齐">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">「按比例该多大」与「实际多大」：同一比例尺，顶端对齐，差额靠弦补偿</text>
  </g>
  <path d="M150,56 C156.7,57.3 180,59.9 190.3,63.8 C200.6,67.7 205.9,70.3 211.8,79.4 C217.8,88.5 229.5,104.1 226.1,118.4 C222.7,132.7 191.2,150.5 191.2,165.2 C191.2,179.9 220.3,193.8 226.1,206.8 C231.9,219.8 226.1,230.2 226.1,243.2 C226.1,256.2 232.7,274.2 226.1,284.8 C219.5,295.4 199.1,301.7 186.4,306.9 C173.7,312.1 156.1,314.5 150,316 M150,316 C143.9,314.5 126.3,312.1 113.6,306.9 C100.9,301.7 80.5,295.4 73.9,284.8 C67.3,274.2 73.9,256.2 73.9,243.2 C73.9,230.2 68.1,219.8 73.9,206.8 C79.7,193.8 108.8,179.9 108.8,165.2 C108.8,150.5 77.3,132.7 73.9,118.4 C70.5,104.1 82.2,88.5 88.2,79.4 C94.1,70.3 99.4,67.7 109.7,63.8 C120,59.9 143.3,57.3 150,56 Z" fill="#17171A" stroke="#9C7A3C" stroke-width="1.6"/>
  <text x="150" y="46" text-anchor="middle" font-size="11" fill="#9C7A3C">理想 ≈ 534 mm</text>
  <path d="M400,56 C405.2,57 423.1,59 431,62 C438.9,65 443,67 447.6,74 C452.2,81 461.2,93 458.5,104 C455.9,115 431.7,128.7 431.7,140 C431.7,151.3 454.1,162 458.5,172 C463,182 458.5,190 458.5,200 C458.5,210 463.6,223.8 458.5,232 C453.4,240.2 437.8,245 428,249 C418.2,253 404.7,254.8 400,256 M400,256 C395.3,254.8 381.8,253 372,249 C362.2,245 346.6,240.2 341.5,232 C336.4,223.8 341.5,210 341.5,200 C341.5,190 337,182 341.5,172 C345.9,162 368.3,151.3 368.3,140 C368.3,128.7 344.1,115 341.5,104 C338.8,93 347.8,81 352.4,74 C357,67 361.1,65 369,62 C376.9,59 394.8,57 400,56 Z" fill="#17171A" stroke="#A9A49B" stroke-width="1.4"/>
  <text x="400" y="46" text-anchor="middle" font-size="11" fill="#A9A49B">实际 410 mm</text>
  <g stroke="#CE4A32" stroke-width="1.2" stroke-dasharray="3 3" fill="none">
    <path d="M150,316 L470,316"/>
  </g>
  <g stroke="#CE4A32" stroke-width="1.2" fill="none">
    <path d="M470,256 L470,316"/>
    <path d="M465,262 L470,256 L475,262"/>
    <path d="M465,310 L470,316 L475,310"/>
  </g>
  <text x="482" y="290" font-size="11" fill="#CE4A32">差 124 mm</text>
  <text x="150" y="336" text-anchor="middle" font-size="10.5" fill="#6E6A64">≈ 21 英寸 —— 低五度所需</text>
  <text x="400" y="278" text-anchor="middle" font-size="10.5" fill="#6E6A64">人能握持的上限</text>
</svg>
```

为什么不做大？**因为要夹在肩与手之间演奏**。410 毫米已经接近成年人能把琴端稳、
左手还能在低把位自由伸展的极限；再大 12 厘米，小提琴那套持琴方式就废了。

于是中提琴走了一条妥协路线：**弦加粗、张力调高**，让短的弦也能发出低的音。代价有两条，
都是它音色的来源：

1. **C 弦天生偏弱** —— 它是一根"为了低音而被逼粗"的弦，共鸣箱对它不够大，
   所以中提琴的最低音不像大提琴那样有底气，而是发闷、发暗。
2. **反应偏慢** —— 弦更粗意味着起振更慢。快速乐句里，中提琴不像小提琴那样"一点就响"。

换句话说：那种被形容为「鼻音」「木讷」「像蒙了一层纱」的音色，**不是音色，是尺寸**。

## 音域

```range
{"range":"C3–E6","common":"C3–C5","caption":"中提琴的音域与常用音区","caption_en":"The viola’s range and its working register","note":"中提琴是实音乐器，记谱音与实际音高相同。最低的 C3 就是 C 弦空弦，比小提琴最低的 G3 低纯五度。"}
```

四个八度不到一点，但**它的"本钱"集中在中音区**。看音域图会发现：
C3 到 C5 这一段（两个八度）是中提琴在乐队里干活的区域，再往上就进入了与
小提琴重叠、音色又不如小提琴明亮的地方 —— 所以写得好的人不会把它往上推。

谱号上有一件事值得记住：中提琴主要用**中音谱号**（alto clef）—— 五线谱的第三线是中央 C。
这不是复古癖好，而是因为它的音域正好跨在低音谱号与高音谱号之间，
用中音谱号可以避免大量加线。往上到高把位时，会临时改用[[concept:clef|高音谱号]]。

| 弦 | 空弦音 | 音色 |
|---|---|---|
| C 弦 | C3 | 暗、发闷，但有一种别的乐器没有的"哽咽感" |
| G 弦 | G3 | 厚，中提琴最常用的旋律区 |
| D 弦 | D4 | 温，接近人声的中音 |
| A 弦 | A4 | 相对明亮，但不像小提琴的 A 弦那样有穿透力 |

## 音色与听辨

认出中提琴，靠的是**在一个熟悉的地方听到陌生的东西**：它的音高、弓法、
演奏方式和[[instrument:violin|小提琴]]一模一样，但音色像被压低了一层。

三条听辨线索：

1. **同一段旋律，用小提琴的音区听会亮，用中提琴听会暗**。差别不在音高，
   在**每根弦的相对分量**：中提琴的高频分音更少。
2. **中音区的"黏合剂"**：在弦乐四重奏或管弦乐里，当内声部听起来"浑然一体、
   说不出是谁在拉"时，多半就是中提琴在起作用。这是它的本职。
3. **C 弦的与众不同**：低音区不是浑厚，而是**略带沙哑的闷**。
   这种音色在别的弦乐器上很难找到替代品。

下面这个试听件给的是四根空弦。**空弦是听音色最干净的材料** —— 没有按指、
没有换把，只有弦与琴体本身的声音。先用合成近似（零下载）听，再点真实音色对照。

```audiolab
{"type":"instrument","gm":"Viola","synth":"bowed","phrase":["C3","G3","D4","A4"],"label":"四根空弦：从 C 弦到 A 弦","label_en":"Four open strings — C up to A","hint":"注意最低那根 C 弦的闷与涩；它和 G 弦的音色差别比小提琴的 G/E 差别更大","hint_en":"Listen for the dull, slightly gritty low C — the gap between it and the G string is wider than on a violin."}
```

> 本页「在库中听例子」里的曲子是**乐谱与演奏的骨架**（转写或雕版 MIDI），
> 音色由上面的试听件负责。两者听的是同一段音乐的两个不同层面。

## 演奏技法

中提琴的技法与小提琴**完全同源**（同一套弓法、同一套左手技术），
所以这里只说三件在中提琴上需要**改写**的事：

- **把位下移**：同一段音乐要落在它自己的音区里，指法与弓段分配都得重新算。
  小提琴用空弦的地方，中提琴常常要按指 —— 音色因此不那么"空"。
- **C 弦上的高把位**：C 弦很粗、很长，高把位按指需要更大的力，
  所以中提琴手会尽量避开在 C 弦上爬高。
- **重奏里的动态克制**：中提琴的音量在强奏时不如小提琴，在弱奏时又容易糊。
  好的中提琴手做的事，是把内声部弹得"清楚但不抢"。

技法本身（连弓、跳弓、泛音、双音、拨弦、弱音器）与小提琴一致，
详见[[concept:articulation|运音法]]与[[instrument:violin|小提琴]]一节，此处不重复。

## 家族与近亲

中提琴是「西洋弦乐四件套」里按音高排下来的第二件。四件的定弦都按五度
（低音提琴是四度），琴体是几何相似体：

| 乐器 | 琴体长约 | 定弦（低→高） | 实音音域 | 在乐队里干什么 |
|---|---|---|---|---|
| [[instrument:violin\|小提琴]] | 356 毫米 | G3 D4 A4 E5 | G3–E7 | 主旋律、最高声部 |
| **中提琴** | 410 毫米 | C3 G3 D4 A4 | C3–E6 | 中音区黏合剂，常写内声部 |
| [[instrument:cello\|大提琴]] | 760 毫米 | C2 G2 D3 A3 | C2–C6 | 低音线条兼歌唱性独奏 |
| [[instrument:double-bass\|低音提琴]] | 1,100 毫米 | E1 A1 D2 G2 | E1–G4 | 和声的地基（四度定弦） |

四件里只有中提琴有「**尺寸困境**」—— 因为只有它被夹在「声学上该多大」
与「人能撑住多大」之间。大提琴 760 毫米已经接近理想尺寸，所以它没有这个毛病；
低音提琴则走向了另一个极端（见 [[instrument:double-bass|低音提琴]] 一节）。

## 历史演变

中提琴的来历和和小提琴同时：16 世纪意大利的**维奥尔**（viol）家族被逐渐替换，
弓弦乐器按音高分成了三种尺寸 —— 高音、中音、低音。中音的那件就是中提琴。

它此后两百年的处境，可以用一句话概括：**工作是持续的，名字是稀薄的**。
它几乎是每一部弦乐四重奏、交响曲、室内乐的内声部，但 19 世纪以前，
把它当独奏主角写的作品很少。作曲家把这个位置给大提琴（它有底气）、
给小提琴（它有光芒），中提琴通常是那个"把空隙填上"的角色。

20 世纪情况变了：**Hindemith、Bartók、Walton、Shostakovich** 这一代作曲家
重新发现了它 —— 先是 Hindemith 本人就是中提琴手，后来一批作品把这个音色
从内声部推到了舞台中央。今天中提琴独奏曲目的主体是 20 世纪之后的。

## 常见误解

- **"中提琴就是把小提琴放大一点的同一件乐器。"** → **一半对**。形状与工艺确实是放大的
  （几何相似），但「放大」的幅度被人的身体限制住了 —— 它是一个**没放大到位的**设计。
  中提琴音色的所有问题都来自这 124 毫米的缺口。
- **"中提琴的音域在小提琴和大提琴之间，所以只是过渡。"** → 三件的音域**大面积重叠**。
  它们的区别不是音高，是**在这个重叠区里各有什么音色**。中提琴的独立价值在音色与角色，
  不在于补哪个空档。
- **"中提琴总是拉伴奏，没有独奏曲。"** → 19 世纪以前确实少，但 20 世纪有一批
  重要作品。把它当作"没有曲目的乐器"是过时的印象。
- **"低音谱号、高音谱号，中提琴都能读很厉害。"** → 中提琴手读的主要是**中音谱号**，
  不是"能读很多谱号"。用中音谱号的目的很实际：不用一堆加线。
- **"中提琴的弦就是小提琴的弦换个调。"** → 弦的具体规格不同（更长、更粗）。
  同一根弦装到不同的乐器上，音色与寿命都会变。

## 下一步

想继续往下走：先听 [[instrument:cello|大提琴]] —— 同为「低五度」的邻居，
但它没有中提琴的尺寸困境，两件对照能把「尺寸 → 音色」这条因果听得很清楚；
再回到 [[concept:timbre|音色]] 一节，把"同样的音、不同的弦"这件事接到概念上。
:::

::: en
The viola is the easiest instrument in the violin family to miss. It sits a full perfect fifth below
the violin and its body is only a little larger — and that small step down loads it with a problem
no other instrument in the family has: **by acoustic proportions it should be much bigger, and the
human arm cannot reach that far.**

| Classification | Value |
|---|---|
| **HS class** | **Chordophone** — the vibrating body is the string itself |
| **Sub-type** | Friction-excited (bowed) · necked, with a box resonator |
| **Family** | Western · Strings |
| **Bayin** | Not applicable — the eight categories are a Chinese system; the viola is outside it |

## Structure: the violin, only bigger

```svg
<svg viewBox="0 0 640 442" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Viola parts, with the violin's outline overlaid in dashed blue to show the size difference">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">Viola — outer form and principal parts (dashed = violin, aligned at the top)</text>
  </g>
  <!-- violin dashed outline for scale -->
  <path d="M320,120 C325.8,121.1 346.1,123.4 355,126.8 C363.9,130.2 368.2,132.4 373.3,140.3 C378.5,148.2 389,161.8 386,174.2 C383.1,186.7 355.6,202.1 355.6,214.9 C355.6,227.7 380.9,239.8 386,251.1 C391.1,262.4 386,271.4 386,282.7 C386,294 391.8,309.7 386,318.9 C380.3,328.1 362.6,333.6 351.6,338.1 C340.6,342.6 325.3,344.7 320,346 M320,346 C314.7,344.7 299.4,342.6 288.4,338.1 C277.4,333.6 259.7,328.1 254,318.9 C248.2,309.7 254,294 254,282.7 C254,271.4 248.9,262.4 254,251.1 C259.1,239.8 284.4,227.7 284.4,214.9 C284.4,202.1 256.9,186.7 254,174.2 C251,161.8 261.5,148.2 266.7,140.3 C271.8,132.4 276.1,130.2 285,126.8 C293.9,123.4 314.2,121.1 320,120 Z"
        fill="none" stroke="#5B7FA8" stroke-width="1.3" stroke-dasharray="4 3"/>
  <!-- neck and fingerboard (longer than a violin's) -->
  <path d="M305,92 L335,92 L343,256 L297,256 Z" fill="#0E0E10"/>
  <!-- scroll and pegs -->
  <path d="M306,50 L334,50 L336,92 L304,92 Z" fill="#17171A" stroke="#343439" stroke-width="1.2"/>
  <path d="M320,48 C309,48 302,39 306,29 C310,19 322,15 330,21 C338,26 337,37 328,40 C322,42 317,38 318,33"
        fill="none" stroke="#A9A49B" stroke-width="2.4" stroke-linecap="round"/>
  <g fill="#343439">
    <rect x="288" y="58" width="16" height="6" rx="1"/>
    <rect x="336" y="58" width="16" height="6" rx="1"/>
    <rect x="290" y="76" width="14" height="6" rx="1"/>
    <rect x="336" y="76" width="14" height="6" rx="1"/>
  </g>
  <!-- viola body -->
  <path d="M320,120 C326.7,121.3 350,123.9 360.3,127.8 C370.6,131.7 375.9,134.3 381.8,143.4 C387.8,152.5 399.5,168.1 396.1,182.4 C392.7,196.7 361.2,214.5 361.2,229.2 C361.2,243.9 390.3,257.8 396.1,270.8 C401.9,283.8 396.1,294.2 396.1,307.2 C396.1,320.2 402.7,338.2 396.1,348.8 C389.5,359.4 369.1,365.7 356.4,370.9 C343.7,376.1 326.1,378.5 320,380 M320,380 C313.9,378.5 296.3,376.1 283.6,370.9 C270.9,365.7 250.5,359.4 243.9,348.8 C237.3,338.2 243.9,320.2 243.9,307.2 C243.9,294.2 238.1,283.8 243.9,270.8 C249.7,257.8 278.8,243.9 278.8,229.2 C278.8,214.5 247.3,196.7 243.9,182.4 C240.5,168.1 252.2,152.5 258.2,143.4 C264.1,134.3 269.4,131.7 279.7,127.8 C290,123.9 313.3,121.3 320,120 Z"
        fill="#17171A" stroke="#343439" stroke-width="1.4"/>
  <!-- f-holes -->
  <g stroke="#0E0E10" stroke-width="7" stroke-linecap="round" fill="none">
    <path d="M285,182 C277,207 293,239 285,263"/>
    <path d="M355,182 C363,207 347,239 355,263"/>
  </g>
  <!-- bridge -->
  <path d="M292,248 L348,248 L344,255 L296,255 Z" fill="#A9A49B"/>
  <!-- tailpiece and end button -->
  <path d="M306,312 L334,312 L328,362 L312,362 Z" fill="#0E0E10" stroke="#343439" stroke-width="1"/>
  <circle cx="320" cy="370" r="3" fill="#A9A49B"/>
  <!-- chinrest -->
  <path d="M298,330 C282,334 268,348 270,362 C272,374 288,379 300,370 Z" fill="#111113" stroke="#343439" stroke-width="1.1"/>
  <!-- four strings -->
  <g stroke="#C9A227" stroke-width="1" opacity=".85">
    <path d="M311,94 L311,318"/><path d="M316.5,94 L316.5,318"/>
    <path d="M322,94 L322,318"/><path d="M327.5,94 L327.5,318"/>
  </g>
  <!-- labels -->
  <g class="lead" stroke="#6E6A64" stroke-width=".9">
    <path d="M528,58 L340,64"/><path d="M496,78 L340,80"/><path d="M480,108 L306,110"/>
    <path d="M470,166 L388,166"/><path d="M464,196 L382,196"/>
    <path d="M186,150 L262,152"/><path d="M186,188 L276,190"/><path d="M186,232 L276,232"/>
    <path d="M186,300 L246,300"/><path d="M186,360 L268,360"/>
    <path d="M566,248 L350,248"/><path d="M506,290 L392,290"/><path d="M482,330 L340,328"/>
  </g>
  <g font-family="system-ui,sans-serif" font-size="11" fill="#A9A49B">
    <text x="600" y="61" text-anchor="end">Scroll</text>
    <text x="600" y="81" text-anchor="end">Tuning pegs (four)</text>
    <text x="600" y="111" text-anchor="end">Fingerboard (longer)</text>
    <text x="600" y="169" text-anchor="end" fill="#5B7FA8">Dashed = violin, 356 mm</text>
    <text x="600" y="199" text-anchor="end" fill="#9C7A3C">Viola, 410 mm (1.15×)</text>
    <text x="180" y="153" text-anchor="end">Upper bout</text>
    <text x="180" y="191" text-anchor="end">f-hole</text>
    <text x="180" y="235" text-anchor="end">C-bout (waist)</text>
    <text x="180" y="303" text-anchor="end">Lower bout</text>
    <text x="180" y="363" text-anchor="end">Chinrest</text>
    <text x="610" y="251" text-anchor="end">Bridge</text>
    <text x="610" y="293" text-anchor="end">Top plate · spruce</text>
    <text x="610" y="333" text-anchor="end">Tailpiece · end button</text>
  </g>
  <text x="20" y="410" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">The four are geometrically similar — a viola is essentially a violin scaled by 1.15,</text>
  <text x="20" y="426" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">which is why fingerings transfer. The difference is in the strings.</text>
</svg>
```

Fingerboard length, string gauges and bridge height all scale with the body, and **the making
requires almost no new craft at all**. That is why one maker can build a
[[instrument:violin|violin]], a viola and a [[instrument:cello|cello]] with the same skills,
and why players move between the three so easily.

## The size problem: it ought to be bigger

Everything difficult about the viola lives in this section.

A string's frequency is inversely proportional to its length: **lengthen a string by 1.5× and it
drops a perfect fifth**. To be a true scaled-up violin a fifth lower, a viola's body would have to
be 356 × 1.5 ≈ **534 mm** — about 21 inches. In practice it stops at **410 mm**, nearly a quarter
short:

```svg
<svg viewBox="0 0 640 356" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="The theoretical ideal viola size of 534 mm against the 410 mm actually built, drawn to the same scale with tops aligned">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">The size it ought to be, and the size it is — same scale, tops aligned; the gap is paid for by the strings</text>
  </g>
  <path d="M150,56 C156.7,57.3 180,59.9 190.3,63.8 C200.6,67.7 205.9,70.3 211.8,79.4 C217.8,88.5 229.5,104.1 226.1,118.4 C222.7,132.7 191.2,150.5 191.2,165.2 C191.2,179.9 220.3,193.8 226.1,206.8 C231.9,219.8 226.1,230.2 226.1,243.2 C226.1,256.2 232.7,274.2 226.1,284.8 C219.5,295.4 199.1,301.7 186.4,306.9 C173.7,312.1 156.1,314.5 150,316 M150,316 C143.9,314.5 126.3,312.1 113.6,306.9 C100.9,301.7 80.5,295.4 73.9,284.8 C67.3,274.2 73.9,256.2 73.9,243.2 C73.9,230.2 68.1,219.8 73.9,206.8 C79.7,193.8 108.8,179.9 108.8,165.2 C108.8,150.5 77.3,132.7 73.9,118.4 C70.5,104.1 82.2,88.5 88.2,79.4 C94.1,70.3 99.4,67.7 109.7,63.8 C120,59.9 143.3,57.3 150,56 Z" fill="#17171A" stroke="#9C7A3C" stroke-width="1.6"/>
  <text x="150" y="46" text-anchor="middle" font-size="11" fill="#9C7A3C">Ideal ≈ 534 mm</text>
  <path d="M400,56 C405.2,57 423.1,59 431,62 C438.9,65 443,67 447.6,74 C452.2,81 461.2,93 458.5,104 C455.9,115 431.7,128.7 431.7,140 C431.7,151.3 454.1,162 458.5,172 C463,182 458.5,190 458.5,200 C458.5,210 463.6,223.8 458.5,232 C453.4,240.2 437.8,245 428,249 C418.2,253 404.7,254.8 400,256 M400,256 C395.3,254.8 381.8,253 372,249 C362.2,245 346.6,240.2 341.5,232 C336.4,223.8 341.5,210 341.5,200 C341.5,190 337,182 341.5,172 C345.9,162 368.3,151.3 368.3,140 C368.3,128.7 344.1,115 341.5,104 C338.8,93 347.8,81 352.4,74 C357,67 361.1,65 369,62 C376.9,59 394.8,57 400,56 Z" fill="#17171A" stroke="#A9A49B" stroke-width="1.4"/>
  <text x="400" y="46" text-anchor="middle" font-size="11" fill="#A9A49B">Actual 410 mm</text>
  <g stroke="#CE4A32" stroke-width="1.2" stroke-dasharray="3 3" fill="none">
    <path d="M150,316 L470,316"/>
  </g>
  <g stroke="#CE4A32" stroke-width="1.2" fill="none">
    <path d="M470,256 L470,316"/>
    <path d="M465,262 L470,256 L475,262"/>
    <path d="M465,310 L470,316 L475,310"/>
  </g>
  <text x="482" y="290" font-size="11" fill="#CE4A32">124 mm short</text>
  <text x="150" y="336" text-anchor="middle" font-size="10.5" fill="#6E6A64">≈ 21 in — what a fifth lower needs</text>
  <text x="400" y="278" text-anchor="middle" font-size="10.5" fill="#6E6A64">the limit a player can hold</text>
</svg>
```

Why not build it larger? **Because it has to be held between shoulder and hand.** At 410 mm the
viola is already near the limit of what an adult can support while keeping the left hand free in
low positions; another 12 cm and the violin-style hold collapses.

So the viola takes the compromise route: **thicker strings, raised tension**, letting short
strings produce low notes. Two consequences follow, and both are the source of its tone:

1. **The C string is inherently weak.** It is a string made artificially thick in order to be low,
   and the box beneath it is too small. The viola's lowest notes therefore sound dull and
   hollow rather than solid — quite unlike a cello's depth.
2. **It responds slowly.** Thicker strings take longer to speak, so in fast passagework the viola
   does not "answer" the way a violin does.

Put differently: what listeners call the viola's "nasal" or "veiled" tone **is not a tone colour.
It is a dimension.**

## Range

```range
{"range":"C3–E6","common":"C3–C5","caption":"中提琴的音域与常用音区","caption_en":"The viola’s range and its working register","note":"中提琴是实音乐器，记谱音与实际音高相同。最低的 C3 就是 C 弦空弦，比小提琴最低的 G3 低纯五度。"}
```

A little under four octaves — but **its capital sits in the middle**. The chart shows it: C3 to C5
is where a viola does its work. Above that it overlaps the violin without the violin's brightness,
so good writing does not push it up there.

One clef fact worth keeping: the viola is read mainly in **alto clef**, where the middle line of
the staff is middle C. That is not nostalgia — the viola's range straddles bass and treble clefs,
and alto clef avoids piles of ledger lines. Higher passages switch to
[[concept:clef|treble clef]].

| String | Open note | Colour |
|---|---|---|
| C | C3 | dark and dull, with a choked quality nothing else has |
| G | G3 | full; the viola's usual melodic register |
| D | D4 | warm, close to a human middle voice |
| A | A4 | comparably bright, but without the violin's A-string edge |

## Timbre, and how to hear it

You recognise a viola by **hearing something unfamiliar in a familiar place**: same pitch range,
same bowing, same technique as a [[instrument:violin|violin]], but the colour sits a layer lower.

Three cues:

1. **Bright on a violin, dark on a viola.** The difference is not pitch but **the balance of
   overtones**: a viola simply puts less energy into the high harmonics.
2. **The middle's glue.** When the inner parts of a quartet or orchestra sound seamless — when you
   cannot say who is playing — it is usually the viola. That is the job.
3. **That C string.** Down low it is not rich, it is **dull and slightly gritty** — a colour hard
   to substitute from any other bowed instrument.

The player below gives the four open strings. **Open strings are the cleanest material for
hearing a timbre** — no stopping, no shifting, just string and box. Try the synthesised version
first (nothing to download), then the real sampled one.

```audiolab
{"type":"instrument","gm":"Viola","synth":"bowed","phrase":["C3","G3","D4","A4"],"label":"四根空弦：从 C 弦到 A 弦","label_en":"Four open strings — C up to A","hint":"注意最低那根 C 弦的闷与涩；它和 G 弦的音色差别比小提琴的 G/E 差别更大","hint_en":"Listen for the dull, slightly gritty low C — the gap between it and the G string is wider than on a violin."}
```

> The tracks under “Listen in the library” are the **skeleton of the music** — transcription or
> engraving MIDI — while timbre is handled by the player above. Two layers of the same music.

## Playing techniques

The viola's technique is **entirely the violin's** — the same bowing, the same left hand. So here
are only the three things that have to be **re-planned** on this instrument:

- **Shift everything down.** Music has to be relocated into the viola's own register, and both
  fingering and bow distribution recalculated. Where a violin uses an open string, the viola often
  has to stop the note — so it sounds less "hollow".
- **High positions on the C string.** That string is thick and long; stopping it high up demands
  real force, so violists avoid climbing on it.
- **Restraint in ensembles.** The viola cannot match a violin at fortissimo, and at pianissimo it
  blurs. A good violist makes the inner part **clear without competing**.

The techniques themselves (legato, spiccato, harmonics, double stops, pizzicato, mute) are the
violin's — see [[concept:articulation|articulation]] and the [[instrument:violin|violin]] entry.

## The family

The viola is the second of the four by pitch. All four are tuned in fifths (the bass in fourths),
and their bodies are geometrically similar:

| Instrument | Body length | Tuning (low→high) | Range | Role |
|---|---|---|---|---|
| [[instrument:violin\|Violin]] | 356 mm | G3 D4 A4 E5 | G3–E7 | melody, the top line |
| **Viola** | 410 mm | C3 G3 D4 A4 | C3–E6 | the middle's glue, inner parts |
| [[instrument:cello\|Cello]] | 760 mm | C2 G2 D3 A3 | C2–C6 | bass line and singing solos |
| [[instrument:double-bass\|Double bass]] | 1,100 mm | E1 A1 D2 G2 | E1–G4 | the floor of the harmony (fourths) |

Only the viola has the **size problem** — because only the viola is squeezed between "how large it
should be" and "how large a person can hold". A cello at 760 mm is already close to ideal and has
no such trouble; the double bass goes to the opposite extreme (see [[instrument:double-bass|double bass]]).

## History

The viola is as old as the violin. Through the 16th century the **viol** family gave way to bowed
instruments built at three sizes — high, middle, low — and the middle one is the viola.

Its next two centuries can be summed up in one sentence: **constant work, thin reputation.**
It played an inner part in practically every string quartet, symphony and chamber work, yet before
the 19th century few composers made it the protagonist. That seat went to the cello (it has depth)
or the violin (it has brilliance); the viola was the one that filled the gaps.

The 20th century changed it. **Hindemith, Bartók, Walton and Shostakovich** rediscovered the
instrument — Hindemith was himself a violist — and a body of work moved that colour from the middle
of the texture to centre stage. Today's viola solo repertoire is largely a 20th-century and later
story.

## Common misconceptions

- **"A viola is just a scaled-up violin."** Half true. The shape and craft really are scaled
  (geometrically similar) — but the scaling stopped early, because the player's body set the limit.
  The viola is a design that **did not get to its intended size**, and every tonal quirk comes from
  those missing 124 mm.
- **"It fills the gap between violin and cello."** The ranges **overlap heavily**. What separates
  them is not pitch but **what colour each has in the shared register**. The viola's value is its
  role and its colour, not a sonic gap-filling.
- **"Violas only play accompaniment; there is no solo repertoire."** True before the 19th century,
  false since. Calling it an instrument without repertoire is an outdated impression.
- **"Violists can read anything, bass clef and treble clef alike."** Violists read mainly **alto
  clef** — not "all clefs". The point of alto clef is practical: fewer ledger lines.
- **"Its strings are violin strings tuned down."** The gauges are different — longer and thicker.
  The same string on a different instrument changes both tone and lifespan.

## Next

A good next step: listen to the [[instrument:cello|cello]] — the other "a fifth lower" neighbour,
but one that escaped the size problem. Comparing the two makes the causal chain from
**size to tone** audible. Then read [[concept:timbre|timbre]] to tie "same note, different string"
back to the concept.
:::
