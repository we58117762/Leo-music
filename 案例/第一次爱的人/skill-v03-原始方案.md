# 第一次爱的人｜leo 翻唱制作方案

版本：v03
父版本：v02
状态：待试听
制作日期：2026-10-30（Asia/Shanghai）
原唱与参考版本：王心凌／专辑收录版／爱你
原始歌词：[source.lrc](source.lrc)
制作方式：Cover 翻唱
模型：v6（账号提供时；适用条件见参数表）

## 歌手档案快照

- ID：leo-male-01；档案名：Leo Male 01；本任务称呼：leo。
- 性别/年龄感：男声、青年；音色：自然、清澈、温暖。
- 音质：自然、有适度厚度，不刻意制造沙哑；舒适音区：中音区，未设未经测量的数值音域。
- 语言与咬字：普通话清晰自然；档案固定演唱倾向：无；参考声音：无。
- 长期约束：避免挤压、尖锐和刻意做作。本曲唱法另列，不写回长期档案。
- 本项目首次初始化采用技能内置种子；档案描述是音色目标，不能保证每次生成的声线完全一致。

角色映射：全部演唱段落由 leo 担任；少量背景叠唱如有需要也保持同一男声音色，不新增第二位歌手。

本次网页 Voice：鑫 温's voice（用户指定）；对应 https://suno.com/voice/fc60246a-a934-4cfd-858e-36af416fbca6 。上述 leo 档案沿用为音色与唱法目标。

## 用户偏好与翻唱设计

用户要求：每首分析并依技能归档；没有额外偏好，全部按推荐直接生成；歌手使用 leo。

授权内采用的推荐：**清亮而带遗憾的原声流行，保存初恋记忆的叙事**。默认忠实于指定参考版本的旋律、歌词和主要气质，不作大幅风格迁移；原版多人作品在本次统一改为 leo 独唱。

保留依据：爱贝克思官方频道提供王心凌《第一次爱的人》MV；本地元数据为《爱你》，LRC 列林怡芬作词及 Marion Elise Ravn、Marit Elizabeth Larsen 作曲。参考的是现有中文歌词版本，英文钩子原样保留。 来源：[爱贝克思官方：王心凌《第一次愛的人》](https://www.youtube.com/watch?v=6j5fLo2c9IY)（2026-10-30）。本地参考时长 03:53；身份与署名来自元数据和 LRC。未进行音频试听，因此下述是可执行建议，不是听感实测。

编曲调整：建议木吉他与清亮键盘维持轻盈流行骨架，贝斯、轻鼓保持向前；副歌加一点温度而不改成厚重慢板，尾段新叙事逐步减去鼓的存在感。

本曲演唱：leo 以青年男声讲述第一次分离，短句清楚，长句自然连贯；the day you went away 轻连而不夸张转音。末段以回望代替宣誓，歌词代词不因男声改变。

避免项：本曲无额外硬性排除；用正向 Style 表达推荐方向，Exclude 留空。

文本/版本注意：原词包含他的坏他的好，按源保留；本版不改为男声视角的新歌词。

| 源稿约起点 | 本版标签 | 推进意图 |
|---|---|---|
| 00:00 | Verse 1 | 初次分离的感受 |
| 00:40 | Pre-Chorus | 爱与失去的判断 |
| 00:51 | Chorus | 中文旋律与英文钩子 |
| 01:23 | Verse 2 | 鞋与手链的具体记忆 |
| 01:43 | Pre-Chorus | 再次回到失去 |
| 01:54 | Chorus | 熟悉记忆展开 |
| 02:29 | Pre-Chorus | 最后一次铺垫 |
| 02:40 | Chorus | 完整重复 |
| 03:00 | Outro | 有一天之后的新叙事 |

以上时间仅作为阅读 LRC 的定位辅助，不代表生成时能精确锁定时点。详细证据分层与清理记录见 [research.md](research.md)。

## Suno 输入

### Lyrics
本版按用户要求将汉字转为带声调汉语拼音；英文歌词、段落标签、行序、重复次数保持不变。汉字原词见 v02 与 source.lrc。
<!-- suno:lyrics -->
```text
[Verse 1]
huī sè de tiān
nǐ de liǎn
ài guò yě kū guò xiào guò tòng guò zhī hòu
zhǐ shèng zài jiàn
wǒ de yǎn lèi
shī le liǎn
shī qù dì yī cì ài de rén jìng rán shì
zhè zhǒng gǎn jué

[Pre-Chorus]
zǒng yǐ wéi
ài shì quán bù de xīn tiào
shī qù ài wǒ men jiù yào
jiù yào
yì diǎn diǎn màn màn de sǐ diào

[Chorus]
dāng wǒ
shī qù nǐ nà yī miǎo
xīn tū rán jiù biàn lǎo
the day you went away
xuān nào de jiē
méi fā xiàn wǒ de lèi
bèi yí wàng zài jiē jiǎo
the day you went away

[Verse 2]
wǒ kàn zhe nǐ
zǒu guò jiē
hái chuān zhe qù nián xià tiān wǒ sòng nǐ de nà shuāng qiú xié
yín sè shǒu liàn
hái yào yǎn
nǐ de shì jiè sì hū yì diǎn yě méi yǒu yīn cǐ gǎi biàn

[Pre-Chorus]
zǒng yǐ wéi
ài shì quán bù de xīn tiào
shī qù ài wǒ men jiù yào
jiù yào
yì diǎn diǎn màn màn de sǐ diào

[Chorus]
dāng wǒ
shī qù nǐ nà yī miǎo
xīn tū rán jiù biàn lǎo
the day you went away
xuān nào de jiē
méi fā xiàn wǒ de lèi
bèi yí wàng zài jiē jiǎo
the day you went away

[Pre-Chorus]
zǒng yǐ wéi
ài shì quán bù de xīn tiào
shī qù ài wǒ men jiù yào
jiù yào
yì diǎn diǎn màn màn de sǐ diào

[Chorus]
dāng wǒ
shī qù nǐ nà yī miǎo
xīn tū rán jiù biàn lǎo
the day you went away
xuān nào de jiē
méi fā xiàn wǒ de lèi
bèi yí wàng zài jiē jiǎo
the day you went away

[Outro]
yǒu yī tiān
yě xǔ wǒ néng bǎ zì jǐ zhì hǎo
zài yí cì xiǎng qǐ lái
yīng gāi yào zěn me xiào
dì yī cì ài de rén tā de huài tā de hǎo
què xiàng xiōng kǒu cì qīng
shì yǒng yuǎn de jì hào
gēn zhe wǒ de hū xī
zhí dào tíng zhǐ xīn tiào
```

### Style of Music
Style 字符数：627
<!-- suno:style -->
```text
Clear, bittersweet Mandarin acoustic pop with lightly strummed guitar, bright but soft keyboards, rounded bass and a gentle forward pulse. One young adult male lead with a natural, clear, warm voice, moderate body and lucid Mandarin diction. Keep the short verses direct and the longer lines connected in a comfortable middle register. Sing the recurring English hook smoothly with restrained ornamentation. Open the choruses through warmth rather than weight. Preserve the Chinese lyric version, its pronouns, every repeated hook and the distinct final narrative passage. Ease the accompaniment beneath the closing reflection.
```

### Exclude
留空，不将“无”或“None”粘入。
<!-- suno:exclude -->
```text

```

### 参数

经验预设：还原原曲风格 v1。来源：用户于 2026-10-30 确认的制作经验。下表为本版实际参数快照，供首轮直接照填。Style Influence 和 Audio Influence 均取经验范围 80%～85% 的默认起点 80%。

| 参数 | 建议值/适用状态 | 本曲依据 |
|---|---|---|
| 模型/制作方式 | v6（账号提供时）／Cover 翻唱 | 采用已经明确的本曲方向：清亮而带遗憾的原声流行，保存初恋记忆的叙事；优先稳定执行。v6 官方注明面向 Pro/Premier；其他账号以实际可选模型为准。 |
| Vocal Gender | Male（界面提供时） | 使用 leo 的青年男声档案；具体音色在 Style 描述。 |
| Weirdness | 20% | 采用用户“还原原曲风格 v1”经验预设，固定 20% 作为稳定制作的首轮起点。 |
| Style Influence | 80% | 采用经验范围 80%～85% 的默认起点 80%，执行本曲已确认的 Style。让模型执行本版的核心处理：建议木吉他与清亮键盘维持轻盈流行骨架，贝斯、轻鼓保持向前；该参数控制文本风格贴合，不代表旋律相似度。 |
| Variety | Off（关闭；数值界面设为 0） | 采用默认预设关闭变化，稳定执行本曲已确认的提示词。 |
| Audio Influence | 80% | 采用经验范围 80%～85% 的默认起点 80%。保留专辑收录版的旋律轮廓和段落，主要改变为本次声音与编曲设计。 |
| Max Mode | On（开启） | 采用默认预设开启，以还原原曲风格及保持本曲声音、风格和段落连贯为目标。 |

本版数值来源于用户经验预设，尚待本曲试听验证。模型和控件是否可用以实际界面为准；上述建议值不因尚未查看账号界面而省略。

控件含义沿用 v01 的资料记录（2026-10-30）；本次仅按用户经验修订制作参数，未重新联网核实产品信息。

## 质量检查

本次 v03 为汉语拼音输入版。以 v02 的 Lyrics 为唯一转换底稿，逐行检查汉字数与拼音音节数、段落标签、行序及重复次数；英文词和标点保留。拼音 Lyrics 共 1466 字符，未超过当前网页 5000 字符上限；不含残留汉字。已人工复核多音字和助词，包括“两行”“用尽”“恋曲”“落下”“长发”“呜咽”“吞没”等。

Style、Exclude 与 v02 逐块一致，Style 共 627 字符，低于 1000 上限。参数沿用：Max Mode On；Weirdness 20%；Style Influence 80%；Audio Influence 80%；Variety Off。原始 source.lrc、v01、v02 保持不变。

原词逐字相等的旧检查不适用于拼音版，本次没有把该检查结果冒称为 v03 通过；改用上述转换对应检查。尚未试听拼音版，实际普通话发音与音乐效果以生成结果为准。

## 试听反馈与修订

2026-10-30：用户取消重新填词，要求将此前 12 首提交未确认歌曲中除《月光》外的 11 首转为汉语拼音，并以新制作稿重新生成。本曲按要求更新 Lyrics，英文部分保留；声音、Style、Exclude、编曲方向及参数沿用。未采用未完成的改写歌词。

待试听。首轮重点：英文钩子连贯；短句不机械断开；最后新叙事不能被自动替换成副歌。

后续修订另存 cover-v04.md；保留当前 v03 与早期汉字版本。提交结果另见批次报告。