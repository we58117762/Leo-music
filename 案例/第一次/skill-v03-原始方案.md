# 第一次｜leo 翻唱制作方案

版本：v03
父版本：v02
状态：待试听
制作日期：2026-10-30（Asia/Shanghai）
原唱与参考版本：光良／专辑收录版／第1次个人创作专辑
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

授权内采用的推荐：**清新原声流行，唱出第一次告白的忐忑**。默认忠实于指定参考版本的旋律、歌词和主要气质，不作大幅风格迁移；原版多人作品在本次统一改为 leo 独唱。

保留依据：滚石官方 MV 及音乐平台可确认光良的《第一次》；本地 LRC 明确列出钢琴、吉他、打击乐、贝斯与和声制作信息。 来源：[滚石唱片：光良《第一次》MV](https://www.youtube.com/watch?v=rFsn1tzhcHk)（2026-10-30）。本地参考时长 04:23；身份与署名来自元数据和 LRC。未进行音频试听，因此下述是可执行建议，不是听感实测。

编曲调整：沿用钢琴、木吉他、贝斯和轻打击乐的原声骨架；副歌用细小律动与少量同声叠唱增温，保留间奏的轻盈。

本曲演唱：leo 清晰、微带笑意地唱，短句有自然呼吸。哦字与第一次的重音轻弹，不做深沉苦情处理；桥段更近声，最后副歌才开放共鸣。

避免项：本曲无额外硬性排除；用正向 Style 表达推荐方向，Exclude 留空。

文本/版本注意：未发现需要额外改动的文本说明；实际演唱仍以用户 LRC 的文字和重复顺序为准。

| 源稿约起点 | 本版标签 | 推进意图 |
|---|---|---|
| 00:00 | Verse 1 | 害羞观察 |
| 00:51 | Chorus | 第一次告白 |
| 01:57 | Verse 2 | 再次鼓起勇气 |
| 02:22 | Chorus | 熟悉旋律回归 |
| 02:51 | Bridge | 确认归属 |
| 03:08 | Chorus | 温暖而完整地收束 |

以上时间仅作为阅读 LRC 的定位辅助，不代表生成时能精确锁定时点。详细证据分层与清理记录见 [research.md](research.md)。

## Suno 输入

### Lyrics
本版按用户要求将汉字转为带声调汉语拼音；英文歌词、段落标签、行序、重复次数保持不变。汉字原词见 v02 与 source.lrc。
<!-- suno:lyrics -->
```text
[Verse 1]
dāng nǐ kàn zhe wǒ
wǒ méi yǒu kāi kǒu yǐ bèi nǐ cāi tòu
hái shì méi bǎ wò
hái shì méi yǒu fú hé nǐ de yāo qiú
shì wǒ zì jǐ xiǎng de tài duō
hái shì nǐ yě zài shǎn duǒ
rú guǒ zhēn de xuǎn zé shì wǒ
wǒ gǔ qǐ yǒng qì qù jiē shòu
bù zhī bù jué ràng shì xiàn kāi shǐ shǎn shuò

[Chorus]
ō dì yī cì wǒ shuō ài nǐ de shí hòu
hū xī nán guò xīn bù tíng de chàn dǒu
ō dì yī cì wǒ qiān qǐ nǐ de shuāng shǒu
shī qù fāng xiàng bù zhī gāi wǎng nǎ ér zǒu
nà shì yì qǐ xiāng ài de lǐ yóu
nà shì yì qǐ sī shǒu
ō dì yī cì wěn nǐ shēn shēn de jiǔ wō
xiǎng yào qīng xǐng què chōng hūn le tóu
ō dì yī cì nǐ tǎng zài wǒ de xiōng kǒu
èr shí sì xiǎo shí méi yǒu fēn kāi guò
nà shì dì yī cì zhī dào tiān cháng dì jiǔ

[Verse 2]
shì wǒ zì jǐ xiǎng de tài duō
hái shì nǐ yě zài shǎn duǒ
rú guǒ zhēn de xuǎn zé shì wǒ
wǒ gǔ qǐ yǒng qì qù jiē shòu
bù zhī bù jué ràng shì xiàn kāi shǐ shǎn shuò

[Chorus]
ō dì yī cì wǒ shuō ài nǐ de shí hòu
hū xī nán guò xīn bù tíng de chàn dǒu
ō dì yī cì wǒ qiān qǐ nǐ de shuāng shǒu
shī qù fāng xiàng bù zhī gāi wǎng nǎ ér zǒu
nà shì yì qǐ xiāng ài de lǐ yóu duì wǒ

[Bridge]
gǎn jué nǐ shǔ yú wǒ
gǎn jué nǐ de yǎn móu
dì yī cì jiù jué dìng jué bú huì cuò

[Chorus]
ō dì yī cì wǒ shuō ài nǐ de shí hòu
hū xī nán guò xīn bù tíng de chàn dǒu
ō dì yī cì wǒ qiān qǐ nǐ de shuāng shǒu
shī qù fāng xiàng bù zhī gāi wǎng nǎ ér zǒu
nà shì yì qǐ xiāng ài de lǐ yóu
nà shì yì qǐ sī shǒu
ō dì yī cì wěn nǐ shēn shēn de jiǔ wō
xiǎng yào qīng xǐng què chōng hūn le tóu
ō dì yī cì nǐ tǎng zài wǒ de xiōng kǒu
èr shí sì xiǎo shí méi yǒu fēn kāi guò
nà shì dì yī cì zhī dào tiān cháng dì jiǔ
```

### Style of Music
Style 字符数：602
<!-- suno:style -->
```text
Fresh acoustic Mandopop with piano, lightly picked acoustic guitar, rounded bass and gentle percussion. Preserve the nervous joy of a first confession and the familiar melody. One young adult male lead: natural, clear, warm, moderately full and effortless in Mandarin. Sing the verses conversationally with a slight smile; give the recurring opening syllables a light rhythmic lift. Open the chorus without heavy belting, then bring the bridge closer before the final refrain. A small amount of same-voice doubling may warm the final chorus. Keep the arrangement airy and the instrumental break intact.
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
| 模型/制作方式 | v6（账号提供时）／Cover 翻唱 | 采用已经明确的本曲方向：清新原声流行，唱出第一次告白的忐忑；优先稳定执行。v6 官方注明面向 Pro/Premier；其他账号以实际可选模型为准。 |
| Vocal Gender | Male（界面提供时） | 使用 leo 的青年男声档案；具体音色在 Style 描述。 |
| Weirdness | 20% | 采用用户“还原原曲风格 v1”经验预设，固定 20% 作为稳定制作的首轮起点。 |
| Style Influence | 80% | 采用经验范围 80%～85% 的默认起点 80%，执行本曲已确认的 Style。让模型执行本版的核心处理：沿用钢琴、木吉他、贝斯和轻打击乐的原声骨架；该参数控制文本风格贴合，不代表旋律相似度。 |
| Variety | Off（关闭；数值界面设为 0） | 采用默认预设关闭变化，稳定执行本曲已确认的提示词。 |
| Audio Influence | 80% | 采用经验范围 80%～85% 的默认起点 80%。保留专辑收录版的旋律轮廓和段落，主要改变为本次声音与编曲设计。 |
| Max Mode | On（开启） | 采用默认预设开启，以还原原曲风格及保持本曲声音、风格和段落连贯为目标。 |

本版数值来源于用户经验预设，尚待本曲试听验证。模型和控件是否可用以实际界面为准；上述建议值不因尚未查看账号界面而省略。

控件含义沿用 v01 的资料记录（2026-10-30）；本次仅按用户经验修订制作参数，未重新联网核实产品信息。

## 质量检查

本次 v03 为汉语拼音输入版。以 v02 的 Lyrics 为唯一转换底稿，逐行检查汉字数与拼音音节数、段落标签、行序及重复次数；英文词和标点保留。拼音 Lyrics 共 1591 字符，未超过当前网页 5000 字符上限；不含残留汉字。已人工复核多音字和助词，包括“两行”“用尽”“恋曲”“落下”“长发”“呜咽”“吞没”等。

Style、Exclude 与 v02 逐块一致，Style 共 602 字符，低于 1000 上限。参数沿用：Max Mode On；Weirdness 20%；Style Influence 80%；Audio Influence 80%；Variety Off。原始 source.lrc、v01、v02 保持不变。

原词逐字相等的旧检查不适用于拼音版，本次没有把该检查结果冒称为 v03 通过；改用上述转换对应检查。尚未试听拼音版，实际普通话发音与音乐效果以生成结果为准。

## 试听反馈与修订

2026-10-30：用户取消重新填词，要求将此前 12 首提交未确认歌曲中除《月光》外的 11 首转为汉语拼音，并以新制作稿重新生成。本曲按要求更新 Lyrics，英文部分保留；声音、Style、Exclude、编曲方向及参数沿用。未采用未完成的改写歌词。

待试听。首轮重点：是否保留青涩与轻快；哦字不抢拍；副歌不能变成喊唱。

后续修订另存 cover-v04.md；保留当前 v03 与早期汉字版本。提交结果另见批次报告。
