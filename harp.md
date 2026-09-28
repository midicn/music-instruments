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
  - 「七个踏板分别控制 D C B 与 E F G A 七个音名，每个踏板三档（降／还原／升）」属通行乐器学常识，各版乐器词典表述一致，本文为原创表述
  - 「弦按降 C 大调自然音阶排列，八度内只有七个音，靠踏板取得全部半音」依通行竖琴演奏法与制琴规范
  - ⚠️ 库内没有标题或作曲家可确认为竖琴的曲目 —— 本条给出的是**同族拨弦曲目**，音色由试听件负责
updated: 2026-09-26
---

::: zh
竖琴是唯一一件**不用弓、不用品、也不靠指板取音**的弦乐器：
它的音高在**造琴时就定死了** —— 每根弦只发一个音。

它也是唯一一件**用踏板来取得半音**的乐器：弦上排着六个半八度的**自然音阶**，
所有升降都靠七个踏板改变弦的张力。

| 分类 | 归属 |
|---|---|
| **HS 分类** | **弦鸣**（Chordophone）—— 发声体是弦本身 |
| **次级类型** | 拨奏（指腹）· **弦直接张在共鸣箱与琴颈之间，没有指板** |
| **所属族** | 西洋 · 弦乐（弹拨支系） |
| **八音** | 不适用 —— 周代八音是中国乐器的体系，竖琴不在其中 |

## 结构：一个三角框架，四十七根弦

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

四个部件，各有各的职责：

| 部件 | 作用 |
|---|---|
| **共鸣箱** | 低音侧的斜梁，箱体随音高变细 —— 低音要更大的空间 |
| **琴颈** | 上方张弦的梁，弦轴装在这里 |
| **前柱** | 承受**全部弦的张力**（47 根弦合计约 10 吨），柱一旦失效整个框架就会向内塌 |
| **踏板盒** | 底座里的七个踏板（下一节） |

弦长从低音的约 1.47 米递减到高音的约 7 厘米 —— 相差二十倍。
所以竖琴的声音在**低音区厚、高音区细**，这也决定了写竖琴的方式：
它最适合用**琶音**把整个音域一次扫过，让这二十倍的差别变成一种"流动"。

## 七个踏板：为什么弦上只有自然音阶

这是竖琴最独特的设计，也是它与其他所有弦乐器最大的不同。

竖琴的弦**只按降 C 大调的自然音阶排**（C♭ D♭ E♭ F♭ G♭ A♭ B♭）——
一个八度里只有**七个音**，没有升号也没有还原音。要弹别的音怎么办？

**用踏板改弦长。**

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

这套机制带来三个**只有竖琴有**的后果：

1. **它的和声变化是"预先准备"的**。要弹降 D 大调，得先把 D、E、G 三个踏板踩下去（得到 D♯、E♯、G♯）。
   演奏者在曲子里必须**提前几个小节**把踏板换好 —— 所以竖琴谱上常能看到踏板记号，
   而演奏者的脚是独立的第三只手。
2. **它能做出别处做不出的滑奏**。把某个踏板推成升号或还原以后，
   在整条弦列上刮过去（glissando）会自动得到一个和弦 —— 这就是竖琴在电影配乐里
   那种"一片水波"的来源。
3. **同一个音名在全音域只有一个音高**。C 在所有八度里要么全是还原 C、要么全是升 C ——
   **不可能低音是还原 C 而高音是升 C**。这是竖琴写作最硬的一条限制，
   所以写竖琴的人要先想清楚"这一段的七个音名各要什么状态"。

## 音域

```range
{"range":"C♭1–G♯7","caption":"音乐会竖琴的音域（47 根弦，六个半八度）","caption_en":"Concert harp range — 47 strings, six and a half octaves","note":"最低的 C♭1 是最长的那根弦，最高的 G♯7 只有约 7 厘米长。竖琴不是移调乐器，记谱音与实际音高相同。"}
```

六个半八度，是管弦乐队里除钢琴外**音域最宽的乐器之一**。
但注意：**宽不等于自由**。音域越宽，"同一个音名只有一个状态"这条限制影响的面越大 ——
一段音乐里 C 只能有一个状态，而 C 出现在六个半八度里。

谱号上，竖琴主要用**大谱表**（上下两行，一手一行），
所以它的乐谱看起来像钢琴谱 —— 但它**不是键盘乐器**：上下两行指的是**两只手**，
不是"低音区和高音区"。两手都能弹整个音域。

## 音色与听辨

四条线索：

1. **音头极短、余音很长**。拨一次，声音在两三秒里慢慢退去。
   所以竖琴的和声常常"糊在一起" —— 前面拨的音还没停，后面的音已经响了。
   好的竖琴写作会利用这一点（堆积成一片），也会避开它（用捂弦）。
2. **在弦列上刮过去**（glissando）是它的招牌。一整片音同时响，
   但**都是同一个和弦**（因为踏板的限制）—— 所以听起来既丰富又统一。
3. **低音厚、高音细**。弦长差二十倍这件事在音色上非常明显：
   低音区暗而浑，高音区清而薄。同一段旋律在低音区和高音区弹，像两件不同的乐器。
4. **不用小指**。大部分竖琴传统只用拇指、食指、中指、无名指四指（小指太短、够不到），
   所以指法分配与钢琴完全不同 —— 听起来"手很多"，其实只有八根手指在工作。

```audiolab
{"type":"instrument","synth":"plucked","phrase":["C3","G3","C4","E4","G4","C5"],"label":"琶音：竖琴最典型的音响","label_en":"An arpeggio — the harp's signature sound","hint":"GM 音色表里没有竖琴，这里是合成近似。注意每个音都留着余音 —— 它们叠在一起就是竖琴的「和声感」","hint_en":"The GM palette has no harp, so this is the synthesised approximation. Notice how every note keeps ringing — that layering is a harp's harmony."}
```

> 本页「在库中听例子」里的曲子是**同族拨弦曲目**（库内没有可确认为竖琴的曲目），
> 音色由上面的试听件负责。

## 演奏技法

- **琶音（arpeggio）**：最基本的手法 —— 拇指到无名指依次扫过弦列。
  上行、下行、跨越几个八度，都是这一件事的变化。
- **滑奏（glissando）**：指甲在弦列上快速刮过。得到的是**一个和弦的所有音**，
  具体是哪个和弦由踏板决定 —— 所以它是**踏板的创作，不只是手的动作**。
- **泛音**：在弦的中点上轻触，得到高八度的透明音。竖琴的泛音很容易做，
  音色像钟，常用来做结尾（"泛音结尾"是竖琴写作的常用手法）。
- **捂弦（étouffé）**：手掌贴住弦列立刻止音，做出短促的断音 ——
  这是"防止糊"的主要手段。
- **同音异弦（bisbigliando）**：两条同音弦交替快速拨动，得到类似颤音的流动效果。

## 家族与近亲

竖琴属于**板腔体之外**的一支：弦**直接张在共鸣箱和琴颈之间**，中间没有指板、
没有品、也没有按压的余地。这一支在世界上分布很广：

| 乐器 | 弦数 | 弦的排列 | 取半音的方式 |
|---|---|---|---|
| **音乐会竖琴** | 47 | 自然音阶（一音一弦） | **七个踏板** |
| [[instrument:classical-guitar\|古典吉他]] | 6 | 定弦（四度加三度） | 手指按品 |
| [[instrument:violin\|小提琴]] | 4 | 五度 | 手指按弦（无品） |
| 中国竖琴谱系（箜篌、竖箜篌） | 多 | 一音一弦 | 无踏板（历史形制） |

有趣的对照：**"一音一弦"是最古老的思路**（竖琴、箜篌、中国的古筝都是），
"少数几根弦 + 手指取音"是后来的路子。两条路的取舍很清楚：
一音一弦**音准绝对可靠**（不用按），但**半音要靠额外机制**（踏板 / 按弦 / 移码）。

## 历史演变

竖琴是**人类最早的弦乐器之一**：公元前三千年的美索不达米亚与埃及就有弓形竖琴的图画，
古希腊的里拉琴、中世纪的竖琴都是它的后裔。今天的形制来自三个关键节点：

| 时间 | 变化 |
|---|---|
| 中世纪—文艺复兴 | 爱尔兰竖琴等形制使用金属弦，靠**指甲**拨，音色清亮 |
| 17–18 世纪 | 出现**钩式（hook）**竖琴：手工扳动小钩改变单根弦的音高 |
| **约 1720 年** | 巴伐利亚的 Hochbrucker 发明**踏板**机构，用脚远程操纵那些钩 |
| **1810 年前后** | Sébastien Érard 做出**双动踏板**（每档升降一个半音，共三档）—— 这就是今天的标准 |
| 19 世纪 | 弦数定型为 47，音域 C♭1–G♯7；成为管弦乐队固定成员 |

**双动踏板是竖琴史上最重要的一次改良**。单动踏板只能把弦升一个半音（降 → 还原），
双动踏板让每根弦拥有**三种状态**（降／还原／升），于是竖琴第一次能弹所有调性。
在此之前，一首曲子里频繁转调的段落是竖琴的禁区。

所以竖琴的"现代化"其实很晚：**它是一件 19 世纪才真正定型的古老乐器**，
而它之所以在管弦乐里那么好用（音域宽、和声厚、滑奏独特），
靠的正是那个 1810 年的机械改良。

## 常见误解

- **"竖琴弦那么多，弹起来最难。"** → 恰恰相反：**它不用按音，音准是造好的**。
  少了"左手找音"这一层，入门比小提琴容易得多。真正难的是**踏板的安排**和**双手覆盖音域**。
- **"竖琴可以随便弹半音。"** → 不行。**同一个音名在全音域只有一个状态** ——
  一段音乐里 C 要么全是还原 C，要么全是升 C。这是竖琴写作最硬的限制。
- **"踏板是装饰性的。"** → 踏板是**发音机制的一部分**。不踩对踏板，音就是错的；
  而且必须在正确的时间踩，跳过去是不行的。
- **"竖琴和钢琴一样是上下两个音区。"** → 竖琴谱的上下两行是**左右手**，
  不是音区。两只手都能弹整个音域。
- **"它的音色就是"叮叮咚咚"。** → 那多半是低频流行音乐里的滑奏印象。
  竖琴的低音区厚而暗，中音区是它的主体 —— 大部分独奏曲都在中音区。
- **"十根手指都用。"** → 传统上不用小指（够不到），八根手指工作。
  这条限制直接影响了竖琴的指法分配。

## 下一步

到这里，西洋弦乐（I1）已经完成 14 条中的 13 条。剩下的 [[instrument:viol|维奥尔琴]] 在下一段；
想接着看"一音一弦"这条思路在中国乐器里的形态，可以看本站的中国弹拨族（古筝、箜篌、扬琴）。
:::

::: en
The harp is the only string instrument that is **bowed by nothing, fretted by nothing, and stopped by
nothing**: its pitches are **fixed when the instrument is built** — each string sounds exactly one note.

It is also the only instrument that obtains its semitones **with pedals**: six and a half octaves of
**diatonic** strings, with every sharp, flat and natural produced by seven pedals changing string tension.

| Classification | Value |
|---|---|
| **HS class** | **Chordophone** — the vibrating body is the string itself |
| **Sub-type** | Plucked (fingertips) · strings strung **directly between resonator and neck, with no fingerboard** |
| **Family** | Western · Strings (plucked branch) |
| **Bayin** | Not applicable — the eight categories are a Chinese system; the harp is outside it |

## Structure: a triangular frame and forty-seven strings

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

Four parts, four jobs:

| Part | Job |
|---|---|
| **Soundbox** | the sloping beam on the bass side; the box narrows as the pitch rises — bass needs more air |
| **Neck** | the upper beam where the strings are anchored and tuned |
| **Pillar** | carries the **entire string tension** (about ten tonnes across 47 strings); if it fails, the frame folds inwards |
| **Pedal box** | seven pedals in the base (next section) |

String length runs from about 1.47 m at the bottom down to about 7 cm at the top — a factor of twenty.
So a harp is **thick in the bass and thin on top**, which dictates how it is written: it excels at
**arpeggios** that sweep the whole range, turning that twentyfold difference into motion.

## Seven pedals: why the strings carry only the diatonic scale

This is the harp's most distinctive design, and its biggest difference from every other string instrument.

The strings are tuned to **the diatonic scale of C♭ major** (C♭ D♭ E♭ F♭ G♭ A♭ B♭) —
just **seven notes per octave**, with no sharps and no naturals. So how do you play anything else?

**You change string length with a pedal.**

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

That mechanism produces three consequences **unique to the harp**:

1. **Harmony has to be prepared in advance.** To play in D♭ major you must first press the D, E and G
   pedals to get D♯, E♯ and G♯. Players must set pedals **several bars ahead** — which is why harp parts
   carry pedal markings, and why the feet are effectively a third hand.
2. **It can glissando in a way nothing else can.** Once the pedals are set, sweeping a fingernail across
   the whole string band yields **a chord** automatically — the origin of the "sheet of water" sound in
   film scores.
3. **A note name has exactly one state across the whole range.** All the Cs are either C♮ or C♯ —
   **you cannot have a natural C low down and a sharp C up high**. That is the hardest constraint in
   writing for harp: you must decide the state of all seven names before you write.

## Range

```range
{"range":"C♭1–G♯7","caption":"音乐会竖琴的音域（47 根弦，六个半八度）","caption_en":"Concert harp range — 47 strings, six and a half octaves","note":"最低的 C♭1 是最长的那根弦，最高的 G♯7 只有约 7 厘米长。竖琴不是移调乐器，记谱音与实际音高相同。"}
```

Six and a half octaves — among the widest ranges of any orchestral instrument except the piano.
But note: **wide is not the same as free**. The wider the range, the more the one-state-per-name rule
bites, because a single C appears across six and a half octaves.

The harp is written on the **grand staff** (one line per hand), so the page looks like piano music —
but it is **not a keyboard instrument**: the two staves are the **two hands**, not "low register and
high register". Either hand can play anywhere in the range.

## Timbre, and how to hear it

Four cues:

1. **A very short attack with a long decay.** One pluck rings for two or three seconds, so harp
   harmonies **blur together** — earlier notes are still sounding when later ones arrive. Good harp
   writing exploits that (building a wash of sound) or avoids it (with damping).
2. **The glissando is the signature.** A whole sweep of notes sounds at once, yet all of them belong to
   **one chord** (because of the pedals) — rich and unified at the same time.
3. **Thick at the bottom, thin on top.** A twentyfold difference in string length is unmistakable:
   dark and full in the bass, clear and slight in the treble. The same melody sounds like two different
   instruments at the two ends.
4. **No little finger.** Most traditions use only thumb, index, middle and ring — the little finger is
   too short to reach. That changes fingering completely: it sounds like many hands, but only eight
   fingers are working.

```audiolab
{"type":"instrument","synth":"plucked","phrase":["C3","G3","C4","E4","G4","C5"],"label":"琶音：竖琴最典型的音响","label_en":"An arpeggio — the harp's signature sound","hint":"GM 音色表里没有竖琴，这里是合成近似。注意每个音都留着余音 —— 它们叠在一起就是竖琴的和声感","hint_en":"The GM palette has no harp, so this is the synthesised approximation. Notice how every note keeps ringing — that layering is a harp's harmony."}
```

> The tracks under “Listen in the library” are **related plucked repertoire** (nothing in the library can
> be confirmed as harp music); timbre is handled by the player above.

## Playing techniques

- **Arpeggios**: the fundamental gesture — thumb through ring finger across the strings. Up, down, or
  spanning several octaves, it is all the same thing.
- **Glissando**: a fingernail swept quickly across the band. What you get is **every note of one
  chord**, and which chord is decided by the pedals — so it is **a composition for the feet**, not just
  a hand movement.
- **Harmonics**: touch a node at the midpoint and a transparent octave sounds. Easy on a harp, bell-like,
  and a favourite way to end a phrase.
- **Damping (étouffé)**: the palm laid on the strings for a short, clipped sound — the main defence
  against blur.
- **Bisbigliando**: two strings of the same pitch alternated rapidly for a shimmering tremolo.

## The family

The harp sits **outside the box-and-fingerboard branch**: strings run **directly between resonator and
neck**, with no fingerboard, no frets and nothing to stop. That branch is spread across the world:

| Instrument | Strings | Arrangement | How semitones are made |
|---|---|---|---|
| **Concert harp** | 47 | diatonic, one note per string | **seven pedals** |
| [[instrument:classical-guitar\|Classical guitar]] | 6 | tuned in fourths plus a third | fingers on frets |
| [[instrument:violin\|Violin]] | 4 | tuned in fifths | fingers on the string (no frets) |
| Harps of the Chinese lineage (konghou) | many | one note per string | no pedals (historical forms) |

An interesting contrast: **one-note-per-string is the older idea** (harps, konghou, the Chinese guzheng),
while "few strings plus a stopping hand" came later. The trade-off is clear — one note per string is
**intonation-proof** (nothing to stop) but needs **an extra mechanism** for semitones
(pedals, presses, or moved bridges).

## History

The harp is **one of humanity's oldest string instruments**: harps appear in Mesopotamian and Egyptian
depictions around 3000 BCE, and the Greek lyre and the medieval harp descend from them. Today's
instrument comes from three turning points:

| Time | Change |
|---|---|
| Medieval–Renaissance | Irish and other harps used metal strings plucked with the **fingernail**, giving a bright tone |
| 17th–18th c. | **Hook** harps appeared — small hooks turned by hand to change a single string's pitch |
| **Around 1720** | the Bavarian Hochbrucker invented the **pedal** mechanism, moving those hooks with the feet |
| **Around 1810** | Sébastien Érard built the **double-action pedal** (three positions, one semitone per step) — today's standard |
| 19th c. | string count settled at 47; the range C♭1–G♯7; the harp became a fixture of the orchestra |

**The double-action pedal is the single most important improvement in the harp's history.** A
single-action pedal could only raise a string by a semitone (flat → natural); the double-action pedal
gave every string **three states** (flat / natural / sharp), and only then could the harp play in all
keys. Before it, music that modulated often was off-limits.

So the harp's modernisation was remarkably late: **an ancient instrument that only settled into its
present form in the 19th century** — and the reason it works so well in an orchestra (wide range, thick
harmony, unique glissando) is exactly that 1810 mechanism.

## Common misconceptions

- **"All those strings must make it the hardest to play."** The opposite: **nothing is stopped, so the
  intonation is built in**. Without a left hand hunting for pitch, it is far easier to start than a
  violin. What is genuinely hard is **planning the pedals** and covering the range with two hands.
- **"A harp can play any semitone at any time."** No. **A note name has one state across the whole
  range** — all Cs natural, or all Cs sharp. It is the hardest constraint in harp writing.
- **"The pedals are decorative."** They are part of **how the instrument makes its pitches**. Wrong
  pedals mean wrong notes, and they must be changed at the right moment — you cannot skip ahead.
- **"The harp staff means low and high register, like a piano."** The two staves are **left and right
  hand**, not registers. Either hand can reach the whole range.
- **"It just goes plink-plonk."** That is the glissando cliché of low-budget pop. A harp's bass is deep
  and dark, and its middle register carries most solo writing.
- **"All ten fingers are used."** Traditionally not the little finger (it cannot reach), so eight
  fingers work — a limit that reshapes the fingering.

## Next

That completes 13 of the 14 entries in I1 (Western strings). The remaining one, the
[[instrument:viol|viol]], follows shortly; to see the "one note per string" idea in Chinese instruments,
see the Chinese plucked entries (guzheng, konghou, yangqin).
:::
