---
id: violin
site: inst
cat: I1
title: 小提琴
title_en: Violin
summary: 四根按纯五度定弦的弓弦乐器，管弦乐队里音域最高的常任声部
summary_en: A bowed instrument whose four strings are tuned in fifths — the highest standing section of the orchestra
level: core
tags: [乐器, 弦乐, 西洋]
tags_en: [instrument, strings, western]
alias: [小提琴, violin, violino, fiddle, 提琴, 梵婀玲]
order: 10
links:
  - "[[concept:pitch]]"
  - "[[concept:interval]]"
  - "[[concept:register]]"
  - "[[concept:timbre]]"
  - "[[concept:articulation]]"
  - "[[concept:harmonic-series]]"
  - "[[concept:consonance]]"
  - "[[concept:melody]]"
  - "[[instrument:viola]]"
  - "[[instrument:cello]]"
  - "[[instrument:double-bass]]"
instances:
  - musicnet-000039 | 独奏柔板，一条单旋律线几乎不间断 —— 换弓处的细小断口、长音的稳定度，是弓弦乐器最好认的特征
  - musicnet-000000 | 同一部无伴奏组曲的前奏曲 —— 分解和弦与连续十六分音符，可听出四根弦各自的音色与响度差异
  - musicnet-000041 | 西西里舞曲，附点节奏的歌唱性连弓，与上一首的跑句正好对照
  - mutopia-000070 | 同一首奏鸣曲的纯记谱渲染版本，可对照「演奏转写」与「乐谱」两种形态
  - thesession-000001 | 爱尔兰单声部舞曲 —— 提琴在传统音乐里的用法，全曲只有一条旋律线、没有伴奏
sources:
  - 琴体比例取通行制琴数据：琴体长 356 毫米、上琴腰宽 168 毫米、腰宽 112 毫米、下琴腰宽 208 毫米
  - 定弦 G–D–A–E（纯五度）与常用音域属通行乐器学常识，各版乐器词典表述一致，本文为原创表述
  - 四个空弦的音高（G3 D4 A4 E5）依通行乐谱，属公有领域
  - 巴洛克琴与现代琴在琴颈角度、低音梁、指板长度、琴弦材质上的差异，依通行制琴史叙述
  - 「**琴体越大 → 声音越低**（弦长与共鸣体同步增大）」依弦鸣乐器原理 —— 这也是小提琴族四件成为一组的原因
updated: 2026-09-25
---

::: zh
小提琴是四根弦、没有品的弓弦乐器。这两件事决定了它的一切：
**没有品**，所以音高不是"格子"而是连续的位置 —— 音准靠耳朵和左手的手感；
**用弓摩擦**，所以声音可以一直持续，不必像弹拨或击弦那样一响就衰减。

它是管弦乐队里音域最高的常任声部，也是数量最多的：一个标准编制的乐队里，
第一与第二小提琴加起来常有二十多人。

| 分类 | 归属 |
|---|---|
| **HS 分类** | **弦鸣**（Chordophone）—— 发声体是弦本身 |
| **次级类型** | 摩擦激励（用弓擦弦）· 有颈、有板腔共鸣箱 |
| **所属族** | 西洋 · 弦乐 |
| **八音** | 不适用 —— 周代八音是中国乐器的体系，小提琴不在其中 |

## 结构：一把琴由什么组成

小提琴的琴体只有 356 毫米长，却要塞进一整套声学机关。看得见的和看不见的分两层：

```svg
<svg viewBox="0 0 640 420" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="小提琴外形与主要部件：琴头、弦轴、指板、琴体、f 孔、琴桥、系弦板、腮托，并用虚线标出内部的低音梁与音柱">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">小提琴 · 外形与主要部件（演奏者视角：G 弦在左、E 弦在右）</text>
  </g>
  <!-- 琴颈与指板 -->
  <path d="M309,92 L331,92 L338,236 L302,236 Z" fill="#0E0E10"/>
  <!-- 琴头与弦轴 -->
  <path d="M308,52 L332,52 L334,92 L306,92 Z" fill="#17171A" stroke="#343439" stroke-width="1.2"/>
  <path d="M320,50 C310,50 303,42 306,33 C309,24 320,20 328,25 C335,29 335,39 327,42 C321,44 316,41 317,36"
        fill="none" stroke="#A9A49B" stroke-width="2.4" stroke-linecap="round"/>
  <g fill="#343439">
    <rect x="292" y="58" width="16" height="6" rx="1"/>
    <rect x="332" y="58" width="16" height="6" rx="1"/>
    <rect x="294" y="74" width="14" height="6" rx="1"/>
    <rect x="332" y="74" width="14" height="6" rx="1"/>
  </g>
  <!-- 琴体 -->
  <path d="M320,116 C326.5,117.2 348.9,119.8 358.8,123.5 C368.6,127.2 376.2,129.8 379,138.5 C381.8,147.2 378.8,162.2 375.5,176 C372.2,189.8 360,206.8 359.2,221 C358.5,235.2 365.6,248.5 371.2,261 C376.9,273.5 390.8,283.5 393,296 C395.2,308.5 390.6,325.8 384.2,336 C377.9,346.2 365.7,352.2 355,357.2 C344.3,362.2 325.8,364.5 320,366 M320,366 C314.2,364.5 295.7,362.2 285,357.2 C274.3,352.2 262.1,346.2 255.8,336 C249.4,325.8 244.8,308.5 247,296 C249.2,283.5 263.1,273.5 268.8,261 C274.4,248.5 281.5,235.2 280.8,221 C280,206.8 267.8,189.8 264.5,176 C261.2,162.2 258.2,147.2 261,138.5 C263.8,129.8 271.4,127.2 281.2,123.5 C291.1,119.8 313.5,117.2 320,116 Z"
        fill="#17171A" stroke="#343439" stroke-width="1.4"/>
  <!-- 内部件（虚线标位置，剖面图里才看得见）-->
  <g stroke="#9C7A3C" stroke-width="1.4" stroke-dasharray="3 3" fill="none" opacity=".9">
    <path d="M298,152 L294,272"/>
    <path d="M350,244 L352,282"/>
  </g>
  <!-- f 孔 -->
  <g stroke="#0E0E10" stroke-width="7" stroke-linecap="round" fill="none">
    <path d="M282,176 C274,200 290,232 282,258"/>
    <path d="M358,176 C366,200 350,232 358,258"/>
  </g>
  <!-- 琴桥 -->
  <path d="M292,236 L348,236 L344,243 L296,243 Z" fill="#A9A49B"/>
  <!-- 系弦板与尾钮 -->
  <path d="M306,300 L334,300 L328,348 L312,348 Z" fill="#0E0E10" stroke="#343439" stroke-width="1"/>
  <circle cx="320" cy="356" r="3" fill="#A9A49B"/>
  <!-- 腮托 -->
  <path d="M298,318 C282,322 268,336 270,350 C272,362 288,367 300,358 Z" fill="#111113" stroke="#343439" stroke-width="1.1"/>
  <!-- 四根弦 -->
  <g stroke="#C9A227" stroke-width=".9" opacity=".85">
    <path d="M312,94 L312,306"/><path d="M317,94 L317,306"/>
    <path d="M323,94 L323,306"/><path d="M328.5,94 L328.5,306"/>
  </g>
  <!-- 标注 -->
  <g class="lead" stroke="#6E6A64" stroke-width=".9">
    <path d="M528,48 L340,58"/><path d="M528,68 L340,70"/><path d="M145,96 L302,98"/>
    <path d="M186,131 L262,132"/><path d="M186,153 L292,172"/><path d="M186,183 L274,186"/>
    <path d="M186,217 L274,216"/><path d="M186,289 L246,288"/><path d="M186,351 L266,352"/>
    <path d="M511,154 L338,152"/><path d="M527,214 L348,250"/><path d="M582,242 L348,240"/>
    <path d="M538,274 L392,272"/><path d="M571,324 L338,320"/>
  </g>
  <g font-family="system-ui,sans-serif" font-size="11" fill="#A9A49B">
    <text x="600" y="49" text-anchor="end">琴头（涡卷）</text>
    <text x="600" y="69" text-anchor="end">弦轴 · 四个</text>
    <text x="40" y="97" text-anchor="start">琴颈与指板（无品）</text>
    <text x="180" y="133" text-anchor="end">上琴腰</text>
    <text x="180" y="155" text-anchor="end" fill="#9C7A3C">低音梁（在内部）</text>
    <text x="180" y="185" text-anchor="end">f 孔</text>
    <text x="180" y="219" text-anchor="end">腰（C 部）</text>
    <text x="180" y="291" text-anchor="end">下琴腰</text>
    <text x="180" y="353" text-anchor="end">腮托（近代加装）</text>
    <text x="610" y="155" text-anchor="end">四根弦 · G D A E</text>
    <text x="610" y="215" text-anchor="end" fill="#9C7A3C">音柱（在内部）</text>
    <text x="610" y="243" text-anchor="end">琴桥</text>
    <text x="610" y="275" text-anchor="end">面板（云杉）</text>
    <text x="610" y="325" text-anchor="end">系弦板</text>
  </g>
</svg>
```

看不见的两件才是关键：**低音梁**（粘在面板内侧、偏低音弦一侧的木条）与**音柱**
（立在面板与背板之间、偏高音弦一侧的小圆木棍）。它们的作用在下一节。

## 发声原理

弓毛上涂松香，擦过弦时产生**粘滞—滑动**交替：弓毛把弦拽走一小段，弦的弹力又把它拽回来，
如此每秒几百次 —— 这就是**摩擦激励**，与拨弦的「敲一下自由振动」完全不同。
它的好处是**能量持续输入**，所以弦可以连响几十秒而不衰减。

弦的振动经**琴桥**压到**面板**上。面板是云杉做的：比重小、顺纹刚度高，
既容易被推动，又能把能量铺开成大面积振动 —— 这是"用一块木板放大几根弦"的核心。
两条路径分成两半：

```svg
<svg viewBox="0 0 640 260" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="在琴桥处的横剖图：四根弦端视、琴桥、拱形面板、低音梁、音柱、侧板、背板，以及腹腔里被带动的空气">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="20">横剖 · 在琴桥处切开（看的不是外形，是能量往哪儿走）</text>
  </g>
  <!-- 腹腔空气 -->
  <path d="M110,120 C170,104 470,104 530,120 L530,186 C470,206 170,206 110,186 Z"
        fill="#5B7FA8" opacity=".12"/>
  <text x="330" y="150" text-anchor="middle" font-family="system-ui,sans-serif" font-size="11"
        fill="#5B7FA8">腹腔空气 · 自己的共振频率补上低音区</text>
  <!-- 面板：拱形，f 孔处留缺口 -->
  <g stroke="#A9A49B" stroke-width="4" fill="none" stroke-linecap="round">
    <path d="M110,118 C150,102 190,98 216,97"/>
    <path d="M232,96 C272,92 368,92 408,96"/>
    <path d="M424,97 C450,98 490,102 530,118"/>
  </g>
  <!-- 背板与侧板 -->
  <path d="M110,186 C170,206 470,206 530,186" stroke="#6E6A64" stroke-width="5"
        fill="none" stroke-linecap="round"/>
  <g stroke="#6E6A64" stroke-width="4">
    <path d="M110,117 L110,187"/><path d="M530,117 L530,187"/>
  </g>
  <!-- 低音梁（青铜）与音柱（金）-->
  <path d="M230,101 L302,97 L302,108 L230,112 Z" fill="#9C7A3C"/>
  <path d="M336,99 L344,99 L344,199 L336,199 Z" fill="#C9A227"/>
  <!-- 琴桥：两脚分别落在低音梁与音柱上 -->
  <path d="M312,50 L328,50 L330,86 L350,86 L350,95 L290,95 L290,86 L310,86 Z" fill="#A9A49B"/>
  <!-- 四根弦（端视 = 四个点）-->
  <g fill="#C9A227">
    <circle cx="309" cy="43" r="3.4"/><circle cx="316" cy="43" r="3.4"/>
    <circle cx="323" cy="43" r="3.4"/><circle cx="330" cy="43" r="3.4"/>
  </g>
  <!-- 标注 -->
  <g class="lead" stroke="#6E6A64" stroke-width=".9">
    <path d="M156,43 L299,43"/><path d="M156,75 L296,77"/><path d="M156,97 L212,96"/>
    <path d="M156,128 L226,122"/><path d="M156,148 L180,112"/><path d="M156,172 L108,172"/>
    <path d="M156,204 L108,196"/><path d="M584,112 L348,112"/>
  </g>
  <g font-family="system-ui,sans-serif" font-size="11" fill="#A9A49B">
    <text x="150" y="46" text-anchor="end">弦 · 四根</text>
    <text x="150" y="78" text-anchor="end">琴桥</text>
    <text x="150" y="100" text-anchor="end">f 孔（面板上的开口）</text>
    <text x="150" y="131" text-anchor="end" fill="#9C7A3C">低音梁</text>
    <text x="150" y="151" text-anchor="end">面板 · 云杉</text>
    <text x="150" y="175" text-anchor="end">侧板</text>
    <text x="150" y="207" text-anchor="end">背板 · 枫木</text>
    <text x="612" y="115" text-anchor="end" fill="#C9A227">音柱</text>
  </g>
  <text x="20" y="242" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">琴桥的两只脚正好各压在一件内部构件上：左脚压低音梁、右脚压音柱 —— 弦的振动就是这样被一分为二的。</text>
</svg>
```

| 路径 | 走法 | 结果 |
|---|---|---|
| **低音侧** | 经**低音梁**加强的面板 | 低频厚实，低音弦不"塌" |
| **高音侧** | 经**音柱**传给背板 | 背板（枫木）被带动一起振动，高音更亮、更有"芯" |

箱体里的空气也不算闲人：它有一个自己的共振频率（现代小提琴约在 290 Hz 附近），
正好补上低音区那一段天生偏弱的响度。所以一把琴的声音是**弦—面板—音柱—背板—空气**
五者配合的结果，不是"木头好就行"。

定弦是 **G3–D4–A4–E5**，四组**纯五度**。这个选择不是随手定的：纯五度的频率比最简单，
在 [[concept:harmonic-series|泛音列]] 里出现得最早，所以相邻两弦的高次分音会互相重合 ——
一把琴上每根弦的"空弦音"都能被另一根弦的泛音找到，按音位置因此成体系。
这也是为什么小提琴手可以只凭手感与耳朵找准音：他靠的不是格子，而是**弦与弦之间的音程关系**。

## 音域

```range
{"range":"G3–E7","common":"G3–E6","caption":"小提琴的实音音域与常用音区","caption_en":"The violin’s sounding range and its working register","note":"小提琴是实音乐器：记谱音与实际音高相同，不移调。四个空弦音 G3、D4、A4、E5 都落在图内。"}
```

四个八度的跨度，但**四根弦各有自己的性格**，这是小提琴写作最常用的一个杠杆：

| 弦 | 空弦音 | 音色 | 常用场合 |
|---|---|---|---|
| G 弦 | G3 | 最厚、最暗 | 低音线条、悲剧性主题 |
| D 弦 | D4 | 温厚、有木质感 | 中音区旋律 |
| A 弦 | A4 | 明亮、有穿透力 | 主旋律的常用区 |
| E 弦 | E5 | 最锋利、最亮 | 高潮、华彩、极高音区 |

所以同一段旋律写在 A 弦上还是 E 弦上，听感差别很大 —— 演奏者会为了**换弦时机**反复试奏。

## 音色与听辨

认出小提琴，抓两个特征就够了：

1. **起音有一瞬间的"毛刺"**：弓毛擦弦的最初一刹那有摩擦噪声，之后才进入平稳的持续音。
   这段"毛刺"是弓弦乐器的指纹 —— 没有它，就是电子合成的假弦乐。
2. **音量可以一直不变**：长音不会自己衰减。听到一个长时间保持力度不变的音，
   基本可以排除弹拨（吉他一类）与击弦（钢琴一类）。

听的时候请用下面的试听件（那才是"琴的音色"），音色模型先用**合成近似**（零下载），
想听真实采样音色再点**真实音色**（首次需要下载音色库，之后会缓存）。

```audiolab
{"type":"instrument","gm":"Violin","synth":"bowed","phrase":["G3","D4","A4","E5"],"label":"四根空弦：小提琴的四个音区","label_en":"Four open strings — the violin’s four registers","hint":"空弦音 G3–D4–A4–E5 就是纯五度；先听合成近似，再听 GM 采样对照","hint_en":"G3–D4–A4–E5 are the four open strings — each a fifth apart. Try the synth first, then the GM samples."}
```

> 本页「在库中听例子」里的曲子是**乐谱与演奏的骨架**（转写或雕版 MIDI），
> 音色由本页的试听件负责。两者听同一段音乐的两个不同层面，不要混为一谈。

## 演奏技法

右手（弓）决定发音，左手决定音高与色彩。常见的几组：

- **连弓 legato / 分弓 détaché**：一弓几个音，还是一弓一个音 —— 最基础的句法工具。
- **跳弓 spiccato / 顿弓 staccato**：让弓毛离弦再落回，得到短促、有弹性的音。
- **泛音**：手指虚按弦的 1/2、1/3 等分点，只留下该处的分音 —— 音色透明得像另一件乐器。
  这是 [[concept:harmonic-series|泛音列]] 被直接演奏出来的现场。
- **双音与和弦**：同时拉两根弦（如三度、六度、八度），四根弦也能拉三音和弦
  （只是低音会稍作分解）。
- **揉弦 vibrato**：左手在指板上小幅摆动，让音高以每秒 5–7 次微动 ——
  这是"有表情的持续音"和"平直的长音"之间的分界线。
- **弱音器 con sordino**：夹在琴桥上，压低高频，声音变远、变哑。
- **拨弦 pizzicato**：放下弓，用手指拨弦 —— 同一个箱子，音色立刻变成弹拨。

## 家族与近亲

小提琴不是孤件，而是一个按音高排下来的四件套。四件的定弦都按五度（低音提琴是四度），
所以指法与音程关系高度相似，一个学琴的人换件演奏的门槛远低于换族：

| 乐器 | 琴体长约 | 定弦（低→高） | 实音音域 | 在乐队里干什么 |
|---|---|---|---|---|
| **小提琴** | 356 毫米 | G3 D4 A4 E5 | G3–E7 | 主旋律、最高声部 |
| [[instrument:viola\|中提琴]] | 410 毫米 | C3 G3 D4 A4 | C3–E6 | 中音区黏合剂，常写内声部 |
| [[instrument:cello\|大提琴]] | 760 毫米 | C2 G2 D3 A3 | C2–C6 | 低音线条兼歌唱性独奏 |
| [[instrument:double-bass\|低音提琴]] | 1,100 毫米 | E1 A1 D2 G2 | E1–G4 | 和声的地基（四度定弦） |

除了管弦乐里的这四件，同"弦鸣 · 摩擦/拨奏"这一支上还有
[[instrument:viol|维奥尔琴]]（六弦、有品，巴洛克早期的主角）、
[[instrument:lute|鲁特琴]]与 [[instrument:harp|竖琴]]（拨弦，不走弓）。
另外一个常见混淆：**民间提琴（fiddle）不是另一种乐器** —— 它通常就是小提琴，
只是定弦、持琴方式与曲目传统不同。

## 历史演变

现代小提琴的定型发生在 16–18 世纪的意大利：克雷莫纳的 Amati、Stradivari、
Guarneri 三代把琴体比例推到今天的标准。此后最大的变化不在琴体，而在**配件**：

| 部件 | 巴洛克时期 | 现代 |
|---|---|---|
| 琴颈 | 与面板基本平行、较短 | 后仰、加长 |
| 低音梁 | 细 | 加粗加高 |
| 琴弦 | 羊肠弦 | 金属缠弦（E 弦为钢） |
| 琴桥与指板 | 矮、短 | 高、长 |
| 腮托与肩垫 | 无 | 19 世纪起逐步加装 |

这一整套改动的方向只有一个：**更响**。为了填满越来越大的音乐厅，
琴弦张力提高了，面板就必须撑得更牢，于是低音梁加粗；琴颈后仰、指板加长，
才承得住更高的张力与更高的把位。代价是巴洛克琴那种柔和的"羊肠味"变淡了 ——
所以在"历史演奏"实践里，人们会特意把琴恢复成巴洛克配置。

## 常见误解

- **"小提琴的音域和钢琴一样高。"** → 差得远。钢琴最高到 C8，小提琴的极限音大约到 E7，
  还低一个大三度；但小提琴**在 G3–E6 这一段更常用、更响亮**，钢琴在那一段反而要靠更多音堆起来。
- **"没有品，所以音拉不准。"** → 没有品正是为了两件事：音高能连续变化（才能揉弦、
  才能做出微调），以及四根弦的音程关系自成体系。音准靠训练，不靠格子。
- **"弓毛是头发，绷得越紧越好。"** → 恰恰相反。弓毛张力过大会让弓杆失去弹性，
  跳弓与控制都做不出来，长期还会拉伤弓毛与弓杆。正常演奏时弓毛几乎贴住弓杆。
- **"贵琴的声音一定更好。"** → 声音是一个系统（琴 + 弓 + 松香 + 演奏者 + 房间）。
  多次盲测中，演奏者与听众都不能稳定分辨老琴与现代高价琴，甚至会把现代琴评为更好。
- **"四根弦一样粗。"** → 从 G 到 E 逐弦变细：粗弦振动慢、出低音。
  这也是为什么低音弦要更长（琴颈短了不行），以及为什么低音提琴的定弦改成了四度。
- **"琴越大声音越低，所以低音提琴就是放大版的小提琴。"** → 低音提琴不只是放大的小提琴，
  它的定弦是四度（E–A–D–G）、琴颈角度与琴弓握法都不同，弓法体系也是独立的一套。

## 下一步

想继续往下走，建议按这个顺序听：先听 [[instrument:viola|中提琴]]（同一个家族、
只低五度，但角色的差别比音高的差别大得多），再看
[[concept:articulation|运音法]]（同一把琴上，弓怎么走就换了一种语言），
最后去 [[concept:timbre|音色]] 一节，把这些听感接到概念上。
:::

::: en
The violin has four strings and no frets. Everything about it follows from those two facts.
**No frets** means pitch is not a grid but a continuum — intonation comes from the ear and the
left hand. **Bowing** means the sound can be sustained indefinitely, instead of decaying the
moment it starts the way a plucked or struck string does.

It is the highest standing section of the orchestra and the largest: a full orchestra may carry
twenty-odd players across first and second violins.

| Classification | Value |
|---|---|
| **HS class** | **Chordophone** — the vibrating body is the string itself |
| **Sub-type** | Friction-excited (bowed) · necked, with a box resonator |
| **Family** | Western · Strings |
| **Bayin** | Not applicable — the eight categories are a Chinese system; the violin is outside it |

## Structure: how the sound is built

The body is only 356 mm long, yet it holds a complete acoustic mechanism. There are two layers
to it — one you can see, one you cannot.

```svg
<svg viewBox="0 0 640 420" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Violin parts: scroll, tuning pegs, fingerboard, body, f-holes, bridge, tailpiece and chinrest, with the internal bass bar and soundpost marked in dashed lines">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">Violin — outer form and principal parts (player’s view: G string left, E string right)</text>
  </g>
  <!-- neck and fingerboard -->
  <path d="M309,92 L331,92 L338,236 L302,236 Z" fill="#0E0E10"/>
  <!-- scroll and pegs -->
  <path d="M308,52 L332,52 L334,92 L306,92 Z" fill="#17171A" stroke="#343439" stroke-width="1.2"/>
  <path d="M320,50 C310,50 303,42 306,33 C309,24 320,20 328,25 C335,29 335,39 327,42 C321,44 316,41 317,36"
        fill="none" stroke="#A9A49B" stroke-width="2.4" stroke-linecap="round"/>
  <g fill="#343439">
    <rect x="292" y="58" width="16" height="6" rx="1"/>
    <rect x="332" y="58" width="16" height="6" rx="1"/>
    <rect x="294" y="74" width="14" height="6" rx="1"/>
    <rect x="332" y="74" width="14" height="6" rx="1"/>
  </g>
  <!-- body -->
  <path d="M320,116 C326.5,117.2 348.9,119.8 358.8,123.5 C368.6,127.2 376.2,129.8 379,138.5 C381.8,147.2 378.8,162.2 375.5,176 C372.2,189.8 360,206.8 359.2,221 C358.5,235.2 365.6,248.5 371.2,261 C376.9,273.5 390.8,283.5 393,296 C395.2,308.5 390.6,325.8 384.2,336 C377.9,346.2 365.7,352.2 355,357.2 C344.3,362.2 325.8,364.5 320,366 M320,366 C314.2,364.5 295.7,362.2 285,357.2 C274.3,352.2 262.1,346.2 255.8,336 C249.4,325.8 244.8,308.5 247,296 C249.2,283.5 263.1,273.5 268.8,261 C274.4,248.5 281.5,235.2 280.8,221 C280,206.8 267.8,189.8 264.5,176 C261.2,162.2 258.2,147.2 261,138.5 C263.8,129.8 271.4,127.2 281.2,123.5 C291.1,119.8 313.5,117.2 320,116 Z"
        fill="#17171A" stroke="#343439" stroke-width="1.4"/>
  <!-- internal parts, positions only -->
  <g stroke="#9C7A3C" stroke-width="1.4" stroke-dasharray="3 3" fill="none" opacity=".9">
    <path d="M298,152 L294,272"/>
    <path d="M350,244 L352,282"/>
  </g>
  <!-- f-holes -->
  <g stroke="#0E0E10" stroke-width="7" stroke-linecap="round" fill="none">
    <path d="M282,176 C274,200 290,232 282,258"/>
    <path d="M358,176 C366,200 350,232 358,258"/>
  </g>
  <!-- bridge -->
  <path d="M292,236 L348,236 L344,243 L296,243 Z" fill="#A9A49B"/>
  <!-- tailpiece and end button -->
  <path d="M306,300 L334,300 L328,348 L312,348 Z" fill="#0E0E10" stroke="#343439" stroke-width="1"/>
  <circle cx="320" cy="356" r="3" fill="#A9A49B"/>
  <!-- chinrest -->
  <path d="M298,318 C282,322 268,336 270,350 C272,362 288,367 300,358 Z" fill="#111113" stroke="#343439" stroke-width="1.1"/>
  <!-- four strings -->
  <g stroke="#C9A227" stroke-width=".9" opacity=".85">
    <path d="M312,94 L312,306"/><path d="M317,94 L317,306"/>
    <path d="M323,94 L323,306"/><path d="M328.5,94 L328.5,306"/>
  </g>
  <!-- leader lines -->
  <g class="lead" stroke="#6E6A64" stroke-width=".9">
    <path d="M495,48 L340,58"/><path d="M495,68 L340,70"/><path d="M232,96 L302,98"/>
    <path d="M186,131 L262,132"/><path d="M186,153 L292,172"/><path d="M186,183 L274,186"/>
    <path d="M186,217 L274,216"/><path d="M186,289 L246,288"/><path d="M186,351 L266,352"/>
    <path d="M483,154 L338,152"/><path d="M505,214 L348,250"/><path d="M566,242 L348,240"/>
    <path d="M503,274 L392,272"/><path d="M546,324 L338,320"/>
  </g>
  <g font-family="system-ui,sans-serif" font-size="11" fill="#A9A49B">
    <text x="600" y="49" text-anchor="end">Scroll</text>
    <text x="600" y="69" text-anchor="end">Tuning pegs (four)</text>
    <text x="40" y="97" text-anchor="start">Neck and fretless fingerboard</text>
    <text x="180" y="133" text-anchor="end">Upper bout</text>
    <text x="180" y="155" text-anchor="end" fill="#9C7A3C">Bass bar (inside)</text>
    <text x="180" y="185" text-anchor="end">f-hole</text>
    <text x="180" y="219" text-anchor="end">C-bout (waist)</text>
    <text x="180" y="291" text-anchor="end">Lower bout</text>
    <text x="180" y="353" text-anchor="end">Chinrest (added later)</text>
    <text x="610" y="155" text-anchor="end">Four strings · G D A E</text>
    <text x="610" y="215" text-anchor="end" fill="#9C7A3C">Soundpost (inside)</text>
    <text x="610" y="243" text-anchor="end">Bridge</text>
    <text x="610" y="275" text-anchor="end">Top plate (spruce)</text>
    <text x="610" y="325" text-anchor="end">Tailpiece</text>
  </g>
</svg>
```

The two parts you cannot see are the ones that matter: the **bass bar** (a strip glued inside
the top plate, under the bass-string side) and the **soundpost** (a small rod standing between
top plate and back plate, under the treble-string side). Their job is the next section.

## How it sounds

Rosin is sticky. Drawn across the string, the bow alternately grips it and lets it slip:
the string is pulled aside, then snaps back, hundreds of times a second. This is
**friction excitation**, and it differs from plucking in one decisive way — energy keeps being
fed in, so a note can last for tens of seconds without decaying.

The string's vibration reaches the **top plate** through the **bridge**. That plate is spruce:
low density, high stiffness along the grain — easy to set moving, and good at spreading the
motion over a large area. THIS is how a few strings fill a room with sound. The energy then
splits two ways:

```svg
<svg viewBox="0 0 640 260" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Cross-section taken at the bridge: the four strings end-on, the bridge, the arched top plate, the bass bar, the soundpost, the ribs, the back plate, and the air set moving inside the box">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="20">Cross-section at the bridge (not the outline — where the energy goes)</text>
  </g>
  <!-- air volume -->
  <path d="M110,120 C170,104 470,104 530,120 L530,186 C470,206 170,206 110,186 Z"
        fill="#5B7FA8" opacity=".12"/>
  <text x="330" y="150" text-anchor="middle" font-family="system-ui,sans-serif" font-size="11"
        fill="#5B7FA8">Air in the box — its own resonance fills in the low register</text>
  <!-- top plate: arched, with gaps at the f-holes -->
  <g stroke="#A9A49B" stroke-width="4" fill="none" stroke-linecap="round">
    <path d="M110,118 C150,102 190,98 216,97"/>
    <path d="M232,96 C272,92 368,92 408,96"/>
    <path d="M424,97 C450,98 490,102 530,118"/>
  </g>
  <!-- back plate and ribs -->
  <path d="M110,186 C170,206 470,206 530,186" stroke="#6E6A64" stroke-width="5"
        fill="none" stroke-linecap="round"/>
  <g stroke="#6E6A64" stroke-width="4">
    <path d="M110,117 L110,187"/><path d="M530,117 L530,187"/>
  </g>
  <!-- bass bar (bronze) and soundpost (gold) -->
  <path d="M230,101 L302,97 L302,108 L230,112 Z" fill="#9C7A3C"/>
  <path d="M336,99 L344,99 L344,199 L336,199 Z" fill="#C9A227"/>
  <!-- bridge: its two feet land on the bass bar and the soundpost -->
  <path d="M312,50 L328,50 L330,86 L350,86 L350,95 L290,95 L290,86 L310,86 Z" fill="#A9A49B"/>
  <!-- four strings, seen end-on -->
  <g fill="#C9A227">
    <circle cx="309" cy="43" r="3.4"/><circle cx="316" cy="43" r="3.4"/>
    <circle cx="323" cy="43" r="3.4"/><circle cx="330" cy="43" r="3.4"/>
  </g>
  <!-- labels -->
  <g class="lead" stroke="#6E6A64" stroke-width=".9">
    <path d="M128,43 L299,43"/><path d="M156,75 L296,77"/><path d="M156,97 L212,96"/>
    <path d="M156,128 L226,122"/><path d="M156,148 L180,112"/><path d="M156,172 L108,172"/>
    <path d="M156,204 L108,196"/><path d="M546,112 L348,112"/>
  </g>
  <g font-family="system-ui,sans-serif" font-size="11" fill="#A9A49B">
    <text x="122" y="46" text-anchor="end">Strings (four)</text>
    <text x="150" y="78" text-anchor="end">Bridge</text>
    <text x="150" y="100" text-anchor="end">f-hole (an opening)</text>
    <text x="150" y="131" text-anchor="end" fill="#9C7A3C">Bass bar</text>
    <text x="150" y="151" text-anchor="end">Top plate · spruce</text>
    <text x="150" y="175" text-anchor="end">Rib</text>
    <text x="150" y="207" text-anchor="end">Back plate · maple</text>
    <text x="612" y="115" text-anchor="end" fill="#C9A227">Soundpost</text>
  </g>
  <text x="20" y="234" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">The bridge’s two feet land exactly on two internal parts —</text>
  <text x="20" y="250" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">the left on the bass bar, the right on the soundpost. That is where the vibration splits in two.</text>
</svg>
```

| Route | Path | Result |
|---|---|---|
| **Bass side** | top plate stiffened by the **bass bar** | full low end; the low strings do not collapse |
| **Treble side** | through the **soundpost** into the back plate | the maple back joins in; the top end gains brightness and a core |

The air inside the box is not idle either: it has its own resonance (around 290 Hz in a modern
violin), which fills in exactly the register the low strings are weak in. A violin's voice is
therefore the joint product of **string, top plate, soundpost, back plate and air** — not
simply "good wood".

The strings are tuned **G3–D4–A4–E5** — four **perfect fifths**. That is not arbitrary:
a perfect fifth has one of the simplest frequency ratios, and appears at the very front of the
[[concept:harmonic-series|harmonic series]]. Overtones of adjacent strings therefore coincide,
so every open string can be found among another string's overtones. On this instrument,
intuition is not guesswork: the player's hand and ear work from the **interval relationships
between the strings**, not from a grid.

## Range

```range
{"range":"G3–E7","common":"G3–E6","caption":"小提琴的实音音域与常用音区","caption_en":"The violin’s sounding range and its working register","note":"小提琴是实音乐器：记谱音与实际音高相同，不移调。四个空弦音 G3、D4、A4、E5 都落在图内。"}
```

Four octaves of span — but **each string has its own character**, and that is the lever
composers use most often:

| String | Open note | Colour | Typical use |
|---|---|---|---|
| G | G3 | darkest, thickest | bass lines, tragic themes |
| D | D4 | warm, woody | mid-register melody |
| A | A4 | bright, penetrating | the workhorse register for tunes |
| E | E5 | sharpest, brightest | climaxes, cadenzas, extreme high notes |

The same melody on the A string and on the E string sounds markedly different, which is why
players rehearse **when to change string** as carefully as the notes themselves.

## Timbre, and how to hear it

Two features are enough to identify a violin:

1. **A brief scrape at the start.** The first instant of bow contact adds friction noise before
   the steady tone settles in. That scrape is the fingerprint of a bowed instrument — chest
   string patches without it are synthesised, not bowed.
2. **Volume that simply keeps going.** A long note does not decay. A sustained tone with
   constant loudness rules out plucked instruments (guitars) and struck ones (pianos).

Use the player below for the timbre itself. Start with the **synth approximation** — it needs no
download — then switch to **real timbre** if you want the sampled GM instrument.

```audiolab
{"type":"instrument","gm":"Violin","synth":"bowed","phrase":["G3","D4","A4","E5"],"label":"四根空弦：小提琴的四个音区","label_en":"Four open strings — the violin’s four registers","hint":"空弦音 G3–D4–A4–E5 就是纯五度；先听合成近似，再听 GM 采样对照","hint_en":"G3–D4–A4–E5 are the four open strings — each a fifth apart. Try the synth first, then the GM samples."}
```

> The tracks under “Listen in the library” are the **skeleton of the music** — transcription or
> engraving MIDI — while timbre is handled by the player above. They are two layers of the same
> music, not two versions of the same thing.

## Playing techniques

The bow shapes the sound; the left hand shapes pitch and colour:

- **Legato / détaché**: several notes per bow, or one note per bow — the basic unit of phrasing.
- **Spiccato / staccato**: let the bow leave the string and drop back for short, springy notes.
- **Harmonics**: touch the string lightly at the 1/2, 1/3 division and only that partial speaks.
  The [[concept:harmonic-series|harmonic series]] performed live, in front of you.
- **Double stops and chords**: two strings at once (thirds, sixths, octaves); three-note chords
  work too, with the lowest note slightly broken.
- **Vibrato**: the left hand rocks on the fingerboard, bending the pitch five to seven times a
  second. This is the line between an expressive sustained note and a flat one.
- **Mute (con sordino)**: clamped on the bridge, it cuts the highs — the sound recedes and dulls.
- **Pizzicato**: put the bow down and pluck. Same box, immediately a plucked voice.

## The family

The violin is not a single instrument but the top of a set of four, ranked by pitch. All four
are tuned in fifths (the double bass in fourths), so fingerings and intervals transfer closely:
for a player, switching instrument within the family is far easier than switching family.

| Instrument | Body length | Tuning (low→high) | Range | Role in the orchestra |
|---|---|---|---|---|
| **Violin** | 356 mm | G3 D4 A4 E5 | G3–E7 | melody, the top line |
| [[instrument:viola\|Viola]] | 410 mm | C3 G3 D4 A4 | C3–E6 | the middle's glue, inner parts |
| [[instrument:cello\|Cello]] | 760 mm | C2 G2 D3 A3 | C2–C6 | bass line and singing solos |
| [[instrument:double-bass\|Double bass]] | 1,100 mm | E1 A1 D2 G2 | E1–G4 | the floor of the harmony (fourths) |

Beyond the orchestral four, the same bowed or plucked chordophone branch includes the
[[instrument:viol|viol]] (six strings, fretted, the earlier Baroque favourite),
the [[instrument:lute|lute]] and the [[instrument:harp|harp]] (plucked, no bow).
One frequent mix-up: a **fiddle is not a different instrument** — it is normally a violin,
differing only in tuning, hold and repertoire.

## History

The modern violin took shape in 16th–18th-century Italy: three generations in Cremona — Amati,
Stradivari, Guarneri — pushed the body proportions to what they still are. The largest changes
since then were not to the body but to the **fittings**:

| Part | Baroque | Modern |
|---|---|---|
| Neck | roughly parallel to the top, short | angled back, lengthened |
| Bass bar | thin | thicker and taller |
| Strings | gut | metal-wound (steel E) |
| Bridge and fingerboard | low, short | high, long |
| Chinrest and shoulder rest | none | added from the 19th century |

Every one of those changes pushed in a single direction: **louder**. To fill ever larger halls,
string tension rose; the top plate then needed more support, so the bass bar grew; the neck was
angled back and the fingerboard lengthened so the instrument could carry that tension and those
higher positions. The cost was a softening of the gut-strung Baroque tone — which is exactly why
the historical-performance movement puts instruments back to Baroque specification.

## Common misconceptions

- **"The violin reaches as high as the piano."** No. The piano goes to C8; the violin's extreme
  lies around E7, a major third lower. But the violin is far more **usable and audible across
  G3–E6**, where the piano needs a pile of notes to compete.
- **"No frets means it plays out of tune."** Frets are absent precisely so pitch can move
  continuously (vibrato, fine adjustment) and so the four strings form their own system of
  intervals. Intonation is trained, not gridded.
- **"The hair should be as tight as possible."** The opposite: over-tight hair kills the stick's
  spring, so spiccato and control disappear, and the hair and stick suffer. In playing, the hair
  lies almost against the stick.
- **"A more expensive instrument sounds better."** Sound is a system — instrument, bow, rosin,
  player, room. In repeated blind tests neither players nor listeners could reliably pick out the
  old Italian instruments, and modern ones were sometimes preferred.
- **"All four strings are the same thickness."** They get thinner from G to E: a thick string
  vibrates slowly. Which is also why the bass strings need length, and why the double bass moved
  to fourths.
- **"A bigger instrument is just an enlarged violin."** The double bass is tuned in fourths
  (E–A–D–G), with a different neck angle and bow grip; its bowing technique is a system of its own.

## Next

A good order from here: listen to the [[instrument:viola|viola]] first — same family, only a
fifth lower, but the difference in role is far bigger than the difference in pitch. Then read
[[concept:articulation|articulation]] (the same instrument changes language with every bow
stroke), and finally [[concept:timbre|timbre]], to tie these impressions back to concepts.
:::
