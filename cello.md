---
id: cello
site: inst
cat: I1
title: 大提琴
title_en: Cello
summary: 抱在膝间演奏的男中音弦乐器，音色最接近人声，独奏曲目从巴赫开始
summary_en: The baritone of the string family, held between the knees — its voice is the closest to a human one
level: core
tags: [乐器, 弦乐, 西洋]
tags_en: [instrument, strings, western]
alias: [大提琴, cello, violoncello, 大提琴]
order: 12
links:
  - "[[concept:register]]"
  - "[[concept:clef]]"
  - "[[concept:timbre]]"
  - "[[concept:articulation]]"
  - "[[concept:melody]]"
  - "[[concept:harmonic-series]]"
  - "[[instrument:violin]]"
  - "[[instrument:viola]]"
  - "[[instrument:double-bass]]"
instances:
  - musicnet-000020 | 无伴奏大提琴组曲的前奏曲 —— 分解和弦与持续低音一条线走完，最能听出低音区的共鸣与余音
  - musicnet-000023 | 同一组曲的萨拉班德舞曲，慢速歌唱性段落，大提琴"像人声"的说法就出自这种写法
  - musicnet-000025 | 同一组曲的吉格舞曲，快速断奏与换弦，可对照上一首听弓法差异
  - giantmidi-007290 | 独奏大提琴变奏曲 —— 纯独奏织体，没有伴奏把人声般的音色糊掉
  - musicnet-000069 | 弦乐四重奏的慢乐章 —— 大提琴在重奏里最常见的职能，用长音与走动铺住地基
sources:
  - 琴体尺寸取通行制琴数据：琴体长 760 毫米（4/4），弦长约 690 毫米，上琴腰宽 340、腰宽 240、下琴腰宽 450 毫米
  - 定弦 C–G–D–A（比中提琴低一个八度）与音域范围属通行乐器学常识，各版乐器词典表述一致，本文为原创表述
  - 尾柱（endpin）19 世纪中叶起普及、以及它同时承担"固定琴身"与"耦合地板"两项功能，依通行制琴史与演奏史叙述
  - 谱号用法（低音谱号为主，高把位转次中音谱号或高音谱号）依通行记谱规范
updated: 2026-09-25
---

::: zh
大提琴是弦乐家族里的**男中音**：比中提琴低一个八度，却不像低音提琴那样只做地基。
它同时拥有两件事 —— **低音的重量**与**歌唱的音区**，所以既能压住和声，也能唱主旋律。

| 分类 | 归属 |
|---|---|
| **HS 分类** | **弦鸣**（Chordophone）—— 发声体是弦本身 |
| **次级类型** | 摩擦激励（用弓擦弦）· 有颈、有板腔共鸣箱 |
| **所属族** | 西洋 · 弦乐 |
| **八音** | 不适用 —— 周代八音是中国乐器的体系，大提琴不在其中 |

## 结构：尺寸终于"够大"了

```svg
<svg viewBox="0 0 640 484" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="大提琴外形与主要部件：琴头、弦轴、指板、琴体、f 孔、琴桥、系弦板、尾柱与地板">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">大提琴 · 外形与主要部件（抱在膝间演奏，没有腮托）</text>
  </g>
  <!-- 指板（比小提琴粗、宽） -->
  <path d="M306,74 L334,74 L343,262 L297,262 Z" fill="#0E0E10"/>
  <!-- 琴头与弦轴 -->
  <path d="M306,32 L334,32 L336,74 L304,74 Z" fill="#17171A" stroke="#343439" stroke-width="1.2"/>
  <path d="M320,30 C309,30 302,21 306,11 C310,2 322,-2 330,4 C338,9 337,20 328,23 C322,25 317,21 318,16"
        fill="none" stroke="#A9A49B" stroke-width="2.4" stroke-linecap="round"/>
  <g fill="#343439">
    <rect x="288" y="40" width="16" height="6" rx="1"/>
    <rect x="336" y="40" width="16" height="6" rx="1"/>
    <rect x="290" y="58" width="14" height="6" rx="1"/>
    <rect x="336" y="58" width="14" height="6" rx="1"/>
  </g>
  <!-- 琴体 -->
  <path d="M320,120 C326.7,121.3 350.6,123.9 360.3,127.8 C370,131.7 372,134.3 378.2,143.4 C384.3,152.5 399.8,168.1 397,182.4 C394.1,196.7 361.1,214.5 361.1,229.2 C361.1,243.9 391,257.8 397,270.8 C403,283.8 397,294.2 397,307.2 C397,320.2 403.7,338.2 397,348.8 C390.2,359.4 369.2,365.7 356.4,370.9 C343.6,376.1 326.1,378.5 320,380 M320,380 C313.9,378.5 296.4,376.1 283.6,370.9 C270.8,365.7 249.8,359.4 243,348.8 C236.3,338.2 243,320.2 243,307.2 C243,294.2 237,283.8 243,270.8 C249,257.8 278.9,243.9 278.9,229.2 C278.9,214.5 245.9,196.7 243,182.4 C240.2,168.1 255.7,152.5 261.8,143.4 C268,134.3 270,131.7 279.7,127.8 C289.4,123.9 313.3,121.3 320,120 Z"
        fill="#17171A" stroke="#343439" stroke-width="1.4"/>
  <!-- f 孔 -->
  <g stroke="#0E0E10" stroke-width="7" stroke-linecap="round" fill="none">
    <path d="M285,190 C277,213 293,245 285,268"/>
    <path d="M355,190 C363,213 347,245 355,268"/>
  </g>
  <!-- 琴桥 -->
  <path d="M292,252 L348,252 L344,259 L296,259 Z" fill="#A9A49B"/>
  <!-- 系弦板 -->
  <path d="M306,300 L334,300 L328,364 L312,364 Z" fill="#0E0E10" stroke="#343439" stroke-width="1"/>
  <!-- 尾柱与地板 -->
  <g stroke="#A9A49B" stroke-width="2.6" stroke-linecap="round">
    <path d="M320,382 L320,436"/>
  </g>
  <path d="M313,436 L327,436 L320,448 Z" fill="#A9A49B"/>
  <g stroke="#6E6A64" stroke-width="1.6" stroke-linecap="round">
    <path d="M180,452 L460,452"/>
  </g>
  <g stroke="#343439" stroke-width="1">
    <path d="M190,458 L184,466"/><path d="M230,458 L224,466"/><path d="M270,458 L264,466"/>
    <path d="M310,458 L304,466"/><path d="M350,458 L344,466"/><path d="M390,458 L384,466"/>
    <path d="M430,458 L424,466"/>
  </g>
  <!-- 四根弦 -->
  <g stroke="#C9A227" opacity=".85">
    <path d="M310,76 L310,306" stroke-width="1.5"/>
    <path d="M316.5,76 L316.5,306" stroke-width="1.2"/>
    <path d="M323,76 L323,306" stroke-width="1"/>
    <path d="M329,76 L329,306" stroke-width=".8"/>
  </g>
  <!-- 标注 -->
  <g class="lead" stroke="#6E6A64" stroke-width=".9">
    <path d="M528,38 L340,44"/><path d="M486,58 L340,60"/><path d="M186,108 L304,110"/>
    <path d="M530,148 L332,148"/><path d="M524,176 L378,176"/>
    <path d="M186,198 L276,200"/><path d="M572,250 L350,250"/><path d="M528,290 L392,290"/>
    <path d="M542,330 L340,328"/><path d="M186,340 L266,338"/><path d="M186,412 L312,414"/>
    <path d="M396,438 L440,450"/>
  </g>
  <g font-family="system-ui,sans-serif" font-size="11" fill="#A9A49B">
    <text x="600" y="41" text-anchor="end">琴头（涡卷）</text>
    <text x="600" y="61" text-anchor="end">弦轴 · 四个</text>
    <text x="180" y="111" text-anchor="end">指板（更长更宽）</text>
    <text x="600" y="151" text-anchor="end">C 弦（最粗）</text>
    <text x="600" y="179" text-anchor="end">琴体 760 mm</text>
    <text x="180" y="201" text-anchor="end">f 孔</text>
    <text x="180" y="341" text-anchor="end">膝间持琴 · 无腮托</text>
    <text x="610" y="253" text-anchor="end">琴桥</text>
    <text x="610" y="293" text-anchor="end">面板（云杉）</text>
    <text x="610" y="333" text-anchor="end">系弦板</text>
    <text x="180" y="415" text-anchor="end">尾柱（19 世纪中叶起普及）</text>
    <text x="610" y="441" text-anchor="end">地板</text>
  </g>
  <text x="20" y="480" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">760 毫米已经接近"按比例该有的尺寸"，所以大提琴没有中提琴那种尺寸困境。</text>
</svg>
```

大提琴的琴体长 **760 毫米**，弦长 **690 毫米**。按上一节中提琴用的同一把尺子算：
**它基本就是按比例该有的尺寸** —— 没有那个"够不到"的缺口。
所以它的低音（C2）有底气，音色也没有中提琴那种闷。

三件家族乐器在小提琴式的工艺下逐级放大，这里第一次**放大到位**。

## 发声原理：多了尾柱这一条路

大提琴的声学机制与小提琴完全同构：弦 → 琴桥 → 面板 → **音柱**传背板、**低音梁**撑低音，
箱内空气补上低频。这一套不重复，见 [[instrument:violin|小提琴]] 一节。

它多出来的是**尾柱**（endpin）—— 琴体底部伸出的一根金属或碳纤维细杆。它做两件事：

```svg
<svg viewBox="0 0 640 320" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="大提琴纵剖示意：弦、琴桥、琴体、尾柱与地板，以及振动经尾柱传向地板的路径">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="20">纵剖示意 · 尾柱做了两件事</text>
  </g>
  <!-- 弦（端视）与琴桥 -->
  <g fill="#C9A227">
    <circle cx="305" cy="50" r="3.2"/><circle cx="313" cy="50" r="3.2"/>
    <circle cx="321" cy="50" r="3.2"/><circle cx="329" cy="50" r="3.2"/>
  </g>
  <path d="M304,58 L330,58 L333,92 L352,92 L352,100 L282,100 L282,92 L301,92 Z" fill="#A9A49B"/>
  <!-- 琴体（示意） -->
  <rect x="250" y="100" width="140" height="112" rx="6" fill="#17171A" stroke="#343439" stroke-width="1.4"/>
  <path d="M250,128 C280,120 360,120 390,128" fill="none" stroke="#A9A49B" stroke-width="2.4"/>
  <path d="M250,186 C280,196 360,196 390,186" fill="none" stroke="#6E6A64" stroke-width="2.8"/>
  <text x="320" y="160" text-anchor="middle" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">腹腔空气</text>
  <!-- 尾柱 -->
  <g stroke="#A9A49B" stroke-width="2.6" stroke-linecap="round">
    <path d="M320,212 L320,272"/>
  </g>
  <path d="M313,272 L327,272 L320,284 Z" fill="#A9A49B"/>
  <!-- 地板 -->
  <g stroke="#6E6A64" stroke-width="1.6" stroke-linecap="round">
    <path d="M170,286 L470,286"/>
  </g>
  <g stroke="#343439" stroke-width="1">
    <path d="M180,292 L174,300"/><path d="M220,292 L214,300"/><path d="M260,292 L254,300"/>
    <path d="M300,292 L294,300"/><path d="M340,292 L334,300"/><path d="M380,292 L374,300"/>
    <path d="M420,292 L414,300"/><path d="M460,292 L454,300"/>
  </g>
  <!-- 振动路径 -->
  <g stroke="#9C7A3C" stroke-width="1.4" fill="none">
    <path d="M352,214 L352,268"/>
    <path d="M346,258 L352,268 L358,258"/>
  </g>
  <text x="366" y="246" font-family="system-ui,sans-serif" font-size="11" fill="#9C7A3C">振动 → 地板</text>
  <!-- 标注 -->
  <g class="lead" stroke="#6E6A64" stroke-width=".9">
    <path d="M186,50 L296,50"/><path d="M186,84 L296,84"/><path d="M186,140 L244,140"/>
    <path d="M186,246 L308,250"/><path d="M186,290 L162,288"/>
  </g>
  <g font-family="system-ui,sans-serif" font-size="11" fill="#A9A49B">
    <text x="180" y="53" text-anchor="end">四根弦</text>
    <text x="180" y="87" text-anchor="end">琴桥</text>
    <text x="180" y="143" text-anchor="end">琴体（面板 / 侧板 / 背板）</text>
    <text x="180" y="249" text-anchor="end">尾柱</text>
  </g>
  <text x="20" y="312" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">尾柱把琴固定住（左手因此自由），也把振动送进地板 —— 低频因此更实。</text>
</svg>
```

1. **把琴固定住**。没有尾柱，大提琴得用两腿夹住整个琴体 —— 那样左手换把会受限。
   19 世纪中叶尾柱普及之后，琴身交给一根杆子支撑，演奏者的双腿与左手都松开了。
2. **把振动耦合到地板**。琴体底部的振动经尾柱传进地板，地板跟着一起振 ——
   舞台的木地板相当于多了一个巨大的共鸣体。这也是为什么同一把琴在不同场地的低频听感会变。

## 音域

```range
{"range":"C2–C6","common":"C2–G4","caption":"大提琴的音域与常用音区","caption_en":"The cello’s range and its working register","note":"大提琴是实音乐器，记谱音与实际音高相同。最低的 C2 是 C 弦空弦，比中提琴最低的 C3 低一个八度。"}
```

四个八度。这段音域的位置很关键：

- **它的低端（C2–G2）刚好在"有音高感的低频"下缘** —— 比这更低就到了低音提琴的地界，
  那里的音高感开始变得含糊。
- **它的中段（C3–C5）与人声的中音区重叠** —— 这就是"像人声"说法的物理来源。
  作曲家用它写旋律时，听者会觉得像有人在唱，而不是像乐器在响。

谱号上有条实用知识：大提琴主要用**低音谱号**；上到高把位时改用**次中音谱号**
（tenor clef，第四线为中央 C），再高会用[[concept:clef|高音谱号]]。
三个谱号不是炫技，是为了让音符尽可能落在五线谱内。

| 弦 | 空弦音 | 音色 |
|---|---|---|
| C 弦 | C2 | 厚、有重量，是四弦里最"低音"的一根 |
| G 弦 | G2 | 饱满，常用旋律区 |
| D 弦 | D3 | 温暖，接近人声的中音区 |
| A 弦 | A3 | 最明亮，独奏的常用入口 |

## 音色与听辨

大提琴最好认的特征是**"人声般的持续音"**。三条线索：

1. **长音里有呼吸**。大提琴的连弓长音不是死的：演奏者用它模拟人唱的**乐句** ——
   起音稍晚、中间渐强、句尾收住。听到"一句一句"的走向，多半是大提琴。
2. **低音不是轰，是"托"**。它在低音区没有低音提琴那种压倒性的量感，
   而是清楚、有音高、能跟得上和声变化 —— 这是它比低音提琴更适合写旋律的原因。
3. **A 弦与 C 弦的音色落差很大**。同一段旋律用 A 弦还是 C 弦拉，
   听感会从"明亮"变成"含蓄"。演奏者会为了音色而不是为了省力去选择把位。

下面的试听件给的是四根空弦。**注意 C 弦与 A 弦的落差** —— 这是它在家族里最特别的地方：
一根弦在低音，一根弦在中音，而两者都属于同一件"能唱歌"的乐器。

```audiolab
{"type":"instrument","gm":"Cello","synth":"bowed","phrase":["C2","G2","D3","A3"],"label":"四根空弦：从 C 弦到 A 弦","label_en":"Four open strings — C up to A","hint":"注意最低的 C2 与最高的 A3 的音色落差；这是大提琴能同时做低音与旋律的原因","hint_en":"Note the tonal gap between the low C2 and the A3 — that range is why a cello can carry both the bass and the tune."}
```

> 本页「在库中听例子」里的曲子是**乐谱与演奏的骨架**（转写或雕版 MIDI），
> 音色由上面的试听件负责。

## 演奏技法

大提琴的左手与小提琴同源，右手则**分成了两派**：

- **法式弓（正握）**：弓毛箱在下、手心朝下，与更小的弦乐器接近。
- **德式弓（下握）**：手在弓毛箱**上方**，是低音弦乐器的老传统。
  两派的差别不只是握法 —— 弓的配重与手腕发力方式不同，音色与跳弓的手感都不同。

需要单独说的几件事：

- **尾柱改变了持琴**：琴身被地面支撑，左手不必再承担"稳住琴"的任务 ——
  这让大提琴的换把比小提琴式的夹持更自由，也让`拇指把位`（左手拇指按在指板上）成为可能。
- **拇指把位**：上到高把位时左手越过琴颈，拇指直接按弦。这是高把位的必需技术。
- **双音与和弦**：大提琴的四根弦张力高、弦距大，拉双音需要更多的右手压力，
  和弦通常要"分解"成两弓。
- **拨弦（pizzicato）**：在爵士与探戈里，大提琴的拨弦是独立的一门手艺
  （音量大、余音长、可以做出"走路低音"）。

## 家族与近亲

| 乐器 | 琴体长约 | 弦长约 | 定弦（低→高） | 实音音域 | 在乐队里干什么 |
|---|---|---|---|---|---|
| [[instrument:violin\|小提琴]] | 356 毫米 | 328 毫米 | G3 D4 A4 E5 | G3–E7 | 主旋律、最高声部 |
| [[instrument:viola\|中提琴]] | 410 毫米 | 370 毫米 | C3 G3 D4 A4 | C3–E6 | 中音区黏合剂 |
| **大提琴** | 760 毫米 | 690 毫米 | C2 G2 D3 A3 | C2–C6 | 低音线条兼歌唱性独奏 |
| [[instrument:double-bass\|低音提琴]] | 1,100 毫米 | 1,050 毫米 | E1 A1 D2 G2 | E1–G4 | 和声的地基（四度定弦） |

留意**弦长那一列**：小提琴的弦长只有琴体长的 0.92 倍，大提琴是 0.91 倍 —— 两件基本一致。
到了低音提琴，这个比变成 0.95 倍以上，而且定弦**从五度改成了四度**。
这是家族里唯一一次规则改动，原因见 [[instrument:double-bass|低音提琴]] 一节。

## 历史演变

大提琴的前身是 16 世纪的**低音维奥尔**（bass viol）。与小提琴家族的其他成员一样，
它在 17 世纪逐步取代了维奥尔的位置：维奥尔有品、竖持、音色更薄，
大提琴无品、横抱于膝间、音量更大 —— 更适合进入越来越大的合奏场合。

真正的转折点在 18 世纪：**巴赫的无伴奏大提琴组曲**（BWV 1007–1012）证明了一件
"低音乐器"可以独自撑起一场音乐。这六首组曲在大提琴史上的地位，
大约相当于《平均律》在键盘乐器史上的地位。

19 世纪它又多了两样东西：**尾柱**（约 1840 年代起普及）与**更粗的金属缠弦**。
两者一起把它的音量与音域都推高了，于是大提琴从"低音声部"变成了**独奏乐器** ——
协奏曲、奏鸣曲的传统从这一百年开始真正成形。

今天的处境很清楚：**在管弦乐队里，它是低音的骨干；在室内乐里，它是旋律与对话的参与者；
在独奏舞台上，它的曲目横跨巴洛克到当代。** 三件事它都做，而且都是主力。

## 常见误解

- **"大提琴就是放大版的小提琴。"** → 形状与工艺是放大的（几何相似），但**持琴方式与弓法
  是独立的一套**：抱在膝间、尾柱支撑、德式/法式两种握弓、拇指把位 —— 这些在小提琴上都不存在。
- **"低音乐器只能伴奏。"** → 大提琴是反例：它的中音区能唱歌，独奏曲目从巴赫起就没有断过。
  "低音"说的是它最强的区域，不是它唯一的区域。
- **"C 弦比低音提琴的 E 弦低。"** → 反了。低音提琴最低到 E1，比大提琴的 C2 还低六度。
  这也是两件乐器分工不同的原因。
- **"尾柱只是用来把琴架高。"** → 架高只是附带效果。它真正的两件事是**把琴固定住**
  （解放左手）与**把振动耦合到地板**。换场地时低频听感变化，原因就在这里。
- **"五个谱号太复杂。"** → 大提琴主要在**三个**谱号间切换（低音、次中音、高音），
  而且切换是为了少画加线。会读三个谱号是大提琴手的日常，不是特殊技能。

## 下一步

顺着家族继续听：往上是 [[instrument:viola|中提琴]]（同一个低音区方向上的另一条路，
但它背负着尺寸问题），往下是 [[instrument:double-bass|低音提琴]]（家族里唯一改了定弦规则的一件）。
想接概念的话，[[concept:melody|旋律]] 与 [[concept:register|音区]] 两节会解释
"为什么中音区听起来像人声"。
:::

::: en
The cello is the **baritone** of the string family: an octave below the viola, yet nothing like the
double bass's role of pure foundation. It owns two things at once — **the weight of a bass** and
**a singing register** — so it can hold down the harmony and carry the tune.

| Classification | Value |
|---|---|
| **HS class** | **Chordophone** — the vibrating body is the string itself |
| **Sub-type** | Friction-excited (bowed) · necked, with a box resonator |
| **Family** | Western · Strings |
| **Bayin** | Not applicable — the eight categories are a Chinese system; the cello is outside it |

## Structure: finally big enough

```svg
<svg viewBox="0 0 640 484" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Cello parts: scroll, tuning pegs, fingerboard, body, f-holes, bridge, tailpiece, endpin and floor">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">Cello — outer form and principal parts (held between the knees; no chinrest)</text>
  </g>
  <!-- fingerboard -->
  <path d="M306,74 L334,74 L343,262 L297,262 Z" fill="#0E0E10"/>
  <!-- scroll and pegs -->
  <path d="M306,32 L334,32 L336,74 L304,74 Z" fill="#17171A" stroke="#343439" stroke-width="1.2"/>
  <path d="M320,30 C309,30 302,21 306,11 C310,2 322,-2 330,4 C338,9 337,20 328,23 C322,25 317,21 318,16"
        fill="none" stroke="#A9A49B" stroke-width="2.4" stroke-linecap="round"/>
  <g fill="#343439">
    <rect x="288" y="40" width="16" height="6" rx="1"/>
    <rect x="336" y="40" width="16" height="6" rx="1"/>
    <rect x="290" y="58" width="14" height="6" rx="1"/>
    <rect x="336" y="58" width="14" height="6" rx="1"/>
  </g>
  <!-- body -->
  <path d="M320,120 C326.7,121.3 350.6,123.9 360.3,127.8 C370,131.7 372,134.3 378.2,143.4 C384.3,152.5 399.8,168.1 397,182.4 C394.1,196.7 361.1,214.5 361.1,229.2 C361.1,243.9 391,257.8 397,270.8 C403,283.8 397,294.2 397,307.2 C397,320.2 403.7,338.2 397,348.8 C390.2,359.4 369.2,365.7 356.4,370.9 C343.6,376.1 326.1,378.5 320,380 M320,380 C313.9,378.5 296.4,376.1 283.6,370.9 C270.8,365.7 249.8,359.4 243,348.8 C236.3,338.2 243,320.2 243,307.2 C243,294.2 237,283.8 243,270.8 C249,257.8 278.9,243.9 278.9,229.2 C278.9,214.5 245.9,196.7 243,182.4 C240.2,168.1 255.7,152.5 261.8,143.4 C268,134.3 270,131.7 279.7,127.8 C289.4,123.9 313.3,121.3 320,120 Z"
        fill="#17171A" stroke="#343439" stroke-width="1.4"/>
  <!-- f-holes -->
  <g stroke="#0E0E10" stroke-width="7" stroke-linecap="round" fill="none">
    <path d="M285,190 C277,213 293,245 285,268"/>
    <path d="M355,190 C363,213 347,245 355,268"/>
  </g>
  <!-- bridge -->
  <path d="M292,252 L348,252 L344,259 L296,259 Z" fill="#A9A49B"/>
  <!-- tailpiece -->
  <path d="M306,300 L334,300 L328,364 L312,364 Z" fill="#0E0E10" stroke="#343439" stroke-width="1"/>
  <!-- endpin and floor -->
  <g stroke="#A9A49B" stroke-width="2.6" stroke-linecap="round">
    <path d="M320,382 L320,436"/>
  </g>
  <path d="M313,436 L327,436 L320,448 Z" fill="#A9A49B"/>
  <g stroke="#6E6A64" stroke-width="1.6" stroke-linecap="round">
    <path d="M180,452 L460,452"/>
  </g>
  <g stroke="#343439" stroke-width="1">
    <path d="M190,458 L184,466"/><path d="M230,458 L224,466"/><path d="M270,458 L264,466"/>
    <path d="M310,458 L304,466"/><path d="M350,458 L344,466"/><path d="M390,458 L384,466"/>
    <path d="M430,458 L424,466"/>
  </g>
  <!-- four strings -->
  <g stroke="#C9A227" opacity=".85">
    <path d="M310,76 L310,306" stroke-width="1.5"/>
    <path d="M316.5,76 L316.5,306" stroke-width="1.2"/>
    <path d="M323,76 L323,306" stroke-width="1"/>
    <path d="M329,76 L329,306" stroke-width=".8"/>
  </g>
  <!-- labels -->
  <g class="lead" stroke="#6E6A64" stroke-width=".9">
    <path d="M560,38 L340,44"/><path d="M486,58 L340,60"/><path d="M186,108 L304,110"/>
    <path d="M480,148 L332,148"/><path d="M524,176 L378,176"/>
    <path d="M186,198 L276,200"/><path d="M560,250 L350,250"/><path d="M496,290 L392,290"/>
    <path d="M542,330 L340,328"/><path d="M186,340 L266,338"/><path d="M186,412 L312,414"/>
    <path d="M396,438 L440,450"/>
  </g>
  <g font-family="system-ui,sans-serif" font-size="11" fill="#A9A49B">
    <text x="600" y="41" text-anchor="end">Scroll</text>
    <text x="600" y="61" text-anchor="end">Tuning pegs (four)</text>
    <text x="180" y="111" text-anchor="end">Fingerboard (longer, wider)</text>
    <text x="600" y="151" text-anchor="end">C string (thickest)</text>
    <text x="600" y="179" text-anchor="end">Body 760 mm</text>
    <text x="180" y="201" text-anchor="end">f-hole</text>
    <text x="180" y="341" text-anchor="end">Held between the knees</text>
    <text x="610" y="253" text-anchor="end">Bridge</text>
    <text x="610" y="293" text-anchor="end">Top plate · spruce</text>
    <text x="610" y="333" text-anchor="end">Tailpiece</text>
    <text x="180" y="415" text-anchor="end">Endpin (from the 1840s)</text>
    <text x="610" y="441" text-anchor="end">Floor</text>
  </g>
  <text x="20" y="480" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">At 760 mm the cello is close to the size its proportions call for — so it has none of the viola's trouble.</text>
</svg>
```

The cello's body is **760 mm** and its string length **690 mm**. Measured with the same ruler the viola
was measured on, **it is essentially the size its proportions demand** — no unreachable gap. So its
low C has weight, and it lacks the viola's covered, nasal quality.

Three family instruments scaled up under violin-making technique — and here, for the first time,
the scaling lands where it should.

## How it sounds: one extra path

The acoustics are identical in structure to the violin's: string → bridge → top plate, with the
**soundpost** feeding the back plate, the **bass bar** supporting the low end, and the enclosed air
filling in the bass. That mechanism is not repeated here — see [[instrument:violin|violin]].

What the cello adds is the **endpin** — a thin metal or carbon rod from the bottom of the body.
It does two things:

```svg
<svg viewBox="0 0 640 344" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Cello section diagram: strings, bridge, body, endpin and floor, with the vibration path through the endpin into the floor">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="20">Section diagram · the endpin does two jobs</text>
  </g>
  <g fill="#C9A227">
    <circle cx="305" cy="50" r="3.2"/><circle cx="313" cy="50" r="3.2"/>
    <circle cx="321" cy="50" r="3.2"/><circle cx="329" cy="50" r="3.2"/>
  </g>
  <path d="M304,58 L330,58 L333,92 L352,92 L352,100 L282,100 L282,92 L301,92 Z" fill="#A9A49B"/>
  <rect x="250" y="100" width="140" height="112" rx="6" fill="#17171A" stroke="#343439" stroke-width="1.4"/>
  <path d="M250,128 C280,120 360,120 390,128" fill="none" stroke="#A9A49B" stroke-width="2.4"/>
  <path d="M250,186 C280,196 360,196 390,186" fill="none" stroke="#6E6A64" stroke-width="2.8"/>
  <text x="320" y="160" text-anchor="middle" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">Air in the box</text>
  <g stroke="#A9A49B" stroke-width="2.6" stroke-linecap="round">
    <path d="M320,212 L320,272"/>
  </g>
  <path d="M313,272 L327,272 L320,284 Z" fill="#A9A49B"/>
  <g stroke="#6E6A64" stroke-width="1.6" stroke-linecap="round">
    <path d="M170,286 L470,286"/>
  </g>
  <g stroke="#343439" stroke-width="1">
    <path d="M180,292 L174,300"/><path d="M220,292 L214,300"/><path d="M260,292 L254,300"/>
    <path d="M300,292 L294,300"/><path d="M340,292 L334,300"/><path d="M380,292 L374,300"/>
    <path d="M420,292 L414,300"/><path d="M460,292 L454,300"/>
  </g>
  <g stroke="#9C7A3C" stroke-width="1.4" fill="none">
    <path d="M352,214 L352,268"/>
    <path d="M346,258 L352,268 L358,258"/>
  </g>
  <text x="366" y="246" font-family="system-ui,sans-serif" font-size="11" fill="#9C7A3C">vibration → floor</text>
  <g class="lead" stroke="#6E6A64" stroke-width=".9">
    <path d="M186,50 L296,50"/><path d="M186,84 L296,84"/><path d="M186,140 L244,140"/>
    <path d="M186,246 L308,250"/><path d="M186,290 L162,288"/>
  </g>
  <g font-family="system-ui,sans-serif" font-size="11" fill="#A9A49B">
    <text x="180" y="53" text-anchor="end">Four strings</text>
    <text x="180" y="87" text-anchor="end">Bridge</text>
    <text x="180" y="143" text-anchor="end">Body — plate / ribs / back</text>
    <text x="180" y="249" text-anchor="end">Endpin</text>
  </g>
  <text x="20" y="312" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">The endpin steadies the instrument (freeing the left hand) and feeds</text>
  <text x="20" y="328" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">vibration into the floor — so the bass end gains solidity.</text>
</svg>
```

1. **It steadies the instrument.** Without an endpin, both knees had to clamp the whole body — and
   that restricts shifting with the left hand. Once the pin took over the support in the 1840s, legs
   and left hand were both released.
2. **It couples vibration into the floor.** The bottom of the body feeds the floor through the pin,
   and the floor moves with it — a wooden stage acts as a second, enormous resonator. That is why the
   same instrument can feel different in the bass end from one hall to the next.

## Range

```range
{"range":"C2–C6","common":"C2–G4","caption":"大提琴的音域与常用音区","caption_en":"The cello’s range and its working register","note":"大提琴是实音乐器，记谱音与实际音高相同。最低的 C2 是 C 弦空弦，比中提琴最低的 C3 低一个八度。"}
```

Four octaves, and where they sit matters:

- **Its bottom (C2–G2) sits right at the lower edge of pitched low sound.** Go lower and you are in
  double-bass territory, where pitch itself starts to blur.
- **Its middle (C3–C5) overlaps the human middle voice** — that is where "it sounds like a voice"
  comes from physically. Composing a melody there makes a listener feel someone is singing rather
  than an instrument sounding.

One practical clef note: the cello reads mainly **bass clef**; high passages switch to **tenor clef**
(fourth line = middle C), and higher still to [[concept:clef|treble clef]]. Three clefs is not
showing off — it keeps the notes on the staff.

| String | Open note | Colour |
|---|---|---|
| C | C2 | thick and weighty, the most "bass" of the four |
| G | G2 | full; a common melodic register |
| D | D3 | warm, close to a human middle voice |
| A | A3 | the brightest, a natural entry point for solo work |

## Timbre, and how to hear it

The cello's clearest signature is the **voice-like sustained tone**. Three cues:

1. **Long notes breathe.** A cello's sustained note is not static: players shape it like a sung
   **phrase** — a slightly late attack, a swell in the middle, a controlled ending. If you hear
   sentences rather than notes, it is probably a cello.
2. **The bass does not thump, it carries.** In the low register it lacks the double bass's sheer
   mass, but it stays clear, pitched, and able to follow the harmony — which is exactly why it suits
   melody better.
3. **A string and C string are far apart in colour.** The same tune on the A string and on the C
   string changes from bright to reserved. Players choose positions for colour, not just for comfort.

The player below gives the four open strings. **Listen for the gap between C2 and A3** — that range
is why one instrument can be both the bass and the tune.

```audiolab
{"type":"instrument","gm":"Cello","synth":"bowed","phrase":["C2","G2","D3","A3"],"label":"四根空弦：从 C 弦到 A 弦","label_en":"Four open strings — C up to A","hint":"注意最低的 C2 与最高的 A3 的音色落差；这是大提琴能同时做低音与旋律的原因","hint_en":"Note the tonal gap between the low C2 and the A3 — that range is why a cello can carry both the bass and the tune."}
```

> The tracks under “Listen in the library” are the **skeleton of the music** — transcription or
> engraving MIDI — while timbre is handled by the player above.

## Playing techniques

The left hand follows the violin; the right hand **splits into two schools**:

- **French bow (overhand)**: the frog below, palm down — close to the smaller strings' grip.
- **German bow (underhand)**: the hand **above** the frog — the older tradition of the low strings.

The difference is not cosmetic: weight distribution and wrist action differ, so tone and the feel of
spiccato differ too.

Three things specific to this instrument:

- **The endpin changes the hold.** With the body supported by the floor, the left hand no longer has
  to keep the instrument steady — shifting is freer than in a chin-held instrument, and
  `thumb position` (left thumb pressing on the fingerboard) becomes possible.
- **Thumb position.** In high registers the left hand comes over the neck and the thumb stops the
  string directly. It is not optional technique; it is required.
- **Double stops, chords and pizzicato.** High tension and wide string spacing demand real bow
  pressure for double stops, and chords are usually broken across two strokes. In jazz and tango,
  cello pizzicato is a craft in itself — loud, long-ringing, able to walk a bass line.

## The family

| Instrument | Body | String length | Tuning (low→high) | Range | Role |
|---|---|---|---|---|---|
| [[instrument:violin\|Violin]] | 356 mm | 328 mm | G3 D4 A4 E5 | G3–E7 | melody, the top line |
| [[instrument:viola\|Viola]] | 410 mm | 370 mm | C3 G3 D4 A4 | C3–E6 | the middle's glue |
| **Cello** | 760 mm | 690 mm | C2 G2 D3 A3 | C2–C6 | bass line and singing solos |
| [[instrument:double-bass\|Double bass]] | 1,100 mm | 1,050 mm | E1 A1 D2 G2 | E1–G4 | the floor of the harmony (fourths) |

Note the **string-length column**: on a violin the string is 0.92 of the body length, on a cello 0.91 —
the same ratio. On a double bass it goes above 0.95, and the tuning **changes from fifths to
fourths**. That is the family's one rule change, explained under [[instrument:double-bass|double bass]].

## History

The cello's ancestor is the 16th-century **bass viol**. Like the rest of the violin family it displaced
the viols during the 17th century: viols were fretted, held upright and thinner in tone, while the
cello was fretless, held between the knees and louder — a better fit for ever larger ensembles.

The real turning point came in the 18th century, when **Bach's unaccompanied cello suites**
(BWV 1007–1012) proved that a "bass instrument" could hold a whole piece of music alone. Those six
suites stand to cello history roughly where the Well-Tempered Clavier stands to keyboard history.

The 19th century added two things: the **endpin** (widely adopted from the 1840s) and heavier
metal-wound strings. Together they raised both volume and range, and the cello turned from a bass part
into a **solo instrument** — the concerto and sonata traditions really take shape in that century.

Its position today is clear: **the bass backbone of the orchestra, a conversational partner in chamber
music, and a soloist with a repertoire running from the Baroque to the present.** It does all three,
and it is a main force in each.

## Common misconceptions

- **"A cello is just a big violin."** The shape and craft scale, but **the hold and the bowing are a
  separate system**: between the knees, endpin support, two bow grips, thumb position — none of which
  exist on a violin.
- **"A bass instrument can only accompany."** The cello is the counter-example: its middle register
  sings, and its solo repertoire has been unbroken since Bach. "Bass" describes its strongest region,
  not its only one.
- **"The C string goes lower than the double bass's E."** Backwards. The double bass reaches E1, a
  sixth below the cello's C2. That difference is why the two divide the labour the way they do.
- **"The endpin is just to raise the instrument."** Raising is a side effect. Its real jobs are to
  **steady the body** (freeing the left hand) and to **couple vibration into the floor**. Change venue
  and the bass end changes, for this reason.
- **"Five clefs is too complicated."** The cello mostly uses **three** (bass, tenor, treble), and it
  switches to avoid piles of ledger lines. Reading three clefs is a cellist's daily routine, not a
  special skill.

## Next

Follow the family onwards: up to the [[instrument:viola|viola]] — another route into the lower
register, but one burdened by a size problem — and down to the [[instrument:double-bass|double bass]],
the only member that changed the tuning rule. To tie it to concepts, [[concept:melody|melody]] and
[[concept:register|register]] explain why a middle register can sound like a human voice.
:::
