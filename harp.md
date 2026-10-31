---
id: harp
site: inst
cat: I1
title: 竖琴
title_en: Harp
summary: 四十七根弦、七个踏板的三角框架拨弦乐器，弦只按自然音阶排列
summary_en: Forty-seven strings and seven pedals on a triangular frame — the strings carry only the diatonic scale
level: core
tags: [乐器, 弦乐, 西洋]
tags_en: [instrument, strings, western]
alias: [竖琴, harp, arpa, 音乐会竖琴, 踏板竖琴]
order: 19
links:
  - "[[concept:scale]]"
  - "[[concept:register]]"
  - "[[concept:timbre]]"
  - "[[concept:articulation]]"
  - "[[concept:harmonic-series]]"
  - "[[instrument:violin]]"
  - "[[instrument:classical-guitar]]"
instances:
  - giantmidi-007259 | 竖琴独奏小品 —— 分解和弦与琶音铺满整个音域，最能听出"每根弦只发一个音"这件事
  - giantmidi-006614 | 另一首竖琴独奏曲，织体更密，可对照手指在弦列上的移动方式
  - giantmidi-004921 | 十九世纪竖琴作品，慢速段落多，适合听余音如何在弦列里互相掩盖
  - pdmx-000439 | 竖琴与乐队的作品，能听到它在合奏里如何用琶音铺开和声
  - giantmidi-002931 | 竖琴的沙龙风格小品，句法短、装饰多，是这件乐器 19 世纪最常见的用途
sources:
  - 音乐会踏板竖琴取通行制琴数据：47 根弦、音域 C♭1–G♯7（六个半八度），弦长从约 1,470 毫米（最低）递减到 69 毫米（最高）
  - 「七个踏板分别控制 D C B 与 E F G A 七个音名，每个踏板三档（降／还原／升）」属通行乐器学常识，各版乐器词典表述一致
  - 「弦按降 C 大调自然音阶排列，八度内只有七个音，靠踏板取得全部半音」依通行竖琴演奏法与制琴规范
  - ⚠️ 库内没有标题或作曲家可确认为竖琴的曲目 —— 本条给出的是**同族拨弦曲目**，音色由试听件负责
updated: 2026-09-26
---

::: zh

## 四十七根弦，一个三角

竖琴的音高在造琴时就定死了，每根弦只发一个音。演奏者不按弦、不换把、不用弓，两手只做一件事：拨。所有半音都靠脚下七个踏板改变弦的张力。

| 分类 | 归属 |
|---|---|
| HS 分类 | 弦鸣 —— 发声体是弦本身 |
| 次级类型 | 指腹拨奏 · 弦直接张在共鸣箱与琴颈之间，没有指板 |
| 所属族 | 西洋 · 弦乐（弹拨支系） |
| 八音 | 不适用 —— 周代八音是中国乐器的体系，竖琴不在其中 |

```svg
<svg viewBox="0 0 640 470" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="音乐会竖琴外形与主要部件：柱、琴颈、共鸣箱、底座、踏板与弦列，弦长从低音到高音递减">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">音乐会竖琴 · 框架与主要部件（弦长从低音到高音递减）</text>
  </g>
  <!-- 共鸣箱（斜柱，左） -->
  <path d="M150,60 L196,60 L226,392 L170,392 Z" fill="#17171A" stroke="#343439" stroke-width="1.4"/>
  <!-- 琴颈（上横梁） -->
  <path d="M150,60 L470,150 L470,178 L196,88 Z" fill="#111113" stroke="#343439" stroke-width="1.3"/>
  <!-- 柱（前柱，右） -->
  <path d="M470,150 L498,168 L446,404 L418,388 Z" fill="#17171A" stroke="#343439" stroke-width="1.4"/>
  <!-- 底座 -->
  <path d="M170,392 L446,404 L446,424 L170,412 Z" fill="#111113" stroke="#343439" stroke-width="1.2"/>
  <!-- 弦列（47 根，越长越靠左） -->
  <g stroke="#C9A227" opacity=".85">
    <path d="M182,62 L424,384" stroke-width="1.6"/>
    <path d="M188,64 L424,381" stroke-width="1.5"/>
    <path d="M194,66 L423,378" stroke-width="1.4"/>
    <path d="M200,68 L423,375" stroke-width="1.4"/>
    <path d="M206,70 L423,372" stroke-width="1.3"/>
    <path d="M212,72 L422,369" stroke-width="1.3"/>
    <path d="M218,74 L422,366" stroke-width="1.2"/>
    <path d="M224,76 L422,363" stroke-width="1.2"/>
    <path d="M230,78 L421,360" stroke-width="1.1"/>
    <path d="M236,80 L421,357" stroke-width="1.1"/>
    <path d="M242,82 L421,354" stroke-width="1"/>
    <path d="M248,84 L420,351" stroke-width="1"/>
    <path d="M254,86 L420,348" stroke-width=".95"/>
    <path d="M260,88 L420,345" stroke-width=".95"/>
    <path d="M266,90 L419,342" stroke-width=".9"/>
    <path d="M272,92 L419,339" stroke-width=".9"/>
    <path d="M278,94 L419,336" stroke-width=".85"/>
    <path d="M284,96 L418,333" stroke-width=".85"/>
    <path d="M290,98 L418,330" stroke-width=".8"/>
    <path d="M296,100 L418,327" stroke-width=".8"/>
    <path d="M302,102 L417,324" stroke-width=".75"/>
    <path d="M308,104 L417,321" stroke-width=".75"/>
    <path d="M314,106 L417,318" stroke-width=".7"/>
    <path d="M320,108 L416,315" stroke-width=".7"/>
    <path d="M326,110 L416,312" stroke-width=".65"/>
    <path d="M332,112 L416,309" stroke-width=".65"/>
    <path d="M338,114 L415,306" stroke-width=".6"/>
    <path d="M344,116 L415,303" stroke-width=".6"/>
    <path d="M350,118 L415,300" stroke-width=".55"/>
    <path d="M356,120 L414,297" stroke-width=".55"/>
    <path d="M362,122 L414,294" stroke-width=".5"/>
    <path d="M368,124 L414,291" stroke-width=".5"/>
    <path d="M374,126 L414,288" stroke-width=".45"/>
    <path d="M380,128 L413,285" stroke-width=".45"/>
    <path d="M386,130 L413,282" stroke-width=".4"/>
    <path d="M392,132 L413,279" stroke-width=".4"/>
    <path d="M398,134 L412,276" stroke-width=".35"/>
    <path d="M404,136 L412,273" stroke-width=".35"/>
    <path d="M410,138 L412,270" stroke-width=".3"/>
    <path d="M416,140 L412,267" stroke-width=".3"/>
    <path d="M422,142 L411,264" stroke-width=".28"/>
    <path d="M428,144 L411,261" stroke-width=".28"/>
    <path d="M434,146 L411,258" stroke-width=".25"/>
    <path d="M440,148 L411,255" stroke-width=".25"/>
    <path d="M446,150 L410,252" stroke-width=".22"/>
    <path d="M452,152 L410,249" stroke-width=".22"/>
    <path d="M458,154 L410,246" stroke-width=".2"/>
  </g>
  <!-- 踏板盒 -->
  <path d="M262,424 L346,428 L346,444 L262,440 Z" fill="#0E0E10" stroke="#343439" stroke-width="1.2"/>
  <g fill="#A9A49B">
    <rect x="270" y="428" width="9" height="12" rx="1"/><rect x="284" y="428" width="9" height="12" rx="1"/>
    <rect x="298" y="429" width="9" height="12" rx="1"/><rect x="312" y="429" width="9" height="12" rx="1"/>
    <rect x="326" y="429" width="9" height="12" rx="1"/>
  </g>
  <!-- 标注 -->
  <g class="lead" stroke="#6E6A64" stroke-width=".9">
    <path d="M186,50 L156,52"/><path d="M186,84 L200,86"/><path d="M186,120 L290,124"/>
    <path d="M186,190 L436,210"/><path d="M186,270 L186,290"/>
    <path d="M186,392 L222,352"/><path d="M186,430 L256,430"/>
    <path d="M474,150 L498,158"/>
  </g>
  <g font-family="system-ui,sans-serif" font-size="11" fill="#A9A49B">
    <text x="180" y="53" text-anchor="end">琴颈（张弦的上梁）</text>
    <text x="180" y="87" text-anchor="end">共鸣箱（低音在下方）</text>
    <text x="180" y="123" text-anchor="end">弦列 · 47 根</text>
    <text x="180" y="193" text-anchor="end" fill="#9C7A3C">弦长递减（低音长、高音短）</text>
    <text x="180" y="273" text-anchor="end">中音区（最常弹的一段）</text>
    <text x="180" y="395" text-anchor="end">底座</text>
    <text x="180" y="433" text-anchor="end">踏板盒 · 七个踏板</text>
    <text x="600" y="153" text-anchor="end">前柱（承受全部弦张力）</text>
  </g>
  <text x="20" y="462" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">四十七根弦合计约 10 吨张力，全压在柱上 —— 所以竖琴的柱既是结构件，也是它的外形特征。</text>
</svg>
```

四十七根弦合计约十吨张力，全压在前柱上。弦长从低音的一米四七递减到高音的七厘米，相差二十倍，所以低音厚、高音细。同一段旋律在两头弹，像两件不同的乐器。

## 七个踏板

```svg
<svg viewBox="0 0 640 300" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="竖琴七个踏板示意：每个踏板控制一个音名，三档分别得到降、还原、升三种音高">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">七个踏板 · 每个管一个音名，三档给出三种音高</text>
  </g>
  <!-- 三档参考线（横） -->
  <g stroke="#242427" stroke-width="1">
    <path d="M150,80 L590,80"/><path d="M150,130 L590,130"/><path d="M150,180 L590,180"/>
  </g>
  <g font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64" text-anchor="end">
    <text x="142" y="84">♭ 抬起</text>
    <text x="142" y="134">♮ 中间</text>
    <text x="142" y="184">♯ 踩到底</text>
  </g>
  <!-- 七个踏板 -->
  <g stroke="#9C7A3C" stroke-width="2.6" stroke-linecap="round">
    <path d="M220,80 L220,180"/><path d="M280,80 L280,180"/><path d="M340,80 L340,180"/>
    <path d="M400,80 L400,180"/><path d="M460,80 L460,180"/><path d="M520,80 L520,180"/>
    <path d="M580,80 L580,180"/>
  </g>
  <g fill="#E8C547">
    <circle cx="220" cy="80" r="7"/><circle cx="280" cy="80" r="7"/><circle cx="340" cy="80" r="7"/>
    <circle cx="400" cy="80" r="7"/><circle cx="460" cy="80" r="7"/><circle cx="520" cy="80" r="7"/>
    <circle cx="580" cy="80" r="7"/>
  </g>
  <g font-family="Georgia,serif" font-size="14" fill="#F2EEE6" text-anchor="middle">
    <text x="220" y="212">D</text><text x="280" y="212">C</text><text x="340" y="212">B</text>
    <text x="400" y="212">E</text><text x="460" y="212">F</text><text x="520" y="212">G</text>
    <text x="580" y="212">A</text>
  </g>
  <g stroke="#6E6A64" stroke-width="1" stroke-dasharray="3 3">
    <path d="M180,232 L370,232"/><path d="M370,232 L370,244"/><path d="M370,232 L610,232"/>
  </g>
  <text x="275" y="250" text-anchor="middle" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">左脚三枚</text>
  <text x="490" y="250" text-anchor="middle" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">右脚四枚</text>
  <text x="20" y="284" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">七个音名各一个踏板 —— 所有升、降、还原都在这里完成，抬手或落脚的顺序就是和声的准备。</text>
</svg>
```

弦按降 C 大调的自然音阶排，一个八度只有七个音。要弹别的音，用踏板把某个音名的所有弦升或降一个半音。七个踏板各管一个音名，每个三档。

于是和声必须提前准备。要弹降 D 大调，得先把 D、E、G 三个踏板踩下去。脚因此成了独立的第三只手，竖琴谱上的踏板记号与音符一样重要。

还有一条更硬的限制：**同一个音名在全音域只有一个状态**。低音是还原 C，高音就不可能是升 C。写竖琴的人得先定下七个音名各自的状态，再动笔。

## 音域

```range
{"range":"C♭1–G♯7","caption":"音乐会竖琴的音域（47 根弦，六个半八度）","caption_en":"Concert harp range — 47 strings, six and a half octaves","note":"最低的 C♭1 是最长的那根弦，最高的 G♯7 只有约 7 厘米长。竖琴不是移调乐器，记谱音与实际音高相同。"}
```

C♭1 到 G♯7，六个半八度，管弦乐队里除钢琴之外最宽的音域之一。谱面用大谱表，上下两行是左右手，不是高低音区，两只手都能弹整个音域。

宽不等于自由。音域越宽，一个音名只有一个状态这条限制影响的面越大。

## 手指与声音

拨一次，声音在两三秒里退去，前面的音还在响，后面的音已经来了，和声因此容易糊在一起。好的写作会利用这一点，也会用手掌捂弦避开它。

大部分传统不用小指，八根手指工作，指法分配与钢琴完全不同。滑奏是它的招牌：踏板定好之后，指甲在弦列上刮过去，得到的永远是同一个和弦的所有音。

今天这台乐器的形状来自 1810 年前后 Érard 的**双动踏板**。在那之前，一首曲子里频繁转调是竖琴的禁区；在此之后，它才成为管弦乐队里那个能随时换调的角色。

```audiolab
{"type":"instrument","synth":"plucked","phrase":["C3","G3","C4","E4","G4","C5"],"label":"琶音：竖琴最典型的音响","label_en":"An arpeggio — the harp's signature sound","hint":"GM 音色表里没有竖琴，这里是合成近似。注意每个音都留着余音 —— 它们叠在一起就是竖琴的「和声感」","hint_en":"The GM palette has no harp, so this is the synthesised approximation. Notice how every note keeps ringing — that layering is a harp's harmony."}
```

:::

::: en

## Forty-seven strings on a triangle

A harp's pitches are fixed at the workshop: each string sounds one note. Nothing is stopped or bowed; the hands only pluck. Every semitone comes from seven pedals that change string tension.

| Classification | Value |
|---|---|
| HS class | Chordophone — the vibrating body is the string |
| Sub-type | Plucked with fingertips · strings strung straight between soundbox and neck, no fingerboard |
| Family | Western · Strings (plucked branch) |
| Bayin | Not applicable — a Chinese system |

```svg
<svg viewBox="0 0 640 470" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Concert harp parts: pillar, neck, soundbox, base, pedals and the string band, with string length decreasing from bass to treble">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">Concert harp — frame and principal parts (string length decreases from bass to treble)</text>
  </g>
  <path d="M150,60 L196,60 L226,392 L170,392 Z" fill="#17171A" stroke="#343439" stroke-width="1.4"/>
  <path d="M150,60 L470,150 L470,178 L196,88 Z" fill="#111113" stroke="#343439" stroke-width="1.3"/>
  <path d="M470,150 L498,168 L446,404 L418,388 Z" fill="#17171A" stroke="#343439" stroke-width="1.4"/>
  <path d="M170,392 L446,404 L446,424 L170,412 Z" fill="#111113" stroke="#343439" stroke-width="1.2"/>
  <g stroke="#C9A227" opacity=".85">
    <path d="M182,62 L424,384" stroke-width="1.6"/>
    <path d="M188,64 L424,381" stroke-width="1.5"/>
    <path d="M194,66 L423,378" stroke-width="1.4"/>
    <path d="M200,68 L423,375" stroke-width="1.4"/>
    <path d="M206,70 L423,372" stroke-width="1.3"/>
    <path d="M212,72 L422,369" stroke-width="1.3"/>
    <path d="M218,74 L422,366" stroke-width="1.2"/>
    <path d="M224,76 L422,363" stroke-width="1.2"/>
    <path d="M230,78 L421,360" stroke-width="1.1"/>
    <path d="M236,80 L421,357" stroke-width="1.1"/>
    <path d="M242,82 L421,354" stroke-width="1"/>
    <path d="M248,84 L420,351" stroke-width="1"/>
    <path d="M254,86 L420,348" stroke-width=".95"/>
    <path d="M260,88 L420,345" stroke-width=".95"/>
    <path d="M266,90 L419,342" stroke-width=".9"/>
    <path d="M272,92 L419,339" stroke-width=".9"/>
    <path d="M278,94 L419,336" stroke-width=".85"/>
    <path d="M284,96 L418,333" stroke-width=".85"/>
    <path d="M290,98 L418,330" stroke-width=".8"/>
    <path d="M296,100 L418,327" stroke-width=".8"/>
    <path d="M302,102 L417,324" stroke-width=".75"/>
    <path d="M308,104 L417,321" stroke-width=".75"/>
    <path d="M314,106 L417,318" stroke-width=".7"/>
    <path d="M320,108 L416,315" stroke-width=".7"/>
    <path d="M326,110 L416,312" stroke-width=".65"/>
    <path d="M332,112 L416,309" stroke-width=".65"/>
    <path d="M338,114 L415,306" stroke-width=".6"/>
    <path d="M344,116 L415,303" stroke-width=".6"/>
    <path d="M350,118 L415,300" stroke-width=".55"/>
    <path d="M356,120 L414,297" stroke-width=".55"/>
    <path d="M362,122 L414,294" stroke-width=".5"/>
    <path d="M368,124 L414,291" stroke-width=".5"/>
    <path d="M374,126 L414,288" stroke-width=".45"/>
    <path d="M380,128 L413,285" stroke-width=".45"/>
    <path d="M386,130 L413,282" stroke-width=".4"/>
    <path d="M392,132 L413,279" stroke-width=".4"/>
    <path d="M398,134 L412,276" stroke-width=".35"/>
    <path d="M404,136 L412,273" stroke-width=".35"/>
    <path d="M410,138 L412,270" stroke-width=".3"/>
    <path d="M416,140 L412,267" stroke-width=".3"/>
    <path d="M422,142 L411,264" stroke-width=".28"/>
    <path d="M428,144 L411,261" stroke-width=".28"/>
    <path d="M434,146 L411,258" stroke-width=".25"/>
    <path d="M440,148 L411,255" stroke-width=".25"/>
    <path d="M446,150 L410,252" stroke-width=".22"/>
    <path d="M452,152 L410,249" stroke-width=".22"/>
    <path d="M458,154 L410,246" stroke-width=".2"/>
  </g>
  <path d="M262,424 L346,428 L346,444 L262,440 Z" fill="#0E0E10" stroke="#343439" stroke-width="1.2"/>
  <g fill="#A9A49B">
    <rect x="270" y="428" width="9" height="12" rx="1"/><rect x="284" y="428" width="9" height="12" rx="1"/>
    <rect x="298" y="429" width="9" height="12" rx="1"/><rect x="312" y="429" width="9" height="12" rx="1"/>
    <rect x="326" y="429" width="9" height="12" rx="1"/>
  </g>
  <g class="lead" stroke="#6E6A64" stroke-width=".9">
    <path d="M186,50 L156,52"/><path d="M186,84 L200,86"/><path d="M186,120 L290,124"/>
    <path d="M186,190 L436,210"/><path d="M186,270 L186,290"/>
    <path d="M186,392 L222,352"/><path d="M186,430 L256,430"/>
    <path d="M429,150 L498,158"/>
  </g>
  <g font-family="system-ui,sans-serif" font-size="11" fill="#A9A49B">
    <text x="180" y="53" text-anchor="end">Neck (the upper beam)</text>
    <text x="180" y="87" text-anchor="end">Soundbox (bass at the bottom)</text>
    <text x="180" y="123" text-anchor="end">String band · 47 strings</text>
    <text x="180" y="193" text-anchor="end" fill="#9C7A3C">Strings shorten upward</text>
    <text x="180" y="273" text-anchor="end">Middle register (the workhorse)</text>
    <text x="180" y="395" text-anchor="end">Base</text>
    <text x="180" y="433" text-anchor="end">Pedal box · seven pedals</text>
    <text x="600" y="153" text-anchor="end">Pillar (takes all the tension)</text>
  </g>
  <text x="20" y="462" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">47 strings pull about ten tonnes in total, all of it landing on the pillar — structure and silhouette at once.</text>
</svg>
```

Forty-seven strings pull about ten tonnes onto the pillar. String length runs from roughly 1.47 m at the bottom to 7 cm at the top, a factor of twenty, so the bass is thick and the treble thin. The same melody at the two ends sounds like two instruments.

## Seven pedals

```svg
<svg viewBox="0 0 640 316" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="The harp's seven pedals: each controls one note name and has three positions giving flat, natural and sharp">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">Seven pedals · one note name each, three positions, three pitches</text>
  </g>
  <g stroke="#242427" stroke-width="1">
    <path d="M150,80 L590,80"/><path d="M150,130 L590,130"/><path d="M150,180 L590,180"/>
  </g>
  <g font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64" text-anchor="end">
    <text x="142" y="84">♭ up</text>
    <text x="142" y="134">♮ middle</text>
    <text x="142" y="184">♯ down</text>
  </g>
  <g stroke="#9C7A3C" stroke-width="2.6" stroke-linecap="round">
    <path d="M220,80 L220,180"/><path d="M280,80 L280,180"/><path d="M340,80 L340,180"/>
    <path d="M400,80 L400,180"/><path d="M460,80 L460,180"/><path d="M520,80 L520,180"/>
    <path d="M580,80 L580,180"/>
  </g>
  <g fill="#E8C547">
    <circle cx="220" cy="80" r="7"/><circle cx="280" cy="80" r="7"/><circle cx="340" cy="80" r="7"/>
    <circle cx="400" cy="80" r="7"/><circle cx="460" cy="80" r="7"/><circle cx="520" cy="80" r="7"/>
    <circle cx="580" cy="80" r="7"/>
  </g>
  <g font-family="Georgia,serif" font-size="14" fill="#F2EEE6" text-anchor="middle">
    <text x="220" y="212">D</text><text x="280" y="212">C</text><text x="340" y="212">B</text>
    <text x="400" y="212">E</text><text x="460" y="212">F</text><text x="520" y="212">G</text>
    <text x="580" y="212">A</text>
  </g>
  <g stroke="#6E6A64" stroke-width="1" stroke-dasharray="3 3">
    <path d="M180,232 L370,232"/><path d="M370,232 L370,244"/><path d="M370,232 L610,232"/>
  </g>
  <text x="275" y="250" text-anchor="middle" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">Left foot · three</text>
  <text x="490" y="250" text-anchor="middle" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">Right foot · four</text>
  <text x="20" y="282" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">One pedal per note name — every sharp, flat and natural happens here,</text>
  <text x="20" y="298" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">and the order of your feet is preparation for the harmony.</text>
</svg>
```

The strings carry the diatonic scale of C♭ major, seven notes to the octave. To reach anything else, a pedal raises or lowers every string of one note name by a semitone. Seven pedals, one per name, three positions each.

Harmony must be prepared. To play in D♭ major you press the D, E and G pedals first. The feet become a third hand, and pedal markings matter as much as notes.

A harder rule: a note name has one state across the whole range. If the low C is natural, no C above it can be sharp. Anyone writing for harp settles the state of all seven names before writing a bar.

## Range

```range
{"range":"C♭1–G♯7","caption":"音乐会竖琴的音域（47 根弦，六个半八度）","caption_en":"Concert harp range — 47 strings, six and a half octaves","note":"最低的 C♭1 是最长的那根弦，最高的 G♯7 只有约 7 厘米长。竖琴不是移调乐器，记谱音与实际音高相同。"}
```

C♭1 to G♯7, six and a half octaves, among the widest ranges in the orchestra after the piano. The music is laid out on a grand staff, but the two staves are the two hands, not two registers; either hand can reach anywhere.

Wide is not free. The wider the range, the further the one-state rule reaches.

## Fingers and sound

One pluck rings for two or three seconds, so earlier notes are still sounding when later ones arrive and harmonies blur together. Good writing exploits that wash, or damps it with the palm.

Most traditions leave out the little finger — it cannot reach — so eight fingers work, and fingering departs from piano logic. The glissando is the signature: with the pedals set, a fingernail swept across the strings gives every note of **one chord** at once.

The instrument's modern shape comes from Érard's double-action pedal, around 1810. Before it, music that modulated often was closed to the harp; afterwards the orchestra had an instrument that could follow any key.

```audiolab
{"type":"instrument","synth":"plucked","phrase":["C3","G3","C4","E4","G4","C5"],"label":"琶音：竖琴最典型的音响","label_en":"An arpeggio — the harp's signature sound","hint":"GM 音色表里没有竖琴，这里是合成近似。注意每个音都留着余音 —— 它们叠在一起就是竖琴的和声感","hint_en":"The GM palette has no harp, so this is the synthesised approximation. Notice how every note keeps ringing — that layering is a harp's harmony."}
```

:::
