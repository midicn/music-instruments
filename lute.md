---
id: lute
site: inst
cat: I1
title: 鲁特琴
title_en: Lute
summary: 梨形琴体、折角背板、多组复弦，文艺复兴与巴洛克的独奏主力
summary_en: Pear-shaped with a ribbed back and several doubled courses — the solo instrument of the Renaissance and Baroque
level: standard
tags: [乐器, 弦乐, 西洋]
tags_en: [instrument, strings, western]
alias: [鲁特琴, lute, 琉特琴, 诗琴, 鲁特]
order: 18
links:
  - "[[concept:interval]]"
  - "[[concept:register]]"
  - "[[concept:timbre]]"
  - "[[concept:articulation]]"
  - "[[instrument:classical-guitar]]"
  - "[[instrument:mandolin]]"
  - "[[instrument:viol]]"
instances:
  - giantmidi-000033 | Falckenhagen 的鲁特琴奏鸣曲集 —— 18 世纪巴洛克鲁特琴的典型织体，低音走动加高音旋律
  - giantmidi-006717 | Dowland 的加利亚德舞曲 —— 英国鲁特琴歌曲时代最常被单独演奏的体裁之一
  - giantmidi-006718 | 同一作曲家的另一首舞曲，句法更短，可对照低音线的处理
  - giantmidi-006719 | Dowland 的一首帕凡舞曲，慢速、多声部，最能听出复弦与指腹拨弦的清透
  - giantmidi-006047 | Jane Pickering 的鲁特琴曲集 —— 17 世纪手抄本曲集，收录当时流通的舞曲与歌曲改编
sources:
  - 琴体尺寸取通行制琴数据：文艺复兴鲁特琴琴体长 480 毫米、最大宽 330 毫米，弦长 600 毫米
  - 「文艺复兴鲁特琴常见为 6 组复弦、G 调定弦 G2 C3 F3 A3 D4 G4；第 3 组弦随调性在升 F 与还原 F 之间变化」依通行乐器学与早期音乐演奏惯例，本文为原创表述
  - 弦数随时代递增（15 世纪 4 组 → 16 世纪 6 组 → 17 世纪 7–10 组 → 18 世纪巴洛克鲁特琴 13 组）依通行乐器史叙述
  - 折角背板由多段窄板逐条拼接、与整块拱形背板的结构差异依通行制琴工艺叙述
updated: 2026-09-25
---

::: zh
鲁特琴是[[instrument:classical-guitar|吉他]]的祖先，也是**文艺复兴与巴洛克时期欧洲最普及的独奏乐器**。
它的样子和吉他差别明显：**梨形的琴体、折角拼接的背板、成组的复弦，
琴颈几乎与面板平行地伸出去**。

它还有一件在今天看来很特别的事：**定弦会随调性改变**。

| 分类 | 归属 |
|---|---|
| **HS 分类** | **弦鸣**（Chordophone）—— 发声体是弦本身 |
| **次级类型** | 拨奏（指腹／指甲）· 有颈、有板腔共鸣箱、有品 |
| **所属族** | 西洋 · 弦乐（弹拨支系） |
| **八音** | 不适用 —— 周代八音是中国乐器的体系，鲁特琴不在其中 |

## 结构：梨形琴体与折角背板

```svg
<svg viewBox="0 0 640 470" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="文艺复兴鲁特琴外形与主要部件：折角琴颈、六组复弦、音窗花饰、琴桥、梨形琴体与折角背板位置">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">文艺复兴鲁特琴 · 外形与主要部件（六组复弦，琴颈近乎与面板平行）</text>
  </g>
  <!-- 折角琴颈与琴头 -->
  <path d="M322,86 L338,86 L344,134 L320,134 Z" fill="#17171A" stroke="#343439" stroke-width="1.2"/>
  <g fill="#343439">
    <rect x="304" y="92" width="16" height="5" rx="1"/><rect x="340" y="92" width="16" height="5" rx="1"/>
    <rect x="304" y="104" width="16" height="5" rx="1"/><rect x="340" y="104" width="16" height="5" rx="1"/>
    <rect x="304" y="116" width="16" height="5" rx="1"/><rect x="340" y="116" width="16" height="5" rx="1"/>
  </g>
  <path d="M330,40 C316,40 306,30 310,18 C314,7 326,3 335,9 C343,15 342,27 332,30"
        fill="none" stroke="#A9A49B" stroke-width="2.4" stroke-linecap="round"/>
  <!-- 指板（延伸很远，几乎与面板同面） -->
  <path d="M314,86 L332,86 L330,196 L318,196 Z" fill="#0E0E10"/>
  <g stroke="#343439" stroke-width=".9">
    <path d="M314,110 L332,110"/><path d="M314,134 L332,134"/><path d="M314,158 L332,158"/><path d="M316,182 L331,182"/>
  </g>
  <!-- 梨形琴体 -->
  <path d="M320,120 C322.8,121 330.3,121 336.5,126 C342.7,131 349.9,139 357.1,150 C364.3,161 371.9,175.5 379.8,192 C387.7,208.5 397.3,230 404.6,249 C411.8,268 422.1,286.5 423.1,306 C424.2,325.5 417.6,350.5 410.8,366 C403.9,381.5 393.2,390.8 381.9,399 C370.5,407.2 353,412 342.7,415.5 C332.4,419 323.8,419.2 320,420 M320,420 C316.2,419.2 307.6,419 297.3,415.5 C287,412 269.5,407.2 258.1,399 C246.8,390.8 236.1,381.5 229.2,366 C222.4,350.5 215.8,325.5 216.9,306 C217.9,286.5 228.2,268 235.4,249 C242.7,230 252.3,208.5 260.2,192 C268.1,175.5 275.7,161 282.9,150 C290.1,139 297.3,131 303.5,126 C309.7,121 317.2,121 320,120 Z"
        fill="#17171A" stroke="#343439" stroke-width="1.4"/>
  <!-- 折角背板（虚线）：从顶到底的棱线 -->
  <g stroke="#9C7A3C" stroke-width="1.3" stroke-dasharray="3 3" fill="none" opacity=".9">
    <path d="M320,132 L320,412"/>
    <path d="M292,220 L320,300"/><path d="M348,220 L320,300"/>
  </g>
  <!-- 音窗（花饰） -->
  <circle cx="320" cy="262" r="21" fill="#0E0E10" stroke="#343439" stroke-width="1.4"/>
  <g stroke="#A9A49B" stroke-width="1" opacity=".8">
    <circle cx="320" cy="262" r="13" fill="none"/>
    <circle cx="320" cy="262" r="6" fill="none"/>
    <path d="M320,241 L320,283"/><path d="M299,262 L341,262"/>
    <path d="M305,247 L335,277"/><path d="M335,247 L305,277"/>
  </g>
  <!-- 琴桥（粘住不动） -->
  <path d="M296,330 L344,330 L344,338 L296,338 Z" fill="#111113" stroke="#343439" stroke-width="1.1"/>
  <path d="M302,330 L338,330" stroke="#A9A49B" stroke-width="1.5"/>
  <!-- 六组复弦（11 根） -->
  <g stroke="#C9A227" opacity=".85">
    <path d="M313,88 L313,332" stroke-width="1.1"/><path d="M316,88 L316,332" stroke-width="1.1"/>
    <path d="M318.5,88 L318.5,332" stroke-width="1"/><path d="M321.5,88 L321.5,332" stroke-width="1"/>
    <path d="M324,88 L324,332" stroke-width=".9"/><path d="M326,88 L326,332" stroke-width=".9"/>
    <path d="M328.5,88 L328.5,332" stroke-width=".85"/><path d="M330.5,88 L330.5,332" stroke-width=".85"/>
    <path d="M332.5,88 L332.5,332" stroke-width=".8"/><path d="M334.5,88 L334.5,332" stroke-width=".8"/>
    <path d="M336.5,88 L336.5,332" stroke-width=".8"/>
  </g>
  <!-- 标注 -->
  <g class="lead" stroke="#6E6A64" stroke-width=".9">
    <path d="M186,50 L302,54"/><path d="M186,98 L298,100"/>
    <path d="M186,150 L326,152"/><path d="M186,262 L292,262"/>
    <path d="M186,334 L290,334"/><path d="M186,376 L268,376"/>
    <path d="M186,404 L300,400"/>
  </g>
  <g font-family="system-ui,sans-serif" font-size="11" fill="#A9A49B">
    <text x="180" y="53" text-anchor="end">折角琴头（向后折）</text>
    <text x="180" y="101" text-anchor="end">六组弦轴（三对）</text>
    <text x="180" y="153" text-anchor="end">指板 · 与面板几乎同面</text>
    <text x="180" y="265" text-anchor="end">音窗（花饰，非圆孔）</text>
    <text x="180" y="337" text-anchor="end">琴桥（粘死，不能调）</text>
    <text x="180" y="379" text-anchor="end">下宽 330 mm</text>
    <text x="180" y="407" text-anchor="end" fill="#9C7A3C">折角背板（多段窄板拼接）</text>
  </g>
  <text x="20" y="452" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">琴颈与面板几乎同一平面 —— 这是鲁特琴"低张、轻结构"的一部分，也是折角琴头的由来。</text>
</svg>
```

四处特征，逐条说：

1. **梨形、无腰的琴体**。与小提琴族的"上下腰"完全不同 ——
   它更接近"水滴"：顶端窄、中下部最宽、底部圆收。
2. **折角背板**。背板不是一整块，而是**多段窄板逐条拼成**（像船壳），
   剖面因此是多边形。见下一节。
3. **音窗而不是圆音孔**。音孔上嵌一块雕花木片（rose），既是装饰也略微调节空气流量。
4. **琴桥是粘死的**。不能像吉他那样移动或调高 ——
   音准与手感全靠制琴时定死，所以老鲁特琴的演奏者非常在意温湿度。

## 折角背板：为什么拼起来比一整块更好

```svg
<svg viewBox="0 0 640 300" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="折角背板与拱形背板的横剖对比：鲁特琴由多段窄板拼成多边形，吉他是一整块或两块拼成的平滑弧">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">横剖对比 · 背板怎么做的，决定了它有多轻</text>
  </g>
  <!-- 鲁特琴：折角背板 -->
  <text x="20" y="60">鲁特琴 · 折角背板</text>
  <g stroke="#A9A49B" stroke-width="3.4" stroke-linecap="round">
    <path d="M110,100 L290,100"/>
  </g>
  <polyline points="110,100 138,148 168,178 200,190 232,178 262,148 290,100"
            fill="none" stroke="#9C7A3C" stroke-width="4.4" stroke-linejoin="round"/>
  <g stroke="#E8C547" stroke-width="1.4" fill="none">
    <circle cx="138" cy="148" r="3"/><circle cx="168" cy="178" r="3"/><circle cx="200" cy="190" r="3"/>
    <circle cx="232" cy="178" r="3"/><circle cx="262" cy="148" r="3"/>
  </g>
  <text x="200" y="216" text-anchor="middle" font-size="11" fill="#9C7A3C">六段窄板逐条拼接（剖面是多边形）</text>
  <!-- 吉他：拱形背板 -->
  <text x="350" y="60">古典／民谣吉他 · 拱形背板</text>
  <g stroke="#A9A49B" stroke-width="3.4" stroke-linecap="round">
    <path d="M350,100 L530,100"/>
  </g>
  <path d="M350,100 C378,168 420,192 440,192 C460,192 502,168 530,100"
        fill="none" stroke="#5B7FA8" stroke-width="4.4" stroke-linecap="round"/>
  <text x="440" y="216" text-anchor="middle" font-size="11" fill="#5B7FA8">整块（或两块）弯成平滑弧</text>
  <!-- 对比标注 -->
  <g stroke="#6E6A64" stroke-width="1" stroke-dasharray="3 3">
    <path d="M200,240 L200,268"/><path d="M440,240 L440,268"/>
  </g>
  <text x="20" y="286" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">折角拼法让每块窄板都顺着木纹 —— 背板能做得更薄更轻，所以鲁特琴音量小而音色通透。</text>
</svg>
```

木头的强度是**顺着纹理方向**的。一整块背板要弯成弧，就得让木头横着受力，
于是必须留厚一点；而折角做法是把**窄板一条条顺着木纹拼**，
每条都只承受顺纹的力 —— **同样的强度，板可以薄很多**。

结果是连锁的：

| 更薄的背板 → | 更轻的琴体 → | 更小的张力 → 更小的音量，更通透的音色 |
|---|---|---|

所以鲁特琴的"轻"不是巧合，是它的结构选择的必然结果。
同样用折角背板的还有[[instrument:viol|维奥尔琴]]一族中的部分形制，
以及近代的曼陀林（那波里式碗背）。

## 音域

```range
{"range":"G2–E5","common":"G2–G4","caption":"六组弦鲁特琴（G 调）的实音音域","caption_en":"Sounding range of a six-course lute in G","note":"鲁特琴的定弦随时代与调性变化 —— 尤其第 3 组弦（升 F 与还原 F 并存），所以不同文献给出的音域会有出入。这里给的是文艺复兴 6 组弦 G 调鲁特琴的常见范围。"}
```

**这里必须说清楚一件事**：鲁特琴的音域与定弦**没有唯一答案**。
它的历史跨度是三百年，弦数从 4 组涨到 13 组，定弦随调性调整。
把"鲁特琴的音域"当成一个定值讲是不准确的。

可以确定的是**文艺复兴 6 组弦 G 调**这个最典型的配置：

| 组 | 6 | 5 | 4 | 3 | 2 | 1 |
|---|---|---|---|---|---|---|
| 音名 | G2 | C3 | F3 | A3（或降 B3） | D4 | G4 |

其中**第 3 组的 F3 在需要时会临时调成升 F** —— 为了演奏需要升 F 的调性。
这在今天的乐器上几乎见不到（谁会为了一首曲子重新调一根弦？），
但在鲁特琴时代这是常规操作：**乐器跟着调性走，而不是调性迁就乐器**。

## 音色与听辨

四条线索，前三条是鲁特琴的特征，第四条是它最常见的误认：

1. **音量小、衰减快、音头干净**。羊肠弦 + 薄板 + 轻结构，
   结果是"轻而清楚"而不是"大而厚"。
2. **指腹拨弦**。鲁特琴用指腹（不是指甲，也不是拨片），
   所以音头没有拨片的"啪"，也没有指甲的"啵"，更像"点"了一下。
3. **复弦的波纹**。同音双弦的拍音给每个音一层细微颤动 ——
   与[[instrument:mandolin|曼陀林]]同源，但因为音区更低、衰减更快，听起来更"干"。
4. **它经常被误认为"古典吉他"。** 两者音色接近，
   区别在于：鲁特琴高音更细、低音更薄、整体动态更"文静"。
   如果一段录音里低音只有轮廓没有分量，很可能是鲁特琴而不是吉他。

```audiolab
{"type":"instrument","gm":"Guitar Harmonics","synth":"plucked","phrase":["G2","C3","F3","D4","G4"],"label":"六组空弦（G 调）","label_en":"Six open courses, lute in G","hint":"低音只有轮廓、没有分量 —— 这是薄板加低张力的结果，不是录音问题","hint_en":"The bass has shape but no weight — the consequence of a thin plate and low tension, not a recording fault."}
```

> 通用 MIDI 的音色表里**没有鲁特琴**，所以这里借用最接近的拨弦音色；
> 真实的鲁特琴音色请按"小音量、快衰减、指腹音头"去想象。
> 本页「在库中听例子」里的曲子是**乐谱的骨架**（转写或雕版 MIDI），音色由试听件负责。

## 演奏技法

鲁特琴的技法与后来的吉他有明显不同，主要集中在右手：

- **指腹 + 拇指在外侧**。拇指（p）负责低音组，食指与中指（i、m）负责高音。
  无名指在早期很少用。这与现代吉他的四指分工不同。
- **弹拨方向朝手心**。有些传统要求"向掌内拨"而不是"向外挑"，
  音色更柔、音量更小。
- **低音组用拇指单独走**。鲁特琴音乐的典型织体是"一条低音线 + 一条高音线 + 中间填充"，
  拇指的独立性因此是基本功。
- **不做大幅度的强弱**。轻结构承受不了强奏，所以鲁特琴音乐依赖
  **声部与和声的变化**而不是力度对比。
- **定弦随调性调整**。这是它独有的"演奏前准备"：某些曲目要重调第 3 组弦。

左手方面：有品、弦距小、张力低，所以左手很轻 —— 这也是鲁特琴技巧在 20 世纪
被"古乐运动"重新研究的原因之一。

## 家族与近亲

| 乐器 | 琴体 | 背板 | 弦 | 发音 | 时代重心 |
|---|---|---|---|---|---|
| **鲁特琴** | 梨形 | **折角（多段窄板）** | 6–13 组复弦（羊肠） | 指腹 | 15–18 世纪 |
| [[instrument:viol\|维奥尔琴]] | 有腰 | 折角或平 | 6 根单弦（有品） | 弓 | 15–17 世纪 |
| [[instrument:classical-guitar\|古典吉他]] | 有腰 | 拱形（整块） | 6 根单弦（尼龙） | 指甲 | 19 世纪至今 |
| [[instrument:mandolin\|曼陀林]] | 梨形／碗形 | 折角（那波里式） | 4 组复弦（钢） | 拨片 | 18 世纪至今 |

这张表把一条线串起来了：**复弦、折角背板、指腹拨弦**是早期拨弦乐器的共同特征；
**单弦、拱形背板、拨片／指甲**是后来的方向。
吉他与曼陀林各自保留了一半 —— 曼陀林留了复弦，吉他留了指腹之外的那一半。

## 历史演变

鲁特琴从**阿拉伯世界的乌德琴**（ud）传入欧洲，时间大致在**中世纪晚期**（经由西班牙与西西里）。
它一开始不是独奏乐器，而是**伴奏与合奏**用的。

16 世纪是它的第一个黄金期：**6 组弦、G 调定弦**稳定下来，
欧洲各国出现了大量**手抄本曲集**（tablature，用字母或数字记谱），
其中就有本页实例里的 Jane Pickering 鲁特琴曲集那一类。这时它已是**独奏乐器**。

17 世纪弦数继续增加：7 组、8 组、10 组 —— 多出来的弦放在低音侧，
用来演奏通奏低音。**调性也随之改变**（法国式、德国式鲁特琴的定弦不同）。

18 世纪它到了最后一个高峰，也是终点：**巴洛克鲁特琴**有 **13 组弦**，
为它写作的有 Falckenhagen、Weiss 等人（本页实例里的 Falckenhagen 就在这一列）。
但这个时期的鲁特琴已经**非常难弹、非常难做、非常贵**，
而键盘乐器的音量与和声能力都超过了它。

与此同时发生的是：**吉他（五组、后来六根单弦）在欧洲普及**，
复弦传统被单弦取代。到 18 世纪末，鲁特琴基本退出了舞台 ——
**它不是被更好的鲁特琴取代的，而是被更简单的吉他取代的。**

20 世纪它随"古乐运动"复活：制琴师按博物馆藏品复原，
演奏者重新研究指法与定弦。今天的鲁特琴是一个**小而专业的领域**，
但它留下的曲库（尤其文艺复兴的独奏曲）是拨弦乐器里最早成体系的一批。

## 常见误解

- **"鲁特琴的音域是 X。"** → 没有唯一的 X。弦数从 4 组到 13 组、
  定弦随调性变化，音域也跟着变。说音域必须带上"哪个时代、几组弦、什么调"。
- **"它和古典吉他差不多，只是老一点。"** → 三处结构差异：**复弦 vs 单弦**、
  **折角 vs 拱形背板**、**指腹 vs 指甲**。这三点决定了它音量更小、音色更透、动态更文静。
- **"折角背板是为了好看。"** → 是为了**做得更薄更轻**：窄板顺着木纹拼接，
  每块只承受顺纹的力。这是结构效率问题，不是装饰。
- **"定弦是固定的。"** → 文艺复兴鲁特琴的第 3 组弦在升 F 与还原 F 之间切换，
  巴洛克鲁特琴的定弦又不同。**乐器跟着调性走**是那个时代的常规。
- **"它被更好的乐器淘汰了。"** → 它是被**更简单、更响、更便宜**的吉他取代的。
  淘汰的原因常常是成本与易用性，不是艺术水平。
- **"鲁特琴音乐是民间音乐。"** → 恰恰相反。它留下的曲集多数是**宫廷与城市上层**的独奏曲，
  民间舞曲只是其中一部分体裁。

## 下一步

想继续走这条线：往前看 [[instrument:classical-guitar|古典吉他]]（复弦改成单弦之后的样子），
往旁边看 [[instrument:viol|维奥尔琴]]（同一时代、用弓、同样有品与堆叠背板传统），
往"复弦还活着"的方向看 [[instrument:mandolin|曼陀林]]。

至此西洋弦乐（I1）的核心四件 + 弹拨支系已完成 5 条。剩下的弦乐条目
（竖琴、维奥尔琴、班卓琴、桑图尔、钦巴龙）在下一批继续。
:::

::: en
The lute is the ancestor of the [[instrument:classical-guitar|guitar]] and **the most widely played solo
instrument in Renaissance and Baroque Europe**. It looks clearly different: **a pear-shaped body, a
ribbed back built from narrow staves, strings in doubled courses, and a neck that runs almost parallel
to the top plate**.

It also does something that looks strange today: **its tuning changes with the key**.

| Classification | Value |
|---|---|
| **HS class** | **Chordophone** — the vibrating body is the string itself |
| **Sub-type** | Plucked (fingertips/nails) · necked, with a box resonator, fretted |
| **Family** | Western · Strings (plucked branch) |
| **Bayin** | Not applicable — the eight categories are a Chinese system; the lute is outside it |

## Structure: a pear body and a ribbed back

```svg
<svg viewBox="0 0 640 484" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Renaissance lute parts: angled pegbox, six doubled courses, carved rose, bridge, pear-shaped body and the ribbed back">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">Renaissance lute — outer form and principal parts (six courses; neck nearly parallel to the top)</text>
  </g>
  <path d="M322,86 L338,86 L344,134 L320,134 Z" fill="#17171A" stroke="#343439" stroke-width="1.2"/>
  <g fill="#343439">
    <rect x="304" y="92" width="16" height="5" rx="1"/><rect x="340" y="92" width="16" height="5" rx="1"/>
    <rect x="304" y="104" width="16" height="5" rx="1"/><rect x="340" y="104" width="16" height="5" rx="1"/>
    <rect x="304" y="116" width="16" height="5" rx="1"/><rect x="340" y="116" width="16" height="5" rx="1"/>
  </g>
  <path d="M330,40 C316,40 306,30 310,18 C314,7 326,3 335,9 C343,15 342,27 332,30"
        fill="none" stroke="#A9A49B" stroke-width="2.4" stroke-linecap="round"/>
  <path d="M314,86 L332,86 L330,196 L318,196 Z" fill="#0E0E10"/>
  <g stroke="#343439" stroke-width=".9">
    <path d="M314,110 L332,110"/><path d="M314,134 L332,134"/><path d="M314,158 L332,158"/><path d="M316,182 L331,182"/>
  </g>
  <path d="M320,120 C322.8,121 330.3,121 336.5,126 C342.7,131 349.9,139 357.1,150 C364.3,161 371.9,175.5 379.8,192 C387.7,208.5 397.3,230 404.6,249 C411.8,268 422.1,286.5 423.1,306 C424.2,325.5 417.6,350.5 410.8,366 C403.9,381.5 393.2,390.8 381.9,399 C370.5,407.2 353,412 342.7,415.5 C332.4,419 323.8,419.2 320,420 M320,420 C316.2,419.2 307.6,419 297.3,415.5 C287,412 269.5,407.2 258.1,399 C246.8,390.8 236.1,381.5 229.2,366 C222.4,350.5 215.8,325.5 216.9,306 C217.9,286.5 228.2,268 235.4,249 C242.7,230 252.3,208.5 260.2,192 C268.1,175.5 275.7,161 282.9,150 C290.1,139 297.3,131 303.5,126 C309.7,121 317.2,121 320,120 Z"
        fill="#17171A" stroke="#343439" stroke-width="1.4"/>
  <g stroke="#9C7A3C" stroke-width="1.3" stroke-dasharray="3 3" fill="none" opacity=".9">
    <path d="M320,132 L320,412"/>
    <path d="M292,220 L320,300"/><path d="M348,220 L320,300"/>
  </g>
  <circle cx="320" cy="262" r="21" fill="#0E0E10" stroke="#343439" stroke-width="1.4"/>
  <g stroke="#A9A49B" stroke-width="1" opacity=".8">
    <circle cx="320" cy="262" r="13" fill="none"/>
    <circle cx="320" cy="262" r="6" fill="none"/>
    <path d="M320,241 L320,283"/><path d="M299,262 L341,262"/>
    <path d="M305,247 L335,277"/><path d="M335,247 L305,277"/>
  </g>
  <path d="M296,330 L344,330 L344,338 L296,338 Z" fill="#111113" stroke="#343439" stroke-width="1.1"/>
  <path d="M302,330 L338,330" stroke="#A9A49B" stroke-width="1.5"/>
  <g stroke="#C9A227" opacity=".85">
    <path d="M313,88 L313,332" stroke-width="1.1"/><path d="M316,88 L316,332" stroke-width="1.1"/>
    <path d="M318.5,88 L318.5,332" stroke-width="1"/><path d="M321.5,88 L321.5,332" stroke-width="1"/>
    <path d="M324,88 L324,332" stroke-width=".9"/><path d="M326,88 L326,332" stroke-width=".9"/>
    <path d="M328.5,88 L328.5,332" stroke-width=".85"/><path d="M330.5,88 L330.5,332" stroke-width=".85"/>
    <path d="M332.5,88 L332.5,332" stroke-width=".8"/><path d="M334.5,88 L334.5,332" stroke-width=".8"/>
    <path d="M336.5,88 L336.5,332" stroke-width=".8"/>
  </g>
  <g class="lead" stroke="#6E6A64" stroke-width=".9">
    <path d="M186,50 L302,54"/><path d="M186,98 L298,100"/>
    <path d="M186,150 L326,152"/><path d="M186,262 L292,262"/>
    <path d="M186,334 L290,334"/><path d="M186,376 L268,376"/>
    <path d="M186,404 L300,400"/>
  </g>
  <g font-family="system-ui,sans-serif" font-size="11" fill="#A9A49B">
    <text x="180" y="53" text-anchor="end">Angled pegbox (bent back)</text>
    <text x="180" y="101" text-anchor="end">Six pegs (in pairs)</text>
    <text x="180" y="153" text-anchor="end">Fingerboard (level with top)</text>
    <text x="180" y="265" text-anchor="end">Rose (carved, not a round hole)</text>
    <text x="180" y="337" text-anchor="end">Bridge (glued, not adjustable)</text>
    <text x="180" y="379" text-anchor="end">Width 330 mm</text>
    <text x="180" y="407" text-anchor="end" fill="#9C7A3C">Ribbed back (narrow staves)</text>
  </g>
  <text x="20" y="452" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">Neck and top lie almost in one plane — part of the lute's low-tension build,</text>
  <text x="20" y="468" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">and the reason the pegbox is bent back.</text>
</svg>
```

Four features, one by one:

1. **A pear-shaped body with no waist.** Nothing like the violin family's upper and lower bouts — this
   is closer to a teardrop: narrow at the top, widest in the lower middle, rounded at the bottom.
2. **A ribbed back.** The back is not one plate but **narrow staves joined edge to edge**, like a boat
   hull, so the cross-section is a polygon. Next section.
3. **A rose rather than a round soundhole.** A carved wooden rosette sits in the opening — decoration,
   and a slight control on airflow.
4. **A glued bridge.** It cannot be moved or raised as a guitar's can — intonation and action are fixed
   at construction, which is why lute players are so careful about temperature and humidity.

## The ribbed back: why joined staves beat one plate

```svg
<svg viewBox="0 0 640 300" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Cross-sections compared: a lute's ribbed back is a polygon of narrow staves, a guitar's back is a smooth arc">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">Cross-sections · how the back is built decides how light it can be</text>
  </g>
  <text x="20" y="60">Lute · ribbed back</text>
  <g stroke="#A9A49B" stroke-width="3.4" stroke-linecap="round">
    <path d="M110,100 L290,100"/>
  </g>
  <polyline points="110,100 138,148 168,178 200,190 232,178 262,148 290,100"
            fill="none" stroke="#9C7A3C" stroke-width="4.4" stroke-linejoin="round"/>
  <g stroke="#E8C547" stroke-width="1.4" fill="none">
    <circle cx="138" cy="148" r="3"/><circle cx="168" cy="178" r="3"/><circle cx="200" cy="190" r="3"/>
    <circle cx="232" cy="178" r="3"/><circle cx="262" cy="148" r="3"/>
  </g>
  <text x="200" y="216" text-anchor="middle" font-size="11" fill="#9C7A3C">Six narrow staves joined edge to edge (a polygon)</text>
  <text x="350" y="60">Guitar · arched back</text>
  <g stroke="#A9A49B" stroke-width="3.4" stroke-linecap="round">
    <path d="M350,100 L530,100"/>
  </g>
  <path d="M350,100 C378,168 420,192 440,192 C460,192 502,168 530,100"
        fill="none" stroke="#5B7FA8" stroke-width="4.4" stroke-linecap="round"/>
  <text x="440" y="216" text-anchor="middle" font-size="11" fill="#5B7FA8">One or two plates bent into a smooth arc</text>
  <g stroke="#6E6A64" stroke-width="1" stroke-dasharray="3 3">
    <path d="M200,240 L200,268"/><path d="M440,240 L440,268"/>
  </g>
  <text x="20" y="286" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">Ribs follow the grain — so the back can be far thinner and lighter: less volume, a clearer tone.</text>
</svg>
```

Wood is strong **along the grain**. To bend a single wide plate into an arch you must load it across
the grain, so it has to stay thick. The ribbed method joins **narrow staves that each run along the
grain** — every piece only carries load in the direction it is strong — so **the same strength comes
with far less thickness**.

The consequences chain together:

| Thinner back → | lighter body → | lower tension → smaller volume, clearer tone |
|---|---|---|

So the lute's lightness is not an accident; it follows from how the back is built. The same ribbed
construction appears on some members of the [[instrument:viol|viol]] family, and on Neapolitan
bowl-back [[instrument:mandolin|mandolins]].

## Range

```range
{"range":"G2–E5","common":"G2–G4","caption":"六组弦鲁特琴（G 调）的实音音域","caption_en":"Sounding range of a six-course lute in G","note":"鲁特琴的定弦随时代与调性变化 —— 尤其第 3 组弦（升 F 与还原 F 并存），所以不同文献给出的音域会有出入。这里给的是文艺复兴 6 组弦 G 调鲁特琴的常见范围。"}
```

**One thing must be said clearly**: the lute's range and tuning have **no single answer**. The
instrument spans three centuries, its courses grow from 4 to 13, and its tuning changes with the key.
Treating "the lute's range" as one fixed figure would be inaccurate.

What is well established is the most typical configuration — **Renaissance, six courses, in G**:

| Course | 6 | 5 | 4 | 3 | 2 | 1 |
|---|---|---|---|---|---|---|
| Note | G2 | C3 | F3 | A3 (or B♭3) | D4 | G4 |

The **third course's F3 is retuned to F♯** when the music requires it. You almost never see this on a
modern instrument — who retunes a string for one piece? — but in the lute's era it was routine:
**the instrument followed the key, rather than the key accommodating the instrument.**

## Timbre, and how to hear it

Four cues; the first three are the lute's own, the fourth is its most common misidentification:

1. **Small volume, fast decay, clean attack.** Gut strings, a thin plate and a light build produce
   "light and clear" rather than "big and thick".
2. **Fingertips, not nails or pick.** So there is neither a pick's clack nor a nail's click — more like
   a touch.
3. **The ripple of doubled courses.** Beating between unison pairs leaves a faint tremble, the same
   origin as the [[instrument:mandolin|mandolin]]'s, but lower and shorter — drier.
4. **It is often mistaken for a classical guitar.** The colours are close. The differences: a lute is
   finer on top, thinner at the bottom and quieter overall. If a recording has a bass with outline but
   no weight, it is probably a lute, not a guitar.

```audiolab
{"type":"instrument","gm":"Guitar Harmonics","synth":"plucked","phrase":["G2","C3","F3","D4","G4"],"label":"六组空弦（G 调）","label_en":"Six open courses, lute in G","hint":"低音只有轮廓、没有分量 —— 这是薄板加低张力的结果，不是录音问题","hint_en":"The bass has shape but no weight — the consequence of a thin plate and low tension, not a recording fault."}
```

> The General MIDI palette has **no lute**, so this borrows the closest plucked timbre; imagine the real
> thing as small, fast-decaying, with a fingertip attack. The tracks under “Listen in the library” are
> the **skeleton of the music** (transcription or engraving MIDI); timbre is handled by the player above.

## Playing techniques

The technique differs noticeably from the later guitar, mostly in the right hand:

- **Fingertips, thumb on the outside.** The thumb (p) takes the bass courses; the index and middle
  fingers (i, m) take the treble. The ring finger was rarely used in the early period — unlike the
  modern guitar's four-finger division.
- **Stroking towards the palm.** Some traditions require plucking inward rather than outward — softer,
  quieter.
- **The thumb walks the bass alone.** Lute textures typically combine a bass line, a treble line and
  filling in between, so an independent thumb is basic technique.
- **Little dynamic contrast.** A light structure cannot take forceful playing, so lute music relies on
  **changes of texture and harmony** rather than loud and soft.
- **Retuning before playing.** Unique to this instrument: some pieces require the third course retuned.

On the left hand: frets, close spacing and low tension make the touch very light — which is one reason
the 20th-century early-music movement studied lute technique so closely.

## The family

| Instrument | Body | Back | Strings | Sound | Period |
|---|---|---|---|---|---|
| **Lute** | pear | **ribbed (narrow staves)** | 6–13 doubled courses (gut) | fingertips | 15th–18th c. |
| [[instrument:viol\|Viol]] | waisted | ribbed or flat | 6 single (fretted) | bow | 15th–17th c. |
| [[instrument:classical-guitar\|Classical guitar]] | waisted | arched (single plate) | 6 single (nylon) | nails | 19th c.–now |
| [[instrument:mandolin\|Mandolin]] | pear/bowl | ribbed (Neapolitan) | 4 doubled courses (steel) | pick | 18th c.–now |

The table traces one line: **doubled courses, a ribbed back and fingertip plucking** are shared traits
of the early plucked instruments; **single strings, an arched back and a pick-or-nail attack** are the
later direction. The guitar and the mandolin each kept half — the mandolin kept courses, the guitar
kept everything except the courses.

## History

The lute came into Europe from the Arab **oud**, roughly in the **late Middle Ages**, via Spain and
Sicily. It was not originally a solo instrument but an accompaniment and ensemble one.

The 16th century was its first golden age: **six courses tuned in G** settled down, and across Europe
**manuscript collections** appeared (in tablature), including the Jane Pickering lute book used as an
example on this page. By then it was a **solo** instrument.

In the 17th century the course count kept rising — 7, 8, 10 — with the extra strings on the bass side
to play continuo. **Tuning changed too**: French and German lutes were tuned differently.

The 18th century brought both its last peak and its end: the **Baroque lute** with **13 courses**, with
music written for it by Falckenhagen, Weiss and others (Falckenhagen is in the listening list here).
But by then it was **very hard to play, very hard to make and very expensive**, and keyboard
instruments surpassed it in both volume and harmonic reach.

Meanwhile the **guitar** (five courses, then six single strings) spread across Europe, and single
strings replaced courses. By the end of the 18th century the lute had left the stage — **not displaced
by a better lute, but by a simpler guitar.**

The 20th century revived it with the early-music movement: makers rebuilt instruments from museum
collections and players re-studied tunings and technique. Today the lute is a **small, specialist
field** — but the repertoire it left, especially Renaissance solo music, is the earliest systematic
body of plucked-instrument music there is.

## Common misconceptions

- **"The lute's range is X."** There is no single X. Courses run from 4 to 13 and tuning follows the
  key, so the range moves with them. Any figure needs "which century, how many courses, what key".
- **"It is roughly a classical guitar, only older."** Three structural differences: **courses versus
  single strings**, **a ribbed versus an arched back**, **fingertips versus nails**. Together they make
  it quieter, clearer and more restrained.
- **"The ribbed back is decorative."** It is there to make the back **thinner and lighter**: narrow
  staves running with the grain each carry load only along the grain. Structural efficiency, not
  ornament.
- **"The tuning is fixed."** A Renaissance lute's third course switches between F♯ and F, and Baroque
  lute tunings differ again. **The instrument following the key** was normal practice then.
- **"It was superseded by something better."** It was superseded by something **simpler, louder and
  cheaper**. Instruments usually lose out on cost and convenience, not artistic merit.
- **"Lute music is folk music."** Quite the opposite. Most surviving collections are **courtly and
  urban solo music**; folk dance is only one of its genres.

## Next

To follow this line: forward to the [[instrument:classical-guitar|classical guitar]] (what happened
after courses became single strings), sideways to the [[instrument:viol|viol]] (same era, bowed, with
the same fretted and staved-back tradition), and to where courses still live — the
[[instrument:mandolin|mandolin]].

This completes the core four Western bowed strings plus five plucked entries (I1). The remaining
string entries — harp, viol, banjo, santur and cimbalom — follow in the next batch.
:::
