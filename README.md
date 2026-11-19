<picture>
  <source media="(prefers-color-scheme: dark) and (max-width: 600px)" srcset="readme-assets/em-door-dark-narrow.svg">
  <source media="(max-width: 600px)" srcset="readme-assets/em-door-light-narrow.svg">
  <source media="(prefers-color-scheme: dark)" srcset="readme-assets/em-door-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="readme-assets/em-door-light.svg">
  <img alt="铭哥 · Eric Mingle" src="readme-assets/em-door-light.svg" width="100%">
</picture>

<p align="center">
  <a href="README.md">简体中文</a> · <a href="README.en.md">English</a> · <a href="PERSONAL-NOTICE.md"><picture><source media="(prefers-color-scheme: dark)" srcset="readme-assets/em-logo-dark.svg"><img src="readme-assets/em-logo-light.svg" alt="EM" height="12"></picture> EricMingle69</a>
</p>

基于人因工程做研究和优化，想把人从不必要的负担里解放出来。

我在工厂做过质量。同一份工作要写成日报、周报、月报三遍，检验文件一翻译表格就乱。嫌烦，就自己写了小工具，把这些交给电脑。

后来做什么都差不多是这个路子：看人在哪里多花了注意力、脑力、钱和时间，弄清楚为什么，改掉，再回到现实里验一遍。验过了才算做完。

## 01　空调能不能提前开，周末还要强制断电吗？

厂区宿舍有条规定：一到上班时间就断电，周六周日也一样，到了休息时间才能再开。我想让他们取消这条规定。光说热没人听，只好去算：按上下班提前开机预冷、周末不断电，比到点强制断电到底多用多少电。

说实话挺无奈的。想吹上空调，得先做一个研究。

<a href="https://github.com/Ming-Sir-69/AC-AlwaysOn-vs-TimerOff-Energy-Comparison">
  <picture>
    <source media="(prefers-color-scheme: dark) and (max-width: 600px)" srcset="readme-assets/cards/ac-energy-dark-mobile.svg">
    <source media="(max-width: 600px)" srcset="readme-assets/cards/ac-energy-light-mobile.svg">
    <source media="(prefers-color-scheme: dark)" srcset="readme-assets/cards/ac-energy-dark.svg">
    <img src="readme-assets/cards/ac-energy-light.svg" alt="空调研究：按上下班提前预冷、休息日不断电，比现行强制断电一季多用约 82 kWh（定频，5–95% 情景 51–160）；下班到家室温约从 85°F 降到 80°F，休息日在室最高约从 91°F 降到 83°F。" width="100%">
  </picture>
</a>

## 02　和 AI 一起干活

我一直在改自己和 AI 协作的方式，改到哪写到哪。

**02.1**　以前我让它把我的每次纠正都记下来，想找出反复纠正背后的共同原因，做成了 Astra Harness。后来发现不用另外记，提交、对话、评审意见本来就留着，直接从这些里面找就行。找到以后一次只改一处，过几天回头看还犯不犯。

比如最近发现，好几次返工是同一个原因：任务只写了怎么做，没写给谁用、不做什么。

<a href="https://github.com/Ming-Sir-69/astra-harness">
  <picture>
    <source media="(prefers-color-scheme: dark) and (max-width: 600px)" srcset="readme-assets/cards/astra-harness-dark-mobile.svg">
    <source media="(max-width: 600px)" srcset="readme-assets/cards/astra-harness-light-mobile.svg">
    <source media="(prefers-color-scheme: dark)" srcset="readme-assets/cards/astra-harness-dark.svg">
    <img src="readme-assets/cards/astra-harness-light.svg" alt="Astra Harness：和 AI 一起干活的工作流分享。汇集已有痕迹，归并共同原因，对照做得好的做法，一次只改一处，回头看是否再犯。" width="100%">
  </picture>
</a>

<p>&nbsp;</p>

**02.2**　Engram 是这套做法底下的知识库。同一件事，我不想对 AI 交代第二遍。

<a href="https://github.com/Ming-Sir-69/engram">
  <picture>
    <source media="(prefers-color-scheme: dark) and (max-width: 600px)" srcset="readme-assets/cards/engram-dark-mobile.svg">
    <source media="(max-width: 600px)" srcset="readme-assets/cards/engram-light-mobile.svg">
    <source media="(prefers-color-scheme: dark)" srcset="readme-assets/cards/engram-dark.svg">
    <img src="readme-assets/cards/engram-light.svg" alt="Engram：多个 AI 共用的本地记忆库。写入时生成向量、自动连上相近的记忆；纠正带来源取代旧版本，过时的记忆归档遗忘；空闲时自己整理。" width="100%">
  </picture>
</a>

<p>&nbsp;</p>

**02.3**　这些工具都要更新，我给它们写了一个统一的更新模块 upall：先检查，再更新，要不要更新由你按下决定。

<a href="https://github.com/Ming-Sir-69/upall">
  <picture>
    <source media="(prefers-color-scheme: dark) and (max-width: 600px)" srcset="readme-assets/cards/upall-dark-mobile.svg">
    <source media="(max-width: 600px)" srcset="readme-assets/cards/upall-light-mobile.svg">
    <source media="(prefers-color-scheme: dark)" srcset="readme-assets/cards/upall-dark.svg">
    <img src="readme-assets/cards/upall-light.svg" alt="upall：一个命令检查并更新整套 AI 工具：编程 CLI、Agent、Skill、MCP、平台与应用。先自动检查，按 Space 更新，按 Enter 退出。" width="100%">
  </picture>
</a>

## 03　更早

课程设计和毕业设计，当时都是当真做的。

**03.1**　毕业设计

<a href="https://github.com/Ming-Sir-69/Ming-Sir-69-Human-Factors-Simulation-System-for-Graduation-Project">
  <picture>
    <source media="(prefers-color-scheme: dark) and (max-width: 600px)" srcset="readme-assets/cards/human-factors-dark-mobile.svg">
    <source media="(max-width: 600px)" srcset="readme-assets/cards/human-factors-light-mobile.svg">
    <source media="(prefers-color-scheme: dark)" srcset="readme-assets/cards/human-factors-dark.svg">
    <img src="readme-assets/cards/human-factors-light.svg" alt="行李箱的人因优化：毕业设计，基于人因工程的结构设计优化。方法：问卷、聚类、AnyBody 人体仿真、正交实验、层次分析。" width="100%">
  </picture>
</a>

<p>&nbsp;</p>

**03.2**　课程设计与建模

<a href="https://github.com/Ming-Sir-69/Human-Factors-Engineering-Project">
  <picture>
    <source media="(prefers-color-scheme: dark) and (max-width: 600px)" srcset="readme-assets/cards/3d-modeling-dark-mobile.svg">
    <source media="(max-width: 600px)" srcset="readme-assets/cards/3d-modeling-light-mobile.svg">
    <source media="(prefers-color-scheme: dark)" srcset="readme-assets/cards/3d-modeling-dark.svg">
    <img src="readme-assets/cards/3d-modeling-light.svg" alt="3D 建模：用 Shapr3D 设计的肥皂盒。铅笔起稿、墨线、爆炸再合拢；滚轴把肥皂搓出泡沫，手不碰肥皂；用完挂在墙上沥水。" width="100%">
  </picture>
</a>

## 04　更多公开项目

有些项目从日常麻烦出发，有些是早期做的实验。按用途放在这里，方便直接找到。

- [Read Everything v3](https://github.com/Ming-Sir-69/read-everything-v3)：把文档、图片、录音和视频音轨转成 Markdown，存到原文件旁边。
- [Fucairserver](https://github.com/Ming-Sir-69/Fucairserver)：让 Windows 接收 AirPlay 画面和声音；当前主分支还加入了 Mac 跨屏键鼠控制。
- [Expert Process](https://github.com/Ming-Sir-69/expert-process)：给 AI 协作准备的工作方法，普通任务少建档，需要人为决定时停下来等答复。
- [Edge 文献检索工具](https://github.com/Ming-Sir-69/Edge-Literature-Web-Crawler)：早期 Windows 原型，用 Edge 收集百度学术检索结果，按中文期刊、会议、英文期刊归类。
- [氢能供应链寻优](https://github.com/Ming-Sir-69/Hydrogen-Supply-Chain-SA-Firefly)：用离散模拟退火萤火虫算法比较制氢与运输组合的成本。

## 从贡献记录看

上面是我自己选的作品。下面是 GHFind 按公开 GitHub 数据生成的另一种视角；点开可以看它的评分维度和依据。

<a href="https://ghfind.com/u/ming-sir-69?ref=badge">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://ghfind.com/api/card/mini/ming-sir-69?variant=radar&amp;theme=dark&amp;lang=zh">
    <img src="https://ghfind.com/api/card/mini/ming-sir-69?variant=radar&amp;theme=light&amp;lang=zh" alt="GHFind · Ming-Sir-69 公开 GitHub 贡献雷达" width="440">
  </picture>
</a>

[直接查看 GHFind 详情](https://ghfind.com/u/ming-sir-69?ref=badge) · [浏览 GitHub 贡献记录](https://github.com/Ming-Sir-69#contributions)

## 交流

想聊人因、质量、工厂里的小工具，或者怎么和 AI 一起干活，都欢迎。项目问题请到对应仓库提 Issue 或 Pull Request。

保持好奇，动手验证，上了生活的贼船，就做快乐的海盗。🏴‍☠️

---

文档维护：<picture><source media="(prefers-color-scheme: dark)" srcset="readme-assets/em-logo-dark.svg"><img src="readme-assets/em-logo-light.svg" alt="EM" height="13"></picture> <b>EricMingle69</b> · <a href="https://github.com/Ming-Sir-69">Ming-Sir-69</a><br>
[个人标识、许可与权限说明](PERSONAL-NOTICE.md) 
