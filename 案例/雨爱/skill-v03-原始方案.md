# 雨爱｜leo 翻唱制作方案

版本：v03
父版本：v02
状态：待试听
制作日期：2026-10-30（Asia/Shanghai）
原唱与参考版本：杨丞琳／专辑收录版／雨爱
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

授权内采用的推荐：**有流动感的流行摇滚，雨滴意象与克制情绪并行**。默认忠实于指定参考版本的旋律、歌词和主要气质，不作大幅风格迁移；原版多人作品在本次统一改为 leo 独唱。

保留依据：杨丞琳官方频道的《雨爱》MV 发行说明标注 Sony Music 2010；本地文件对应《雨爱》专辑，LRC 列出吉他黄宣铭、贝斯方奎棠及和声制作。歌词以雨滴、室内湿气和最终彩虹组织情绪。 来源：[杨丞琳官方频道：雨愛](https://www.youtube.com/watch?v=oec9R5ypf-o)（2026-10-30）。本地参考时长 04:20；身份与署名来自元数据和 LRC。未进行音频试听，因此下述是可执行建议，不是听感实测。

编曲调整：建议清亮电吉他与钢琴短音型形成连续水滴般的流动，鼓贝斯在副歌加宽但不压平动态；第二段先收回，尾部保留源稿副歌后半的复唱，不加新的歌词段。

本曲演唱：leo 以清楚的中音叙述保持距离，进入听雨段时增加连贯性；较长句保持气流而不赶字。Rainie Love 照原词演唱，最后彩虹保持希望感，避免所有句尾都处理成哭腔。

避免项：本曲无额外硬性排除；用正向 Style 表达推荐方向，Exclude 留空。

文本/版本注意：片尾制作人员条目为元数据，应从可演唱 Lyrics 移除并在清理记录保留。

| 源稿约起点 | 本版标签 | 推进意图 |
|---|---|---|
| 00:00 | Verse 1 | 观察窗外天气 |
| 00:38 | Pre-Chorus | 安静抽离 |
| 00:50 | Chorus | 雨滴与记忆，长线旋律展开 |
| 02:04 | Verse 2 | 冷空气与距离 |
| 02:26 | Pre-Chorus | 再次学会放弃 |
| 02:41 | Chorus | 更清楚地表达想念 |
| 03:33 | Outro | 保留副歌后半复唱并向彩虹收束 |

以上时间仅作为阅读 LRC 的定位辅助，不代表生成时能精确锁定时点。详细证据分层与清理记录见 [research.md](research.md)。

## Suno 输入

### Lyrics
本版按用户要求将汉字转为带声调汉语拼音；英文歌词、段落标签、行序、重复次数保持不变。汉字原词见 v02 与 source.lrc。
<!-- suno:lyrics -->
```text
[Verse 1]
chuāng wài de tiān qì
jiù xiàng shì nǐ duō biàn de biǎo qíng
xià yǔ le yǔ péi wǒ kū qì
kàn bù qīng wǒ yě bù xiǎng kàn qīng

[Pre-Chorus]
lí kāi nǐ wǒ ān jìng de chōu lí
bù rěn jiē xiǎo de jù qíng
wǒ de lèi liú zài xīn lǐ
xué huì fàng qì

[Chorus]
tīng yǔ de shēng yīn yī dī dī qīng xī
nǐ de hū xī xiàng yǔ dī shèn rù wǒ de ài lǐ
zhēn xī wàng yǔ néng xià bù tíng
ràng xiǎng niàn jì xù ràng ài biàn tòu míng
wǒ ài shàng gěi wǒ yǒng qì de Rainie Love
chuāng wài de yǔ dī yī dī dī lěi jī
wū nèi de shī qì xiàng chǔ cún ài nǐ de jì yì
zhēn xī wàng yǔ néng xià bù tíng
yǔ ài de mì mì néng yì zhí yán xù
wǒ xiāng xìn wǒ jiāng huì kàn dào
cǎi hóng de měi lì

[Verse 2]
lěng lěng de kōng qì
hěn zhì xī wǒ wú fǎ hū xī
yī wàn kē yǔ dī de jù lí
hěn chè dǐ ràng ài xiāo shī wú xī

[Pre-Chorus]
lí kāi nǐ wǒ ān jìng de chōu lí
bù rěn jiē xiǎo de jù qíng
wǒ de lèi liú zài xīn lǐ
xué huì fàng qì

[Chorus]
tīng yǔ de shēng yīn yī dī dī qīng xī
nǐ de hū xī xiàng yǔ dī shèn rù wǒ de ài lǐ
zhēn xī wàng yǔ néng xià bù tíng
ràng xiǎng niàn jì xù ràng ài biàn tòu míng
wǒ ài shàng gěi wǒ yǒng qì de Rainie Love
chuāng wài de yǔ dī yī dī dī lěi jī
wū nèi de shī qì xiàng chǔ cún ài nǐ de jì yì
zhēn xī wàng yǔ néng xià bù tíng
yǔ ài de mì mì néng yì zhí yán xù
wǒ xiāng xìn wǒ jiāng huì kàn dào
cǎi hóng de měi lì

[Outro]
wū nèi de shī qì xiàng chǔ cún ài nǐ de jì yì
zhēn xī wàng yǔ néng xià bù tíng
yǔ ài de mì mì néng yì zhí yán xù
wǒ xiāng xìn wǒ jiāng huì kàn dào
cǎi hóng de měi lì
```

### Style of Music
Style 字符数：635
<!-- suno:style -->
```text
Flowing Mandarin pop-rock with clear electric guitar figures, lightly articulated piano, rounded bass and measured drums. One young adult male lead with a natural, clear, warm voice, moderate body and precise Mandarin diction. Keep the verses intimate and the long chorus lines connected, opening the resonance without strain in a comfortable male key. Let guitar and rhythm create motion while the vocal remains emotionally contained. Preserve the English phrase and every supplied repeat, including the partial final refrain. Build the second chorus through instrumental width, then let the final rainbow image carry restrained hope.
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
| 模型/制作方式 | v6（账号提供时）／Cover 翻唱 | 采用已经明确的本曲方向：有流动感的流行摇滚，雨滴意象与克制情绪并行；优先稳定执行。v6 官方注明面向 Pro/Premier；其他账号以实际可选模型为准。 |
| Vocal Gender | Male（界面提供时） | 使用 leo 的青年男声档案；具体音色在 Style 描述。 |
| Weirdness | 20% | 采用用户“还原原曲风格 v1”经验预设，固定 20% 作为稳定制作的首轮起点。 |
| Style Influence | 80% | 采用经验范围 80%～85% 的默认起点 80%，执行本曲已确认的 Style。让模型执行本版的核心处理：建议清亮电吉他与钢琴短音型形成连续水滴般的流动，鼓贝斯在副歌加宽但不压平动态；该参数控制文本风格贴合，不代表旋律相似度。 |
| Variety | Off（关闭；数值界面设为 0） | 采用默认预设关闭变化，稳定执行本曲已确认的提示词。 |
| Audio Influence | 80% | 采用经验范围 80%～85% 的默认起点 80%。保留专辑收录版的旋律轮廓和段落，主要改变为本次声音与编曲设计。 |
| Max Mode | On（开启） | 采用默认预设开启，以还原原曲风格及保持本曲声音、风格和段落连贯为目标。 |

本版数值来源于用户经验预设，尚待本曲试听验证。模型和控件是否可用以实际界面为准；上述建议值不因尚未查看账号界面而省略。

控件含义沿用 v01 的资料记录（2026-10-30）；本次仅按用户经验修订制作参数，未重新联网核实产品信息。

## 质量检查

本次 v03 为汉语拼音输入版。以 v02 的 Lyrics 为唯一转换底稿，逐行检查汉字数与拼音音节数、段落标签、行序及重复次数；英文词和标点保留。拼音 Lyrics 共 1478 字符，未超过当前网页 5000 字符上限；不含残留汉字。已人工复核多音字和助词，包括“两行”“用尽”“恋曲”“落下”“长发”“呜咽”“吞没”等。

Style、Exclude 与 v02 逐块一致，Style 共 635 字符，低于 1000 上限。参数沿用：Max Mode On；Weirdness 20%；Style Influence 80%；Audio Influence 80%；Variety Off。原始 source.lrc、v01、v02 保持不变。

原词逐字相等的旧检查不适用于拼音版，本次没有把该检查结果冒称为 v03 通过；改用上述转换对应检查。尚未试听拼音版，实际普通话发音与音乐效果以生成结果为准。

## 试听反馈与修订

2026-10-30：用户取消重新填词，要求将此前 12 首提交未确认歌曲中除《月光》外的 11 首转为汉语拼音，并以新制作稿重新生成。本曲按要求更新 Lyrics，英文部分保留；声音、Style、Exclude、编曲方向及参数沿用。未采用未完成的改写歌词。

待试听。首轮重点：长句是否连贯；Rainie Love 不改写；尾声部分复唱是否按原稿保留。

后续修订另存 cover-v04.md；保留当前 v03 与早期汉字版本。提交结果另见批次报告。
