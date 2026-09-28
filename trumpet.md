---
id: trumpet
site: inst
cat: I3
title: 小号
title_en: Trumpet
summary: 靠嘴唇振动发声的活塞铜管，管弦乐与爵士里最灵活的高音铜管
summary_en: The piston-valve brass driven by vibrating lips — the most agile high brass in orchestra and jazz
level: standard
tags: [乐器, 铜管, 西洋, 爵士]
tags_en: [instrument, brass, western, jazz]
alias: [小号, trumpet, 小喇叭, 降B调小号]
order: 42
links:
  - "[[concept:interval]]"
  - "[[concept:register]]"
  - "[[concept:timbre]]"
  - "[[concept:articulation]]"
  - "[[instrument:flute]]"
  - "[[instrument:cornet]]"
  - "[[instrument:flugelhorn]]"
  - "[[instrument:trombone]]"
instances:
  - pdmx-002313 | 海顿 降 E 大调小号协奏曲 Hob.VIIe:1 —— 小号文献的巅峰，第三乐章尤其著名
  - pdmx-002820 | 为三支小号与定音鼓而作的协奏曲 TWV 54:D4 —— 巴洛克小号的多声部写法
  - pdmx-001449 | Sound the trumpet（普赛尔）—— 巴洛克时期小号最典型的用法之一
  - pdmx-001964 | Trumpet Concerto Op.18 —— 浪漫派的小号协奏曲
sources:
  - 结构依通行制琴资料：全长约 1.48 米（含盘绕），黄铜管身在通向喇叭口前以圆柱为主，三个活塞阀，杯形号嘴
  - 「降 B 调小号是移调乐器，记谱比实音高大二度」依通行配器资料
  - 「音域记谱 F♯3–C6（实音 E3–B♭5）」依通行配器资料
  - 「铜管靠嘴唇振动（唇鸣）发声，音高由管长与泛音列共同决定；活塞延长管长以补齐泛音列之间的音」依管乐器声学
  - 『库内标题含 cornet 的曲目多指文艺复兴的 cornetto（科尔内管），与本族的活塞短号不是同一件乐器』依乐器史
updated: 2026-09-26
---

::: zh
小号是铜管组里最灵活的一支，也是"铜管是什么"这个问题最好的入口。
它与木管的根本差别不在材料，而在**驱动方式**：木管靠**气流**（切边或吹簧片），
铜管靠**嘴唇本身的振动**。演奏者的嘴唇就是簧片。

这带来一个木管没有的现象：**一根管子只能吹出泛音列上的那些音。**
想要中间的音，就得**改变管长** —— 这正是活塞存在的理由。

| 分类 | 归属 |
|---|---|
| **HS 分类** | **气鸣**（Aerophone）· **唇鸣**（lip-vibrated） |
| **次级类型** | 杯形号嘴 · **三活塞阀** · 管身以圆柱为主 + 圆锥喇叭口 · **降 B 调移调乐器** |
| **所属族** | 西洋 · 铜管（小号族） |
| **八音** | 不适用 —— 周代八音是中国乐器的体系，小号不在其中 |

> ⚠️ **一个概念上的要点**：**铜管与木管的分界在"什么在振动"，不在"什么材料"。**
> 长笛是金属的，但属木管；[[instrument:serpent|蛇形号]]是木头的，却属铜管（靠嘴唇吹）。
> 判据只有一条：**振源是空气柱（木管）还是嘴唇（铜管）。**
> 小号是铜管的**典型**：它的音色、它的灵活性、它的难度，全都从"嘴唇当簧片"这一条推出来。

## 铜管的三个层次

和木管一样，铜管的差异也可以用几个正交的维度说清。**三个层次**：

| 层次 | 决定什么 | 取值 |
|---|---|---|
| **管长的改变方式** | 能吹多快 / 能不能滑音 | 滑管（长号）/ 活塞（小号一族）/ 无（自然号只用泛音列） |
| **管形的圆锥度** | 音色偏亮还是偏柔 | 圆柱为主（亮）/ 圆锥为主（柔） |
| **号嘴的深度** | 音色的厚薄与高音难度 | 浅（亮、高音易）/ 深（柔、高音难） |

小号在这三项上的取值是：**活塞 · 圆柱为主 · 浅号嘴** —— 三项都指"亮而灵活"。
而[[instrument:french-horn|圆号]]的三项几乎全都相反，所以两者音色差得极远。

## 结构：活塞、直管与喇叭口

```svg
<svg viewBox="0 0 640 380" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="小号外形与主要部件：号嘴、三活塞阀、以圆柱为主的管身、圆锥喇叭口与指环">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">小号 · 外形与主要部件（活塞阀 + 以圆柱为主的管身）</text>
  </g>
  <rect x="96" y="164" width="34" height="16" rx="6" fill="#17171A" stroke="#9C7A3C" stroke-width="1.3"/>
  <path d="M130,166 L206,158 L206,186 L130,178 Z" fill="#17171A" stroke="#343439" stroke-width="1.3"/>
  <rect x="204" y="140" width="52" height="66" rx="5" fill="#17171A" stroke="#343439" stroke-width="1.4"/>
  <g fill="#0E0E10" stroke="#E07A3F" stroke-width="1.4">
    <rect x="212" y="112" width="10" height="30" rx="4"/>
    <rect x="226" y="104" width="10" height="38" rx="4"/>
    <rect x="240" y="116" width="10" height="26" rx="4"/>
  </g>
  <path d="M256,158 L364,150 L364,178 L256,186 Z" fill="#17171A" stroke="#343439" stroke-width="1.3"/>
  <path d="M364,152 L452,146 L452,182 L364,176 Z" fill="#17171A" stroke="#343439" stroke-width="1.3"/>
  <path d="M452,144 C500,142 534,150 548,166 C534,182 500,190 452,184 Z" fill="#17171A" stroke="#343439" stroke-width="1.4"/>
  <path d="M548,166 L560,150 L566,182 Z" fill="#17171A" stroke="#343439" stroke-width="1.2"/>
  <rect x="344" y="188" width="62" height="9" rx="4" fill="#343439"/>
  <g class="lead" stroke="#6E6A64" stroke-width=".9">
    <path d="M186,166 L186,152"/><path d="M186,104 L186,118"/>
    <path d="M186,240 L186,200"/><path d="M486,132 L470,142"/>
  </g>
  <g font-family="system-ui,sans-serif" font-size="11" fill="#A9A49B">
    <text x="180" y="149" text-anchor="end">杯形号嘴</text>
    <text x="180" y="101" text-anchor="end" fill="#E07A3F">三个活塞阀（七种组合）</text>
    <text x="180" y="243" text-anchor="end">管身以圆柱为主</text>
    <text x="492" y="129">圆锥喇叭口</text>
  </g>
  <text x="20" y="300" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">管子在喇叭口之前基本是等径的圆柱 —— 这是小号音色"亮而集中"的第一个原因。</text>
  <text x="20" y="322" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">三个活塞可以让气流走三条额外的短管，把管长加长 1、2 或 3 个半音的量，组合起来共七种。</text>
  <text x="20" y="344" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">七种管长 × 各自的一条泛音列 = 覆盖十二个半音 —— 这就是活塞的全部任务。</text>
</svg>
```

三处要点：

1. **号嘴是杯形的**（cup mouthpiece）。嘴唇贴在杯口内，靠气压与张力振动 ——
   与木管"让气流切过某个边缘"完全不是一回事。
2. **管身以圆柱为主**。这是小号与[[instrument:french-horn|圆号]]、[[instrument:flugelhorn|富鲁格号]]音色分野的关键
   （后两者的圆锥比例更大）。
3. **三个活塞 = 七种管长**。每个活塞接入一段额外短管；
   组合起来可把管长加长 0、1、2、3、4、5、6 个半音的量。

## 泛音列 × 活塞

```svg
<svg viewBox="0 0 640 400" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="小号的泛音列与活塞：空管只给出泛音列上的音，活塞把整条泛音列下移以补齐半音">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">一根管子只能吹泛音列，活塞把泛音列整体挪位</text>
  </g>
  <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">
    <text x="20" y="76">空管（无活塞）</text>
    <text x="20" y="126">按 2 键（+1 半音）</text>
    <text x="20" y="176">按 1 键（+2 半音）</text>
    <text x="20" y="226">按 1+2 键（+3 半音）</text>
  </g>
  <g stroke="#E07A3F" stroke-width="5" stroke-linecap="round">
    <path d="M180,64 L180,84"/><path d="M240,64 L240,84"/><path d="M300,64 L300,84"/>
    <path d="M360,64 L360,84"/><path d="M420,64 L420,84"/><path d="M480,64 L480,84"/>
  </g>
  <g stroke="#E07A3F" stroke-width="5" stroke-linecap="round" opacity=".78">
    <path d="M180,114 L180,134"/><path d="M240,114 L240,134"/><path d="M300,114 L300,134"/>
    <path d="M360,114 L360,134"/><path d="M420,114 L420,134"/><path d="M480,114 L480,134"/>
  </g>
  <g stroke="#E07A3F" stroke-width="5" stroke-linecap="round" opacity=".6">
    <path d="M180,164 L180,184"/><path d="M240,164 L240,184"/><path d="M300,164 L300,184"/>
    <path d="M360,164 L360,184"/><path d="M420,164 L420,184"/><path d="M480,164 L480,184"/>
  </g>
  <g stroke="#E07A3F" stroke-width="5" stroke-linecap="round" opacity=".44">
    <path d="M180,214 L180,234"/><path d="M240,214 L240,234"/><path d="M300,214 L300,234"/>
    <path d="M360,214 L360,234"/><path d="M420,214 L420,234"/><path d="M480,214 L480,234"/>
  </g>
  <path d="M160,258 L560,258" stroke="#343439" stroke-width="1.4"/>
  <g stroke="#343439" stroke-width="1">
    <path d="M180,254 L180,262"/><path d="M240,254 L240,262"/><path d="M300,254 L300,262"/>
    <path d="M360,254 L360,262"/><path d="M420,254 L420,262"/><path d="M480,254 L480,262"/>
  </g>
  <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64" text-anchor="middle">
    <text x="180" y="278">1 次</text><text x="240" y="278">2 次</text><text x="300" y="278">3 次</text>
    <text x="360" y="278">4 次</text><text x="420" y="278">5 次</text><text x="480" y="278">6 次</text>
  </g>
  <g class="lead" stroke="#6E6A64" stroke-width=".9">
    <path d="M520,74 L492,74"/><path d="M520,224 L492,224"/>
  </g>
  <text x="20" y="316" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">同一列的相邻音之间是固定音程（八度、五度…）；活塞把整条列往下挪，挪出的空档由别的列补上。</text>
  <text x="20" y="338" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">四条列错开后，它们覆盖的音就拼成了完整的十二个半音；越往上的泛音越密，所以高音区本来就"音多"。</text>
  <text x="20" y="364" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">而"孔距"这种东西在铜管上不存在 —— 变音靠加长管，不靠开孔。</text>
</svg>
```

**这条机制是理解全部铜管的钥匙**：

- **音高来自泛音列**，所以铜管的指法逻辑与木管完全不同 —— 木管是"开孔改变有效管长"，
  铜管是"加长管身 + 选泛音"。
- **泛音越高越密**，所以铜管的高音区可以用活塞吹出很密的半音，
  低音区却必须靠**唇部与气息**"拉"出相邻的音 —— 这是低音区难的根本原因。
- **七种管长是标准配置**（三活塞）。这七条泛音列合起来，
  在常用音区里刚好覆盖十二个半音；更低的音（第七泛音之下）就需要**第四活塞**或加长管。

## 音域

```range
{"range":"E3–B♭5","written":"F♯3–C6","caption":"小号的记谱音域与实音音域","caption_en":"The trumpet: notated range above, sounding range below","note":"⚠️ 降 B 调小号是移调乐器 —— 记谱比实音高大二度。谱面写 F♯3–C6，实际出声 E3–B♭5。高音区可再上探，但需要极强的唇部控制。"}
```

- **实音 E3–B♭5**，约两个半八度 —— 与[[instrument:flute|长笛]]相当。
- **低音区（E3 附近）难**：泛音稀，活塞帮不上多少忙。
- **常用区 C4–C6**，是它的"说话区"。
- **高音区（C6 以上）** 是铜管演奏技术的试金石：难度全在唇部肌肉的张力控制。

## 音色与听辨

四条线索：

1. **亮、集中、带金属感**。圆柱管身 + 浅号嘴共同造成的，不是"因为是铜做的"。
2. **起音清晰**。嘴唇从静止到振动只要一瞬间，所以小号的**发音极确定** ——
   这是它同时适合号角式宣告与快速爵士句的原因。
3. **能"炸"也能"柔"**。加弱音器、改变唇部张力、用不同的号嘴，
   可以在很大范围里改变音色。
4. **强奏时带"边缘感"**。高音量下频谱会明显变宽 —— 这是它在管弦乐里常用于高潮与宣告的原因。

```audiolab
{"type":"instrument","gm":"Trumpet","synth":"brass","phrase":["E3","B3","E4","G4","B♭4","E5"],"label":"小号的常用区：E3 到 E5","label_en":"The trumpet's working register — E3 up to E5","hint":"注意起音的确定感与音色的集中 —— 振源是嘴唇，不是气流切边","hint_en":"Hear the decisive attack and focused tone — the source is vibrating lips, not a cut jet."}
```

## 演奏技法

- **弱音器（mute）是铜管特有的手段**。Straight / Cup / Harmon 等不同弱音器能大幅改变音色，
  而**木管没有对应的通用做法**。这是小号在爵士里音色变化极多的原因。
- **吐音（tonguing）**：舌头在号嘴处阻断气流，得到清晰的音头。铜管的吐音比木管更"硬"。
- **滑音（glissando）**：靠唇部张力快速滑动 —— 但**不如[[instrument:trombone|长号]]那样连续**，
  因为活塞只能离散地改变管长。
- **双吐与三吐（double / triple tonguing）**：快速重复音的技术，铜管的硬吐音使它特别有效。
- **花舌（flutter）**：与小号结合产生"咆哮"效果，爵士里常用。

## 家族与近亲

| 乐器 | 圆锥度 | 号嘴深度 | 音色 | 灵活性 |
|---|---|---|---|---|
| **小号** | 圆柱为主 | 较浅 | 亮、集中 | 极高 |
| [[instrument:cornet\|短号]] | 圆锥更多 | 略深 | 更圆、更柔 | 高 |
| [[instrument:flugelhorn\|富鲁格号]] | 圆锥最多 | 最深 | 柔、暗、像人声 | 中 |
| [[instrument:french-horn\|圆号]] | 圆锥更多 | 喇叭形 | 温润、远 | 中（音准最难） |
| [[instrument:trombone\|长号]] | 圆柱为主 | 较浅 | 亮而庄重 | 中（但可滑音） |
| [[instrument:tuba\|大号]] | 圆锥为主 | 很深 | 厚、暗 | 低 |

**小号族的"三兄弟"**（小号 / 短号 / 富鲁格号）是同一套管长、同一套指法，
**只靠圆锥度与号嘴深度**分出三个音色档位。
三者相差极小，音色却明显可辨 —— 这是"圆锥度决定音色"最干净的例证。

## 历史演变

| 时期 | 状态 |
|---|---|
| 古代 | 各类直管号角在多地使用，只能吹两三个音 |
| 中世纪—文艺复兴 | 长号形的**自然小号**（无活塞）用于仪典；高音技巧渐成专门的技艺 |
| 巴洛克 | **自然小号**的黄金期：靠泛音列能吹到很高的音，为它写了大量华丽的独奏段 |
| 19 世纪初 | **活塞阀**发明并普及 → 小号可以吹出完整的十二个半音，音乐写法随之解放 |
| 19 世纪 | 降 B 调小号定型；进入管弦乐与军乐队；同时**短号**在管乐团与早期爵士里流行 |
| 20 世纪 | 成为爵士乐的核心独奏乐器之一；弱音器技法被大量开发 |
| 20 世纪后期至今 | 管弦乐、管乐团、爵士、流行全面通用；也是当代作品里的常客 |

## 常见误解

- **"铜管因为是用铜做的。"** 材料不是判据。
  长笛是金属的却属木管，[[instrument:serpent|蛇形号]]是木头的却属铜管。
  **判据是"什么在振动"：嘴唇（铜管）还是空气柱（木管）。**
- **"活塞是改变音高的开关，按哪个键就出哪个音。"** 活塞做的是**加长管子**，
  而**具体出哪个音取决于泛音列** —— 同一个指法可以吹出好几个不同的音。
- **"小号只有一个调。"** 除降 B 调外还有 C 调、D 调、降 E 调等多种；
  巴洛克小号（[[instrument:natural-trumpet|自然小号]]）则完全没有活塞。
- **"短号就是小号。"** 同一族、同一套指法，但**圆锥度更大、号嘴更深** →
  音色明显更柔。这是"管形决定音色"的典型例证。
- **"铜管族的 cornet 就是短号。"** ⚠️ **历史上的 cornetto（科尔内管）是另一件乐器**：
  文艺复兴的木制（或骨制）管，靠**指孔**取音，不是活塞铜管。
  曲目单里看到 "cornet" 要先判断是哪一个 —— **名字相同不等于乐器相同**。

## 下一步

小号族的"两个兄弟"是下一步最自然的对照：
[[instrument:cornet|短号]]（圆锥度更大）与 [[instrument:flugelhorn|富鲁格号]]（圆锥度最大）——
三件一起看，"圆锥度决定音色"这条规律最为清楚。

想换一个层次看铜管，就去看 [[instrument:trombone|长号]]：
它不用活塞，而是用**滑管连续改变管长** —— 铜管三层次里"管长改变方式"的另一极。
:::

::: en
The trumpet is the brass group's most agile instrument, and the best doorway to the question "what is
brass?". Its difference from the woodwinds is not material but **drive**: woodwinds are driven by **air**
(a cut jet or a reed), brass by **the lips themselves vibrating**. The player's lips *are* the reed.

That produces something no woodwind has: **a single tube can only sound the notes of one harmonic series.**
To get the notes in between, the **tube length must change** — which is exactly why valves exist.

| Classification | Value |
|---|---|
| **HS class** | **Aerophone** · **lip-vibrated** |
| **Sub-type** | Cup mouthpiece · **three piston valves** · mainly cylindrical body + conical bell · **B♭ transposing instrument** |
| **Family** | Western · Brass (trumpet family) |
| **Bayin** | Not applicable — a Chinese system; the trumpet is outside it |

> ⚠️ **One conceptual point**: **the brass/woodwind line is drawn by what vibrates, not by material.**
> A flute is metal but a woodwind; a [[instrument:serpent|serpent]] is wood but brass (blown with the lips).
> The only test: **is the source an air column (woodwind) or the lips (brass)?**
> The trumpet is the archetype — its colour, its agility and its difficulty all follow from "the lips as
> reed".

## The three layers of brass

As with woodwinds, the differences inside the brass can be laid out in a few orthogonal dimensions.
**Three layers**:

| Layer | Decides | Values |
|---|---|---|
| **How length changes** | speed / whether glissando is possible | slide (trombone) / valves (trumpets) / none (natural instruments) |
| **Conical vs cylindrical bore** | bright or soft | mostly cylindrical (bright) / mostly conical (soft) |
| **Mouthpiece depth** | thickness of tone, difficulty of the top | shallow (bright, easy top) / deep (soft, hard top) |

The trumpet reads **valves · mostly cylindrical · shallow cup** — all three pointing at "bright and agile".
The [[instrument:french-horn|horn]] reads almost the opposite on all three, which is why the two sound
worlds apart.

## Structure: valves, straight tube and bell

```svg
<svg viewBox="0 0 640 380" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Trumpet parts: mouthpiece, three piston valves, a mainly cylindrical body and a conical bell">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">Trumpet — outer form and principal parts (piston valves, mainly cylindrical body)</text>
  </g>
  <rect x="96" y="164" width="34" height="16" rx="6" fill="#17171A" stroke="#9C7A3C" stroke-width="1.3"/>
  <path d="M130,166 L206,158 L206,186 L130,178 Z" fill="#17171A" stroke="#343439" stroke-width="1.3"/>
  <rect x="204" y="140" width="52" height="66" rx="5" fill="#17171A" stroke="#343439" stroke-width="1.4"/>
  <g fill="#0E0E10" stroke="#E07A3F" stroke-width="1.4">
    <rect x="212" y="112" width="10" height="30" rx="4"/>
    <rect x="226" y="104" width="10" height="38" rx="4"/>
    <rect x="240" y="116" width="10" height="26" rx="4"/>
  </g>
  <path d="M256,158 L364,150 L364,178 L256,186 Z" fill="#17171A" stroke="#343439" stroke-width="1.3"/>
  <path d="M364,152 L452,146 L452,182 L364,176 Z" fill="#17171A" stroke="#343439" stroke-width="1.3"/>
  <path d="M452,144 C500,142 534,150 548,166 C534,182 500,190 452,184 Z" fill="#17171A" stroke="#343439" stroke-width="1.4"/>
  <path d="M548,166 L560,150 L566,182 Z" fill="#17171A" stroke="#343439" stroke-width="1.2"/>
  <rect x="344" y="188" width="62" height="9" rx="4" fill="#343439"/>
  <g class="lead" stroke="#6E6A64" stroke-width=".9">
    <path d="M186,166 L186,152"/><path d="M186,104 L186,118"/>
    <path d="M186,240 L186,200"/><path d="M486,132 L470,142"/>
  </g>
  <g font-family="system-ui,sans-serif" font-size="11" fill="#A9A49B">
    <text x="180" y="149" text-anchor="end">Cup mouthpiece</text>
    <text x="180" y="101" text-anchor="end" fill="#E07A3F">Three piston valves</text>
    <text x="180" y="243" text-anchor="end">Mainly cylindrical body</text>
    <text x="492" y="129">Conical bell</text>
  </g>
  <text x="20" y="300" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">The tube is essentially even bore until the bell — the first reason the trumpet sounds bright and focused.</text>
  <text x="20" y="322" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">Each valve routes air through an extra length, adding one, two or three semitones' worth of tube.</text>
  <text x="20" y="344" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">Three valves in combination give seven lengths; with their harmonic series that covers all twelve semitones.</text>
</svg>
```

Three points:

1. **A cup mouthpiece.** The lips rest inside the cup and vibrate through pressure and tension — nothing
   like "letting a jet cross an edge".
2. **A mainly cylindrical bore.** The key to the split between the trumpet and the
   [[instrument:french-horn|horn]] and [[instrument:flugelhorn|flugelhorn]], both far more conical.
3. **Three valves = seven lengths.** Each valve adds a length of tube; in combination they add 0, 1, 2, 3, 4,
   5 or 6 semitones' worth.

## Harmonic series × valves

```svg
<svg viewBox="0 0 640 400" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Trumpet harmonics and valves: an open tube offers only its harmonic series, and valves shift that series down to fill in the semitones">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">One tube sounds one harmonic series; valves move the whole series</text>
  </g>
  <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">
    <text x="20" y="76">Open (no valve)</text>
    <text x="20" y="126">Valve 2 (+1 semitone)</text>
    <text x="20" y="176">Valve 1 (+2 semitones)</text>
    <text x="20" y="226">Valves 1+2 (+3 semitones)</text>
  </g>
  <g stroke="#E07A3F" stroke-width="5" stroke-linecap="round">
    <path d="M180,64 L180,84"/><path d="M240,64 L240,84"/><path d="M300,64 L300,84"/>
    <path d="M360,64 L360,84"/><path d="M420,64 L420,84"/><path d="M480,64 L480,84"/>
  </g>
  <g stroke="#E07A3F" stroke-width="5" stroke-linecap="round" opacity=".78">
    <path d="M180,114 L180,134"/><path d="M240,114 L240,134"/><path d="M300,114 L300,134"/>
    <path d="M360,114 L360,134"/><path d="M420,114 L420,134"/><path d="M480,114 L480,134"/>
  </g>
  <g stroke="#E07A3F" stroke-width="5" stroke-linecap="round" opacity=".6">
    <path d="M180,164 L180,184"/><path d="M240,164 L240,184"/><path d="M300,164 L300,184"/>
    <path d="M360,164 L360,184"/><path d="M420,164 L420,184"/><path d="M480,164 L480,184"/>
  </g>
  <g stroke="#E07A3F" stroke-width="5" stroke-linecap="round" opacity=".44">
    <path d="M180,214 L180,234"/><path d="M240,214 L240,234"/><path d="M300,214 L300,234"/>
    <path d="M360,214 L360,234"/><path d="M420,214 L420,234"/><path d="M480,214 L480,234"/>
  </g>
  <path d="M160,258 L560,258" stroke="#343439" stroke-width="1.4"/>
  <g stroke="#343439" stroke-width="1">
    <path d="M180,254 L180,262"/><path d="M240,254 L240,262"/><path d="M300,254 L300,262"/>
    <path d="M360,254 L360,262"/><path d="M420,254 L420,262"/><path d="M480,254 L480,262"/>
  </g>
  <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64" text-anchor="middle">
    <text x="180" y="278">1st</text><text x="240" y="278">2nd</text><text x="300" y="278">3rd</text>
    <text x="360" y="278">4th</text><text x="420" y="278">5th</text><text x="480" y="278">6th</text>
  </g>
  <g class="lead" stroke="#6E6A64" stroke-width=".9">
    <path d="M520,74 L492,74"/><path d="M520,224 L492,224"/>
  </g>
  <text x="20" y="316" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">Shifted series interlock into a chromatic scale, and upper partials sit closer together.</text>
  <text x="20" y="338" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">That is also why the low register is hard: partials there are sparse, and valves cannot fill the gaps.</text>
  <text x="20" y="364" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">Note that "tone holes" do not exist on brass — you change the tube, not a hole.</text>
</svg>
```

**This mechanism is the key to all brass**:

- **Pitch comes from the harmonic series**, so brass fingering logic is nothing like a woodwind's: woodwinds
  open holes to change the *effective* length, brass **adds tube and picks a partial**.
- **Partials crowd together higher up**, so the upper register can produce dense semitones with valves, while
  the low register must be "pulled" into place by **lips and air** — the root of its difficulty.
- **Seven lengths** is the standard (three valves). Together those series cover all twelve semitones across
  the usual range; lower notes (below about the seventh partial) need a **fourth valve** or extra tubing.

## Range

```range
{"range":"E3–B♭5","written":"F♯3–C6","caption":"小号的记谱音域与实音音域","caption_en":"The trumpet: notated range above, sounding range below","note":"⚠️ 降 B 调小号是移调乐器 —— 记谱比实音高大二度。谱面写 F♯3–C6，实际出声 E3–B♭5。高音区可再上探，但需要极强的唇部控制。"}
```

- **Sounding E3–B♭5**, about two and a half octaves — comparable to the [[instrument:flute|flute]].
- **The low register (around E3) is hard**: partials are sparse and valves barely help.
- **The working register is C4–C6**, where it "speaks".
- **Above C6** is the brass player's proving ground, all of it controlled by lip tension.

## Timbre, and how to hear it

Four cues:

1. **Bright, focused, metallic.** Caused by the cylindrical bore plus the shallow cup — not by being made of
   brass.
2. **A decisive attack.** The lips go from still to vibrating in an instant, so the note starts with
   certainty — the reason it suits both fanfare and fast jazz lines.
3. **It can blare or soften.** Mutes, lip tension and different mouthpieces change the colour enormously.
4. **An "edge" at high volume**, where the spectrum broadens — why orchestras use it for climaxes and
   proclamations.

```audiolab
{"type":"instrument","gm":"Trumpet","synth":"brass","phrase":["E3","B3","E4","G4","B♭4","E5"],"label":"小号的常用区：E3 到 E5","label_en":"The trumpet's working register — E3 up to E5","hint":"注意起音的确定感与音色的集中 —— 振源是嘴唇，不是气流切边","hint_en":"Hear the decisive attack and focused tone — the source is vibrating lips, not a cut jet."}
```

## Playing techniques

- **Mutes are a brass specialty.** Straight, cup and harmon mutes transform the colour, and **no woodwind has
  a comparable general device** — part of why the trumpet changes character so much in jazz.
- **Tonguing**: the tongue interrupts the air at the mouthpiece for a crisp attack — harder than a
  woodwind's.
- **Glissando** by sliding the lip tension is possible, but **never as continuous as the
  [[instrument:trombone|trombone]]'s**, since valves change length in discrete steps.
- **Double and triple tonguing** are especially effective because of that hard attack.
- **Flutter tonguing** produces a growl, much used in jazz.

## The family

| Instrument | Conical? | Mouthpiece | Timbre | Agility |
|---|---|---|---|---|
| **Trumpet** | mostly cylindrical | fairly shallow | bright, focused | very high |
| [[instrument:cornet\|Cornet]] | more conical | a little deeper | rounder, softer | high |
| [[instrument:flugelhorn\|Flugelhorn]] | most conical | deepest | soft, dark, voice-like | medium |
| [[instrument:french-horn\|Horn]] | more conical | funnel | warm, distant | medium (hardest to keep in tune) |
| [[instrument:trombone\|Trombone]] | mostly cylindrical | fairly shallow | bright and solemn | medium (but can glide) |
| [[instrument:tuba\|Tuba]] | mostly conical | very deep | thick, dark | low |

**The trumpet's "three brothers"** (trumpet / cornet / flugelhorn) share one length and one set of fingerings
and **differ only in conicality and cup depth**. The differences are tiny on paper and obvious to the ear —
the cleanest demonstration anywhere of "the bore decides the colour".

## History

| Period | State |
|---|---|
| Antiquity | straight horns exist in many cultures, capable of only two or three notes |
| Medieval–Renaissance | the long **natural trumpet** (valveless) serves ceremony; high playing becomes a specialist craft |
| Baroque | the natural trumpet's golden age: its harmonic series reaches very high, and much brilliant solo writing exists for it |
| Early 19th c. | the **valve** is invented and spreads → a fully chromatic trumpet, and the writing is liberated |
| 19th c. | the B♭ trumpet settles; it enters orchestra and band, while the **cornet** thrives in bands and early jazz |
| 20th c. | becomes a core jazz solo instrument; mute techniques are greatly developed |
| Late 20th c. onward | used across orchestra, band, jazz and pop, and a regular in contemporary music |

## Common misconceptions

- **"Brass instruments are brass because they are made of brass."** Material is not the test: a flute is
  metal yet a woodwind, and a [[instrument:serpent|serpent]] is wood yet brass.
  **The test is what vibrates: lips (brass) or an air column (woodwind).**
- **"Valves are switches; press a key and you get that note."** A valve **adds tube**, and **which note comes
  out depends on the harmonic series** — one fingering gives several different notes.
- **"There is only one trumpet."** Besides B♭ there are C, D and E♭ trumpets, and the Baroque
  [[instrument:natural-trumpet|natural trumpet]] has no valves at all.
- **"A cornet is a trumpet."** Same family, same fingerings, but **more conical with a deeper cup** — audibly
  softer. A textbook case of bore deciding colour.
- **"The family's 'cornet' means the valved cornet."** ⚠️ **The historical cornetto is a different
  instrument**: a Renaissance wooden (or bone) pipe with **finger holes**, not a valved brass.
  Seeing "cornet" on a programme, check which one — **the same name is not the same instrument.**

## Next

The trumpet's two brothers are the natural next comparison: the [[instrument:cornet|cornet]] (more conical)
and the [[instrument:flugelhorn|flugelhorn]] (most conical) — read together, "the bore decides the colour" is
at its clearest.

For a different layer of brass, go to the [[instrument:trombone|trombone]]: no valves at all, but a **slide
that changes the tube length continuously** — the other pole of the "how length changes" layer.
:::
