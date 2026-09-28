---
id: banjo
site: inst
cat: I1
title: 班卓琴
title_en: Banjo
summary: 圆形琴体上绷着一张膜的拨弦乐器，第五弦是短的高音持续弦
summary_en: A plucked instrument whose resonator is a membrane stretched over a circular rim, with a short high drone string
level: standard
tags: [乐器, 弦乐, 西洋]
tags_en: [instrument, strings, western]
alias: [班卓琴, banjo, 五弦班卓, 斑鸠琴]
order: 23
links:
  - "[[concept:interval]]"
  - "[[concept:register]]"
  - "[[concept:timbre]]"
  - "[[concept:articulation]]"
  - "[[instrument:ukulele]]"
  - "[[instrument:classical-guitar]]"
  - "[[instrument:viola]]"
instances:
  - m21-001955 | 传统里尔舞曲 BanjoReel —— 班卓琴在民间舞曲里的本职：单声部旋律加节奏型
  - thesession-017740 | Banjo Breakdown —— 标题就是它的用法，速度快的传统舞曲
  - thesession-012802 | Tilting Banjo, The —— 另一首同类型的传统曲子，可对照节奏型的处理
  - thesession-014734 | 短小的传统舞曲，结构只有两个乐句，最容易听出膜的"炸"音头
  - norbeck-000018 | 另一份曲集里的传统舞曲，句法更方整，与上面几首形成对照
sources:
  - 结构依通行制琴资料：圆形琴体（鼓面直径约 280 毫米）、一层膜（羊皮或合成材料）、音环与二十余枚张力钩，五弦
  - 「五弦班卓的开放 G 定弦自第 5 弦到第 1 弦为 G4–D3–G3–B3–D4，第 5 弦是短弦（弦轴装在第五品处），音高高于第 4 弦」依通行调弦资料
  - 「四弦高音班卓琴（tenor）定弦 C–G–D–A（纯五度）」「班卓里里（banjolele）定弦与尤克里里相同 G–C–E–A」依通行资料
  - 起源自西非的拨弦乐器、经大西洋奴隶贸易传入北美，19 世纪在美国普及，20 世纪成为蓝草音乐的核心乐器，依通行乐器史
  - ⚠️ 库内没有标题或作曲家可确认为班卓琴的曲目 —— 本条给出的是**传统单声部舞曲**（班卓琴最典型的用途之一），音色由试听件负责
updated: 2026-09-26
---

::: zh
班卓琴有一件别的弦乐器都没有的东西：**它的共鸣体不是木板，是一张膜。**

圆形琴体上绷着一张皮（传统是羊皮，现代多用合成材料），弦把振动压到这张膜上，
膜再把它推给空气。这一条决定了它的全部音响特征 —— **亮、炸、短**。

它还有一件反直觉的设计：**五根弦里的第五根是短弦**，音高却比第四弦还高，
几乎只当"持续音"用。这与[[instrument:ukulele|尤克里里]]的复入式定弦是同一类思路。

| 分类 | 归属 |
|---|---|
| **HS 分类** | **弦鸣**（Chordophone）—— 发声体是弦本身（**膜是放大件，不是振源**） |
| **次级类型** | 拨奏（拨片或手指）· 有颈、有品 · **共鸣体是绷紧的膜** |
| **所属族** | 西洋 · 弦乐（弹拨支系）· 与非洲拨弦乐器同源 |
| **八音** | 不适用 —— 周代八音是中国乐器的体系，班卓琴不在其中 |

> ⚠️ **一个概念上的要点**：班卓琴在 HS 分类里属于**弦鸣**，不是膜鸣。
> 判断依据是"**什么在振动发声**"：发源是**弦**，膜只是把弦的振动放大并染上自己的性格。
> 定音鼓是膜鸣（膜本身是振源），班卓琴不是 —— 这是 HS 体系里一条常见的分界。

## 结构：圆形琴体与短弦

```svg
<svg viewBox="0 0 640 460" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="五弦班卓琴外形与主要部件：圆形琴体上的膜、张力钩、音环、琴桥、长琴颈与第五弦的短弦与弦轴">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">五弦班卓琴 · 外形与主要部件（圆形膜面 + 第五弦是短弦）</text>
  </g>
  <!-- 琴颈（长） -->
  <path d="M304,66 L336,66 L344,330 L296,330 Z" fill="#0E0E10"/>
  <g stroke="#343439" stroke-width=".9">
    <path d="M300,96 L340,96"/><path d="M301,126 L339,126"/><path d="M302,156 L338,156"/>
    <path d="M302,186 L338,186"/><path d="M303,216 L337,216"/><path d="M303,246 L337,246"/>
    <path d="M304,276 L336,276"/><path d="M304,306 L336,306"/>
  </g>
  <!-- 琴头 -->
  <path d="M306,34 L334,34 L336,66 L304,66 Z" fill="#17171A" stroke="#343439" stroke-width="1.2"/>
  <g fill="#343439">
    <rect x="288" y="38" width="16" height="5" rx="1"/><rect x="336" y="38" width="16" height="5" rx="1"/>
    <rect x="288" y="50" width="16" height="5" rx="1"/><rect x="336" y="50" width="16" height="5" rx="1"/>
    <rect x="288" y="62" width="16" height="5" rx="1"/><rect x="336" y="62" width="16" height="5" rx="1"/>
  </g>
  <!-- 第五弦的弦轴（在第五品处） -->
  <rect x="336" y="122" width="18" height="7" rx="1" fill="#9C7A3C"/>
  <!-- 圆形琴体 -->
  <circle cx="320" cy="372" r="66" fill="#17171A" stroke="#343439" stroke-width="1.6"/>
  <circle cx="320" cy="372" r="56" fill="#111113" stroke="#343439" stroke-width="1"/>
  <circle cx="320" cy="372" r="46" fill="#0E0E10" stroke="#5B7FA8" stroke-width="1.2"/>
  <!-- 张力钩 -->
  <g stroke="#6E6A64" stroke-width="2.2" stroke-linecap="round">
    <path d="M320,300 L320,308"/><path d="M352,305 L349,312"/><path d="M380,320 L374,326"/>
    <path d="M392,348 L384,352"/><path d="M392,382 L384,378"/><path d="M380,406 L374,400"/>
    <path d="M352,420 L349,414"/><path d="M320,436 L320,428"/><path d="M288,420 L291,414"/>
    <path d="M260,406 L266,400"/><path d="M248,382 L256,378"/><path d="M248,348 L256,352"/>
    <path d="M260,320 L266,326"/><path d="M288,305 L291,312"/>
  </g>
  <!-- 琴桥（立在膜上） -->
  <path d="M296,356 L344,356 L340,364 L300,364 Z" fill="#A9A49B"/>
  <!-- 琴弦（四根长弦 + 一根短弦） -->
  <g stroke="#C9A227" opacity=".85">
    <path d="M310,68 L310,352" stroke-width="1.2"/>
    <path d="M315.5,68 L315.5,352" stroke-width="1.1"/>
    <path d="M321,68 L321,352" stroke-width="1"/>
    <path d="M326.5,68 L326.5,352" stroke-width=".9"/>
    <path d="M331,126 L331,352" stroke-width=".8"/>
  </g>
  <!-- 标注 -->
  <g class="lead" stroke="#6E6A64" stroke-width=".9">
    <path d="M186,42 L286,44"/><path d="M186,86 L296,88"/>
    <path d="M186,126 L330,130"/><path d="M186,232 L296,232"/>
    <path d="M186,306 L246,306"/><path d="M186,372 L252,372"/>
    <path d="M487,320 L382,326"/><path d="M487,392 L376,384"/>
    <path d="M186,436 L268,428"/>
  </g>
  <g font-family="system-ui,sans-serif" font-size="11" fill="#A9A49B">
    <text x="180" y="45" text-anchor="end">琴头 · 五个弦轴</text>
    <text x="180" y="89" text-anchor="end">有品的指板（琴颈长）</text>
    <text x="180" y="129" text-anchor="end" fill="#9C7A3C">第五弦的弦轴（在第五品处）</text>
    <text x="180" y="235" text-anchor="end">第五弦：短，音高在第四弦之上</text>
    <text x="180" y="309" text-anchor="end">膜（羊皮或合成材料）</text>
    <text x="180" y="375" text-anchor="end">琴桥立在膜上</text>
    <text x="492" y="323">音环与张力钩</text>
    <text x="492" y="395">圆形琴体（鼓面）</text>
    <text x="180" y="439" text-anchor="end">张力钩二十余枚</text>
  </g>
  <text x="20" y="452" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">膜靠二十余枚张力钩拉紧 —— 张力变了音色就变，所以班卓琴对温湿度比吉他敏感得多。</text>
</svg>
```

三处要点：

1. **圆形琴体是一张鼓**。膜绷在圆环上，用二十余枚**张力钩**拉紧。
   弦经琴桥把振动压到膜上 → **膜是放大件**。所以班卓琴的琴体不需要"音孔"：
   整张膜都在辐射声音。
2. **第五弦是短弦**。它的弦轴装在第五品的位置（不是琴头），
   所以这根弦只能按到第五品为止 —— 它的用途是**持续音（drone）**，
   在滚奏（roll）里提供一条固定的高音**G4**。这与[[instrument:ukulele|尤克里里]]
   的复入式定弦属于同一类设计：**让一根弦不参与旋律，只提供色彩**。
3. **琴颈很长、品很多**。五弦班卓的琴颈比吉他长，弦细张力小，
   所以它跑动极快 —— 这也是蓝草音乐里那些密集音型的物理前提。

**定弦**（第五弦到第一弦）：**G4 – D3 – G3 – B3 – D4**。
空弦一起响就是一个 G 大三和弦，所以叫"开放 G"。
族人里还有两个常见变体：

| 变体 | 弦数 | 定弦 | 用在哪 |
|---|---|---|---|
| **五弦班卓**（标准） | 5（含短弦） | G4 D3 G3 B3 D4 | 蓝草、老派（old-time）、民谣 |
| 四弦高音班卓（tenor） | 4 | C3 G3 D4 A4（**纯五度**） | 爱尔兰传统音乐、早期爵士 |
| 班卓里里（banjolele） | 4 | G4 C4 E4 A4（与尤克里里相同） | 轻伴奏、歌曲 |

注意 tenor 班卓的定弦是**纯五度**（C–G–D–A）—— 与[[instrument:viola|中提琴]]同一套逻辑。
这也是它成为爱尔兰传统音乐常客的原因：**它与小提琴同定弦，可以照搬指法**。

## 发声原理：膜为什么听起来"炸"

```svg
<svg viewBox="0 0 640 320" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="两种共鸣体的对比：一层薄膜音头炸、衰减极快；一块木板加音梁音头柔、衰减慢">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">共鸣体：一层膜，还是一块木板</text>
  </g>
  <!-- 左：膜 -->
  <text x="170" y="60" text-anchor="middle" fill="#6E6A64">班卓琴 · 一张膜</text>
  <path d="M70,110 C110,88 230,88 270,110" fill="none" stroke="#9C7A3C" stroke-width="3"/>
  <g stroke="#6E6A64" stroke-width="2.6" stroke-linecap="round">
    <path d="M70,110 L70,126"/><path d="M270,110 L270,126"/>
  </g>
  <path d="M162,86 L178,86 L176,72 L164,72 Z" fill="#A9A49B"/>
  <g stroke="#C9A227" opacity=".9">
    <path d="M90,72 L250,72" stroke-width="1.1"/><path d="M90,80 L250,80" stroke-width=".9"/>
  </g>
  <!-- 右：木板 -->
  <text x="470" y="60" text-anchor="middle" fill="#6E6A64">吉他一族 · 一块木板</text>
  <rect x="370" y="94" width="200" height="12" rx="2" fill="#5B7FA8"/>
  <g stroke="#5B7FA8" stroke-width="5" stroke-linecap="round" opacity=".7">
    <path d="M410,110 L410,126"/><path d="M470,110 L470,126"/><path d="M530,110 L530,126"/>
  </g>
  <path d="M464,80 L480,80 L478,94 L466,94 Z" fill="#A9A49B"/>
  <g stroke="#C9A227" opacity=".9">
    <path d="M390,68 L550,68" stroke-width="1.1"/><path d="M390,76 L550,76" stroke-width=".9"/>
  </g>
  <!-- 衰减包络 -->
  <g stroke="#242427" stroke-width="1">
    <path d="M70,240 L290,240"/><path d="M370,240 L590,240"/>
  </g>
  <path d="M78,240 L86,176 L104,222 L124,234 L150,238 L200,240 L280,240"
        fill="none" stroke="#9C7A3C" stroke-width="2.4" stroke-linejoin="round"/>
  <path d="M378,240 L386,190 L410,206 L450,220 L500,230 L560,236 L586,240"
        fill="none" stroke="#5B7FA8" stroke-width="2.4" stroke-linejoin="round"/>
  <g font-family="system-ui,sans-serif" font-size="11" text-anchor="middle">
    <text x="170" y="262" fill="#9C7A3C">音头炸，衰减极快</text>
    <text x="470" y="262" fill="#5B7FA8">音头柔，衰减慢</text>
  </g>
  <text x="20" y="292" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">膜薄、轻、内阻尼大 —— 声音来得快去得也快；木板厚、硬、有音梁撑住，声音留得久。</text>
  <text x="20" y="310" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">所以班卓琴的音色不是风格选择，是材料决定的。</text>
</svg>
```

**膜与木板的差别，可以从四个物理量说清**：

| | 膜（班卓琴） | 木板（吉他） |
|---|---|---|
| 厚度 | 极薄（不到 1 毫米） | 厚（2–3 毫米，还有音梁） |
| 质量 | 极轻 | 重 |
| 内阻尼 | 大（皮/塑料本身吸收能量） | 小（木材顺着纹理传能量） |
| 结果 | **音头炸、衰减极快** | **音头柔、衰减慢** |

四个量是同一条因果链：**轻 + 阻尼大 → 高频多、留不住**。
所以班卓琴的声音**亮得刺耳、短得像敲了一下**，而且低音尤其薄
（膜小、又留不住低频）。

这也解释了它为什么在**蓝草与爱尔兰传统音乐**里那么好用：
这些音乐要的是**节奏的清晰度**，而不是和声的厚度。
一根根音清清楚楚地"啪"出来，正是它擅长的。

## 音域

```range
{"range":"D3–D6","common":"D3–D5","caption":"五弦班卓琴的音域（开放 G 定弦）","caption_en":"Five-string banjo range in open G","note":"最低的 D3 是第 4 弦空弦；最高按第 1 弦（D4）上到高把位约两个八度计算，随品格数不同。第 5 弦是短弦，空弦为 G4。"}
```

音域不宽（约三个八度），但**用法很特别**：

- **低音区只有 D3 到 G3**（第 4、3 弦）。班卓琴**没有真正的低音** ——
  这也是它在合奏里不承担低音声部的原因。
- **第 5 弦（G4）是一条固定的高音线**。它不参与旋律，但在滚奏里每一个循环都会响一次，
  提供"闪"的听感 —— 与[[instrument:ukulele|尤克里里]]那根高音 G 弦的作用完全一样。
- **常用区集中在中高音**（D4–D5），因为旋律通常在第 1、2 弦上跑。

## 音色与听辨

四条线索：

1. **音头极"炸"**。拨弦的瞬间有一声清脆的"啪"，比吉他明显得多 ——
   这是膜被瞬间推动的结果。
2. **余音极短**。音出来后很快就退，所以快速音型不会糊成一片，
   反而像一串珠子。
3. **低音薄**。整件乐器没有厚实的底部，听起来总是"悬"在上面。
4. **膜对温湿度很敏感**。天气变化会让膜的张力改变 → 音准与音色一起变。
   演奏者常常在演出前重新调弦、甚至调膜的张力 —— 这是木吉他不需要操心的。

```audiolab
{"type":"instrument","gm":"Banjo","synth":"plucked","phrase":["D3","G3","B3","D4","G4"],"label":"五根空弦：D3 到 G4","label_en":"Five open strings — D3 up to G4","hint":"注意最低的 D3 与最高的 G4（短弦）之间的落差 —— 中间那一段是班卓琴的常用区","hint_en":"Hear the leap from the low D3 to the G4 of the short drone string — the middle is where banjo melodies live."}
```

> 本页「在库中听例子」里的曲子是**传统单声部舞曲**（库内没有可确认为班卓琴的曲目），
> 音色由上面的试听件负责。

## 演奏技法

班卓琴的右手分成**两大流派**，差别不只是手型，而是两种音乐语言：

- **爪锤式（clawhammer / frailing）**：手背朝外，用指甲**向下**扫弦，
  拇指随后拨第 5 弦（短弦）补一个高音 —— 这就是"老派"（old-time）的声音。
  节奏感强、和声简单，多用于伴唱与舞蹈。
- **三指滚奏（Scruggs style）**：拇指、食指、中指（常戴指套）
  按固定模式轮流拨弦，形成**滚奏（roll）** —— 这是蓝草音乐的声音。
  速度快、颗粒密，能一边跑旋律一边维持节奏型。

两种技法都高度依赖**第 5 弦那条持续音**：爪锤式用拇指拨它，滚奏在各式 pattern 里插入它。
可以说，**没有第 5 弦，班卓琴的风格就不成立**。

其余技法与吉他族共通：滑音、击弦、勾弦等，但**弦细、张力小**，
所以推弦（bend）幅度比吉他小，而滑音更滑。

## 家族与近亲

| 乐器 | 弦 | 定弦 | 共鸣体 | 特色 |
|---|---|---|---|---|
| **五弦班卓** | 5（含短弦） | G4 D3 G3 B3 D4 | **膜** | 短弦持续音、滚奏 |
| 四弦高音班卓 | 4 | C3 G3 D4 A4（五度） | **膜** | 与[[instrument:viola\|中提琴]]同定弦逻辑 |
| 班卓里里 | 4 | G4 C4 E4 A4 | **膜** | 与[[instrument:ukulele\|尤克里里]]同定弦 |
| [[instrument:classical-guitar\|古典吉他]] | 6 | E A D G B E | 木板 | 尼龙弦、指弹 |
| [[instrument:ukulele\|尤克里里]] | 4 | G4 C4 E4 A4（复入式） | 木板 | 复入式定弦 |

**一条很值得注意的对照**：班卓琴与尤克里里都是"复入式定弦 + 一根高音弦"
（班卓是第 5 弦短弦，尤克里里是第 4 弦）—— 两者**出自完全不同的传统**
（非洲—北美 vs 葡萄牙—夏威夷），却各自独立地选到了同一种设计。
这不是巧合：**一根固定的高音弦，是小体型拨弦乐器"把和声变得明亮"的通用手段。**

## 历史演变

| 时期 | 状态 |
|---|---|
| 17 世纪起 | 源自**西非**的拨弦乐器（形制与演奏方式），随大西洋奴隶贸易被带到北美 |
| 18–19 世纪 | 在美国的黑人社群与南方乡村中使用；琴体多为葫芦或木环蒙皮 |
| 19 世纪中叶 | **第五弦（短弦）**出现并固定下来，成为今天五弦班卓的直接前身 |
| 19 世纪后期 | 工业化生产（含金属音环与张力钩）让它普及；**游艺表演（minstrel show）**把它推向大众 —— 那是一种带有种族歧视色彩的表演形式，这是班卓琴历史里无法绕过的一页 |
| 19 世纪末—20 世纪初 | 四弦高音班卓（tenor）进入爵士与舞蹈乐队；琴体由皮膜逐步改为塑料膜 |
| 1940 年代 | **Earl Scruggs** 的三指滚奏与 Bill Monroe 的蓝草乐队把它定格为蓝草的核心乐器 |
| 20 世纪中叶起 | 同时被民谣复兴（Pete Seeger 等人）与爱尔兰传统音乐吸收 —— 后者用的多是四弦高音班卓 |

## 常见误解

- **"班卓琴是膜鸣乐器。"** → 在 HS 分类里它是**弦鸣**。判据是"**什么在振动发声**"：
  弦是振源，**膜只是放大件**。定音鼓是膜鸣（膜本身是振源），班卓琴不是。
- **"第 5 弦短是为了省料。"** → 那条短弦是**刻意的设计**：它空弦为高音 G4，
  比第 4 弦还高，专门提供持续音。少了它，爪锤式与滚奏都不成立。
- **"弦越多声音越厚。"** → 班卓琴五根弦，声音却**没有低音**：膜小、又留不住低频。
  厚不厚取决于共鸣体，不取决于弦数。
- **"它和吉他差不多。"** → 共鸣体一个是膜、一个是板，衰减曲线完全不同
  （见本页第二张图）。两者在合奏里的角色因此也不同。
- **"定弦只有一种。"** → 五弦班卓有开放 G、双 C、山调（Sawmill）等多种；
  四弦高音班卓是纯五度；班卓里里与尤克里里相同。族群内部的差异很大。
- **"音准调一次就行。"** → 膜对温湿度敏感，张力会变。
  班卓琴演奏者需要比吉他手更频繁地检查音准，有时还要调膜。

## 下一步

到这里，**西洋弦乐（I1）14 条全部完成**。想继续听"膜"这条线：
同族里还有中东的**达夫鼓**、日本的**太鼓**（世界乐器条目里会讲）；
想对照"复入式定弦"这条线，[[instrument:ukulele|尤克里里]] 一节讲得最细。
:::

::: en
The banjo has something no other string instrument has: **its resonator is not a wooden plate but a membrane.**

A skin (traditionally goatskin, now usually synthetic) is stretched over a circular rim, the strings press
their vibration onto that skin, and the skin pushes it into the air. That one fact decides all of its
sound — **bright, explosive and short**.

It also has a counter-intuitive piece of design: **the fifth of its five strings is a short one**, pitched
*higher* than the fourth, and used almost purely as a drone. That is the same kind of idea as the
[[instrument:ukulele|ukulele]]'s re-entrant tuning.

| Classification | Value |
|---|---|
| **HS class** | **Chordophone** — the vibrating body is the string (the **membrane is an amplifier, not a source**) |
| **Sub-type** | Plucked (pick or fingers) · necked, fretted · **resonator is a stretched membrane** |
| **Family** | Western · Strings (plucked branch) · shares ancestry with West African plucked instruments |
| **Bayin** | Not applicable — the eight categories are a Chinese system; the banjo is outside it |

> ⚠️ **One conceptual point**: in Hornbostel–Sachs the banjo is a **chordophone**, not a membranophone.
> The test is **what vibrates to make the sound**: the string is the source; the membrane amplifies and
> colours it. A timpani is a membranophone (the membrane *is* the source); a banjo is not — a common line
> to get wrong in the HS system.

## Structure: a circular body and a short string

```svg
<svg viewBox="0 0 640 476" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Five-string banjo parts: the membrane over a circular rim, tension hooks, tone ring, bridge, long neck and the short fifth string with its peg">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">Five-string banjo — outer form and principal parts (circular head, short fifth string)</text>
  </g>
  <path d="M304,66 L336,66 L344,330 L296,330 Z" fill="#0E0E10"/>
  <g stroke="#343439" stroke-width=".9">
    <path d="M300,96 L340,96"/><path d="M301,126 L339,126"/><path d="M302,156 L338,156"/>
    <path d="M302,186 L338,186"/><path d="M303,216 L337,216"/><path d="M303,246 L337,246"/>
    <path d="M304,276 L336,276"/><path d="M304,306 L336,306"/>
  </g>
  <path d="M306,34 L334,34 L336,66 L304,66 Z" fill="#17171A" stroke="#343439" stroke-width="1.2"/>
  <g fill="#343439">
    <rect x="288" y="38" width="16" height="5" rx="1"/><rect x="336" y="38" width="16" height="5" rx="1"/>
    <rect x="288" y="50" width="16" height="5" rx="1"/><rect x="336" y="50" width="16" height="5" rx="1"/>
    <rect x="288" y="62" width="16" height="5" rx="1"/><rect x="336" y="62" width="16" height="5" rx="1"/>
  </g>
  <rect x="336" y="122" width="18" height="7" rx="1" fill="#9C7A3C"/>
  <circle cx="320" cy="372" r="66" fill="#17171A" stroke="#343439" stroke-width="1.6"/>
  <circle cx="320" cy="372" r="56" fill="#111113" stroke="#343439" stroke-width="1"/>
  <circle cx="320" cy="372" r="46" fill="#0E0E10" stroke="#5B7FA8" stroke-width="1.2"/>
  <g stroke="#6E6A64" stroke-width="2.2" stroke-linecap="round">
    <path d="M320,300 L320,308"/><path d="M352,305 L349,312"/><path d="M380,320 L374,326"/>
    <path d="M392,348 L384,352"/><path d="M392,382 L384,378"/><path d="M380,406 L374,400"/>
    <path d="M352,420 L349,414"/><path d="M320,436 L320,428"/><path d="M288,420 L291,414"/>
    <path d="M260,406 L266,400"/><path d="M248,382 L256,378"/><path d="M248,348 L256,352"/>
    <path d="M260,320 L266,326"/><path d="M288,305 L291,312"/>
  </g>
  <path d="M296,356 L344,356 L340,364 L300,364 Z" fill="#A9A49B"/>
  <g stroke="#C9A227" opacity=".85">
    <path d="M310,68 L310,352" stroke-width="1.2"/>
    <path d="M315.5,68 L315.5,352" stroke-width="1.1"/>
    <path d="M321,68 L321,352" stroke-width="1"/>
    <path d="M326.5,68 L326.5,352" stroke-width=".9"/>
    <path d="M331,126 L331,352" stroke-width=".8"/>
  </g>
  <g class="lead" stroke="#6E6A64" stroke-width=".9">
    <path d="M186,42 L286,44"/><path d="M186,86 L296,88"/>
    <path d="M186,126 L330,130"/><path d="M186,232 L296,232"/>
    <path d="M186,306 L246,306"/><path d="M186,372 L252,372"/>
    <path d="M455,320 L382,326"/><path d="M481,392 L376,384"/>
    <path d="M497,436 L268,428"/>
  </g>
  <g font-family="system-ui,sans-serif" font-size="11" fill="#A9A49B">
    <text x="180" y="45" text-anchor="end">Headstock · five pegs</text>
    <text x="180" y="89" text-anchor="end">Fretted fingerboard (long)</text>
    <text x="180" y="129" text-anchor="end" fill="#9C7A3C">Fifth string's peg (at fret 5)</text>
    <text x="180" y="235" text-anchor="end">Fifth string (short, high)</text>
    <text x="180" y="309" text-anchor="end">Head (skin or synthetic)</text>
    <text x="180" y="375" text-anchor="end">Bridge standing on the head</text>
    <text x="612" y="323" text-anchor="end">Tone ring and tension hooks</text>
    <text x="612" y="395" text-anchor="end">Circular rim (the drum)</text>
    <text x="180" y="439" text-anchor="end">Twenty-plus tension hooks</text>
  </g>
  <text x="20" y="446" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">The head is tensioned by twenty-odd hooks — change the tension and the timbre changes,</text>
  <text x="20" y="462" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">so a banjo is far more humidity-sensitive than a guitar.</text>
</svg>
```

Three points:

1. **The circular body is a drum.** The head is stretched over a rim and tensioned by twenty-odd
   **hooks**. The strings press their vibration onto it through the bridge — **the head is the amplifier**,
   so a banjo needs no "soundhole": the whole head radiates.
2. **The fifth string is short.** Its tuning peg sits at the fifth fret rather than on the headstock, so
   the string can be stopped no higher than fret 5. Its job is to be a **drone**, supplying a fixed high
   **G4** inside rolls — the same family of idea as the [[instrument:ukulele|ukulele]]'s re-entrant
   tuning: **one string that stays out of the melody and only adds colour**.
3. **A long neck and many frets.** The neck is longer than a guitar's and the strings are thin and
   lightly tensioned, so it moves very fast — the physical precondition for bluegrass's dense patterns.

**Tuning** (fifth string to first): **G4 – D3 – G3 – B3 – D4.** Struck open, they spell a G major chord,
hence "open G". Two relatives matter:

| Variant | Strings | Tuning | Used in |
|---|---|---|---|
| **Five-string** (standard) | 5 (one short) | G4 D3 G3 B3 D4 | bluegrass, old-time, folk |
| Tenor (four-string) | 4 | C3 G3 D4 A4 (**fifths**) | Irish traditional music, early jazz |
| Banjolele | 4 | G4 C4 E4 A4 (as a ukulele) | light accompaniment, songs |

Note that the tenor banjo is tuned in **perfect fifths** (C–G–D–A) — the
[[instrument:viola|viola]]'s logic. That is why it became a fixture of Irish traditional music:
**same tuning as the fiddle, so the fingerings transfer.**

## How it sounds: why a membrane "cracks"

```svg
<svg viewBox="0 0 640 320" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Two resonators compared: a thin membrane gives a hard attack and a very fast decay; a wooden plate with braces gives a softer attack and a slow decay">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">The resonator: a layer of membrane, or a plate of wood</text>
  </g>
  <text x="170" y="60" text-anchor="middle" fill="#6E6A64">Banjo · a membrane</text>
  <path d="M70,110 C110,88 230,88 270,110" fill="none" stroke="#9C7A3C" stroke-width="3"/>
  <g stroke="#6E6A64" stroke-width="2.6" stroke-linecap="round">
    <path d="M70,110 L70,126"/><path d="M270,110 L270,126"/>
  </g>
  <path d="M162,86 L178,86 L176,72 L164,72 Z" fill="#A9A49B"/>
  <g stroke="#C9A227" opacity=".9">
    <path d="M90,72 L250,72" stroke-width="1.1"/><path d="M90,80 L250,80" stroke-width=".9"/>
  </g>
  <text x="470" y="60" text-anchor="middle" fill="#6E6A64">Guitar family · a wooden plate</text>
  <rect x="370" y="94" width="200" height="12" rx="2" fill="#5B7FA8"/>
  <g stroke="#5B7FA8" stroke-width="5" stroke-linecap="round" opacity=".7">
    <path d="M410,110 L410,126"/><path d="M470,110 L470,126"/><path d="M530,110 L530,126"/>
  </g>
  <path d="M464,80 L480,80 L478,94 L466,94 Z" fill="#A9A49B"/>
  <g stroke="#C9A227" opacity=".9">
    <path d="M390,68 L550,68" stroke-width="1.1"/><path d="M390,76 L550,76" stroke-width=".9"/>
  </g>
  <g stroke="#242427" stroke-width="1">
    <path d="M70,240 L290,240"/><path d="M370,240 L590,240"/>
  </g>
  <path d="M78,240 L86,176 L104,222 L124,234 L150,238 L200,240 L280,240"
        fill="none" stroke="#9C7A3C" stroke-width="2.4" stroke-linejoin="round"/>
  <path d="M378,240 L386,190 L410,206 L450,220 L500,230 L560,236 L586,240"
        fill="none" stroke="#5B7FA8" stroke-width="2.4" stroke-linejoin="round"/>
  <g font-family="system-ui,sans-serif" font-size="11" text-anchor="middle">
    <text x="170" y="262" fill="#9C7A3C">hard attack, very fast decay</text>
    <text x="470" y="262" fill="#5B7FA8">soft attack, slow decay</text>
  </g>
  <text x="20" y="292" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">A membrane is thin, light and highly damped — the sound arrives and leaves at once.</text>
  <text x="20" y="310" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">A wood plate is thick and braced — the sound stays. So a banjo's tone is material, not style.</text>
</svg>
```

**The difference between membrane and plate comes down to four quantities**:

| | Membrane (banjo) | Wood plate (guitar) |
|---|---|---|
| Thickness | extremely thin (under 1 mm) | thick (2–3 mm, plus braces) |
| Mass | very light | heavy |
| Internal damping | high (skin or plastic absorbs energy) | low (wood passes it along the grain) |
| Result | **hard attack, very fast decay** | **soft attack, slow decay** |

The four form one causal chain: **light plus damped means lots of high frequency and no tail.** So a banjo
sounds **piercingly bright and as short as a tap**, with a particularly thin bass (small head, and low
frequencies cannot be held).

That also explains why it works so well in **bluegrass and Irish traditional music**: those repertoires
want **rhythmic clarity**, not harmonic weight. A note that cracks out cleanly is exactly what it offers.

## Range

```range
{"range":"D3–D6","common":"D3–D5","caption":"五弦班卓琴的音域（开放 G 定弦）","caption_en":"Five-string banjo range in open G","note":"最低的 D3 是第 4 弦空弦；最高按第 1 弦（D4）上到高把位约两个八度计算，随品格数不同。第 5 弦是短弦，空弦为 G4。"}
```

The range is narrow (about three octaves) but its use is unusual:

- **The bass runs only D3 to G3** (strings 4 and 3). A banjo has **no real bass** — which is why it does
  not carry the bass part in an ensemble.
- **The fifth string (G4) is a fixed high line.** It stays out of the melody, but in a roll it sounds once
  per cycle, giving the shimmer — exactly the role of the ukulele's high G.
- **The working register sits in the upper middle** (D4–D5), because melodies run on strings 1 and 2.

## Timbre, and how to hear it

Four cues:

1. **An explosive attack.** The pluck lands with a sharp "crack", far more pronounced than a guitar's —
   the head being set in motion at once.
2. **A very short tail.** The note leaves almost as soon as it arrives, so fast passagework never smears;
   it beads instead.
3. **A thin bottom.** There is no solid low end; the instrument always seems to hang above the music.
4. **Extreme sensitivity to humidity.** Weather changes head tension, which changes intonation and timbre
   together. Players retune before playing and sometimes adjust the head itself — nothing a guitarist
   needs to think about.

```audiolab
{"type":"instrument","gm":"Banjo","synth":"plucked","phrase":["D3","G3","B3","D4","G4"],"label":"五根空弦：D3 到 G4","label_en":"Five open strings — D3 up to G4","hint":"注意最低的 D3 与最高的 G4（短弦）之间的落差 —— 中间那一段是班卓琴的常用区","hint_en":"Hear the leap from the low D3 to the G4 of the short drone string — the middle is where banjo melodies live."}
```

> The tracks under “Listen in the library” are **single-line traditional dance tunes** (nothing in the
> library can be confirmed as banjo music); timbre comes from the player above.

## Playing techniques

The right hand splits into **two schools** that differ not just in hand shape but in musical language:

- **Clawhammer (frailing)**: the back of the hand faces out and the nails strike **downwards**, with the
  thumb then catching the fifth string — the "old-time" sound. Strongly rhythmic, harmonically simple,
  used for songs and dancing.
- **Scruggs style (three-finger rolls)**: thumb, index and middle finger (usually with picks) alternate in
  fixed patterns to make **rolls** — the bluegrass sound. Fast and densely grained, able to run a melody
  while keeping the rhythm going.

Both depend heavily on **the fifth string's drone**: clawhammer takes it with the thumb, and rolls insert
it in every pattern. It is fair to say that **without the fifth string the banjo's styles would not exist**.

The rest of the technique is shared with the guitar family — slides, hammer-ons, pull-offs — but the
strings are thin and lightly tensioned, so bends are smaller and slides are slicker.

## The family

| Instrument | Strings | Tuning | Resonator | Distinction |
|---|---|---|---|---|
| **Five-string banjo** | 5 (one short) | G4 D3 G3 B3 D4 | **membrane** | short drone string, rolls |
| Tenor banjo | 4 | C3 G3 D4 A4 (fifths) | **membrane** | same tuning logic as a [[instrument:viola\|viola]] |
| Banjolele | 4 | G4 C4 E4 A4 | **membrane** | same tuning as a [[instrument:ukulele\|ukulele]] |
| [[instrument:classical-guitar\|Classical guitar]] | 6 | E A D G B E | wood plate | nylon strings, fingers |
| [[instrument:ukulele\|Ukulele]] | 4 | G4 C4 E4 A4 (re-entrant) | wood plate | re-entrant tuning |

**One comparison worth noting**: the banjo and the ukulele both use "re-entrant tuning plus one high
string" (the banjo's short fifth, the ukulele's fourth) — and they come from **completely different
traditions** (West Africa via North America; Portugal via Hawaiʻi), yet both landed independently on the
same design. That is not coincidence: **a fixed high string is the general-purpose way for a small plucked
instrument to make its harmony sound bright.**

## History

| Period | State |
|---|---|
| From the 17th c. | derived from **West African** plucked instruments, carried to North America by the Atlantic slave trade |
| 18th–19th c. | played in Black communities and the rural American South; bodies were gourds or wooden rims with skin heads |
| Mid-19th c. | **the short fifth string** appears and settles — the direct ancestor of today's five-string |
| Late 19th c. | industrial production (metal tone rings, tension hooks) spreads it; **minstrel shows** popularised it — a form of performance built on racist caricature, and a page of the banjo's history that cannot be skipped |
| Late 19th–early 20th c. | the four-string tenor banjo enters jazz and dance bands; skin heads give way to plastic |
| 1940s | **Earl Scruggs**'s three-finger rolls and Bill Monroe's bluegrass band fix the banjo as bluegrass's core instrument |
| From the mid-20th c. | also taken up by the folk revival (Pete Seeger and others) and by Irish traditional music — the latter mostly on the tenor banjo |

## Common misconceptions

- **"The banjo is a membranophone."** In Hornbostel–Sachs it is a **chordophone**. The test is **what
  vibrates to make the sound**: the string is the source, the **membrane only amplifies**. A timpani is a
  membranophone; a banjo is not.
- **"The fifth string is short to save material."** That short string is **deliberate design**: open it
  sounds G4, higher than the fourth string, expressly as a drone. Without it neither clawhammer nor rolls
  would exist.
- **"More strings means a thicker sound."** A banjo has five strings and **no bass**: a small head cannot
  hold low frequencies. Thickness comes from the resonator, not the string count.
- **"It is more or less a guitar."** One resonator is a membrane, the other a plate, and the decay curves
  differ completely (see the second diagram). Their roles in an ensemble differ for the same reason.
- **"There is only one tuning."** Five-string banjos use open G, double C, sawmill and more; tenor banjos
  are tuned in fifths; banjoleles match a ukulele. The family's internal variety is large.
- **"Tune it once and you are done."** The head is humidity-sensitive and its tension drifts.
  Banjo players check intonation more often than guitarists, and sometimes adjust the head itself.

## Next

That completes **all 14 entries of I1 (Western strings)**. To follow the "membrane" thread further: the
same family includes the Middle Eastern **daf** and the Japanese **taiko** (covered with world instruments). For
"re-entrant tuning", the [[instrument:ukulele|ukulele]] entry covers it in most detail.
:::
