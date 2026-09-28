---
id: harmonium
site: inst
cat: I5
title: 簧风琴
title_en: Harmonium
summary: 脚踏风箱驱动自由簧的键盘乐器，与管风琴同属气鸣但发声体不同
summary_en: A keyboard instrument whose foot bellows drives free reeds — an aerophone with a different vibrating body from the organ
level: standard
tags: [乐器, 键盘, 西洋, 世界]
tags_en: [instrument, keyboard, western, world]
alias: [簧风琴, harmonium, 脚踏风琴, 风琴（脚踏）, 印度风琴]
order: 83
links:
  - "[[concept:interval]]"
  - "[[concept:register]]"
  - "[[concept:timbre]]"
  - "[[concept:articulation]]"
  - "[[instrument:organ]]"
  - "[[instrument:accordion]]"
  - "[[instrument:harmonica]]"
  - "[[instrument:piano]]"
instances:
  - pdmx-000322 | 鲁特琴与竖笛的协奏曲 —— 巴洛克室内乐编制，可对照"持续音键盘乐器"在合奏里的角色
  - pdmx-001402 | G 大调竖笛奏鸣曲 —— 独奏乐器 + 键盘的编制，簧风琴在 19 世纪常担此职
  - pdmx-000062 | 管乐五重奏（长笛 · 双簧管 · 单簧管 · 圆号 · 巴松）—— 无键盘的编制，可作对照
sources:
  - 结构依通行制琴资料：**脚踏风箱**供气，气流通过**自由簧（free reed）**发声；键盘控制进气，另有音栓（stops）改变音色与音量
  - 「簧风琴属**气鸣**乐器 —— 气流使自由簧振动，管式共鸣体辅助放大」依 Hornbostel–Sachs 分类
  - 「**自由簧**指簧片在一个略大的框内自由振动，频率主要由簧片本身决定；这与木管的**拍簧**（簧片互相拍打）是两种不同机制」依管乐器声学
  - 「常见音域 C2–C6」依通行乐器资料
  - 「19 世纪在欧洲的家庭、小教堂与学校广泛使用；在印度成为常用乐器」依乐器史
updated: 2026-09-26
---

::: zh
簧风琴是"管风琴的小型替代品"：**它用脚踏风箱供气，靠自由簧发声。**
它与[[instrument:organ|管风琴]]同属**气鸣**（都是气流驱动），
但**发声体不同**：一个是音管里的**空气柱**，一个是**簧片本身**。

这条差别带来了一整套不同的乐器（簧风琴 · 手风琴 · 口琴）。

| 分类 | 归属 |
|---|---|
| **HS 分类** | **气鸣**（Aerophone）—— 气流使**自由簧**振动 |
| **次级类型** | **脚踏风箱**供气 · 键盘控制进气 · 自由簧发声 · 音栓改变音色 |
| **所属族** | 西洋 · 键盘（自由簧支系）· 同时是**世界乐器**（在印度尤为常见） |
| **八音** | 不适用 —— 周代八音是中国乐器的体系，簧风琴不在其中 |

> ⚠️ **一个概念上的要点**：**"自由簧"与木管的"拍簧"是两种不同的发声机制。**
> - **自由簧**（free reed）：簧片装在一个**略大于它**的框里，
>   振动时**不碰到框**，频率**主要由簧片本身的刚度与质量决定**。
>   → 簧风琴 · 手风琴 · 口琴 · 笙（中国的笙是自由簧的早期实例）。
> - **拍簧**（beating reed）：簧片**拍打**一个开口或互相拍打。
>   → [[instrument:clarinet|单簧管]]（单片拍簧）· [[instrument:oboe|双簧管]]（双片互拍）。
>
> **两种机制都叫"簧"，但自由度完全不同** —— 自由簧的频率由簧片自身定，
> 拍簧的频率则与管长耦合。这也是为什么自由簧乐器**不需要不同长度的管**来定音高：
> **一片小簧就能发出很低的音**（口琴就是最好的证明）。

## 结构：脚踏风箱 + 自由簧 + 键盘

```svg
<svg viewBox="0 0 640 320" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="簧风琴的结构：脚踏风箱供气、气流经键盘控制进入自由簧、音栓改变音色">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">簧风琴 · 结构（脚踏送气 → 自由簧发声）</text>
  </g>
  <rect x="70" y="86" width="260" height="34" rx="4" fill="#17171A" stroke="#343439" stroke-width="1.4"/>
  <g stroke="#6E6A64" stroke-width="1.2">
    <path d="M86,86 L86,120"/><path d="M104,86 L104,120"/><path d="M122,86 L122,120"/>
    <path d="M140,86 L140,120"/><path d="M158,86 L158,120"/><path d="M176,86 L176,120"/>
    <path d="M194,86 L194,120"/><path d="M212,86 L212,120"/><path d="M230,86 L230,120"/>
    <path d="M248,86 L248,120"/><path d="M266,86 L266,120"/><path d="M284,86 L284,120"/>
  </g>
  <rect x="70" y="146" width="260" height="46" rx="4" fill="#17171A" stroke="#5B7FA8" stroke-width="1.6"/>
  <g stroke="#5B7FA8" stroke-width="2.4">
    <rect x="96" y="158" width="9" height="22" rx="3"/>
    <rect x="130" y="158" width="9" height="22" rx="3"/>
    <rect x="164" y="158" width="9" height="22" rx="3"/>
    <rect x="198" y="158" width="9" height="22" rx="3"/>
    <rect x="232" y="158" width="9" height="22" rx="3"/>
    <rect x="266" y="158" width="9" height="22" rx="3"/>
    <rect x="300" y="158" width="9" height="22" rx="3"/>
  </g>
  <path d="M70,224 L330,224" stroke="#343439" stroke-width="2.6"/>
  <path d="M110,246 C130,232 150,232 170,246" fill="none" stroke="#E07A3F" stroke-width="3"/>
  <path d="M230,246 C250,232 270,232 290,246" fill="none" stroke="#E07A3F" stroke-width="3"/>
  <rect x="160" y="252" width="80" height="30" rx="4" fill="#17171A" stroke="#E07A3F" stroke-width="1.6"/>
  <g class="lead" stroke="#6E6A64" stroke-width=".9">
    <path d="M186,70 L186,80"/><path d="M186,140 L186,132"/>
    <path d="M186,204 L186,218"/><path d="M186,300 L186,284"/>
    <path d="M486,124 L360,150"/><path d="M486,246 L346,246"/>
  </g>
  <g font-family="system-ui,sans-serif" font-size="11" fill="#A9A49B">
    <text x="180" y="67" text-anchor="end">键盘（控制进气）</text>
    <text x="180" y="143" text-anchor="end" fill="#5B7FA8">自由簧（发声体）</text>
    <text x="180" y="207" text-anchor="end">音栓（改变音色与音量）</text>
    <text x="180" y="303" text-anchor="end" fill="#E07A3F">脚踏风箱（自己供气）</text>
    <text x="492" y="121">自由簧振动时碰到框 →</text>
    <text x="492" y="141">频率由簧片自身决定</text>
    <text x="492" y="249" fill="#E07A3F">送气量由脚控制</text>
  </g>
  <text x="20" y="292" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">自由簧不需要不同长度的管来定音高 —— 所以一台簧风琴可以做得比管风琴小得多，音量却不小。</text>
</svg>
```

三处要点：

1. **自由簧是发声体**。气流使它在一个略大的框里自由振动，
   **频率由簧片本身的刚度与质量决定** —— 与管长无关。
2. **脚踏风箱使演奏者自己供气**。所以送气的多少由脚控制，
   这也是簧风琴与[[instrument:organ|管风琴]]（由机械鼓风）的一个实际差别。
3. **音栓仍然存在**（改变音色与音量），但功能与管风琴的音栓不同 ——
   管风琴换的是"哪一组音管"，簧风琴换的是"哪一组簧与共鸣箱"。

## 它与管风琴的关系

```svg
<svg viewBox="0 0 640 280" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="管风琴与簧风琴的对照：同为气鸣、由气流驱动，但发声体分别是空气柱与自由簧">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">同是"气流 + 键盘"，发声体不同</text>
  </g>
  <rect x="50" y="56" width="240" height="150" rx="6" fill="#17171A" stroke="#5B7FA8" stroke-width="1.6"/>
  <text x="170" y="82" text-anchor="middle" font-size="11" fill="#5B7FA8">管风琴</text>
  <rect x="120" y="98" width="18" height="66" rx="8" fill="#0E0E10" stroke="#5B7FA8" stroke-width="1.4"/>
  <rect x="150" y="108" width="18" height="56" rx="8" fill="#0E0E10" stroke="#5B7FA8" stroke-width="1.4"/>
  <rect x="180" y="116" width="18" height="48" rx="8" fill="#0E0E10" stroke="#5B7FA8" stroke-width="1.4"/>
  <text x="170" y="184" text-anchor="middle" font-size="10.5" fill="#A9A49B">发声体：管内的空气柱</text>
  <text x="170" y="204" text-anchor="middle" font-size="10.5" fill="#5B7FA8">音高由管长决定</text>
  <rect x="350" y="56" width="240" height="150" rx="6" fill="#17171A" stroke="#E07A3F" stroke-width="1.6"/>
  <text x="470" y="82" text-anchor="middle" font-size="11" fill="#E07A3F">簧风琴</text>
  <g stroke="#E07A3F" stroke-width="2.6">
    <rect x="424" y="104" width="8" height="26" rx="3"/>
    <rect x="448" y="104" width="8" height="26" rx="3"/>
    <rect x="472" y="104" width="8" height="26" rx="3"/>
    <rect x="496" y="104" width="8" height="26" rx="3"/>
  </g>
  <path d="M412,146 L516,146" stroke="#E07A3F" stroke-width="2"/>
  <text x="470" y="184" text-anchor="middle" font-size="10.5" fill="#A9A49B">发声体：自由簧</text>
  <text x="470" y="204" text-anchor="middle" font-size="10.5" fill="#E07A3F">音高由簧片本身决定</text>
  <text x="20" y="240" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">两者的差别不只是"大小"：管风琴要靠几米长的管才能发出低频，簧风琴一片小簧就够了。</text>
  <text x="20" y="262" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">所以「自由簧是把"低音"从"体积"里解放出来的一项技术」 —— 也正是口琴能塞进口袋的原因。</text>
</svg>
```

**"自由簧把低音从体积里解放出来"** 是这一族乐器共同的技术意义：
[[instrument:organ|管风琴]]要靠几米长的音管才能发出低频，
而自由簧乐器用一片小簧就能做到 —— 于是键盘乐器第一次可以被搬动。

## 音域

```range
{"range":"C2–C6","common":"C2–C5","caption":"簧风琴的音域","caption_en":"Harmonium range","note":"簧风琴属气鸣乐器（自由簧）。常见音域约 C2–C6，视乐器而定；常用区 C2–C5。它与管风琴音区相近，但体积小得多。"}
```

- **约 C2–C6**（视乐器），与[[instrument:organ|管风琴]]音区相近，但体积小得多。
- **常用区 C2–C5**：它的音乐多为伴奏、和声与宗教音乐，所以低中音区最重要。
- **它没有管风琴那样的超低音**（32 英尺管）—— 自由簧的低音有物理上限。

## 音色与听辨

四条线索：

1. **温暖、略带"簧"的颤动**。它不像管风琴那样"纯"，有一种持续音里的轻微起伏 ——
   这是自由簧的特征。
2. **音可无限持续**（与管风琴一样，气流不停音就不停）。
3. **力度可以靠脚踏控制**（但幅度有限）。这一点与管风琴不同 ——
   管风琴的送气由机械完成，簧风琴由演奏者的脚控制，所以**能做出一些强弱的呼吸感**。
4. **音色随音栓变化，但不如管风琴丰富**。它的表现力主要靠**和声与持续**。

```audiolab
{"type":"instrument","gm":"Reed Organ","synth":"blown","phrase":["C3","E3","G3","C4","E4","G4"],"label":"簧风琴的常用区：C3 到 G4","label_en":"The harmonium's working register — C3 up to G4","hint":"注意音色里那点持续的「簧」的颤动 —— 这是自由簧与音管的区别","hint_en":"Hear the slight reedy tremble under the sustained tone — free reed versus air column."}
```

## 演奏技法

- **脚踏风箱是技术核心**。脚的力度与均匀度直接决定声音的稳定与呼吸感。
- **双手弹键盘**，另有音栓供切换。
- **常作为伴奏与和声乐器**：为独唱、合唱或独奏乐器伴奏（尤其在小教堂与家庭里）。
- **印度用法不同**：在印度，簧风琴成为**声乐伴奏**的常用乐器
  （演奏者常用右手弹旋律、左手控制风箱或做持续音），并发展出独特的演奏风格。

## 家族与近亲

| 乐器 | 发声体 | 送气方式 | 音域 | 用途 |
|---|---|---|---|---|
| [[instrument:organ\|管风琴]] | **空气柱** | 机械鼓风 | C2–C7 | 教堂与音乐厅 |
| **簧风琴** | **自由簧** | **脚踏** | C2–C6 | 家庭、小教堂、伴奏 |
| [[instrument:accordion\|手风琴]] | **自由簧** | **手动风箱** | F3–A6 | 独奏、民间音乐 |
| [[instrument:harmonica\|口琴]] | **自由簧** | **嘴吹吸** | C4–C7 | 独奏、民间、蓝调 |

**后三行是"自由簧三件"**，它们的差别在**送气方式**：
**脚踏（簧风琴）· 手动（手风琴）· 口吹（口琴）** ——
同一原理的三种操作方案。

## 历史演变

| 时期 | 状态 |
|---|---|
| 19 世纪初 | 欧洲出现脚踏风箱 + 自由簧的键盘乐器；很快在家庭与小教堂普及（管风琴太贵太大） |
| 19 世纪中期 | 形制定型；成为**家庭音乐与教会音乐的常见乐器**；也是学校与传教的常用工具 |
| 19 世纪后期 | 随传教与殖民传播到印度、东亚等地；**在印度扎根并成为主流伴奏乐器** |
| 20 世纪 | 在西方被钢琴与电子乐器取代；**在印度仍是常用乐器** |
| 20 世纪后期至今 | 西方作为复古与民谣乐器使用；印度与南亚继续广泛使用 |

**它是"传播后在新地方生根"的典型案例**：
在欧洲退场，在印度成为常用乐器 ——
**同一件乐器在不同文化里的命运可以完全相反。**

## 常见误解

- **"簧风琴就是小管风琴。"** 同属**气鸣**，但**发声体不同**：
  管风琴是空气柱（音高由管长定），簧风琴是自由簧（音高由簧片定）。
- **"自由簧与木管的簧片是一回事。"** 机制不同：自由簧在框里自由振动；
  木管的簧片是**拍簧**（拍打开口或互相拍打）。
- **"它没有力度控制。"** 它**有一点**：脚踏送气量会影响音量与音色，
  这是它与[[instrument:organ|管风琴]]的一个实际差别。
- **"它在今天已经消失。"** 在西方确实少见，但在**印度与南亚仍是常用乐器**，
  且西方民谣与古乐领域也有人使用。
- **"管风琴音栓与簧风琴音栓是一回事。"** 功能相似（选择音色），
  但对象不同：一个换"哪组音管"，一个换"哪组簧与共鸣箱"。

## 下一步

自由簧一族还剩 2 条：[[instrument:accordion|手风琴]]（手动风箱）与
[[instrument:harmonica|口琴]]（嘴吹吸）。
三件一起看，"**同一个原理、三种送气方式**"这条线就完整了。
:::

::: en
The harmonium is the [[instrument:organ|organ]]'s small substitute: **foot bellows supply the air, and free
reeds sound.** It shares the organ's **aerophone** class — both are air-driven — but the **vibrating body
differs**: air columns in pipes versus **the reed itself**.

That one difference produces a whole family of instruments (harmonium, accordion, harmonica).

| Classification | Value |
|---|---|
| **HS class** | **Aerophone** — the air sets **free reeds** vibrating |
| **Sub-type** | **Foot bellows** supply air · keys admit it · free reeds sound · stops change colour |
| **Family** | Western · Keyboard (free-reed branch) · also a **world instrument** (especially common in India) |
| **Bayin** | Not applicable — a Chinese system; the harmonium is outside it |

> ⚠️ **One conceptual point**: **a "free reed" and a woodwind's "beating reed" are two different
> mechanisms.**
> - **Free reed**: the reed sits in a frame **slightly larger** than itself and vibrates **without touching**
>   it; the frequency is **set mainly by the reed's own stiffness and mass**.
>   → harmonium · accordion · harmonica · the Chinese *sheng* (an early free-reed instance).
> - **Beating reed**: the reed **strikes** an opening or another reed.
>   → [[instrument:clarinet|clarinet]] (single, beating) · [[instrument:oboe|oboe]] (two, striking each other).
>
> **Both are called "reeds", but their freedom differs completely** — a free reed's pitch comes from the reed
> itself, whereas a beating reed's is coupled to the tube length. Which is why free-reed instruments **need no
> pipes of different lengths to set pitch**: **one small reed can sound very low** — the harmonica proves it.

## Structure: foot bellows, free reeds, keyboard

```svg
<svg viewBox="0 0 640 320" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Harmonium structure: foot bellows supply air, keys admit it to free reeds, and stops change the colour">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">Harmonium — structure (foot air supply → free reeds)</text>
  </g>
  <rect x="70" y="86" width="260" height="34" rx="4" fill="#17171A" stroke="#343439" stroke-width="1.4"/>
  <g stroke="#6E6A64" stroke-width="1.2">
    <path d="M86,86 L86,120"/><path d="M104,86 L104,120"/><path d="M122,86 L122,120"/>
    <path d="M140,86 L140,120"/><path d="M158,86 L158,120"/><path d="M176,86 L176,120"/>
    <path d="M194,86 L194,120"/><path d="M212,86 L212,120"/><path d="M230,86 L230,120"/>
    <path d="M248,86 L248,120"/><path d="M266,86 L266,120"/><path d="M284,86 L284,120"/>
  </g>
  <rect x="70" y="146" width="260" height="46" rx="4" fill="#17171A" stroke="#5B7FA8" stroke-width="1.6"/>
  <g stroke="#5B7FA8" stroke-width="2.4">
    <rect x="96" y="158" width="9" height="22" rx="3"/>
    <rect x="130" y="158" width="9" height="22" rx="3"/>
    <rect x="164" y="158" width="9" height="22" rx="3"/>
    <rect x="198" y="158" width="9" height="22" rx="3"/>
    <rect x="232" y="158" width="9" height="22" rx="3"/>
    <rect x="266" y="158" width="9" height="22" rx="3"/>
    <rect x="300" y="158" width="9" height="22" rx="3"/>
  </g>
  <path d="M70,224 L330,224" stroke="#343439" stroke-width="2.6"/>
  <path d="M110,246 C130,232 150,232 170,246" fill="none" stroke="#E07A3F" stroke-width="3"/>
  <path d="M230,246 C250,232 270,232 290,246" fill="none" stroke="#E07A3F" stroke-width="3"/>
  <rect x="160" y="252" width="80" height="30" rx="4" fill="#17171A" stroke="#E07A3F" stroke-width="1.6"/>
  <g class="lead" stroke="#6E6A64" stroke-width=".9">
    <path d="M186,70 L186,80"/><path d="M186,140 L186,132"/>
    <path d="M186,204 L186,218"/><path d="M186,300 L186,284"/>
    <path d="M486,124 L360,150"/><path d="M486,246 L346,246"/>
  </g>
  <g font-family="system-ui,sans-serif" font-size="11" fill="#A9A49B">
    <text x="180" y="67" text-anchor="end">Keys (admit the air)</text>
    <text x="180" y="143" text-anchor="end" fill="#5B7FA8">Free reeds (the source)</text>
    <text x="180" y="207" text-anchor="end">Stops (colour and volume)</text>
    <text x="180" y="303" text-anchor="end" fill="#E07A3F">Foot bellows</text>
    <text x="492" y="121">The reed vibrates without</text>
    <text x="492" y="141">touching its frame</text>
    <text x="492" y="249" fill="#E07A3F">Air is metered by the foot</text>
  </g>
  <text x="20" y="292" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">Free reeds need no pipes of different lengths, so a harmonium can be far smaller than an organ — and still loud.</text>
</svg>
```

Three points:

1. **The free reed is the source.** Air makes it vibrate without touching its frame, and **pitch is set by the
   reed's own stiffness and mass** — independent of any tube.
2. **Foot bellows mean the player supplies the air**, so how much is sent is controlled by the foot. A practical
   difference from the [[instrument:organ|organ]], whose air comes from a blower.
3. **Stops still exist** (changing colour and volume), but unlike the organ's they select **sets of reeds and
   resonators** rather than ranks of pipes.

## Its relation to the organ

```svg
<svg viewBox="0 0 640 280" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Organ and harmonium compared: both aerophones driven by air, but their vibrating bodies are an air column and a free reed">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">Both are "air plus keyboard" — the vibrating body differs</text>
  </g>
  <rect x="50" y="56" width="240" height="150" rx="6" fill="#17171A" stroke="#5B7FA8" stroke-width="1.6"/>
  <text x="170" y="82" text-anchor="middle" font-size="11" fill="#5B7FA8">Organ</text>
  <rect x="120" y="98" width="18" height="66" rx="8" fill="#0E0E10" stroke="#5B7FA8" stroke-width="1.4"/>
  <rect x="150" y="108" width="18" height="56" rx="8" fill="#0E0E10" stroke="#5B7FA8" stroke-width="1.4"/>
  <rect x="180" y="116" width="18" height="48" rx="8" fill="#0E0E10" stroke="#5B7FA8" stroke-width="1.4"/>
  <text x="170" y="184" text-anchor="middle" font-size="10.5" fill="#A9A49B">source: air column in a pipe</text>
  <text x="170" y="204" text-anchor="middle" font-size="10.5" fill="#5B7FA8">pitch set by pipe length</text>
  <rect x="350" y="56" width="240" height="150" rx="6" fill="#17171A" stroke="#E07A3F" stroke-width="1.6"/>
  <text x="470" y="82" text-anchor="middle" font-size="11" fill="#E07A3F">Harmonium</text>
  <g stroke="#E07A3F" stroke-width="2.6">
    <rect x="424" y="104" width="8" height="26" rx="3"/>
    <rect x="448" y="104" width="8" height="26" rx="3"/>
    <rect x="472" y="104" width="8" height="26" rx="3"/>
    <rect x="496" y="104" width="8" height="26" rx="3"/>
  </g>
  <path d="M412,146 L516,146" stroke="#E07A3F" stroke-width="2"/>
  <text x="470" y="184" text-anchor="middle" font-size="10.5" fill="#A9A49B">source: free reed</text>
  <text x="470" y="204" text-anchor="middle" font-size="10.5" fill="#E07A3F">pitch set by the reed itself</text>
  <text x="20" y="240" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">The difference is not just size: an organ needs metres of pipe for low notes; a harmonium needs one small reed.</text>
  <text x="20" y="262" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">「The free reed freed low pitch from bulk」 — and that is why a harmonica fits in a pocket.</text>
</svg>
```

**"The free reed freed low pitch from bulk"** is the shared technical significance of this family: an
[[instrument:organ|organ]] needs metres of pipe to sound low, while a free-reed instrument needs one small
reed — and keyboards became portable for the first time.

## Range

```range
{"range":"C2–C6","common":"C2–C5","caption":"簧风琴的音域","caption_en":"Harmonium range","note":"簧风琴属气鸣乐器（自由簧）。常见音域约 C2–C6，视乐器而定；常用区 C2–C5。它与管风琴音区相近，但体积小得多。"}
```

- **About C2–C6** depending on the instrument — close to an [[instrument:organ|organ]]'s register, at a
  fraction of the size.
- **The working register is C2–C5**: its music is mostly accompaniment, harmony and church music, so the low
  middle matters most.
- **It has no organ-like sub-bass** (32-foot pipes) — free reeds have a physical lower limit.

## Timbre, and how to hear it

Four cues:

1. **Warm, with a slight reedy tremble.** Less "pure" than an organ — a slight movement inside the sustained
   tone, characteristic of free reeds.
2. **Unlimited sustain** (as with the organ: as long as air flows, the note holds).
3. **Some dynamic control via the feet**, though limited. Unlike the organ, whose air comes from a blower, the
   harmonium's air is metered by the player's foot, allowing a little breathing.
4. **Colour varies with the stops, but less widely than an organ's.** Its expression lies in **harmony and
   sustain**.

```audiolab
{"type":"instrument","gm":"Reed Organ","synth":"blown","phrase":["C3","E3","G3","C4","E4","G4"],"label":"簧风琴的常用区：C3 到 G4","label_en":"The harmonium's working register — C3 up to G4","hint":"注意音色里那点持续的「簧」的颤动 —— 这是自由簧与音管的区别","hint_en":"Hear the slight reedy tremble under the sustained tone — free reed versus air column."}
```

## Playing techniques

- **The foot bellows are the core technique**: foot pressure and evenness decide the stability and breath of
  the sound.
- **Both hands on the keyboard**, with stops for changes.
- **Usually an accompanying and harmonic instrument**: for solo voice, choir or solo instruments (especially in
  small churches and homes).
- **Indian practice differs**: there the harmonium became a standard **vocal accompanist** (the right hand often
  plays the melody while the left works the bellows or holds a drone), developing its own performance style.

## The family

| Instrument | Vibrating body | Air supplied by | Range | Use |
|---|---|---|---|---|
| [[instrument:organ\|Organ]] | **air columns** | mechanical blower | C2–C7 | church and hall |
| **Harmonium** | **free reeds** | **foot** | C2–C6 | home, chapel, accompaniment |
| [[instrument:accordion\|Accordion]] | **free reeds** | **hand bellows** | F3–A6 | solo, folk music |
| [[instrument:harmonica\|Harmonica]] | **free reeds** | **breath** | C4–C7 | solo, folk, blues |

**The last three are the "free-reed trio"**, distinguished by **how the air is supplied**:
**foot (harmonium) · hand (accordion) · breath (harmonica)** — one principle, three solutions.

## History

| Period | State |
|---|---|
| Early 19th c. | foot-bellows free-reed keyboards appear in Europe and spread quickly in homes and chapels (organs were too costly and large) |
| Mid-19th c. | forms settle; it becomes a **common household and church instrument**, and a standard tool for schools and missions |
| Later 19th c. | travels with missions and colonisation to India, East Asia and beyond; **takes root in India and becomes a mainstream accompanying instrument** |
| 20th c. | displaced in the West by the piano and electronic instruments; **still common in India** |
| Late 20th c. onward | used in the West for revival and folk music; widely played in India and South Asia |

**It is a textbook case of "transplanted and taking root"**: it left the European stage and became an everyday
instrument in India — **the same instrument can have opposite fates in different cultures.**

## Common misconceptions

- **"A harmonium is a small organ."** Both are **aerophones**, but **the vibrating body differs**: an organ's
  is an air column (pitch by pipe length), a harmonium's a free reed (pitch by the reed).
- **"Free reeds and woodwind reeds are the same thing."** The mechanisms differ: a free reed vibrates inside its
  frame without touching it; a woodwind reed is a **beating reed** (striking an opening or another reed).
- **"It has no dynamic control."** It has **some**: the foot's air supply affects volume and colour, a practical
  difference from the [[instrument:organ|organ]].
- **"It has disappeared."** Rare in the West, but **still a standard instrument in India and South Asia**, and
  used in Western folk and early-music circles.
- **"Organ stops and harmonium stops are the same."** Similar in purpose (selecting colour), but their objects
  differ: one chooses pipe ranks, the other reed and resonator sets.

## Next

Two free-reed entries remain: the [[instrument:accordion|accordion]] (hand bellows) and the
[[instrument:harmonica|harmonica]] (breath). Read together, the line "**one principle, three ways of supplying
air**" is complete.
:::
