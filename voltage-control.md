---
id: voltage-control
site: inst
cat: I11
title: 电压控制原理
title_en: Voltage control
summary: 任何模块的输出都能控制任何模块 —— 合成器的第一性原理
summary_en: The output of any module can control any other — the first principle of the synthesizer
level: standard
tags: [乐器, 电子, 电鸣, 西洋, 模拟合成器, 电压控制, VCO, VCF, VCA, ADSR]
tags_en: [instrument, electronic, electrophone, western, analog-synth, voltage-control, vco, vcf, vca, adsr]
alias: [电压控制原理, voltage-control, 压控, CV, 电压控制, 模块化原理]
order: 170
links:
  - "[[instrument:theremin]]"
  - "[[instrument:hammond-organ]]"
  - "[[instrument:electric-guitar]]"
  - "[[instrument:ondes-martenot]]"
  - "[[concept:harmonic-series]]"
  - "[[concept:pitch]]"
instances:
  - chinafolk-001310 | 《有针无线真难寻》 —— ⭐⭐「有针无线」：模块化合成器**没有接线就发不出声**——「**模块只是盒子，默认没有任何连接；必须先 patch（接线），合成器才能发声**」——**有针（旋钮/振荡器）无线（patch 线），真难寻一个音**（**C3 · 仅限学习研究**；库内无合成器录音，取民歌作意象参照）
  - chinafolk-001286 | 《纺线歌》 —— ⭐「纺线」：**把模块「纺」在一起的那些线，就是合成器的乐器本身**——「**你把 patch 从合成器上拔掉，剩下的就是一块白布**」（**C3 · 仅限学习研究**）
  - chinafolk-001865 | 《千祈莫拆针离线》 —— ⭐⭐「千祈莫拆」：Doors 键盘手 **Ray Manzarek**「无法把之前喜欢的效果与配置原样复原——**完美的声音永远无法一模一样地复现**」——**「模拟合成的美与挫败」**（**C3 · 仅限学习研究**）
sources:
  - ⭐⭐ **主线：任何模块的输出都能控制任何模块（本页最该记住的一条）** —— 「**电压控制方法允许任何模块的输出被接线到任何其他模块的输入——一个极其强大且通用的系统**」；⭐⭐ **由 Bob Moog 与 Don Buchla 于 1960 年代初各自独立发展**——「这一技术由『模拟合成器之父』Robert Moog 变成现实，造出 60 年代**第一台商业化合成器**」；⭐⭐ **「真正的合成器」自 1960 年代起实现两大原则：减法合成 + 电压控制**——「Ondes Martenot · Mellotron · Hammond 音色相对有限，**通常不被认为是 synthesizer**」（⭐ **本站前面写的电子乐器「是不是合成器」的判据，就在这里**）
  - ⭐⭐ **VCO（压控振荡器）：1V/octave** —— 「**电压升高 1 伏 = 音高升高一个八度**」；「**电压突变 → 音高突变；电压平滑连续变化 → 滑音（portamento）**」；⭐⭐ **「Moog 从一开始就与音乐家合作，所以他的振荡器内建了指数转换器——线性键盘电压进来，振荡器频率每伏倍增」**；⭐⭐ **「CV 不是绝对参数而是相对参数」——「某个 CV 值（如 +1.0V）不对应任何绝对音高」**：VCO 的最终音高 = 外部 CV + 调音旋钮 + 八度开关 + 其他 CV 输入的**总和**
  - ⭐⭐ **VCF（压控滤波器）与 VCA（压控放大器）** —— 「VCF 被**电压控制**的参数是**截止频率**：控制电压的量改变截止频率，从而改变 VCF 让通过的信号频率范围」；「VCA 的**增益**可被电压控制」；⭐⭐ **减法合成的经典信号链**：「**振荡器产生富谐波的波形 → 滤波器选择性地移除谐波 → 放大器塑造每个音的动态（包络）**」——⭐ **「从富波形里做减法」，与加法合成（Telharmonium/Hammond）正好相反**
  - ⭐⭐ **ADSR 包络发生器** —— 「由触发或门信号激活后，产生一个**从（通常）零伏升到最大电压、再在某段时间后回到零伏**的信号」；「最常用于控制 VCA——**塑造一个音的动态（并保证它最终会停止！）**；也能控制 VCF 产生音色变化」；⭐⭐ **四个阶段**：「**Attack（起音）· Decay（衰减）· Sustain（延持）· Release（释音）——从按键、到抬指、以及之间的全部**」；**GATE 信号**：「对应键盘上按下一颗键——**A-100 内通常高于约 +3V 视为『高』（+5V/+8V/+12V 都行），低于 1V 视为『低』**」
  - ⭐⭐ **LFO（低频振荡器）：不发声的振荡器** —— 「设计为在**极低频率**（从最低可听频约 20 Hz 到远低于 1 Hz）产生精确波形」；⭐⭐ **一个 LFO 三种用途**：「**喂给 VCO → 颤音（vibrato，像歌剧演员的声音）· 喂给 VCA → 震音（tremolo，音量反复增减）· 喂给 VCF → 滤波扫掠（sweep，让更多频率通过又减少，声音不停变化）**」—— ⭐ **「它自己的声音你听不见，但每个音的活气都是它给的」**
  - ⭐⭐ **三类信号（模块化的纪律）** —— 「**Audio 信号**（VCO/NOISE 产生，典型 **10Vpp** 即 -5V 到 +5V）· **控制电压**（LFO 典型 **-2.5 至 +2.5V**；ADSR **0 至 +8V**）· **触发/门/时钟**（矩形波，典型 **0/+5V**，上升沿触发）」→ ⭐⭐ **把「声音」「控制」「时刻」分成三种不同的线——模块化系统的全部纪律就在这根分线上**
  - ⭐⭐ **Patch：模块只是盒子** —— 「**模块只是盒子，默认没有任何东西把它们连起来。必须先 patch（接线），合成器才能发声**」；⭐⭐ **「patches 让这些东西特别」**：「**你可以把任何模块喂给任何模块——一个模块的输出作为另一个的输入——产生各种古怪迷人的声音**」；「**把 patch 从合成器上拔掉，你就剩下一块白布。你带回来的一切都只是习惯，不在设备里——一块完全开放的画布**」依专题类资料
  - ⭐⭐ **模组的代价（Manzarek 的挫败）** —— 「**Doors 键盘手 Ray Manzarek 描述了乐队把喜欢的效果与配置复原时的挫败——完美的声音永远无法一模一样地复现——『模拟合成的美与挫败』**」；「模组化 Moog 的体积也是问题」依专题类资料
  - ⭐ **其他核心模块（速览）** —— **Sub-oscillator（副振荡器）**「加一个低一两八度的振荡器，把声音变厚」· **Ring modulator（环形调制器）**「输出是两输入频率的**和与差**——通常产生西方音阶『之间』的频率，**最常用于金属声**」· **Glide/Portamento/Slew limiter**「把一个音滑到另一个音——**键盘手天然做不到这个效果，因为每颗键都是分离的半音**，这个模块给他们滑音能力」· **Sample & hold**「采样输入并保持，直到下一个触发——输入噪声就是**随机音符序列**」依专题类资料
  - ⭐⭐ **1V/octave 的标准化** —— 「**缺点之一是标准化——这跟 CV 原则无关，而是各家实现不同：不同厂商用不同电压系统，一家公司的合成器难以接到另一家上——最终 1V/octave 系统胜出**」（**Buchla 用的是别的标准**——两位发明人的分歧至今仍在 Eurorack 里）依专题类资料
  - 「合成器属**电鸣**（Electrophone · 电子振荡 + 电压控制）」依 Hornbostel–Sachs 分类
updated: 2026-10-04
---

::: zh
**前面几页的电子乐器，每一件都是一个「完成的设计」——形状在发明时就定了。**

**这一页写的是它们的反面：一台发不出声的乐器——直到你亲手把它连起来。**

> 「**模块只是盒子，默认没有任何东西把它们连起来。必须先 patch（接线），合成器才能发声。**」

⭐⭐ **本页写电压控制原理——模拟合成器小类的理论基石。主线一句话：任何模块的输出都能控制任何模块。**

| 分类 | 归属 |
|---|---|
| **HS 分类** | **电鸣**（Electrophone · 电子振荡 + 电压控制）· **模块化**（可无限重组）· **复音视型号** |
| **两大原则** | ⭐⭐ **「真正的合成器」自 1960 年代起实现两大原则：减法合成 + 电压控制**——「Ondes Martenot · Mellotron · Hammond **音色相对有限，通常不被认为是 synthesizer**」 |
| **发明** | ⭐⭐ **Bob Moog 与 Don Buchla 于 1960 年代初各自独立发展**——Moog 造出「第一台商业化合成器」 |
| **八音对照** | 八音之外——**它甚至不是「一件」乐器，是一套搭建规则** |

## ⭐⭐ 主线：任何模块的输出都能控制任何模块

> 「**电压控制方法允许任何模块的输出被接线到任何其他模块的输入——一个极其强大且通用的系统。**」

⭐⭐ **在这之前，每件乐器的「控制方式」都是固定的**：
弦由手指控、管由气流控、特雷门由手势控——**控制手段与发声体焊死在一起。**

⭐⭐ **电压控制把「控制」本身抽出来变成一种信号**——
**振荡器的音高、滤波器的截止点、放大器的增益，全部是「电压」的函数。**
**于是「控制」可以像接线一样被重排。**

## ⭐⭐ 三大件：VCO · VCF · VCA

减法合成的经典信号链，三个压控模块：

| | ⭐ **VCO 压控振荡器** | ⭐ **VCF 压控滤波器** | ⭐ **VCA 压控放大器** |
|---|---|---|---|
| 管什么 | **音高**（产生富谐波波形） | **音色**（截止频率，选择性移除谐波） | **音量**（增益） |
| 被谁控 | 键盘 CV + 其他 | 包络/LFO/任何 CV | 包络（ADSR） |
| 一句话 | **「声源」** | **「把富波形做减法」** | **「把音的生灭塑形」** |

⭐⭐ **VCO 的 1V/octave 标准**：「**电压升 1 伏 = 音高升一个八度**」；
⭐⭐ **「Moog 从一开始就与音乐家合作，所以他的振荡器内建了指数转换器——
线性键盘电压进来，振荡器频率每伏倍增」。**

⭐⭐ **还有一条容易被忽略的**：「**CV 不是绝对参数而是相对参数**——
某个 CV 值（如 +1.0V）**不对应任何绝对音高**」；
**VCO 的最终音高 = 外部 CV + 调音旋钮 + 八度开关 + 其他 CV 输入的总和**。
⭐ **对照管风琴的音栓（Hammond 拉杆）：那里的音高是「选出来的」；这里的音高是「加出来的」。**

## ⭐⭐ ADSR：一个音的「一生」

> 包络发生器「由触发或门信号激活后，产生一个**从零伏升到最大电压、再回到零伏**的信号」。

⭐⭐ **四个阶段对应一个音的一生**：

| 阶段 | 发生什么 |
|---|---|
| ⭐ **A — Attack 起音** | 键按下 → 音量从零爬到峰值（**多快爬上去**） |
| ⭐ **D — Decay 衰减** | 爬到峰值后往回落（**回落到哪**） |
| ⭐ **S — Sustain 延持** | 按住不放时停在哪（**按住时的水位**） |
| ⭐ **R — Release 释音** | 手抬起来后多久归零（**收尾多快**） |

⭐⭐ **「它最常用于控制 VCA——塑造一个音的动态（并保证它最终会停止！）**」——
**ADSR 是一件乐器对「时间」的第一次完整建模。**

⭐ **GATE 信号**：「对应键盘上按下一颗键——高于约 +3V 视为『高』（+5V/+8V 都行），低于 1V 视为『低』」。

## ⭐⭐ LFO：不发声的振荡器

> 「LFO 设计为在**极低频率**（从最低可听频约 20 Hz 到远低于 1 Hz）产生精确波形。」

⭐⭐ **它自己不出声——但一个 LFO 有三种用途**：

| 喂给 | 效果 | 像什么 |
|---|---|---|
| ⭐ **VCO** | **颤音 vibrato** | 「歌剧演员的声音」 |
| ⭐ **VCA** | **震音 tremolo** | 音量反复增减 |
| ⭐ **VCF** | **滤波扫掠 sweep** | 「让更多频率通过又减少，声音不停变化」 |

⭐⭐ **「它自己的声音你听不见，但每个音的活气都是它给的。」**

## ⭐⭐ 三类信号：模块化的全部纪律

> 「**Audio 信号**（VCO/NOISE 产生，典型 10Vpp 即 -5V 到 +5V）·
> **控制电压**（LFO 典型 -2.5 至 +2.5V；ADSR 0 至 +8V）·
> **触发/门/时钟**（矩形波，典型 0/+5V，上升沿触发）。」

⭐⭐ **把「声音」「控制」「时刻」分成三种不同的线——**
**模块化系统的全部纪律就在这根分线上**：
**声音线不能接进触发口，触发口不该喂音频——每根线都知道自己是什么。**

## ⭐⭐ Patch：有针无线，真难寻一个音

> 「**模块只是盒子，默认没有任何东西把它们连起来。
> 必须先 patch（接线），合成器才能发声。**」

⭐⭐ **「patches 让这些东西特别」**：「**你可以把任何模块喂给任何模块——产生各种古怪迷人的声音**」；
⭐⭐ **「把 patch 从合成器上拔掉，你就剩下一块白布。你带回来的一切都只是习惯，
不在设备里——一块完全开放的画布。」**

⭐⭐ **但代价也在这里**：

> 「**Doors 键盘手 Ray Manzarek 描述了乐队把喜欢的效果与配置复原时的挫败——
> 完美的声音永远无法一模一样地复现——『模拟合成的美与挫败』。**」

⭐⭐ **《千祈莫拆针离线》——这首民歌的标题，就是每一位模块合成器玩家的第一戒律。**

## ⭐⭐ 其他核心模块（速览）

**Sub-oscillator 副振荡器**——「加一个低一两八度的振荡器，把声音变厚」；
**Ring modulator 环形调制器**——「输出是两输入频率的**和与差**——通常产生西方音阶『之间』的频率，**最常用于金属声**」；
**Glide/Slew limiter**——「把一个音滑到另一个音——⭐ **键盘手天然做不到这个效果，因为每颗键都是分离的半音**，这个模块给他们滑音能力」（对照马特诺的丝带：**一个补键盘的短板，一个补人手的短板**）；
**Sample & hold**——「采样输入并保持，直到下一个触发——输入噪声就是**随机音符序列**」。

## ⭐⭐ 1V/oct：一场标准化的胜选

> 「**缺点之一是标准化——不同厂商用不同电压系统，一家公司的合成器难以接到另一家上——
> 最终 1V/octave 系统胜出。**」

⭐⭐ **Buchla 用的是别的标准**——两位发明人的分歧至今仍在 Eurorack 里（⭐ 电压标准的「方言」至今没统一）。

## 收口：三句记住电压控制

| 问 | 答 |
|---|---|
| ⭐ 最要紧的一条 | ⭐⭐ **任何模块的输出都能控制任何模块** —— 「控制」本身变成信号；⭐⭐ **Moog 与 Buchla 各自独立发明** |
| ⭐⭐ 三大件 | ⭐ **VCO**（音高 · 1V/octave · 内建指数转换器）· ⭐ **VCF**（截止频率 · 减法合成的核心）· ⭐ **VCA**（增益 · 包络塑形）；⭐⭐ **减法合成 vs 加法合成（Telharmonium/Hammond）方向相反** |
| ⭐⭐ ADSR | ⭐⭐ **一个音的一生**：Attack 起音 · Decay 衰减 · Sustain 延持 · Release 释音——**乐器对「时间」的第一次完整建模** |
| ⭐⭐ LFO | ⭐⭐ **不发声的振荡器，三种用途**：VCO→颤音 · VCA→震音 · VCF→扫掠；⭐ **「每个音的活气都是它给的」** |
| ⭐⭐ 三类信号 | **Audio（±5V）· CV（LFO ±2.5 / ADSR 0–8V）· Gate/Trigger（0/+5V）**——⭐ **「声音」「控制」「时刻」分线而行，模块化的全部纪律** |
| ⭐⭐ Patch | ⭐⭐ **「模块只是盒子……必须先接线才能发声」**；⭐⭐ 「拔掉 patch 就剩一块白布」；⭐ **代价：Manzarek 无法复现之前的音色——「模拟合成的美与挫败」** |
| ⭐ 其他模块 | Sub-oscillator（加厚）· Ring mod（和与差 → 金属声）· Glide（**补键盘「每键分离」的短板**）· S&H（噪声 → 随机序列） |
| ⭐ 1V/oct | 「不同厂商不同电压系统……最终 **1V/octave 系统胜出**」——Buchla 用别的标准，**分歧至今仍在** |
| ⭐⭐ 判据 | ⭐⭐ **「是不是 synthesizer」的判据：减法合成 + 电压控制**——Martenot/Mellotron/Hammond 「通常不算」（本站前面条目的定位由此而来） |
| HS | **电鸣**（电子振荡 + 电压控制） |

**在这之前，每件乐器的「怎么控制」都是天生的；电压控制之后，控制变成了可以重排的线。**
⭐⭐ **有针无线，真难寻一个音——合成器的第一课不是发声，是接线。**

```svg
<svg viewBox="0 0 640 380" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="The voltage-control principle: a keyboard sends control voltage and gate into an ADSR and a VCO; the VCO's audio feeds a VCF, whose cutoff is swept by an LFO; the filtered audio feeds a VCA shaped by the ADSR; any output can be patched to any input">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">电压控制 · 三大件 + 包络 + LFO</text>
    <text x="20" y="44" font-size="11" fill="#6E6A64">任何模块的输出都能控制任何模块 —— 控制本身变成信号</text>
  </g>

  <rect x="30" y="70" width="100" height="46" rx="6" fill="#26241F" stroke="#9C7A3C" stroke-width="1.3"/>
  <text x="80" y="90" text-anchor="middle" font-size="9.5" fill="#A9A49B">键盘</text>
  <text x="80" y="106" text-anchor="middle" font-size="8.5" fill="#6E6A64">CV + GATE</text>

  <path d="M130,84 L170,84" stroke="#E8C547" stroke-width="1.6"/>
  <text x="132" y="78" font-size="8" fill="#E8C547">CV</text>

  <rect x="174" y="62" width="112" height="52" rx="6" fill="#26241F" stroke="#97C459" stroke-width="1.4"/>
  <text x="230" y="82" text-anchor="middle" font-size="9.5" fill="#97C459">VCO 振荡器</text>
  <text x="230" y="98" text-anchor="middle" font-size="8.5" fill="#6E6A64">1V/oct · 声源</text>

  <path d="M286,88 L330,88" stroke="#E8C547" stroke-width="1.6"/>
  <text x="288" y="82" font-size="8" fill="#E8C547">audio</text>

  <rect x="334" y="62" width="112" height="52" rx="6" fill="#26241F" stroke="#E8C547" stroke-width="1.4"/>
  <text x="390" y="82" text-anchor="middle" font-size="9.5" fill="#E8C547">VCF 滤波器</text>
  <text x="390" y="98" text-anchor="middle" font-size="8.5" fill="#6E6A64">截止频率 · 减法</text>

  <path d="M446,88 L492,88" stroke="#E8C547" stroke-width="1.6"/>
  <rect x="496" y="62" width="112" height="52" rx="6" fill="#26241F" stroke="#F0997B" stroke-width="1.4"/>
  <text x="552" y="82" text-anchor="middle" font-size="9.5" fill="#F0997B">VCA 放大器</text>
  <text x="552" y="98" text-anchor="middle" font-size="8.5" fill="#6E6A64">增益 · 包络塑形</text>

  <rect x="30" y="150" width="140" height="56" rx="6" fill="#26241F" stroke="#97C459" stroke-width="1.3"/>
  <text x="100" y="170" text-anchor="middle" font-size="9.5" fill="#97C459">ADSR 包络</text>
  <text x="100" y="188" text-anchor="middle" font-size="8.5" fill="#6E6A64">A起音 D衰减 S延持 R释音</text>

  <rect x="30" y="222" width="140" height="56" rx="6" fill="#26241F" stroke="#E8C547" stroke-width="1.3"/>
  <text x="100" y="242" text-anchor="middle" font-size="9.5" fill="#E8C547">LFO 低频振荡</text>
  <text x="100" y="260" text-anchor="middle" font-size="8.5" fill="#6E6A64">不发声 · 三种用途</text>

  <path d="M170,172 L320,172" stroke="#F0997B" stroke-width="1.4"/>
  <path d="M320,172 L320,118" stroke="#F0997B" stroke-width="1.4"/>
  <text x="196" y="166" font-size="8.5" fill="#F0997B">→ VCA（塑形音的生灭）</text>

  <path d="M170,244 L360,244" stroke="#E8C547" stroke-width="1.4"/>
  <path d="M360,244 L360,118" stroke="#E8C547" stroke-width="1.4"/>
  <text x="196" y="238" font-size="8.5" fill="#E8C547">→ VCO 颤音 / VCF 扫掠 / VCA 震音</text>

  <text x="20" y="298" font-size="10.5" fill="#E8C547">⭐ 三类信号分线而行：Audio（±5V）· CV（LFO ±2.5V / ADSR 0–8V）· Gate/Trigger（0/+5V）</text>
  <text x="20" y="320" font-size="10" fill="#6E6A64">⭐ 声音、控制、时刻各走各的线 —— 模块化的全部纪律</text>

  <g font-family="system-ui,sans-serif" font-size="10.5" fill="#A9A49B">
    <text x="20" y="346" fill="#E8C547">⭐ 「模块只是盒子……必须先接线才能发声」· 拔掉 patch 就剩一块白布</text>
    <text x="20" y="366" fill="#6E6A64">⚠️ 示意图：按文字描述绘制，非实物比例。</text>
  </g>
</svg>
```

```range
{"range":"C0–C8","common":"C2–C6","caption":"电压控制合成器的音域（VCO 理论无界 · 图示为常用演奏区）","caption_en":"Voltage-controlled synth range (the VCO is theoretically unbounded · common playing region shown)","note":"电压控制合成器属电鸣乐器（电子振荡 + 电压控制）。VCO 音高由控制电压决定（1V/octave 标准：电压升 1 伏音高升一个八度；CV 为相对参数不对应绝对音高），理论上无界，实用演奏区以 C0–C8 示意。减法合成链：VCO 富谐波波形 → VCF 截止频率选择移除 → VCA 由 ADSR 包络塑形（Attack/Decay/Sustain/Release 对应一个音的完整时间形态）。复音视型号而定（模块化单音系统与复音硬线琴并存）。记谱即实音。"}
```

```audiolab
{"type":"instrument","gm":"Lead 2 (sawtooth)","synth":"bowed","phrase":["C3","E3","G3","A3","C4","D4","E4"],"label":"锯齿波主音：减法合成的原型（借 GM Lead 2 近似）","label_en":"A sawtooth lead — subtractive synthesis in its native form (GM Lead 2 stands in)","hint":"通用音色表的 Lead 2 就是锯齿波主音——锯齿波正是减法合成的原料：富谐波波形进滤波器做减法。真实电压控制合成器的两样特征这条固定音色的采样里听不出来：一是包络——每个音的起音、衰减、延持、释音都是 ADSR 捏出来的；二是 patch——线拔掉它就是一块不发声的盒子，而采样里的「接线」是预先焊死的。","hint_en":"General MIDI's Lead 2 is a sawtooth lead — the sawtooth is subtractive synthesis' raw material: a harmonic-rich wave for the filter to carve. Two things are absent in this fixed-timbre sample: the envelope — each note's attack, decay, sustain and release squeezed out by an ADSR; and the patch — unplug it and this is a silent box, whereas the sample's wiring is soldered in advance."}
```
:::

::: en
The previous pages wrote instruments that were finished designs — their shapes fixed at birth.

**This page is the opposite: an instrument that makes no sound — until you wire it yourself.**

> 「**模块只是盒子，默认没有任何东西把它们连起来。必须先 patch（接线），合成器才能发声。**」

⭐⭐ **This page is voltage control — the theoretical bedrock of the analog-synth family. One line:
the output of any module can control any other.**

| Class | Assignment |
|---|---|
| **HS class** | **Electrophone**（electronic oscillation under voltage control）· **modular**（infinitely reconfigurable）· polyphony by model |
| **Two principles** | ⭐⭐ **「the proper synthesizer」 implements two principles: subtractive synthesis + voltage control** — 「Ondes Martenot · Mellotron · Hammond **音色相对有限，通常不被认为是 synthesizer**」 |
| **Invention** | ⭐⭐ **developed independently by Bob Moog and Don Buchla in the early 1960s** — Moog built 「the first commercially available synthesizer」 |
| **Bayin note** | Outside the bayin — it is not even 「one」 instrument but a set of building rules |

## ⭐⭐ The main line: any output controls any input

> 「**电压控制方法允许任何模块的输出被接线到任何其他模块的输入——一个极其强大且通用的系统**」.

⭐⭐ **Before this, every instrument's 「how it is controlled」 was fixed**:
strings by fingers, pipes by breath, theremin by gesture — **the control method was welded to
the sound-maker.**

⭐⭐ **Voltage control lifted 「control」 out into a signal of its own** —
**oscillator pitch, filter cutoff, amplifier gain: all became functions of voltage.**
**And so control could be re-routed like wire.**

## ⭐⭐ The big three: VCO · VCF · VCA

The classic subtractive chain, three voltage-controlled modules:

| | ⭐ **VCO** | ⭐ **VCF** | ⭐ **VCA** |
|---|---|---|---|
| In charge of | **pitch**（harmonic-rich waveforms） | **timbre**（cutoff, selective harmonic removal） | **level**（gain） |
| Controlled by | keyboard CV + anything | envelope/LFO/any CV | envelope（ADSR） |
| In one line | **the source** | **subtracting from a rich wave** | **shaping a note's life** |

⭐⭐ **The VCO's 1V/octave standard**: 「**电压升高 1 伏 = 音高升高一个八度**」;
⭐⭐ **「Moog 从一开始就与音乐家合作，所以他的振荡器内建了指数转换器——线性键盘电压进来，
振荡器频率每伏倍增」**.

⭐⭐ **One easily missed rule**: 「**CV 不是绝对参数而是相对参数**——某个 CV 值
（如 +1.0V）**不对应任何绝对音高**」; the VCO's final pitch = external CV + tune knob +
octave switch + other CV inputs, **summed**.
⭐ **Compare the organ stop（the Hammond's drawbars）: there the pitch is chosen; here it is
added up.**

## ⭐⭐ ADSR: the biography of one note

> The envelope generator 「由触发或门信号激活后，产生一个**从零伏升到最大电压、再回到零伏**
> 的信号」.

⭐⭐ **Four stages, one note's life**:

| Stage | What happens |
|---|---|
| ⭐ **A — Attack** | key down → level climbs from zero（**how fast**） |
| ⭐ **D — Decay** | falls from the peak（**to where**） |
| ⭐ **S — Sustain** | the held level（**where it sits while you hold**） |
| ⭐ **R — Release** | how long to zero after you let go（**how the note dies**） |

⭐⭐ **「它最常用于控制 VCA——塑造一个音的动态（并保证它最终会停止！）」**—
**ADSR is an instrument's first complete model of time.**

⭐ **GATE**: 「对应键盘上按下一颗键——高于约 +3V 视为『高』，低于 1V 视为『低』」.

## ⭐⭐ The LFO: the oscillator that makes no sound

> 「LFO 设计为在**极低频率**（从最低可听频约 20 Hz 到远低于 1 Hz）产生精确波形」.

⭐⭐ **Silent itself — but one LFO has three uses**:

| Fed into | Effect | Like |
|---|---|---|
| ⭐ **VCO** | **vibrato** | 「歌剧演员的声音」 |
| ⭐ **VCA** | **tremolo** | level rising and falling |
| ⭐ **VCF** | **filter sweep** | 「让更多频率通过又减少，声音不停变化」 |

⭐⭐ **「它自己的声音你听不见，但每个音的活气都是它给的」.**

## ⭐⭐ Three kinds of signal: the whole discipline

> 「**Audio 信号**（VCO/NOISE 产生，典型 10Vpp 即 -5V 到 +5V）·
> **控制电压**（LFO 典型 -2.5 至 +2.5V；ADSR 0 至 +8V）·
> **触发/门/时钟**（矩形波，典型 0/+5V，上升沿触发）」.

⭐⭐ **「声音」「控制」「时刻」分线而行 —**
**the whole discipline of a modular system is on this one dividing line**:
an audio line must not feed a trigger input — every wire knows what it is.

## ⭐⭐ Patch: needles without thread

> 「**模块只是盒子，默认没有任何东西把它们连起来。
> 必须先 patch（接线），合成器才能发声**」.

⭐⭐ **「patches 让这些东西特别」**: 「**你可以把任何模块喂给任何模块——产生各种古怪迷人的
声音**」; ⭐⭐ **「把 patch 从合成器上拔掉，你就剩下一块白布。你带回来的一切都只是习惯，
不在设备里——一块完全开放的画布」**.

⭐⭐ **But the cost lives here too**:

> 「**Doors 键盘手 Ray Manzarek 描述了乐队把喜欢的效果与配置复原时的挫败——
> 完美的声音永远无法一模一样地复现——『模拟合成的美与挫败』**」.

⭐⭐ **《千祈莫拆针离线》 — that folk title is the first commandment of every modular player.**

## ⭐⭐ Other core modules（quick tour）

**Sub-oscillator** — 「加一个低一两八度的振荡器，把声音变厚」;
**Ring modulator** — 「输出是两输入频率的**和与差**——通常产生西方音阶『之间』的频率，
**最常用于金属声**」;
**Glide/Slew limiter** — 「把一个音滑到另一个音——⭐ **键盘手天然做不到这个效果，因为每颗键
都是分离的半音**，这个模块给他们滑音能力」（compare the Martenot's ribbon: **one patches the
keyboard's gap, the other patches the hand's**）;
**Sample & hold** — 「采样输入并保持，直到下一个触发——输入噪声就是**随机音符序列**」.

## ⭐⭐ 1V/oct: an election won

> 「**缺点之一是标准化——不同厂商用不同电压系统，一家公司的合成器难以接到另一家上——
> 最终 1V/octave 系统胜出**」.

⭐⭐ **Buchla used another standard** — the two inventors' split lives on inside Eurorack
（⭐ the voltage 「dialects」 never fully merged）.

## Recap: three sentences on voltage control

| Q | A |
|---|---|
| ⭐ The key point | ⭐⭐ **any module's output can control any other** — 「control」 itself became a signal; ⭐⭐ **Moog and Buchla, independently** |
| ⭐⭐ The big three | ⭐ **VCO**（pitch · 1V/oct · built-in exponential converter）· ⭐ **VCF**（cutoff · the heart of subtraction）· ⭐ **VCA**（gain · envelope shaping）; ⭐⭐ **subtractive vs additive（Telharmonium/Hammond）— opposite directions** |
| ⭐⭐ ADSR | ⭐⭐ **one note's biography**: attack · decay · sustain · release — **an instrument's first complete model of time** |
| ⭐⭐ LFO | ⭐⭐ **the silent oscillator, three uses**: VCO→vibrato · VCA→tremolo · VCF→sweep; ⭐ 「每个音的活气都是它给的」 |
| ⭐⭐ Three signals | **Audio（±5V）· CV（LFO ±2.5 / ADSR 0–8V）· Gate/Trigger（0/+5V）**— ⭐ **sound, control and time each on their own wire** |
| ⭐⭐ Patch | ⭐⭐ **「模块只是盒子……必须先接线才能发声」**; ⭐⭐ 「unplug it and you have a blank canvas」; ⭐ the cost: **Manzarek's irreproducible sounds — the beauty and frustration** |
| ⭐ Other modules | sub-oscillator（thicken）· ring mod（sum & difference → metal）· glide（**patches the keyboard's per-note gap**）· S&H（noise → random sequence） |
| ⭐ 1V/oct | 「不同厂商不同电压系统……**最终 1V/octave 系统胜出**」— Buchla differed; **the split survives** |
| ⭐⭐ The criterion | ⭐⭐ **what makes a 「synthesizer」: subtractive synthesis + voltage control** — Martenot/Mellotron/Hammond 「通常不算」（the placing of our earlier entries comes from here） |
| HS | **Electrophone**（oscillation + voltage control） |

**Before this, every instrument's 「how it is controlled」 was born into it; after voltage
control, control became wire that could be re-routed.**

⭐⭐ **Needles without thread: the synthesizer's first lesson is not how to sound — it is how to
wire.**

```svg
<svg viewBox="0 0 640 380" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="The voltage-control principle: a keyboard sends control voltage and gate into an ADSR and a VCO; the VCO's audio feeds a VCF, whose cutoff is swept by an LFO; the filtered audio feeds a VCA shaped by the ADSR; any output can be patched to any input">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">电压控制 · 三大件 + 包络 + LFO</text>
    <text x="20" y="44" font-size="11" fill="#6E6A64">任何模块的输出都能控制任何模块 —— 控制本身变成信号</text>
  </g>

  <rect x="30" y="70" width="100" height="46" rx="6" fill="#26241F" stroke="#9C7A3C" stroke-width="1.3"/>
  <text x="80" y="90" text-anchor="middle" font-size="9.5" fill="#A9A49B">键盘</text>
  <text x="80" y="106" text-anchor="middle" font-size="8.5" fill="#6E6A64">CV + GATE</text>

  <path d="M130,84 L170,84" stroke="#E8C547" stroke-width="1.6"/>
  <text x="132" y="78" font-size="8" fill="#E8C547">CV</text>

  <rect x="174" y="62" width="112" height="52" rx="6" fill="#26241F" stroke="#97C459" stroke-width="1.4"/>
  <text x="230" y="82" text-anchor="middle" font-size="9.5" fill="#97C459">VCO 振荡器</text>
  <text x="230" y="98" text-anchor="middle" font-size="8.5" fill="#6E6A64">1V/oct · 声源</text>

  <path d="M286,88 L330,88" stroke="#E8C547" stroke-width="1.6"/>
  <text x="288" y="82" font-size="8" fill="#E8C547">audio</text>

  <rect x="334" y="62" width="112" height="52" rx="6" fill="#26241F" stroke="#E8C547" stroke-width="1.4"/>
  <text x="390" y="82" text-anchor="middle" font-size="9.5" fill="#E8C547">VCF 滤波器</text>
  <text x="390" y="98" text-anchor="middle" font-size="8.5" fill="#6E6A64">截止频率 · 减法</text>

  <path d="M446,88 L492,88" stroke="#E8C547" stroke-width="1.6"/>
  <rect x="496" y="62" width="112" height="52" rx="6" fill="#26241F" stroke="#F0997B" stroke-width="1.4"/>
  <text x="552" y="82" text-anchor="middle" font-size="9.5" fill="#F0997B">VCA 放大器</text>
  <text x="552" y="98" text-anchor="middle" font-size="8.5" fill="#6E6A64">增益 · 包络塑形</text>

  <rect x="30" y="150" width="140" height="56" rx="6" fill="#26241F" stroke="#97C459" stroke-width="1.3"/>
  <text x="100" y="170" text-anchor="middle" font-size="9.5" fill="#97C459">ADSR 包络</text>
  <text x="100" y="188" text-anchor="middle" font-size="8.5" fill="#6E6A64">A起音 D衰减 S延持 R释音</text>

  <rect x="30" y="222" width="140" height="56" rx="6" fill="#26241F" stroke="#E8C547" stroke-width="1.3"/>
  <text x="100" y="242" text-anchor="middle" font-size="9.5" fill="#E8C547">LFO 低频振荡</text>
  <text x="100" y="260" text-anchor="middle" font-size="8.5" fill="#6E6A64">不发声 · 三种用途</text>

  <path d="M170,172 L320,172" stroke="#F0997B" stroke-width="1.4"/>
  <path d="M320,172 L320,118" stroke="#F0997B" stroke-width="1.4"/>
  <text x="196" y="166" font-size="8.5" fill="#F0997B">→ VCA（塑形音的生灭）</text>

  <path d="M170,244 L360,244" stroke="#E8C547" stroke-width="1.4"/>
  <path d="M360,244 L360,118" stroke="#E8C547" stroke-width="1.4"/>
  <text x="196" y="238" font-size="8.5" fill="#E8C547">→ VCO 颤音 / VCF 扫掠 / VCA 震音</text>

  <text x="20" y="298" font-size="10.5" fill="#E8C547">⭐ 三类信号分线而行：Audio（±5V）· CV（LFO ±2.5V / ADSR 0–8V）· Gate/Trigger（0/+5V）</text>
  <text x="20" y="320" font-size="10" fill="#6E6A64">⭐ 声音、控制、时刻各走各的线 —— 模块化的全部纪律</text>

  <g font-family="system-ui,sans-serif" font-size="10.5" fill="#A9A49B">
    <text x="20" y="346" fill="#E8C547">⭐ 「模块只是盒子……必须先接线才能发声」· 拔掉 patch 就剩一块白布</text>
    <text x="20" y="366" fill="#6E6A64">⚠️ 示意图：按文字描述绘制，非实物比例。</text>
  </g>
</svg>
```

```range
{"range":"C0–C8","common":"C2–C6","caption":"电压控制合成器的音域（VCO 理论无界 · 图示为常用演奏区）","caption_en":"Voltage-controlled synth range (the VCO is theoretically unbounded · common playing region shown)","note":"电压控制合成器属电鸣乐器（电子振荡 + 电压控制）。VCO 音高由控制电压决定（1V/octave 标准：电压升 1 伏音高升一个八度；CV 为相对参数不对应绝对音高），理论上无界，实用演奏区以 C0–C8 示意。减法合成链：VCO 富谐波波形 → VCF 截止频率选择移除 → VCA 由 ADSR 包络塑形（Attack/Decay/Sustain/Release 对应一个音的完整时间形态）。复音视型号而定（模块化单音系统与复音硬线琴并存）。记谱即实音。"}
```

```audiolab
{"type":"instrument","gm":"Lead 2 (sawtooth)","synth":"bowed","phrase":["C3","E3","G3","A3","C4","D4","E4"],"label":"锯齿波主音：减法合成的原型（借 GM Lead 2 近似）","label_en":"A sawtooth lead — subtractive synthesis in its native form (GM Lead 2 stands in)","hint":"通用音色表的 Lead 2 就是锯齿波主音——锯齿波正是减法合成的原料：富谐波波形进滤波器做减法。真实电压控制合成器的两样特征这条固定音色的采样里听不出来：一是包络——每个音的起音、衰减、延持、释音都是 ADSR 捏出来的；二是 patch——线拔掉它就是一块不发声的盒子，而采样里的「接线」是预先焊死的。","hint_en":"General MIDI's Lead 2 is a sawtooth lead — the sawtooth is subtractive synthesis' raw material: a harmonic-rich wave for the filter to carve. Two things are absent in this fixed-timbre sample: the envelope — each note's attack, decay, sustain and release squeezed out by an ADSR; and the patch — unplug it and this is a silent box, whereas the sample's wiring is soldered in advance."}
```
:::