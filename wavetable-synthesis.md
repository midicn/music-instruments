---
id: wavetable-synthesis
site: inst
cat: I11
title: 波表合成
title_en: Wavetable synthesis
summary: 声音在发声前就开始演化 —— 走过一整座美术馆的音色
summary_en: Sound evolves before it sounds — timbre as a walk through an entire gallery
level: standard
tags: [乐器, 电子, 电鸣, 西洋, 数字合成器, 波表合成, PPG, Waldorf]
tags_en: [instrument, electronic, electrophone, western, digital-synth, wavetable, ppg, waldorf]
alias: [波表合成, wavetable-synthesis, 波表, PPG Wave, Wolfgang Palm, 矢量合成]
order: 182
links:
  - "[[instrument:dx7-fm]]"
  - "[[instrument:prophet-5]]"
  - "[[instrument:voltage-control]]"
  - "[[instrument:samplers]]"
  - "[[concept:timbre]]"
  - "[[concept:harmonic-series]]"
instances:
  - chinafolk-000215 | 《画扇面（一）》 —— ⭐⭐「画扇面」：波表的原理就是**在一张波形卷轴上「画」**——「**相邻波形间用插值避免明显跳变**」——**扇面一展开是一幅画，波表一扫过是一串声音**（**C3 · 仅限学习研究**；库内无波表合成器录音，取民歌作意象参照）
  - chinafolk-001057 | 《哪得泥鳅变成龙》 —— ⭐⭐「变成龙」：**波表的全部魅力是「变」**——「**想象按住一个钢琴键……音色慢慢从柔→亮→金属→攻击→空气——全部来自一个持续音**」——⭐ **泥鳅变龙的持续变化，正是波表位置移动的听觉版**（**C3 · 仅限学习研究**）
  - chinafolk-000215 | 《画扇面（一）》 —— ⭐「扇面」再记：「**波表合成改变的是声源本身——波形在到达滤波器之前就开始演化**」——**扇面上的画是早就画好的，翻页速度只是你的手**（**C3 · 仅限学习研究**）
sources:
  - ⭐⭐ **主线：声音在发声前就开始演化（本页最该记住的一条）** —— 「**Subtractive synthesis changes the sound after it's created. Wavetable synthesis changes the sound as it's being created.**（减法合成在声音被创造**后**改变它；波表合成在声音被创造**时**就改变它）」；⭐⭐ **雕刻比喻（全站最漂亮的类比之一）**：「**减法合成：从一块大理石雕刻。FM 合成：两个雕塑家互相改对方的作品。波表合成：走过一整座美术馆**」——**一个块 · 两双手 · 一条走廊：三种合成法的三种空间感**
  - ⭐⭐ **原理（一本书的比喻）** —— 「**想象一本书，每一页都有不同的波形。慢慢翻页，声音不变；快速翻页或跳页，声音就变**」；「**波表合成在存储器中存储一序列单周期波形，让演奏者或调制系统步进它们——产生随时间变形的音**」；「**动态频谱移动通过扫描波形实现，用插值避免相邻波形间的明显跳变**」依专题类资料
  - ⭐⭐ **波表调制（「运动创造情感」）** —— 「**几乎任何东西都能推动波表位置：LFO · 包络 · 力度 · 触后 · 弯音轮 · automation**」；「**想象按住一个钢琴键……音色慢慢从：柔 → 亮 → 金属 → 攻击 → 空气——全部来自一个持续音**」→ ⭐⭐ **「运动创造情感。不再有静态声音——你得到的是演化的声音」**（**现代 EDM 的声音很大程度依赖波表的移动**）
  - ⭐⭐ **软件先于硬件十五年（MUSIC-II 1958）** —— 「**波表合成实际上比矢量合成早一点。它首次用于 MUSIC-II——Max Vernon Mathews 1958 年开发的音色设计程序**」——⭐⭐ **数字合成方法的谱系又一条「软件先于硬件」**（对照 tape-music 的实验室、DX7 的算法——**MUSIC-II 是波表的「最早使用」**）
  - ⭐⭐ **PPG Wavecomputer 360（1978）：无滤波的教训** —— 「Palm 的努力产生了 PPG 第一台波表合成器 **Wavecomputer 360（1978）——为用户提供 30 张不同波表，每张含 64 个波形**」；「** expansive 的声音范围是明显的，但滤波器的缺席使 360 听起来 buzz 又薄——这削弱了它最初商业可行性**」→ ⭐⭐ **对照 Minimoog 的「手感」与 Prophet 的「滤波」——波表的「演化」需要模拟滤波来「收口」：纯数字太刺**
  - ⭐⭐ **PPG Wave 系列（1981–87）：hybrid 的胜利** —— 「**Wave 系列是前身的进化：数字声音引擎 + 模拟 VCA 与 24dB/oct VCF**」；三版：「**Wave 2（1981）8 振荡器 8-bit → Wave 2.2（1982）16 振荡器双调制轮 → Wave 2.3（1984）12-bit（经 Waveterm）· 8 部多音色**」；「**控制面板皆以独特的超群蓝 RAL 5002 着色**」；「**Wave 系列还加了内建音序器——能实时录制滤波与波表变化**」
  - ⭐⭐ **PPG Wave System：对抗 Fairlight 的拼装** —— 「**PPG Wave 可通过定制总线同时连接多个外设：『智能』键盘控制器（PRK）· 8 音扩展单元（EVU）· 以及叫 Waveterm A/B 的波计算机——用于采样、音频操作、编辑、音序与创建用户自定义波表**」；「**这套组合被称为 PPG Wave System，以采样与音序意在与更贵的 Fairlight CMI 竞争**」→ ⭐⭐ **对照 samplers 条：**「** Fairlight 是一台贵机器，PPG 是一套可拼装的中产方案——同一时代的两条民主化路线**」
  - ⭐⭐ **用户谱系（一张长名单）** —— 「**a-ha · Alphaville · David Bowie · Depeche Mode · Gary Numan · Propaganda · Jean Michel Jarre · Art of Noise · Rush · Tangerine Dream · Tears for Fears · Thomas Dolby · Ultravox · Stevie Wonder · Trevor Horn · Steven Halpern · Kitaro**……」——⭐ ** synth-pop 与 Berlin School 的半壁江山都在名单上**
  - ⭐⭐ **矢量合成（vector synthesis）：隔壁的方法** —— 「**矢量合成由 Sequential 在 1980 年代以 Prophet VS 引入——把不同音色分配到正方形四角，用摇杆直观地混合它们——结果的声音可以用坐标平面上的单个点表示——故名矢量合成**」；⭐⭐ **两种方法的区别**：「**矢量合成基于坐标平面位置计算四声源的音量平衡；波表合成在单个波形周期内计算不同波形的振幅比**」；⭐ **人才迁移线**：「**后来 Sequential 被 Yamaha 收购，开发团队转投 Korg——于是有了 Yamaha SY22 与 Korg Wavestation 两台矢量合成器**」（**对照 Prophet-5 的公司史：人走了，方法跟着走**）
  - ⭐⭐ **PPG 关闭与 Waldorf 的续命** —— 「**PPG 1987 年关闭，但波表原理通过后代延续——包括 1990 年代的 Waldorf Microwave 家族与大量现代软件合成器（部分与 Palm 本人合作开发）**」；「**Waldorf Wave——更大更先进的旗舰——今天被视为有史以来最受追捧的合成器之一**」；「**没有 PPG 与 Waldorf，现代波表合成可能不存在**」
  - ⭐⭐ **现代：Serum 与免费 Vital** —— 「**Xfer Serum 可能是世界上最流行的波表合成器——漂亮的界面 · 拖放工作流 · 大型调制系统**」；「**Ableton Wavetable 内置于 Live Suite · Native Instruments Massive · 免费的 Vital**」；「**几乎所有现代流派——EDM · Dubstep · Cinematic · Synthwave——你听到演化的数字质感处，多半有波表合成**」
  - 「波表合成器属**电鸣**（Electrophone · 波表扫描 + 模拟滤波的 hybrid）」依 Hornbostel–Sachs 分类
updated: 2026-10-04
---

::: zh
**上一页的采样器把世界录下来——这一页的乐器说：不用录，让声音自己「长」。**

> 「**Subtractive synthesis changes the sound after it's created. Wavetable synthesis changes the sound as it's being created.**」

⭐⭐ **本页写波表合成——数字合成器第 3 条。主线一句话：声音在发声前就开始演化。**

| 分类 | 归属 |
|---|---|
| **HS 分类** | **电鸣**（Electrophone · 波表扫描 + 模拟滤波的 hybrid）· **数字振荡 + 模拟收口** |
| **出身** | ⭐⭐ **MUSIC-II（1958 · Max Mathews 软件）** → **PPG Wavecomputer 360（1978 · 无滤波受挫）** → **PPG Wave 系列（1981–87 · hybrid 胜利）** → **Waldorf 续命** |
| **两个比喻** | ⭐⭐ **「减法=雕一块大理石 · FM=两个雕塑家互改 · 波表=走过整座美术馆」** |
| **八音对照** | 八音之外——**音色第一次是「一条走廊」而非「一间屋子」** |

## ⭐⭐ 主线：三种合成法的三种空间感

> 「**Subtractive synthesis: Carving one block of marble.
> FM: Two sculptors changing each other's work.
> Wavetable: Walking through an entire art gallery.**」

⭐⭐ **这是全站最漂亮的类比之一，三种合成法一次说清**：

| 方法 | 空间 | 一句话 |
|---|---|---|
| **减法** | **一块大理石** | 从富谐波波形里「雕」 |
| **FM** | **两个雕塑家互改** | 算子互相调制 |
| ⭐⭐ **波表** | **一整座美术馆** | 在几百张波形间「散步」 |

⭐⭐ **「减法合成在声音被创造后改变它；波表合成在声音被创造时就改变它」——**
**波表的演化发生在「发声之前」，这是它与一切先前方法的根本不同。**

## ⭐⭐ 原理：一本书的比喻

> 「**想象一本书，每一页都有不同的波形。慢慢翻页，声音不变；快速翻页或跳页，声音就变。**」

⭐⭐ **技术上**：「**波表合成在存储器中存储一序列单周期波形，让演奏者或调制系统步进它们**」；
「**动态频谱移动通过扫描波形实现，用插值避免相邻波形间的明显跳变**」——
⭐ **「插值」是「走路不摔跤」的技术名：页与页之间是滑过去的，不是跳过去的。**

## ⭐⭐ 波表调制：运动创造情感

> 「**几乎任何东西都能推动波表位置：LFO · 包络 · 力度 · 触后 · 弯音轮 · automation**」；
> 「**想象按住一个钢琴键……音色慢慢从：柔 → 亮 → 金属 → 攻击 → 空气——全部来自一个持续音**」。

⭐⭐ **「运动创造情感。不再有静态声音——你得到的是演化的声音。」**

⭐⭐ **实例对照**：《哪得泥鳅变成龙》——**一个持续音里完成「泥鳅变龙」的全程——
这就是波表位置移动的听觉版。**

## ⭐⭐ 软件先于硬件十五年

> 「**波表合成首次用于 MUSIC-II——Max Vernon Mathews 1958 年开发的音色设计程序。**」

⭐⭐ **对照全站的「实验室先于舞台」**：
**FM 在大学（Chowning）· 采样在电台（El-Dabh）· 波表在贝尔实验室式的程序里（Mathews）——**
⭐⭐ **电子乐器的每一次突破，都先在「没有乐器的地方」发生。**

## ⭐⭐ Wavecomputer 360：无滤波的教训

> 「Palm 的努力产生了 **Wavecomputer 360（1978）——30 张不同波表，每张 64 个波形**」；
> 「**滤波器的缺席使 360 听起来 buzz 又薄——这削弱了它最初商业可行性**」。

⭐⭐ **对照 Minimoog（预接线换易用）与 ARP（预接+可覆盖）——**
**Wavecomputer 的教训是「纯数字太刺」：**
⭐⭐ **波表的「演化」需要模拟滤波来「收口」。**

## ⭐⭐ PPG Wave 系列：hybrid 的胜利

> 「**Wave 系列是前身的进化：数字声音引擎 + 模拟 VCA 与 24dB/oct VCF**」；
> 「**Wave 2（1981）→ Wave 2.2（1982 · 双调制轮）→ Wave 2.3（1984 · 8 部多音色）**」；
> 「**控制面板皆以独特的超群蓝 RAL 5002 着色**」。

⭐⭐ **「数字振荡 + 模拟滤波」——对照 Prophet-5（模拟发声+数字控制）的镜像：**
**Prophet 是「模拟的声音+数字的记忆」，PPG 是「数字的振荡+模拟的收口」——**
**新旧同体的两种拼法。**

## ⭐⭐ PPG Wave System：对抗 Fairlight 的拼装

> 「**可连 PRK 智能键盘 · EVU 8 音扩展 · Waveterm A/B 波计算机——
> 用于采样、音频操作、编辑、音序与创建用户自定义波表**」；
> 「**这套组合意在与更贵的 Fairlight CMI 竞争**」。

⭐⭐ **对照 samplers 条**：**Fairlight 是一台贵机器，PPG 是一套可拼装的中产方案——**
**同一时代的两条民主化路线。**（**结果也同 Fairlight 一样：PPG 1987 关闭。**）

## ⭐⭐ 用户谱系：synth-pop 的半壁江山

> 「**a-ha · Bowie · Depeche Mode · Gary Numan · Jarre · Art of Noise · Rush ·
> Tangerine Dream · Tears for Fears · Dolby · Ultravox · Stevie Wonder · Trevor Horn**……」

⭐⭐ **synth-pop 与 Berlin School 的半壁江山都在名单上——**
**波表的「演化质感」正是那个年代想要的「未来感」。**

## ⭐⭐ 矢量合成：隔壁的方法（与一条人才迁移线）

> 「**矢量合成由 Sequential 以 Prophet VS 引入——把不同音色分配到正方形四角，
> 用摇杆直观混合——声音可用坐标平面上的一个点表示**」。

⭐⭐ **两种方法的区别**：「**矢量基于坐标平面位置算四声源的音量平衡；
波表在单个波形周期内算不同波形的振幅比**」——
**一个是「房间四角的推拉」，一个是「画廊里的漫步」。**

⭐⭐ **人才迁移线**：「**后来 Sequential 被 Yamaha 收购，开发团队转投 Korg——
于是有了 Yamaha SY22 与 Korg Wavestation**」——
**对照 Prophet-5 公司史：人走了，方法跟着走。**

## ⭐⭐ Waldorf 续命与现代复兴

> 「**PPG 1987 年关闭，但波表原理通过 Waldorf Microwave 家族与大量现代软件合成器延续
> （部分与 Palm 本人合作开发）**」；
> 「**Waldorf Wave——今天被视为有史以来最受追捧的合成器之一**」；
> 「**没有 PPG 与 Waldorf，现代波表合成可能不存在**」。

⭐⭐ **现代**：「**Xfer Serum 可能是世界上最流行的波表合成器 · Ableton Wavetable · 免费 Vital**」——
**几乎所有现代流派——EDM · Dubstep · Cinematic · Synthwave——你听到演化的数字质感处，多半有波表合成。**

## 收口：三句记住波表合成

| 问 | 答 |
|---|---|
| ⭐ 最要紧的一条 | ⭐⭐ **声音在发声前就开始演化**——「**减法在创造后改变声音；波表在创造时就改变声音**」；⭐⭐ **「走过一整座美术馆」** |
| ⭐⭐ 原理 | **存储一序列单周期波形，步进扫描**；「**插值避免相邻波形间明显跳变**」——⭐ **「插值」是走路不摔跤的技术名** |
| ⭐⭐ 调制 | ⭐⭐ **「运动创造情感」**——LFO/包络/力度/触后推波表位置：**一个持续音里完成「柔→亮→金属→攻击→空气」** |
| ⭐⭐ 软件先行 | ⭐⭐ **MUSIC-II（1958 · Mathews）早于硬件二十年**——**电子乐器的突破先在「没有乐器的地方」发生** |
| ⭐⭐ Wavecomputer 教训 | **360（1978）无滤波 → buzz 又薄**——⭐⭐ **波表的「演化」需要模拟滤波来「收口」** |
| ⭐⭐ hybrid | **Wave 系列 = 数字振荡 + 模拟 VCF/VCA**——**Prophet（模拟声+数字忆）的镜像：数字声+模拟口** |
| ⭐⭐ 对抗 Fairlight | **PPG Wave System（PRK+EVU+Waveterm）**——**拼装的中产方案 vs 一台贵机器**（同样 1987 收场） |
| ⭐⭐ 矢量合成 | **Prophet VS 的摇杆四角混音**——「**房间四角的推拉** vs **画廊漫步**」；**Sequential→Yamaha/Korg 的人才迁移线** |
| ⭐⭐ Waldorf | **Microwave · Wave · Blofeld 续命**——「**没有 PPG 与 Waldorf，现代波表合成可能不存在**」 |
| ⭐ 现代 | **Serum · Ableton Wavetable · Vital（免费）**——**EDM/Trap/Cinematic 的演化质感之源** |
| HS | **电鸣**（波表扫描 + 模拟滤波 hybrid） |

**减法的声音是「雕」出来的，FM 的声音是「算」出来的，波表的声音是「走」出来的。**
⭐⭐ **波表给了音色第四维——时间上的「长」：**
**一个音不再是一个点，而是一条走廊。**

```svg
<svg viewBox="0 0 640 380" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Wavetable synthesis as a gallery walk: a row of waveform frames — each a different single-cycle shape — scanned with interpolation so pages glide rather than jump; subtractive carves one marble block, FM is two sculptors editing each other, wavetable walks through an entire gallery; the PPG Wave paired digital oscillators with analog filters after the Wavecomputer 360's filterless failure">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">波表合成 · 走过一整座美术馆</text>
    <text x="20" y="44" font-size="11" fill="#6E6A64">减法=雕一块大理石 · FM=两个雕塑家互改 · 波表=画廊漫步</text>
  </g>

  <rect x="30" y="62" width="580" height="96" rx="8" fill="#26241F" stroke="#9C7A3C" stroke-width="1.3"/>
  <g fill="none" stroke="#97C459" stroke-width="1.4">
    <path d="M56,110 Q66,90 76,110 T96,110"/>
    <path d="M126,110 Q136,100 146,110 L166,110"/>
    <path d="M196,110 L216,110 L216,90 L236,90 L236,110 L256,110"/>
    <path d="M286,96 L306,124 L326,96 L346,124"/>
    <path d="M376,110 Q396,86 416,110 T456,110"/>
    <path d="M486,110 L506,92 L526,110 L546,92 L566,110"/>
    <path d="M576,110 Q584,100 592,110"/>
  </g>
  <g fill="#E8C547">
    <circle cx="76" cy="110" r="4"/><circle cx="156" cy="110" r="4"/><circle cx="236" cy="110" r="4"/>
    <circle cx="316" cy="110" r="4"/><circle cx="416" cy="110" r="4"/><circle cx="506" cy="110" r="4"/>
    <circle cx="576" cy="110" r="4"/>
  </g>
  <text x="320" y="146" text-anchor="middle" font-size="9" fill="#6E6A64">波表 = 一排单周期波形 · 时钟/包络/LFO 推动「位置」 · 插值让翻页不跳变</text>

  <text x="20" y="180" font-size="10.5" fill="#E8C547">⭐ 「减法在创造后改变声音；波表在创造时就改变声音」—— 音色的第四维：时间上的「长」</text>
  <text x="20" y="202" font-size="10" fill="#A9A49B">按住一个键：柔 → 亮 → 金属 → 攻击 → 空气 —— 全部来自一个持续音（「运动创造情感」）</text>

  <rect x="30" y="214" width="286" height="56" rx="8" fill="none" stroke="#F0997B" stroke-width="1.2"/>
  <text x="173" y="234" text-anchor="middle" font-size="9.5" fill="#F0997B">Wavecomputer 360（1978）的教训</text>
  <text x="48" y="254" font-size="9" fill="#6E6A64">30 波表 × 64 波形 · 但无滤波 → buzz 又薄</text>
  <text x="48" y="264" font-size="9" fill="#97C459">⭐ 波表的「演化」需要模拟滤波来收口</text>

  <rect x="324" y="214" width="286" height="56" rx="8" fill="none" stroke="#97C459" stroke-width="1.2"/>
  <text x="467" y="234" text-anchor="middle" font-size="9.5" fill="#97C459">PPG Wave（1981–87）：hybrid 胜利</text>
  <text x="342" y="254" font-size="9" fill="#6E6A64">数字振荡 + 模拟 VCF/VCA · 超群蓝面板</text>
  <text x="342" y="264" font-size="9" fill="#97C459">Prophet 的镜像：数字声+模拟口</text>

  <text x="20" y="296" font-size="10.5" fill="#E8C547">⭐ 软件先行：MUSIC-II（1958 · Mathews）早于硬件二十年 —— 突破先在「没有乐器的地方」发生</text>
  <text x="20" y="316" font-size="10" fill="#A9A49B">⭐ 矢量合成是隔壁：VS 摇杆四角混音 = 房间推拉；波表 = 画廊漫步 —— Sequential 团队后来去了 Korg</text>

  <g font-family="system-ui,sans-serif" font-size="10.5" fill="#A9A49B">
    <text x="20" y="344" fill="#E8C547">⭐ PPG 1987 关闭 → Waldorf 续命 → Serum/Ableton/Vital：现代 EDM 的演化质感之源</text>
    <text x="20" y="364" fill="#6E6A64">⚠️ 示意图：按文字描述绘制，非实物比例。</text>
  </g>
</svg>
```

```range
{"range":"C1–C8","common":"C2–C5","caption":"波表合成器的音域（PPG Wave 五八度键盘 · 波表位置由调制推动 · 图示为常用演奏区）","caption_en":"Wavetable synth range (the PPG Wave's five-octave keyboard · wavetable position pushed by modulation · common region shown)","note":"波表合成器属电鸣乐器（波表扫描 + 模拟滤波的 hybrid）。PPG Wave：五八度键盘；每振荡器扫过一张波表（单周期波形序列，PPG 360 为 30 表×64 波形），位置由包络/LFO/触后等调制推动——音色随时间演化；插值避免相邻波形跳变；数字振荡经模拟 24dB/oct VCF 收口。矢量合成（Prophet VS）为隔壁方法：四声源按坐标平面摇杆混音。实用演奏区以 C1–C8 示意。记谱即实音。"}
```

```audiolab
{"type":"instrument","gm":"Pad 5 (bowed)","synth":"bowed","phrase":["C3","G3","C4","E4","G4","B4","C5"],"label":"演化的 pad：一个音里走过美术馆（借弓弦 pad 近似）","label_en":"The evolving pad — a gallery walked in one note (a bowed pad stands in)","hint":"波表的招牌是「一个持续音里音色不断演化」——这条 GM Pad 5 采样取其「弓弦般流动」的一面。真实波表合成的两样特征这里听不出来：一是波表位置的推动（LFO/包络让柔→亮→金属→攻击→空气在按住不放时发生）；二是 hybrid 的收口——数字振荡要过模拟滤波才不刺。","hint_en":"Wavetable's signature is the sustained note whose timbre keeps evolving — this GM Pad 5 takes its bowed-flowing side. Two things are absent: the wavetable position being pushed（LFO/envelope making soft→bright→metallic→aggressive→airy while you hold）, and the hybrid close — digital oscillators passing through analog filters to lose the刺."}
```
:::

::: en
The previous page's sampler recorded the world — this page's instrument says: don't record,
let the sound grow.

> 「**Subtractive synthesis changes the sound after it's created. Wavetable synthesis changes
> the sound as it's being created.**」

⭐⭐ **This page is wavetable synthesis — third of the digital-synth family. One line: sound
evolves before it sounds.**

| Class | Assignment |
|---|---|
| **HS class** | **Electrophone**（wavetable scanning + analog filtering — hybrid）· **digital oscillators, analog close** |
| **Origin** | ⭐⭐ **MUSIC-II（1958 · Max Mathews, software）** → **PPG Wavecomputer 360（1978 · failed without filters）** → **PPG Wave series（1981–87 · hybrid victory）** → **Waldorf carried on** |
| **Two metaphors** | ⭐⭐ **「subtractive = carving one marble · FM = two sculptors editing each other · wavetable = walking through an entire gallery」** |
| **Bayin note** | Outside the bayin — **timbre as a corridor, not a room, for the first time** |

## ⭐⭐ The main line: three synthesis methods, three senses of space

> 「**Subtractive synthesis: Carving one block of marble.
> FM: Two sculptors changing each other's work.
> Wavetable: Walking through an entire art gallery.**」

⭐⭐ **One of the loveliest analogies on the site — three methods in one breath**:

| Method | Space | One line |
|---|---|---|
| **Subtractive** | **one marble block** | carving from a harmonic-rich wave |
| **FM** | **two sculptors editing** | operators modulating each other |
| ⭐⭐ **Wavetable** | **an entire gallery** | strolling among hundreds of waveforms |

⭐⭐ **「减法合成在声音被创造后改变它；波表合成在声音被创造时就改变它」—**
**wavetable's evolution happens 「before sounding」, the fundamental difference from every
earlier method.**

## ⭐⭐ The principle: a book metaphor

> 「**想象一本书，每一页都有不同的波形。慢慢翻页，声音不变；快速翻页或跳页，声音就变**」.

⭐⭐ **Technically**: 「**波表合成在存储器中存储一序列单周期波形，让演奏者或调制系统步进
它们**」; 「**动态频谱移动通过扫描波形实现，用插值避免相邻波形间的明显跳变**」—
⭐ **interpolation is the technical name for 「walking without stumbling」: pages glide, not
jump.**

## ⭐⭐ Wavetable modulation: motion creates emotion

> 「**几乎任何东西都能推动波表位置：LFO · 包络 · 力度 · 触后 · 弯音轮 · automation**」;
> 「**想象按住一个钢琴键……音色慢慢从：柔 → 亮 → 金属 → 攻击 → 空气——全部来自一个持续音**」.

⭐⭐ **「运动创造情感。不再有静态声音——你得到的是演化的声音」**—
**much of modern EDM's sound leans on wavetable movement.**

⭐⭐ **The folk mirror**: 《哪得泥鳅变成龙》 — **a loach becoming a dragon within one sustained
note — the audible version of wavetable position moving.**

## ⭐⭐ Software ran twenty years ahead of hardware

> 「**波表合成首次用于 MUSIC-II——Max Vernon Mathews 1958 年开发的音色设计程序**」.

⭐⭐ **Against the site's 「lab before stage」 pattern**: **FM in a university（Chowning）·
sampling in a radio station（El-Dabh）· wavetable in a Bell-Labs-style program（Mathews）—**
⭐⭐ **every breakthrough in electronic instruments happened first 「where there were no
instruments」.**

## ⭐⭐ The Wavecomputer 360: the lesson of no filter

> 「Palm 的努力产生了 **Wavecomputer 360（1978）——30 张不同波表，每张 64 个波形**」;
> 「**滤波器的缺席使 360 听起来 buzz 又薄——这削弱了它最初商业可行性**」.

⭐⭐ **Against the Minimoog（pre-wiring for ease）and the ARP（pre-wired + overridable）—**
**the Wavecomputer's lesson was 「pure digital is too刺」:**
⭐⭐ **wavetable's evolution needed an analog filter to 「close」 it.**

## ⭐⭐ The PPG Wave series: the hybrid victory

> 「**Wave 系列是前身的进化：数字声音引擎 + 模拟 VCA 与 24dB/oct VCF**」;
> 「**Wave 2（1981）→ Wave 2.2（1982 · twin modulation wheels）→ Wave 2.3（1984 · 8-part
> multitimbral）**」;
> 「**控制面板皆以独特的超群蓝 RAL 5002 着色**」.

⭐⭐ **「数字振荡 + 模拟滤波」— the mirror of the Prophet-5（analog voice + digital control）:**
**the Prophet was 「analog sound + digital memory」; the PPG was 「digital oscillation + analog
close」—**
**two ways of assembling old and new.**

## ⭐⭐ The PPG Wave System: assembling against the Fairlight

> 「**可连 PRK 智能键盘 · EVU 8 音扩展 · Waveterm A/B 波计算机——用于采样、音频操作、
> 编辑、音序与创建用户自定义波表**」;
> 「**这套组合意在与更贵的 Fairlight CMI 竞争**」.

⭐⭐ **Against the samplers page**: **the Fairlight was one expensive machine; the PPG was an
assemblable middle-class setup —**
**two democratisation roads of the same era.**（**And like the Fairlight: PPG closed in
1987.**）

## ⭐⭐ The player lineage: half the wall of synth-pop

> 「**a-ha · Bowie · Depeche Mode · Gary Numan · Jarre · Art of Noise · Rush ·
> Tangerine Dream · Tears for Fears · Dolby · Ultravox · Stevie Wonder · Trevor Horn**……」

⭐⭐ **Half the wall of synth-pop and the Berlin School is on that list —**
**wavetable's 「evolving texture」 was exactly the 「future-feel」 the decade wanted.**

## ⭐⭐ Vector synthesis: the neighbour's method（and a talent migration）

> 「**矢量合成由 Sequential 以 Prophet VS 引入——把不同音色分配到正方形四角，
> 用摇杆直观混合——声音可用坐标平面上的一个点表示**」.

⭐⭐ **The difference**: 「**矢量基于坐标平面位置算四声源的音量平衡；
波表在单个波形周期内算不同波形的振幅比**」—
**one is 「push-pull between four corners of a room」; the other is 「a stroll through a
gallery」.**

⭐⭐ **The talent line**: 「**后来 Sequential 被 Yamaha 收购，开发团队转投 Korg——
于是有了 Yamaha SY22 与 Korg Wavestation**」—
**against the Prophet-5 company history: people leave, methods follow.**

## ⭐⭐ Waldorf carried on, and the modern revival

> 「**PPG 1987 年关闭，但波表原理通过 Waldorf Microwave 家族与大量现代软件合成器延续
> （部分与 Palm 本人合作开发）**」;
> 「**Waldorf Wave——今天被视为有史以来最受追捧的合成器之一**」;
> 「**没有 PPG 与 Waldorf，现代波表合成可能不存在**」.

⭐⭐ **Today**: 「**Xfer Serum 可能是世界上最流行的波表合成器 · Ableton Wavetable ·
免费 Vital**」—
**nearly every modern genre — EDM · Dubstep · Cinematic · Synthwave — wherever you hear evolving
digital textures, wavetable synthesis is likely involved.**

## Recap: three sentences on wavetable synthesis

| Q | A |
|---|---|
| ⭐ The key point | ⭐⭐ **sound evolves before it sounds** — 「**减法在创造后改变声音；波表在创造时就改变声音**」; ⭐⭐ **「walking through an entire gallery」** |
| ⭐⭐ The principle | **a sequence of single-cycle waveforms stored and scanned**; 「**插值避免相邻波形间明显跳变**」 — ⭐ **interpolation = walking without stumbling** |
| ⭐⭐ Modulation | ⭐⭐ **「运动创造情感」** — LFO/envelope/velocity/aftertouch push the position: **柔→亮→金属→攻击→空气 within one sustained note** |
| ⭐⭐ Software first | ⭐⭐ **MUSIC-II（1958 · Mathews）predated hardware by twenty years** — **breakthroughs happen first where there are no instruments** |
| ⭐⭐ The 360 lesson | **Wavecomputer 360（1978）had no filter → buzz and thin** — ⭐⭐ **wavetable evolution needed an analog filter to close it** |
| ⭐⭐ Hybrid | **Wave series = digital oscillators + analog VCF/VCA** — **the mirror of the Prophet-5: analog sound + digital memory vs digital sound + analog close** |
| ⭐⭐ vs Fairlight | **the PPG Wave System（PRK+EVU+Waveterm）** — **an assemblable middle-class setup vs one expensive machine**（both closed in 1987） |
| ⭐⭐ Vector synthesis | **the Prophet VS's joystick four-corner mixing** — 「**房间四角的推拉** vs **画廊漫步**」; **Sequential→Yamaha/Korg: people leave, methods follow** |
| ⭐⭐ Waldorf | **Microwave · Wave · Blofeld** — 「**没有 PPG 与 Waldorf，现代波表合成可能不存在**」 |
| ⭐ Today | **Serum · Ableton Wavetable · Vital（free）** — **the source of EDM/Trap/Cinematic evolving textures** |
| HS | **Electrophone**（wavetable scanning + analog filtering hybrid） |

**Subtractive sound is carved; FM sound is computed; wavetable sound is walked.**

⭐⭐ **Wavetable gave timbre a fourth dimension — 「length」 in time:**

**a note is no longer a point, but a corridor.**

```svg
<svg viewBox="0 0 640 380" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Wavetable synthesis as a gallery walk: a row of waveform frames — each a different single-cycle shape — scanned with interpolation so pages glide rather than jump; subtractive carves one marble block, FM is two sculptors editing each other, wavetable walks through an entire gallery; the PPG Wave paired digital oscillators with analog filters after the Wavecomputer 360's filterless failure">
  <g font-family="system-ui,sans-serif" font-size="11.5" fill="#A9A49B">
    <text x="20" y="22">波表合成 · 走过一整座美术馆</text>
    <text x="20" y="44" font-size="11" fill="#6E6A64">减法=雕一块大理石 · FM=两个雕塑家互改 · 波表=画廊漫步</text>
  </g>

  <rect x="30" y="62" width="580" height="96" rx="8" fill="#26241F" stroke="#9C7A3C" stroke-width="1.3"/>
  <g fill="none" stroke="#97C459" stroke-width="1.4">
    <path d="M56,110 Q66,90 76,110 T96,110"/>
    <path d="M126,110 Q136,100 146,110 L166,110"/>
    <path d="M196,110 L216,110 L216,90 L236,90 L236,110 L256,110"/>
    <path d="M286,96 L306,124 L326,96 L346,124"/>
    <path d="M376,110 Q396,86 416,110 T456,110"/>
    <path d="M486,110 L506,92 L526,110 L546,92 L566,110"/>
    <path d="M576,110 Q584,100 592,110"/>
  </g>
  <g fill="#E8C547">
    <circle cx="76" cy="110" r="4"/><circle cx="156" cy="110" r="4"/><circle cx="236" cy="110" r="4"/>
    <circle cx="316" cy="110" r="4"/><circle cx="416" cy="110" r="4"/><circle cx="506" cy="110" r="4"/>
    <circle cx="576" cy="110" r="4"/>
  </g>
  <text x="320" y="146" text-anchor="middle" font-size="9" fill="#6E6A64">波表 = 一排单周期波形 · 时钟/包络/LFO 推动「位置」 · 插值让翻页不跳变</text>

  <text x="20" y="180" font-size="10.5" fill="#E8C547">⭐ 「减法在创造后改变声音；波表在创造时就改变声音」—— 音色的第四维：时间上的「长」</text>
  <text x="20" y="202" font-size="10" fill="#A9A49B">按住一个键：柔 → 亮 → 金属 → 攻击 → 空气 —— 全部来自一个持续音（「运动创造情感」）</text>

  <rect x="30" y="214" width="286" height="56" rx="8" fill="none" stroke="#F0997B" stroke-width="1.2"/>
  <text x="173" y="234" text-anchor="middle" font-size="9.5" fill="#F0997B">Wavecomputer 360（1978）的教训</text>
  <text x="48" y="254" font-size="9" fill="#6E6A64">30 波表 × 64 波形 · 但无滤波 → buzz 又薄</text>
  <text x="48" y="264" font-size="9" fill="#97C459">⭐ 波表的「演化」需要模拟滤波来收口</text>

  <rect x="324" y="214" width="286" height="56" rx="8" fill="none" stroke="#97C459" stroke-width="1.2"/>
  <text x="467" y="234" text-anchor="middle" font-size="9.5" fill="#97C459">PPG Wave（1981–87）：hybrid 胜利</text>
  <text x="342" y="254" font-size="9" fill="#6E6A64">数字振荡 + 模拟 VCF/VCA · 超群蓝面板</text>
  <text x="342" y="264" font-size="9" fill="#97C459">Prophet 的镜像：数字声+模拟口</text>

  <text x="20" y="296" font-size="10.5" fill="#E8C547">⭐ 软件先行：MUSIC-II（1958 · Mathews）早于硬件二十年 —— 突破先在「没有乐器的地方」发生</text>
  <text x="20" y="316" font-size="10" fill="#A9A49B">⭐ 矢量合成是隔壁：VS 摇杆四角混音 = 房间推拉；波表 = 画廊漫步 —— Sequential 团队后来去了 Korg</text>

  <g font-family="system-ui,sans-serif" font-size="10.5" fill="#A9A49B">
    <text x="20" y="344" fill="#E8C547">⭐ PPG 1987 关闭 → Waldorf 续命 → Serum/Ableton/Vital：现代 EDM 的演化质感之源</text>
    <text x="20" y="364" fill="#6E6A64">⚠️ 示意图：按文字描述绘制，非实物比例。</text>
  </g>
</svg>
```

```range
{"range":"C1–C8","common":"C2–C5","caption":"波表合成器的音域（PPG Wave 五八度键盘 · 波表位置由调制推动 · 图示为常用演奏区）","caption_en":"Wavetable synth range (the PPG Wave's five-octave keyboard · wavetable position pushed by modulation · common region shown)","note":"波表合成器属电鸣乐器（波表扫描 + 模拟滤波的 hybrid）。PPG Wave：五八度键盘；每振荡器扫过一张波表（单周期波形序列，PPG 360 为 30 表×64 波形），位置由包络/LFO/触后等调制推动——音色随时间演化；插值避免相邻波形跳变；数字振荡经模拟 24dB/oct VCF 收口。矢量合成（Prophet VS）为隔壁方法：四声源按坐标平面摇杆混音。实用演奏区以 C1–C8 示意。记谱即实音。"}
```

```audiolab
{"type":"instrument","gm":"Pad 5 (bowed)","synth":"bowed","phrase":["C3","G3","C4","E4","G4","B4","C5"],"label":"演化的 pad：一个音里走过美术馆（借弓弦 pad 近似）","label_en":"The evolving pad — a gallery walked in one note (a bowed pad stands in)","hint":"波表的招牌是「一个持续音里音色不断演化」——这条 GM Pad 5 采样取其「弓弦般流动」的一面。真实波表合成的两样特征这里听不出来：一是波表位置的推动（LFO/包络让柔→亮→金属→攻击→空气在按住不放时发生）；二是 hybrid 的收口——数字振荡要过模拟滤波才不刺。","hint_en":"Wavetable's signature is the sustained note whose timbre keeps evolving — this GM Pad 5 takes its bowed-flowing side. Two things are absent: the wavetable position being pushed（LFO/envelope making soft→bright→metallic→aggressive→airy while you hold）, and the hybrid close — digital oscillators passing through analog filters to lose the刺."}
```
:::