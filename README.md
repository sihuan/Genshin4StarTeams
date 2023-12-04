# Genshin4StarTeams

文件结构：  

* **README.md(即本文档)**：尽可能收集原神纯四星角色的配队，包含简介、评分、手法参考、视频参考、DPS参考等。其中DPS参考使用gcsim模拟。  

* **gcsim_characters.md**：gcsim四星角色标准练度参考面板。  

* **gcsim_teams.md**：gcsim四星队DPS模拟代码。  

* **gcsim_dictionary.md**：gcsim中各游戏名词的中文翻译，如果你有编写gcsim代码的需求可以查阅。  

## 一、纯四星配队简介

声明：作者入坑版本为2.8，对于之前四星队的发展均为查找相关视频得到，可能因为幸存者偏差而不准确，欢迎指正。  

在1.0~1.6时期，18位老四星角色整体强度相比于现在相当在线，特别是倍率与附着。与此同时，刚开服的深渊难度相比于现在也极低。因此尽管当时整体游戏理解、操作普遍一般，只要四星的练度以及配置足够，基本上均可以达到满星。这导致了很多在现在看来匪夷所思但却能打满的队伍，例如单火香菱等。当然这个时期也出现了很多经典配队，例如知名度最高（起码老玩家群体中）的四星队————重云国家队，以及上限最高的四星队————砂糖国家队。这两只队伍取个交集，就是三位六星战神。  

进入2.0，随着永冻雷国两大传奇平民底裤队的出现，深渊难度也开始上升。更加困难的深渊筛选掉了一批数值不足、逻辑不自洽的四星队，但也留下了四星队中堪比永冻雷国的两只传奇队伍————砂糖武装与双冰双火，恰好也是直伤与增幅————这两支四星队几乎霸占了2.0时期的纯四星深渊。是的，没有草系的四星队就是这么枯燥无味，顶多就是找个人换掉行秋，让三位六星战神凑一块。只可惜随着从1.6版本优菈开始的五星伤害命座大膨胀，四星角色打伤害的责任似乎越来越少。整个2.0大版本中实装了7位新四星角色：早柚、九条、托马、五郎、云堇、久岐忍、小鹿，其中九条五郎为专拐，早柚云堇是辅助，托马久岐忍还在等他们的种子，最终只有小鹿可以勉强算得上输出，更不要说风系专拐还远在3.3。因此，2.0大版本几乎很少看到新队伍，可以说是四星队的至暗时刻。  

3.0草体系的实装瞬间拓宽了四星队的选择。绽放系反应超高的元素利用率和剧变反应倍率极大拉高了四星队的下限，尽管草系新四星的附着人均卧龙凤雏，在低练情况下种门仍然能力压一众强力四星队，甚至部分低金队。同时，草体系也为砂糖武装带来了新生，用草系替代行秋后队伍输出模式从直伤变为了上限更高的激化，省下来的行秋则可以在另一队为所欲为，无论是追求上限点秋香合体，还是当一个高效省心的挂水位打种门，都是又有强度又舒适的选择。  

## 二、纯四星配队评价标准

* 主要用以下四个主要指标评价，评分从0到10
* 其中，输出能力主要受四个乘区影响，各乘区的影响大小用极低/低/中/高/极高表示

1.**[输出]**——在合适环境、正常配置、正常练度、较熟练的手法下，阵容的输出能力
> **[环境乘区]**——深渊怪物类型、分布对输出能力的影响（相同输出评分，越低适应性越强）  
> **[配置乘区]**——角色命座、武器类型&精炼等级对输出能力的影响（相同输出评分，越低越适合平民）  
> **[练度乘区]**——角色&武器&天赋等级、圣遗物副词条对输出能力的影响（相同输出评分，越低越适合低练）  
> **[手部乘区]**——循环手法、输出手法、聚怪手法对输出能力的影响（相同输出评分，越低越适合无手玩家）

2.**[生存]**——综合考虑以下各种因素，在较熟练的手法下，阵容的生存能力  
> **[加分]**——足量治疗、盾、减伤、抗打断、高生命/高防御前台，甚至无敌帧、冻结/削韧/击飞、位移等  
> **[扣分]**——极低治疗、自挂内鬼元素、绽放自伤、重击体力消耗、蓄力/站桩

3.**[破盾]**——综合考虑以下两个方面，在较熟练的手法下，阵容的破盾能力  
> **[破盾类型]**——可破盾的种类  
> **[破盾速度]**——对各种可破盾的平均破盾速度

4.**[成本]**——深渊两队四星队的前提下，组出此队后对另外一队的影响，即评分越低，另一队越好组
> 注意与竞速的成本概念区分！  

**注1**：以下不作为评价标准  
a. **[出伤]**——大部分四星队总伤有限，需要若干循环打完一间，所以并不在乎出伤快慢  
b. **[转火]**——同上  
c. **[画地为牢]**——大伙都挺烂的，没有比的必要  
d. **[上位替代]**——纯四星攻略，暂时不考虑  

**注2**：理论上讲，[生存]，[破盾]也受到环境、配置、练度、手部乘区影响，但是相对不太明显，因此不详细列出这两项评分的乘区  

**注3**：[破盾]不作为影响输出的因素，主要是因为绝大部分时候破不了盾可以换另一路

**例1**：砂糖国家队（砂糖 班尼特 香菱 行秋）  
1.[输出]——10+，纯四星没有对手（上限）  
[环境乘区]——低，传统带风增幅体系能应对绝大部分情况，火轮随身不怕多动  
[配置乘区]——高，对香菱4命、行秋6命、高精祭礼剑的需求比较大  
[练度乘区]——高，对香菱双爆要求较高，同时还要兼顾充能和精通  
[手部乘区]——高，双扩对手法要求比较细致  
2.[生存]——8，班尼特治疗(+)，行秋减伤(+)抗打断(+)，自挂火(-)  
3.[破盾]——9，水火附着频率都很高，有风；破水/岩盾略有压力  
4.[成本]——10，四个角色都是四星队中出场率很高的存在，另一队的4组队压力极大  

**例2**：砂糖武装（砂糖 北斗 菲谢尔 行秋）  
1.[输出]——9，较高配置练度下，唯一又强又无脑的纯四星队伍  
[环境乘区]——低，高削抗直伤体系能应对绝大部分情况，输出主要靠砂糖远程平A触发协同，比较简单  
[配置乘区]——高，对北斗2命、行秋2命、高精金珀的需求比较大，其他命座和精炼等级对输出的提升也很高  
[练度乘区]——高，北斗皇女行秋都需要高双爆，同时北斗行秋还要兼顾充能和攻击力  
[手部乘区]——较低，双减伤/抗打断+薄盾+感电+扩散+颠勺，实际对群生存压力低，且输出方式简单  
2.[生存]——8~10，行秋减伤(+)抗打断(+)，北斗减伤(+)抗打断(+)弹反盾(+)，低治疗(-)，较吃体力(-)  
3.[破盾]——8，水雷附着频率都很高，有风；破水雷盾有压力  
4.[成本]——5，砂北皇三人自成一派，主要是抢行秋  

**例3**：芭芭拉双草超绽（草主 柯莱 芭芭拉 久岐忍）  
1.[输出]——6（对群），5（对单），极低成本的满星及格队伍  
[环境乘区]——中，超绽种门能应对大部分情况，但画地为牢比较严重  
[配置乘区]——极低，除草主2命外完全没有刚需命座，只需要低精西风就可以循环  
[练度乘区]——极低，只需要久岐忍90级三精通、双草工具人草套+充能沙+充能武器  
[手部乘区]——中，需要一定的切人操作保证双草工具人的Q循环和芭芭拉前台挂水时间  
2.[生存]——8~9，芭芭拉高生命前台(+)，芭芭拉治疗(++)，久岐忍治疗(+)，自挂水(-)  
3.[破盾]——6，三个新四星挂元素卧龙凤雏，芭芭拉水附着勉强足够  
4.[成本]——0，久岐忍一带三，完全的废物利用，甚至可以和砂糖国家队互补  

**例4**：芭芭拉双草/带风冻绽（柯莱 草主/砂糖 罗莎莉亚/迪奥娜 芭芭拉）  
1.[输出]——8（对群），3（对单），低成本的满星可冻对群及格队伍  
[环境乘区]——极高，刚需群怪否则伤害不足，刚需能冻结否则冻绽不成立  
[配置乘区]——低，比较需要芭芭拉高精祭礼书，此外最好有柯莱2命、砂糖2命、芭芭拉2命、修女2命+高精西风枪  
[练度乘区]——极低，只需要芭芭拉90级三精通、有人带草套、保证充能即可  
[手部乘区]——高，需要聚怪手法保证输出，需要一定的切人操作保证草冰角色的Q循环  
2.[生存]——6~7，芭芭拉治疗(+)，冻结(+)，自挂水(-)，绽放自伤(-)  
3.[破盾]——6~7，与芭芭拉超绽类似，但是可带风破盾更灵活  
4.[成本]——1，与芭芭拉超绽类似，同样是低成本配队，偶尔会抢砂糖和修女  

## 三、纯四星配队简要介绍

**收录配队要求**：

1. 满人配队，不考虑压人配队以及压人之后再带任意角色的配队  
2. 逻辑自洽，不能配置练度拉满各打各的，队伍中的角色要有自己比较独特或比较重要的作用  
3. 较低成本，队伍总金数（五星武器精炼等级之和）<=2  

注：由于时间和精力原因，其中比较主流/自洽的配队会有详细评价，其余队伍仅简单提及。

**配队按照以下方式分类**：

1. 按照队伍理想情况下的主要伤害类型，纯四星配队主要分为四个大类：增幅、激化、直伤、种门（剧变）  
注：由于四星草系过于拉胯，部分归类为种门的队伍直伤占比并不低，但还是勉强算种门。  
2. 每个大类中，根据具体反应类别或角色元素组成，分为若干个小类  
例：激化分为超激化和蔓激化，直伤队分为水雷武装、永冻、纯色、物理等  
3. 每个小类中，按照“模板”+“剩余可选角色”的方式进行分类  
例：火蒸发中有“模板”点秋香+X，按照X的元素类型甚至角色的不同，进行分类

### （一）增幅

#### 1. 火蒸发

##### ① 行秋+班尼特+香菱+X（X国家队）

四星最经典的配队（模板）没有之一。  
由于点秋香过硬的素质，几乎谁都能带，包括空气，因此以下的第四人选择覆盖了所有的四星角色。  
主要输出原理是行秋提供高频(对单)挂水，班尼特提供攻击力，香菱锁面板火轮以几乎100%的增幅覆盖率蒸发输出。  
主要伤害来源是香菱的火轮，行秋4命以上+精3以上祭礼剑时也可以打出不低的水伤爆发。

a. +风  

风系第四人的主要功能是携带风套削火抗（以及水抗），在面对高抗怪时相比其他国家队优势明显  

---

###### 行秋 班尼特 香菱 砂糖

> 砂糖国家队，简称砂国。

评分参考：
> 输出：10+ （环境-低，配置-高，练度-高，手部-高）  
 生存：8~10  
 破盾：9  
 成本：10  

手法参考：
> 简易对群双扩——行QA，班(A)QA，砂糖EQ，香Q染水AE，行AEAE，砂A循环  
 简易对单双扩——行贴脸Q，班Q，砂AE，香QE，砂E，行AEAE，砂A循环  
 一秒双扩——行远Q，班贴脸QE，砂AEA，香QAE，行AEAE，砂A循环  

视频参考：（砂国视频较多，只挑选比较有代表性的展示）
> [神樣Loki，砂国手法讲解](https://www.bilibili.com/video/BV1w24y1r7DT)  
 [神樣Loki，砂国编年史](https://www.bilibili.com/video/BV1s84y1j7xV)  
 [评论区说客，3.6深渊下半（0金低命）](https://www.bilibili.com/video/BV1vo4y1j7Ju)  
 [陆孤凡，3.5深渊换间（0金零氪22天速通）](https://www.bilibili.com/video/BV17M4y127Qx)  

DPS参考：
> 0  
---

###### 行秋 班尼特 香菱 鹿野院平藏

> 小鹿国家队，又称鹿国  

评分参考：  
> 输出： （环境-，配置-，练度-，手部-）  
 生存：  
 破盾：  
 成本：  

手法参考：  
> 简易对群双扩——行QA，班QE后撤，鹿QA重E，香QAE，行AEAE，鹿A循环

视频参考：
> [lyh逗比，3.7深渊12-1下半（等效0金，0命香菱）](https://www.bilibili.com/video/BV1hh411u7UU)  
 [评论区说客，3.5深渊换间（0金低命）](https://www.bilibili.com/video/BV1Th41137G6)  

DPS参考：
> 0
---

###### 行秋 班尼特 香菱 琳妮特

> 琳妮特国家队  

队伍简介：  
> Q嘲讽+E荒+天赋攻击拐+风附魔站场（需6命）  

评分参考：  
> 输出： （环境-，配置-，练度-，手部-）  
 生存：  
 破盾：  
 成本：  

手法参考：
> 0

视频参考：
> 0

DPS参考：
> 0

---
其他风系第四人：珐露珊（弓）、风主（控制）、早柚（治疗/娱乐）  

---

b. +雷

雷系第四人的主要功能是使怪物处于水雷共存的附着状态——此时火轮攻击时（独立弱火附着）会先消耗一部分火元素与等量的雷元素反应，触发超载，
剩余的火元素再与一半量的水元素反应，触发蒸发。这样相比于直接攻击水元素附着的怪物，不仅多打了一个超载的伤害，还减少了蒸发对水元素的消耗。

---

###### 行秋 班尼特 香菱 菲谢尔

> 皇女国家队/奥兹国家队/鸟国。由于剧团套的出现，以及深渊中不可冻的BOSS越来越多，皇女国家队强度逐渐超过经典重云国家队，成为当前版本的纯四星小雷国（DPS已经与1金雷国接近）。皇女的锁面板以及高产球，在打桩时有非常明显的优势。  

评分参考：  
> 输出： （环境-，配置-，练度-，手部-）  
 生存：  
 破盾：  
 成本：

手法参考：
> 0

视频参考：
> [时雨琦罗，4.1深渊12-2下半（0氪0抽）](https://www.bilibili.com/video/BV1EV411c7yz)  
 [时雨琦罗，4.0深渊12-3下半（0抽）](https://www.bilibili.com/video/BV1nu4y147eP)  
 [大白突突突突，4.0深渊下半（0金）](https://www.bilibili.com/video/BV1Fp4y177TX)  
 [Nickess，3.8深渊下半（0金）](https://www.bilibili.com/video/BV1Fu4y127sa)  
 [Nickess，3.4深渊上半（0金）](https://www.bilibili.com/video/BV1Sb411f7eQ)  
 [Nickess，3.1深渊下半（1金）](https://www.bilibili.com/video/BV1ee4y1W76d)  

DPS参考：
> 0
---

###### 行秋 班尼特 香菱 丽莎

> 丽莎国家队  

评分参考：
> 输出： （环境-，配置-，练度-，手部-）  
 生存：  
 破盾：  
 成本：

手法参考：
> 0

视频参考：
> [Nickess，3.8深渊下半（0金）](https://www.bilibili.com/video/BV1Mh4y1L7bC)  
 [Nickess，3.6深渊上半（0金）](https://www.bilibili.com/video/BV1ya4y1A7WZ)  
 [Nickess，3.4深渊上半（0金）](https://www.bilibili.com/video/BV1iv4y1r7cK)  
 [Nickess，3.3深渊下半（0金）](https://www.bilibili.com/video/BV14e411c7Jg)  

DPS参考：
> 0
---

###### 行秋 班尼特 香菱 北斗

> 北斗国家队  

评分参考：
> 输出： （环境-，配置-，练度-，手部-）  
 生存：  
 破盾：  
 成本：

手法参考：
> 0

视频参考：
> [Nickess，3.4深渊上半（1金）](https://www.bilibili.com/video/BV1Td4y1H7Pf)  

DPS参考：
> 0
---
其他雷系第四人：多莉（治疗+充能）、雷泽（驾驶员）、久岐忍（治疗，但屈才）、九条（不推荐，无作用）

---

c. +冰

理论上该模板应该被归类为火融化，然而现在深渊已经出现很多不能冻结的boss甚至精英怪，因此勉强归为火蒸发

冰系第四人的主要功能是使水附着的敌人冻结，从而在火轮攻击时触发融化而不是蒸发，
此时反应系数从1.5提升至2.0，总体提升33%，比10%抗性携带风套时的28%提升略高。

---

###### 行秋 班尼特 香菱 重云

> 经典国家队，对于能冻结的敌人效果相当不错，但是随着深渊12层BOSS越来越多现在优势不再明显。  

评分参考：
> 输出： （环境-，配置-，练度-，手部-）  
 生存：  
 破盾：  
 成本：

手法参考：
> 0

视频参考：
> [Nickess，3.7深渊下半（1金）](https://www.bilibili.com/video/BV1Gs4y1v7Xw)  
 [Nickess，3.2深渊下半（1金）](https://www.bilibili.com/video/BV1pP4y117ze)  
 [Nickess，2.6深渊下半（0金）](https://www.bilibili.com/video/BV1xa411i7R7)  
 [鐮夜，1.5深渊上半（0金）](https://www.bilibili.com/video/BV1564y117Hc)  
 [鐮夜，1.3~1.4深渊上半（0金）](https://www.bilibili.com/video/BV1Rb4y1S7Bo)  

DPS参考：
> 0
---

###### 行秋 班尼特 香菱 罗莎莉亚/凯亚

> 修女/凯亚国家队。也是一些带冰国家队的选择，但同样面临经典国家队的问题。  

评分参考：
> 输出： （环境-，配置-，练度-，手部-）  
 生存：  
 破盾：  
 成本：

手法参考：
> 0

视频参考：
> [像素光点，4.1深渊上半（3命凯亚，0金，较低练）](https://www.bilibili.com/video/BV1Wj41147vn)  
 [Nickess，3.7深渊下半（罗莎莉亚，0金）](https://www.bilibili.com/video/BV1mL411v7J6)  

DPS参考：
> 0
---
其他冰系第四人：凯亚（挂冰，但功能性略差），迪奥娜（盾辅+精通拐），莱依拉（盾辅+千岩），米卡（仅治疗，不推荐）

---

d. +水

水系第四人的主要作用是增加水附着降低反向打工的概率，一般不需要。当香菱多判且行秋命座较低可以考虑此配队（但通常可以用风系角色染水解决）。

---

###### 行秋 班尼特 香菱 坎蒂丝

> 坎蒂丝国家队，坎蒂丝提供水附魔使得行秋可以站场平A，并且让Q的水剑吃到班尼特攻击力加成。  
 比较适合火盾较多的场合，相比于带芭芭拉，坎蒂丝E可以产球给行秋充能，可以避免祭礼剑行秋E踢火盾无法刷新导致开不出Q的情况。  

评分参考：
> 输出： （环境-，配置-，练度-，手部-）  
 生存：  
 破盾：  
 成本：

手法参考：
> 0

视频参考：
> [thehander，4.1深渊下半（0金）](https://www.bilibili.com/video/BV1JC4y1G7j3)  

DPS参考：
> 0

---

其他水系第四人：芭芭拉（治疗+前台水+讨龙）、水主（充能+前台水，如果你敢站桩的话）

---

e. +其他元素（不主流，仅简单提及）

---

**+岩**：凝光（速切），女仆（驾驶员），岩主（暴击拐），五郎/云堇（表演，相性较差不推荐）  
**+火**：安柏（充电宝），辛焱/烟绯/托马（盾辅），可能抢蒸发影响输出，一般不考虑  
**+草**：柯莱（挂草），瑶瑶（治疗），卡维（驾驶员），绮良良（盾辅），极容易抢蒸发影响输出，基本只出现在3.7下半破水盾  

---

##### ② 行秋+班尼特+烟绯+X（国家队香菱换烟绯）

烟绯的倍率和附着并不比香菱差，虽然没有后台与锁面板机制，但也可以当火C输出。

---

###### 行秋 班尼特 烟绯 砂糖

> 带班烟绯蒸发/砂糖国家队香菱换烟绯

评分参考：
> 输出： （环境-，配置-，练度-，手部-）  
 生存：  
 破盾：  
 成本：

手法参考：
> 0

视频参考：
> [Nickess，3.8深渊上半（0金）](https://www.bilibili.com/video/BV1T94y1y7Ft)  
 [Nickess，3.2深渊下半（0金）](https://www.bilibili.com/video/BV1oD4y187kc)  
 [Nickess，3.1深渊上半（0金）](https://www.bilibili.com/video/BV1t24y127Cp)  

DPS参考：
> 0
---

###### 行秋 班尼特 烟绯 菲谢尔

> 带班烟绯武装/皇女国家队香菱换烟绯

评分参考：
> 输出： （环境-，配置-，练度-，手部-）  
 生存：  
 破盾：  
 成本：

手法参考：
> 0

视频参考：
> [Nickess，2.7深渊下半（0金）](https://www.bilibili.com/video/BV1tg411s7Ed)  

DPS参考：
> 0
---
其他第四人：其他风（最好能染色）、北斗等

---

##### ③ 行秋+烟绯+雷X+Y（烟绯武装）

由于烟绯不像香菱一样需要班尼特保证充能，因此可以不带班尼特，换成其他雷/风等角色

---

###### 行秋 烟绯 北斗 菲谢尔

> 经典烟绯武装

评分参考：
> 输出： （环境-，配置-，练度-，手部-）  
 生存：  
 破盾：  
 成本：

手法参考：
> 0

视频参考：
> [弹药福娃，3.5深渊上半（0金，低配）](https://www.bilibili.com/video/BV18Y4y1X7BG)  
 [Nickess，3.5深渊上半（1金）](https://www.bilibili.com/video/BV1mv4y1L7nu)  
 [Nickess，3.2深渊上半（2金）](https://www.bilibili.com/video/BV1EK411d7CT)  

DPS参考：
> 0

---

#### 2. 冰融化

##### ① 班尼特+香菱+冰X+冰Y（双冰双火）

由于四星冰能打输出的只有凯亚、修女、重云，因此双冰的选择只是一个三选二问题。

---

###### 班尼特 香菱 凯亚 罗莎莉亚

> 当前最常见的双冰双火，凯亚E和罗莎莉亚E即使0命也有极高的产球效率，容易满足充能需求。虽然切人复杂度高，但是在三种双冰双火中相对无脑，最适合低配。  

评分参考：
> 输出： （环境-，配置-，练度-，手部-）  
 生存：  
 破盾：  
 成本：

手法参考：
> 修E，班QE，修Q，香QE，凯EQ（+班修凯E充能直到下一个循环）  

视频参考：
> [cbean123，4.1深渊上半（0金，0命）](https://www.bilibili.com/video/BV1uw41127UJ)  
 [弹药福娃，4.0深渊下半（0金，低配）](https://www.bilibili.com/video/BV1z8411z7Zj)  
 [凛疯1f，4.0深渊上半&下半（3金，6命凯亚）](https://www.bilibili.com/video/BV1Y94y147sz)  
 [评论区说客，3.8深渊下半（0金，1命凯亚）](https://www.bilibili.com/video/BV1Mm4y1J7FH)  
 [评论区说客，3.7深渊下半（0金，1命凯亚）](https://www.bilibili.com/video/BV1wN411y7tu)  
 [评论区说客，3.2深渊下半（0金，低配三星武器非连打）](https://www.bilibili.com/video/BV1VG411c7ed)  
 [评论区说客，3.0深渊下半（0金，低配三星武器）](https://www.bilibili.com/video/BV1Ud4y1M7Mv)  
 [评论区说客，2.7深渊下半（0金，低配）](https://www.bilibili.com/video/BV1fZ4y1v7jm)  
 [香香怪coco，2.3深渊下半（0金）](https://www.bilibili.com/video/BV1ph411x7iY)  

DPS参考：
> 0  

---

###### 班尼特 香菱 凯亚 重云

> 比较少见的双冰双火。重云提供冰附魔，可以让普攻高倍率的凯亚站场，但实际上这么做会显著增加充能压力，实际玩起来还是切人复杂度很高的队伍。  

评分参考：
> 输出： （环境-，配置-，练度-，手部-）  
 生存：  
 破盾：  
 成本：

手法参考：
> 0

视频参考：
> [时雨琦罗，4.1深渊12-1上半&12-3下半（0氪0抽）](https://www.bilibili.com/video/BV1EV411c7yz)  
 [时雨琦罗，4.0深渊12-1下半&12-2下半（0抽）](https://www.bilibili.com/video/BV1nu4y147eP)  
 [评论区说客，3.2深渊下半（0金低命）](https://www.bilibili.com/video/BV1Lg411W75L/)  
 [香香怪coco，2.2深渊下半（0金）](https://www.bilibili.com/video/BV1zu411Z7Pr)  
 [香香怪coco，2.1深渊上半（0金）](https://www.bilibili.com/video/BV17341127RU)  

DPS参考：
> 0

---

###### 班尼特 香菱 罗莎莉亚 重云

> 另一种比较少见的双冰双火。罗莎莉亚和重云的增幅覆盖率都很高，有不错的上限，但是对技能释放时机有要求。此外也可以利用枪系重击独立附着的特点，让罗莎莉亚化身冰胡桃整活。  

评分参考：
> 输出： （环境-，配置-，练度-，手部-）  
 生存：  
 破盾：  
 成本：

手法参考：
> 0

视频参考：
> [Nickess，4.0深渊下半（0金）](https://www.bilibili.com/video/BV1fN4y1D7Vp)  
 [Nickess，3.8深渊下半（0金）](https://www.bilibili.com/video/BV13h4y1w7v3)  
 [Nickess，3.5深渊上半（1金）](https://www.bilibili.com/video/BV1Q24y1u7Qj)  
 [Nickess，3.3深渊下半（1金）](https://www.bilibili.com/video/BV1SR4y1h7Tj)  
 [香香怪coco，2.7深渊下半（0金）](https://www.bilibili.com/video/BV17Y411M7eD)  
 [评论区说客，2.3深渊上半（0金低命低练）](https://www.bilibili.com/video/BV18L411773s)  

DPS参考：
> 0

---

##### ② 班尼特+香菱+冰X+风Y（单核冰融化）

---

###### 班尼特 香菱 罗莎莉亚 砂糖

> 融罗/融修。罗莎莉亚EQ每一段伤害都是独立冰附着，增幅覆盖率100%，此外产球回能充足、能拐全队暴击，因此单核冰融化经常在冰位选择罗莎莉亚。  

评分参考：
> 输出： （环境-，配置-，练度-，手部-）  
 生存：  
 破盾：  
 成本：

手法参考：
> 0

视频参考：
> [吃狗头的喵酱，4.1深渊上半（0金）](https://www.bilibili.com/video/BV18h4y167q1)  
 [Nickess，3.6深渊下半（0金）](https://www.bilibili.com/video/BV17c411H79Y)  
 [Nickess，3.5深渊下半（0金）](https://www.bilibili.com/video/BV1mv4y1L7nu)  
 [Nickess，3.4深渊上半（0金）](https://www.bilibili.com/video/BV1L24y1p79K)  
 [Nickess，3.3深渊上半（0金）](https://www.bilibili.com/video/BV1jy4y1d7hP)  

DPS参考：
> 0

---

###### 班尼特 香菱 重云 砂糖

> 冰换重云的版本。优势为爆发、大数字，适合打多动症目标，以及核爆表演。总倍率比修女略低。  

评分参考：
> 输出： （环境-，配置-，练度-，手部-）  
 生存：  
 破盾：  
 成本：

手法参考：
> 0

视频参考：
> [香香怪coco，1.3~1.4深渊上半（0金）](https://www.bilibili.com/video/BV1BK4y1m7Yg)  

DPS参考：
> 0

---

其他冰系选择：凯亚，虽然总倍率高，但融化覆盖率低，因此不是很常见  
其他风系选择：小鹿、琳妮特（嘲讽+荒）等，但是拐力不如砂糖  

---

#### 3. 水蒸发

##### ① 班尼特+香菱+水X（不含行秋）+风Y

---

###### 班尼特 香菱 芭芭拉 砂糖

> 0

评分参考：
> 输出： （环境-，配置-，练度-，手部-）  
 生存：  
 破盾：  
 成本：

手法参考：
> 0

视频参考：
> [Nickess，4.0深渊上半（0金）](https://www.bilibili.com/video/BV1Sh4y1v7rJ)  
 [Nickess，3.8深渊上半（0金）](https://www.bilibili.com/video/BV1194y1Y7Df)  

DPS参考：
> 0

---

其他水系选择：坎蒂丝，水主（不推荐）  
其他风系选择：小鹿、琳妮特等

---

#### 4. 火融化

##### ① 班尼特+风X+冰Y+冰Z（融班）

---

###### 班尼特 砂糖 罗莎莉亚 迪奥娜

> 0

评分参考：
> 输出： （环境-，配置-，练度-，手部-）  
 生存：  
 破盾：  
 成本：

手法参考：
> 0

视频参考：
> 0

DPS参考：
> 0

---

其他风系选择：对拐力和染色要求很高，不建议替换  
其他冰系选择：凯亚（冰直伤、冰附着）

---

### （二）激化

#### 1. 超激化（雷草风）

##### ① 菲谢尔+雷X+草Y+风Z（激扩）

---

###### 菲谢尔 北斗 瑶瑶 砂糖

> 砂糖激扩。最常见的四星超激化队伍，低配出场率很高（瑶瑶实装前常用草主柯莱）。对单DPS与砂糖武装相近。对群时如果能保证草元素覆盖则相比砂糖武装更有优势。  

评分参考：
> 输出： （环境-，配置-，练度-，手部-）  
 生存：  
 破盾：  
 成本：

手法参考：
> 0

视频参考：
> [像素光点，4.1深渊下半（0金，较低练）](https://www.bilibili.com/video/BV1Wj41147vn)  
 [持灵，4.0深渊下半(0金)](https://www.bilibili.com/video/BV1M94y1s7Db)  
 [Nickess，3.8深渊上半（0金）](https://www.bilibili.com/video/BV1Mh4y1L7bC)  
 [Nickess，3.7深渊上半（2金）](https://www.bilibili.com/video/BV1Gs4y1v7Xw)  
 [Nickess，3.6深渊下半（0金）](https://www.bilibili.com/video/BV1ya4y1A7WZ)  
 [评论区说客，3.5深渊下半（0金，低命）](https://www.bilibili.com/video/BV1Th41137G6)  
 [Nickess，3.4深渊下半（0金）](ttps://www.bilibili.com/video/BV1iv4y1r7cK)  
 [评论区说客，3.3深渊下半（0金，低命低练）](https://www.bilibili.com/video/BV1Wy4y197qi)  
 [评论区说客，3.2深渊上半（草主，0金，低配三星武器非连打）](https://www.bilibili.com/video/BV1VG411c7ed)  
 [评论区说客，3.0深渊上半（草主，0金，低配三星武器）](https://www.bilibili.com/video/BV1Ud4y1M7Mv)  

DPS参考：
> 0

---

其他雷系选择：丽莎等  
其他草系选择：绮良良，也可以草主柯莱但是生存能力较差，需要金珀砂糖/小鹿  
其他风系选择：小鹿、早柚、琳妮特等  

---

#### 2. 蔓激化（草雷）

##### ① 草X+草Y+草Z+雷N（三草一雷）

---

###### 卡维 草主 瑶瑶 久岐忍

> 0

评分参考：
> 输出： （环境-，配置-，练度-，手部-）  
 生存：  
 破盾：  
 成本：

手法参考：
> 0

视频参考：
> 0

DPS参考：
> 0

---

其他草系选择：柯莱（后台输出），不过四星草都是卧龙凤雏，区别不大  
其他雷系选择：多莉（充能+治疗）、丽莎（减防）、皇女、北斗（充能压力较大），理论上能后台挂雷即可  

---

### （三）直伤

#### 1. 扩散感电武装（雷水风）

##### ① 北斗+菲谢尔+水X+风Y（经典水雷武装）

---

###### 北斗 菲谢尔 行秋 砂糖

> 砂糖武装。四星经典，低配常客，割草的神。砂糖站场远程攻击+扩散感电+风套水雷双削抗+染色增伤(满命)+控制聚怪+拐精通(但作用不大)，北斗减伤+抗打断+盾(1命)+削雷抗(6命)+后台雷输出+E弹反生存爆发(需要操作)，菲谢尔后台雷输出+产雷球，行秋减伤+抗打断+后台水输出。  

评分参考：
> 输出： （环境-，配置-，练度-，手部-）  
 生存：  
 破盾：  
 成本：

手法参考：
> 0

视频参考：
> [lyh逗比，4.1深渊下半（0金，全锻造武器）](https://www.bilibili.com/video/BV13m4y1G7tL)  
 [弹药福娃，4.0深渊上半（0金，低配）](https://www.bilibili.com/video/BV1z8411z7Zj)  
 [凛疯1f，4.0深渊上半&下半（0金）](https://www.bilibili.com/video/BV1Nh4y1P7RQ)  
 [评论区说客，3.8深渊上半（0金，低练）](https://www.bilibili.com/video/BV1Mm4y1J7FH)  
 [凛疯1f，3.7深渊上半&下半（0金）](https://www.bilibili.com/video/BV1e8411f7XK)  
 [JackTRipper，3.6深渊上半（0金）](https://www.bilibili.com/video/BV1do4y187Ay)  
 [凛疯1f，3.5深渊上半&下半（0金）](https://www.bilibili.com/video/BV1Zx4y1A7fz)  
 [JackTRipper，3.4深渊上半（0金）](https://www.bilibili.com/video/BV1jG4y1D7qk)  
 [评论区说客，2.7深渊上半（0金，低配）](https://www.bilibili.com/video/BV1fZ4y1v7jm)  
 [评论区说客，2.6深渊上半（0金，低配三星武器）](https://www.bilibili.com/video/BV16u411i7TF)  
 [香香怪coco，2.5深渊上半（0金）](https://www.bilibili.com/video/BV1pU4y1f7gr)  
 [香香怪coco，2.3深渊上半（0金）](https://www.bilibili.com/video/BV1ph411x7iY)  
 [香香怪coco，2.2深渊上半（0金）](https://www.bilibili.com/video/BV1zu411Z7Pr)  
 [香香怪coco，2.1深渊下半（0金）](https://www.bilibili.com/video/BV17341127RU)  

DPS参考：
> 0

备注：
> 砂糖换琳妮特（琳妮特武装），thehander，3.8深渊上半（2金），<https://www.bilibili.com/video/BV1pu4y1D724>  

###### 北斗 菲谢尔 行秋 鹿野院平藏

> 小鹿武装。小鹿相比于砂糖，手短、聚怪差，但是近战韧性高、风直伤高、Q冷却短金珀治疗高、不吃充能。  
 由于金珀覆盖率高，可以选择一些更平民的武器，比如以下这一套3锻造且生存能力极强的配装：金珀风套小鹿+浪影绝缘充能沙北斗+静谧战技套攻击沙皇女。相比于砂糖，小鹿带金珀12秒无充能压力的Q可以使北斗皇女武器的buff全覆盖。  

评分参考：
> 输出： （环境-，配置-，练度-，手部-）  
 生存：  
 破盾：  
 成本：

手法参考：
> 0

视频参考：
> [thehander，4.1深渊下半（0金）](https://www.bilibili.com/video/BV1Kw411672C)  
 [凛疯1f，3.6深渊上半（0金）](https://www.bilibili.com/video/BV1Wa4y137Ld)  
 [thehander，3.6深渊下半（0金）](https://www.bilibili.com/video/BV1Xs4y1B7PD)  

DPS参考：
> 0

---

###### 北斗 菲谢尔 芭芭拉 砂糖/风主/琳妮特

> 芭芭拉武装。用海染芭芭拉替代行秋，对单DPS降低，但是对群勉强。由于队伍里有正经治疗，因此风系的选择并不仅限于(金珀)砂糖。  

评分参考：
> 输出： （环境-，配置-，练度-，手部-）  
 生存：  
 破盾：  
 成本：

手法参考：
> 0

视频参考：
> [thehander，4.0深渊下半（砂糖，0金）](https://www.bilibili.com/video/BV1sp4y1L722)  
 [thehander，3.8深渊下半（砂糖，0金）](https://www.bilibili.com/video/BV1Km4y1p7TC)  
 [Nickess，3.7深渊上半（砂糖，2金）](https://www.bilibili.com/video/BV1mL411v7J6)  
 [Nickess，3.2深渊上半（砂糖，2金）](https://www.bilibili.com/video/BV1pP4y117ze)  
 [Nickess，2.8深渊下半（砂糖，0金）](https://www.bilibili.com/video/BV1XK411o7DT)  
 [时雨琦罗，2.7深渊12-1上半（风主，0抽）](https://www.bilibili.com/video/BV1eB4y1S78q)  
 [Nickess，2.6深渊上半（砂糖，0金）](https://www.bilibili.com/video/BV1xa411i7R7)  
 [鐮夜，1.3~1.4深渊下半（0金）](https://www.bilibili.com/video/BV1Rb4y1S7Bo)  

DPS参考：
> 0

---

###### 北斗 菲谢尔 坎蒂丝 鹿野院平藏

> 鹿坎武装，北坎双弹反+全员锻造武器。小鹿携带金珀后，北斗皇女坎蒂丝均可以携带枫丹锻造武器并且有不错的buff覆盖率。此外可以省下砂糖行秋组成砂糖国家队。队伍输出主要依赖双雷，但坎蒂丝仍然最好有4命增加产球效率，以及满命增加挂水频率。  

评分参考：
> 输出： （环境-，配置-，练度-，手部-）  
 生存：  
 破盾：  
 成本：

手法参考：
> 0

视频参考：
> [lyh逗比，4.0深渊上半（0金）](https://www.bilibili.com/video/BV1M34y1A74R)  

DPS参考：
> 0

---

#### 2. 传统永冻（冰冰水风）

##### ① 凯亚+冰X+水Y+风Z（凯亚永冻）

---

###### 凯亚 修女/重云 行秋 砂糖/早柚

> 当前低金勉强能玩的凯亚永冻，带行秋而不是芭芭拉，能提供不少的水系直伤输出。生存能力较弱，聚怪和冻结很吃手部乘区，伤害也很依靠命座以及凯亚的雾切。DPS较低，特别是面对无法冻结的boss，低金一般不建议使用。

评分参考：
> 输出： （环境-，配置-，练度-，手部-）  
 生存：  
 破盾：  
 成本：

手法参考：
> 0

视频参考：
> [持灵，4.0深渊上半（修女砂糖，0金，2命凯亚）](https://www.bilibili.com/video/BV1xF411r7G8)  
 [JackTRipper，3.8深渊上半（修女砂糖，0金，3命凯亚）](https://www.bilibili.com/video/BV1ak4y137fU)  
 [评论区说客，2.6深渊下半（修女早柚，0金，低配三星武器）](https://www.bilibili.com/video/BV16u411i7TF)  

DPS参考：
> 0

---

###### 凯亚 修女/重云 芭芭拉 砂糖

> 比较传统的凯亚永冻，除了生存略强之外不如带行秋的版本，现阶段低金几乎没有满星希望，但仍是一个很不错的开荒配队。

评分参考：
> 输出： （环境-，配置-，练度-，手部-）  
 生存：  
 破盾：  
 成本：

手法参考：
> 0

视频参考：
> [thehander，3.8深渊上半（重云，1金，6命凯）](https://www.bilibili.com/video/BV1ru411E7t6)  
 [Nickess，3.1深渊上半（修女，0金，0命凯）](https://www.bilibili.com/video/BV14g411q7zW)，[配置](https://www.bilibili.com/video/BV1XG4y1t7v2)  

DPS参考：
> 0

---

###### 凯亚 重云 芭芭拉 风主

> 零抽永冻  

评分参考：
> 输出： （环境-，配置-，练度-，手部-）  
 生存：  
 破盾：  
 成本：

手法参考：
> 0

视频参考：
> [时雨琦罗，3.4深渊12-1下半（0抽）](https://www.bilibili.com/video/BV18M4y1D7QL)  

DPS参考：
> 0

---

其他冰系选择：没了，能打伤害的副C就这三个，换其他冰系角色输出压力很大  
其他水系选择：坎蒂丝（水附魔）  
其他风系选择：比较吃聚怪，不建议替换  

---

#### 3. 香班双火+任意直伤（含纯火）

##### ① 班尼特+香菱+岩X+岩Y（双岩双火）

---

###### 班尼特 香菱 凝光 云堇

> 0

评分参考：
> 输出： （环境-，配置-，练度-，手部-）  
 生存：  
 破盾：  
 成本：

手法参考：
> 0

视频参考：
> [Nickess，3.6深渊上半（0金）](https://www.bilibili.com/video/BV1Ez4y1Y7sT)  
 [Nickess，3.1深渊上半（0金）](https://www.bilibili.com/video/BV1aP411c7Cv)  

DPS参考：
> 0

---

##### ② 班尼特+香菱+雷X+雷Y（双雷双火）

---

###### 班尼特 香菱 北斗 菲谢尔

> 经典双雷双火，北斗菲谢尔的锁面板非常适配班尼特。相比于带双冰/双风，显著优势在于有北斗的抗打断减伤不容易暴毙。  

评分参考：
> 输出： （环境-，配置-，练度-，手部-）  
 生存：  
 破盾：  
 成本：

手法参考：
> 0

视频参考：
> [小夜悠，4.1深渊下半（0金）](https://www.bilibili.com/video/BV1DV411F7gE)  
 [lyh逗比，4.0深渊下半（0金）](https://www.bilibili.com/video/BV1w84y1S7Aa)  
 [Nickess，3.7深渊下半（2金）](https://www.bilibili.com/video/BV12k4y1p72C)  
 [lyh逗比，3.5深渊上半（等效0金，0命香菱）](https://www.bilibili.com/video/BV1Sh41137XM)  
 [Nickess，3.4深渊下半（1金）](https://www.bilibili.com/video/BV1Ss4y187AH)  

DPS参考：
> 0

---

##### ③ 班尼特+香菱+火X+风Y（三火一风/纯火）

---

###### 班尼特 香菱 烟绯 砂糖

> 经典四星三火队，香班组合的基础上增加前台烟绯。风系的选择较灵活。  

评分参考：
> 输出： （环境-，配置-，练度-，手部-）  
 生存：  
 破盾：  
 成本：

手法参考：
> 0

视频参考：
> [只会逃跑的小佐伊，4.1深渊上半（0金）](https://www.bilibili.com/video/BV1Ez4y1F7VW)  
 [枕头ツ，4.0深渊下半（2金）](https://www.bilibili.com/video/BV11p4y1A7tH)  

DPS参考：
> 0

---

#### 4. 珐鹿双风+任意直伤（含纯风）

##### ① 珐露珊+鹿野院平藏+雷X+水Y（珐鹿感电）

---

###### 珐露珊 鹿野院平藏 久岐忍 行秋

> 珐露珊主C，小鹿速切，行秋提供额外直伤（需要珐露珊重击之间插入普攻触发协同），久岐忍提供雷元素感电、治疗以及千岩攻击拐。珐露珊加上扩散感电的削韧效果极强。  

评分参考：
> 输出： （环境-，配置-，练度-，手部-）  
 生存：  
 破盾：  
 成本：

手法参考：
> 0

视频参考：
> [lyh逗比，4.0深渊上半（0金）](https://www.bilibili.com/video/BV1w84y1S7Aa)

DPS参考：
> 0

---

###### 珐露珊 鹿野院平藏 菲谢尔 芭芭拉

> 另一种珐鹿感电，菲谢尔提供直伤，芭芭拉提供治疗。  

评分参考：
> 输出： （环境-，配置-，练度-，手部-）  
 生存：  
 破盾：  
 成本：

手法参考：
> 0

视频参考：
> [Nickess，3.7深渊上半（0金）](https://www.bilibili.com/video/BV1Zj411o7My)  

DPS参考：
> 0

---

##### ② 珐露珊+鹿野院平藏+冰X+水Y（珐鹿冻结）

---

###### 珐露珊 鹿野院平藏 罗莎莉亚 芭芭拉

> 带冰水提供冻结，比感电控制更强。  

评分参考：
> 输出： （环境-，配置-，练度-，手部-）  
 生存：  
 破盾：  
 成本：

手法参考：
> 0

视频参考：
> [Nickess，3.8深渊上半（0金）](https://www.bilibili.com/video/BV1Fu4y127sa)  

DPS参考：
> 0

---

##### ③ 珐露珊+鹿野院平藏+冰X+冰Y（珐鹿双冰）

---

###### 珐露珊 鹿野院平藏 罗莎莉亚 莱依拉

> 放弃带双元素打感电/冻结，转而带双冰吃共鸣15%暴击率。  

评分参考：
> 输出： （环境-，配置-，练度-，手部-）  
 生存：  
 破盾：  
 成本：

手法参考：
> 0

视频参考：
> [凛疯1f，4.0深渊上半（2金）](https://www.bilibili.com/video/BV18F411D74C)  

DPS参考：
> 0

---

##### ④ 珐露珊+鹿野院平藏+风X+任意Y（珐鹿三风）

---

###### 珐露珊 鹿野院平藏 琳妮特 莱依拉

> 纯新四星三风直伤队。珐露珊主C，小鹿速切+金珀治疗，琳妮特产球+后台副C+嘲讽+芒+天赋攻击拐，莱依拉提供盾和千岩攻击拐。  

评分参考：
> 输出： （环境-，配置-，练度-，手部-）  
 生存：  
 破盾：  
 成本：

手法参考：
> 0

视频参考：
> [lyh逗比，4.1深渊上半（0金）](https://www.bilibili.com/video/BV1sz4y1G7vt)  

DPS参考：
> 0

---

#### 3&4. 鹿珐香班（双风双火）

> 暴力直伤配队，伤害都是命座和练度打的。  

评分参考：
> 输出： （环境-，配置-，练度-，手部-）  
 生存：  
 破盾：  
 成本：

手法参考：
> 0

视频参考：
> [Nickess，4.0深渊下半（0金）](https://www.bilibili.com/video/BV1BG411R7jJ)  
 [Nickess，3.6深渊下半（0金）](https://www.bilibili.com/video/BV1pX4y167JW)  
 [Nickess，3.5深渊上半（0金）](https://www.bilibili.com/video/BV1dv4y1G7DE)  
 [Nickess，3.3深渊上半（0金）](https://www.bilibili.com/video/BV1hv4y1Q75n)  

DPS参考：
> 0

---

#### 5. 纯岩

##### ① 诺艾尔+五郎+岩X+任意Y（四星纯岩）

---

###### 诺艾尔 五郎 云堇 凝光

> 0

评分参考：
> 输出： （环境-，配置-，练度-，手部-）  
 生存：  
 破盾：  
 成本：

手法参考：
> 0

视频参考：
> 0

DPS参考：
> 0

---

#### 6. 纯雷

##### ① 北斗+菲谢尔+雷X+风Y

---

###### 北斗 菲谢尔 丽莎/九条 砂糖  

> 基本上为武装队将水换为雷，牺牲感电换取同色互充以及其他增益(如丽莎的减防、九条的攻击爆伤等)。  

评分参考：
> 输出： （环境-，配置-，练度-，手部-）  
 生存：  
 破盾：  
 成本：

手法参考：
> 0

视频参考：
> [评论区说客，3.1深渊上半（0金，低配三星武器）](https://www.bilibili.com/video/BV1ke4y1v7As)  
 [Nickess，2.7深渊上半（丽莎，0金）](https://www.bilibili.com/video/BV1XK411o7vt)  

DPS参考：
> 0

---

#### 7. 纯冰

##### ① 凯亚+重云+冰X+风Y（三冰一风）

---

###### 凯亚 重云 迪奥娜 风主  

> 零抽三冰，凯亚主C  

评分参考：
> 输出： （环境-，配置-，练度-，手部-）  
 生存：  
 破盾：  
 成本：

手法参考：
> 0

视频参考：
> [时雨琦罗，2.7深渊换间（0抽）](https://www.bilibili.com/video/BV1eB4y1S78q)  

DPS参考：
> 0

---

#### 8. 物理

这个小类只考虑以物理输出为主的队伍，不收录物理C只作为驾驶员的配队  

##### ① 菲米尼+雷X+Y+Z（菲米尼物理队）

---

###### 菲米尼 菲谢尔

> 0

评分参考：
> 输出： （环境-，配置-，练度-，手部-）  
 生存：  
 破盾：  
 成本：

手法参考：
> 0

视频参考：
> 0

DPS参考：
> 0

---

##### ② 雷泽+冰X+Y+Z（雷泽物理队）

---

###### 雷泽 罗莎莉亚 菲谢尔 行秋

> 0

评分参考：
> 输出： （环境-，配置-，练度-，手部-）  
 生存：  
 破盾：  
 成本：

手法参考：
> 0

视频参考：
> [Nickess，3.1深渊下半（3金）](https://www.bilibili.com/video/BV1i84y1y7pt)  

DPS参考：
> 0

---

###### 雷泽 罗莎莉亚 菲谢尔 辛焱

> 0

评分参考：
> 输出： （环境-，配置-，练度-，手部-）  
 生存：  
 破盾：  
 成本：

手法参考：
> 0

视频参考：
> [Nickess，2.7深渊下半（2金）](https://www.bilibili.com/video/BV1me4y1W7Wv)  

DPS参考：
> 0

---

##### ③ 辛焱+雷X+冰Y+Z（辛焱物理队）

---

###### 辛焱

> 0

评分参考：
> 输出： （环境-，配置-，练度-，手部-）  
 生存：  
 破盾：  
 成本：

手法参考：
> 0

视频参考：
> 0

DPS参考：
> 0

---

### （四）种门

#### 1. 超绽放（草水雷+草/水/雷/冰/风）

由于四星草系都是卧龙凤雏，第四人为水/岩的情况下很难保证产种效率，因此不考虑。  
第四人为火的情况归入超+烈绽放中。

##### ① 草X+草Y+水Z+雷N（双草超绽）

---

###### 草主/柯莱/瑶瑶/卡维/绮良良（五选二） 行秋 久岐忍

> 经典的纯四星种门选择，由于四星草角色的挂草能力都比较弱，因此携带两个草系角色保证草底，同时双草共鸣的精通也能加一些种子伤害。  
 需要注意的是五个草系角色中卡维无后台挂草，绮良良基本没有后台挂草，因此选择这俩个角色时另一个草系角色最好选择后台挂草能力稍强的柯莱/草主。  

评分参考：
> 输出： （环境-，配置-，练度-，手部-）  
 生存：  
 破盾：  
 成本：

手法参考：
> 0

视频参考：
> [cbean123，4.1深渊下半（草主柯莱，0金，除草主外0命）](https://www.bilibili.com/video/BV1uw41127UJ)  
 [持灵，4.0深渊上半(柯莱绮良良，0金)](https://www.bilibili.com/video/BV1M94y1s7Db)  
 [Nickess，3.8深渊下半（柯莱瑶瑶，0金）](https://www.bilibili.com/video/BV1194y1Y7Df)  
 [Nickess，3.6深渊上半（柯莱瑶瑶，0金）](https://www.bilibili.com/video/BV17c411H79Y)  
 [持灵，3.5深渊下半（柯莱瑶瑶，0金）](https://www.bilibili.com/video/BV1hT411B7yv)  
 [lyh逗比，3.5深渊下半（草主瑶瑶，0金）](https://www.bilibili.com/video/BV1Sh41137XM)  
 [弹药福娃，3.4深渊上半（柯莱瑶瑶，0金）](https://www.bilibili.com/video/BV1Qx4y1L7Fc)  

DPS参考：
> 0

---

###### 草主/柯莱/瑶瑶（三选二） 芭芭拉 久岐忍

> 用芭芭拉替换行秋的版本。因为芭芭拉需要站场挂水，所以草系角色最好选择能后台挂草的草主/柯莱/瑶瑶。  
 相比于带行秋的版本，操作较为繁琐，没有抗打断和高额水直伤，但是有群体治疗、更多群体挂水以及海染的群体伤害，在对付流血狗等敌人时比较有优势，最重要的是可以省下一个行秋，在输出压力不大时是一个非常不错的低成本配队选择。

评分参考：
> 输出： （环境-，配置-，练度-，手部-）  
 生存：  
 破盾：  
 成本：

手法参考：
> 0

视频参考：
> [大白突突突突，4.0深渊上半（草主柯莱，0金）](https://www.bilibili.com/video/BV1Fp4y177TX)  
 [lyh逗比，3.6深渊12-2上半龙兽&12-3上半妙脆角（草主柯莱，0金](https://www.bilibili.com/video/BV1hh411u7UU)  
 [lyh逗比，3.4深渊12-2上半武士+雷火蝎（草主柯莱，0金）](https://www.bilibili.com/video/BV1JM411s7KX)  

DPS参考：
> 0

---

##### ② 草X+水Y+水Z+雷N（双水超绽）

---

###### 柯莱/草主/瑶瑶 行秋 坎蒂丝/芭芭拉 久岐忍

> 四星双水超绽。因为四星草的挂草问题，再加上坎蒂丝/芭芭拉没有夜兰的高直伤，一般不带双水。但是在面对大量火盾时还是一个不错的选择。

评分参考：
> 输出： （环境-，配置-，练度-，手部-）  
 生存：  
 破盾：  
 成本：

手法参考：
> 0

视频参考：
> [只会逃跑的小佐伊，4.1深渊下半（柯莱芭芭拉，0金）](https://www.bilibili.com/video/BV1Ez4y1F7VW)  
 [枕头ツ，4.0深渊上半（瑶瑶坎蒂丝，0金）](https://www.bilibili.com/video/BV11p4y1A7tH)  

DPS参考：
> 0

---

##### ③ 草X+水Y+雷Z+雷N（双雷超绽）

双雷超绽原理：简单地讲，草不足时，对水雷共存下（例如各0.4）的敌人施加草附着（例如1单位），此时部分草元素先与雷元素反应生成激元素，激元素与水反应生成一颗种子，此时仍能剩下部分草元素，而不是像水底上草一样由于后手不残留直接变成无附着。也就是说，这样提高了草元素的利用率。  

---

###### 柯莱/草主 行秋 菲谢尔 久岐忍

> 0金标准练度DPS登顶配队（模板）。四星顶级挂草柯莱+四星顶级倍率行秋皇女+四星超绽核心久岐忍，在保住种子伤害基本盘的情况下能打出最高直伤甚至激化。带其他四星草时也有不错表现。

评分参考：
> 输出： （环境-，配置-，练度-，手部-）  
 生存：  
 破盾：  
 成本：

手法参考：
> 0

视频参考：
> [吃狗头的喵酱，4.1深渊下半（0金）](https://www.bilibili.com/video/BV18h4y167q1)  
 [黑塔今天没转圈，4.0深渊上半（柯莱，0金，竞速）](https://www.bilibili.com/video/BV1y34y1P74X)  
 [thehander，3.6深渊上半（柯莱，0金）](https://www.bilibili.com/video/BV1ts4y1A7uN)  

DPS参考：
> 0

---

###### 柯莱 芭芭拉 菲谢尔 久岐忍

> 行秋换为芭芭拉的版本，治疗量更高，但是挂水需要站场稍微麻烦一些。  

评分参考：
> 输出： （环境-，配置-，练度-，手部-）  
 生存：  
 破盾：  
 成本：

手法参考：
> 0

视频参考：
> [thehander，3.8深渊上半（0金）](https://www.bilibili.com/video/BV1TF411f7Zf)  
 [黑塔今天没转圈，3.4深渊上半（2金）](https://www.bilibili.com/video/BV1KT411C7qT)  

DPS参考：
> 0

---

###### 柯莱 行秋 北斗 久岐忍

> 菲谢尔换为北斗的版本，组成双减伤抗打断，强化对双能力，且北斗只有E能点种子，打小体积怪时更不容易抢种子丢伤害。  

评分参考：
> 输出： （环境-，配置-，练度-，手部-）  
 生存：  
 破盾：  
 成本：

手法参考：
> 0

视频参考：
> [uu草籽，4.1深渊下半（0金）](https://www.bilibili.com/video/BV1tN4y1o779)

DPS参考：
> 0

---

###### 瑶瑶 行秋 丽莎 菲谢尔

> 零抽双雷超绽。零抽没有久岐忍，因此使用全精通丽莎e点种。虽然强度一般但仍能满星，足以体现种门的下限之高。  

评分参考：
> 输出： （环境-，配置-，练度-，手部-）  
 生存：  
 破盾：  
 成本：

手法参考：
> 0

视频参考：
> [时雨琦罗，4.1深渊12-3上半（0氪0抽）](https://www.bilibili.com/video/BV1EV411c7yz)  
 [时雨琦罗，4.0深渊12-1上半&12-2上半（0抽）](https://www.bilibili.com/video/BV1nu4y147eP)  
 [时雨琦罗，3.4深渊上半（0抽）](https://www.bilibili.com/video/BV18M4y1D7QL)  
 [评论区说客，3.1深渊下半（草主芭芭拉，0金，低配三星武器）](https://www.bilibili.com/video/BV1ke4y1v7As)  

DPS参考：
> 0

---

##### ④ 草X+水Y+雷Z+冰N（带冰超绽）

绽放带冰的原理：草冰可共存，上水时，水先和冰反应生成二倍元素量的冻元素，剩余水元素和其一半元素量的草元素反应生成一颗种子。  
因此，同样生成一颗种子，带冰时对草元素的消耗量低，即所谓“冻结护草”。  

---

###### 柯莱 行秋 久岐忍 夏洛蒂

> 冰法驾驶员，而且恰好治疗量和伤害都为攻击倍率，带输出装时可同时提供足量治疗和不低的直伤。  

评分参考：
> 输出： （环境-，配置-，练度-，手部-）  
 生存：  
 破盾：  
 成本：

手法参考：
> 0

视频参考：
> [lyh逗比，4.1深渊上半（0金）](https://www.bilibili.com/video/BV1eN411M7jJ)  

DPS参考：
> 0

###### 柯莱 行秋 久岐忍 菲米尼/重云

> 冰系大剑驾驶员，可提供不错直伤，但是大剑攻速慢有丢水剑协同的风险  

评分参考：
> 输出： （环境-，配置-，练度-，手部-）  
 生存：  
 破盾：  
 成本：

手法参考：
> 0

视频参考：
> [小夜悠，4.1深渊上半（重云，0金）](https://www.bilibili.com/video/BV1DV411F7gE)  
 [藤原动感新之助，4.0深渊12-1上半（菲米尼，0金）](https://www.bilibili.com/video/BV14w411U7Yc)  

DPS参考：
> 0

---

##### ⑤ 草X+水Y+雷Z+风N（带风超绽）

---

###### 瑶瑶/柯莱 行秋 菲谢尔/北斗 砂糖

> 增加一个灵活的风系，可以染/扩水或雷增加附着(通常为雷，这样就不需要高精通久岐忍了)，另外可以提供削抗聚怪，甚至拐精通。  

评分参考：
> 输出： （环境-，配置-，练度-，手部-）  
 生存：  
 破盾：  
 成本：

手法参考：
> 0

视频参考：
> [Nickess，4.0深渊上半（柯莱菲谢尔，1金）](https://www.bilibili.com/video/BV1fN4y1D7Vp)  
 [Nickess，3.8深渊上半（瑶瑶北斗，0金）](https://www.bilibili.com/video/BV11m4y1j7iS)  
 [Nickess，3.5深渊下半（瑶瑶菲谢尔，0金）](https://www.bilibili.com/video/BV1Q24y1u7Qj)  
 [Nickess，3.4深渊下半（瑶瑶北斗，1金）](https://www.bilibili.com/video/BV1yM411e7mS)  
 [Nickess，3.3深渊上半（瑶瑶菲谢尔，0金）](https://www.bilibili.com/video/BV1SR4y1h7Tj)  

DPS参考：
> 0

---

#### 2. 烈绽放（水草火+草/火/风）

第四人不带水岩，理由同上。  
第四人为雷的情况归入超+烈绽放中。  
第四人为冰的烈绽待开发。  

##### ① 草X+草Y+水Z+火N（双草烈绽）

---

###### 瑶瑶 草主/柯莱 行秋 托马

> 0

评分参考：
> 输出： （环境-，配置-，练度-，手部-）  
 生存：  
 破盾：  
 成本：

手法参考：
> 0

视频参考：
> [Nickess，3.7深渊上半（柯莱，0金）](https://www.bilibili.com/video/BV12k4y1p72C)  
 [Nickess，3.6深渊下半（柯莱，0金）](https://www.bilibili.com/video/BV1Ez4y1Y7sT)  

DPS参考：
> 0

##### ② 草X+水Y+火Z+火N（双火烈绽）

---

###### 瑶瑶 行秋 托马 辛焱

> 0

评分参考：
> 输出： （环境-，配置-，练度-，手部-）  
 生存：  
 破盾：  
 成本：

手法参考：
> 0

视频参考：
> [Nickess，3.5深渊上半（0金）](https://www.bilibili.com/video/BV1zN411w7B4)  

DPS参考：
> 0

---

##### ③ 草X+水Y+火Z+风N（带风烈绽）

---

###### 瑶瑶 行秋 托马 砂糖

> 0

评分参考：
> 输出： （环境-，配置-，练度-，手部-）  
 生存：  
 破盾：  
 成本：

手法参考：
> 0

视频参考：
> [Nickess，4.0深渊上半（0金）](https://www.bilibili.com/video/BV1BG411R7jJ)  
 [Nickess，3.8深渊上半（0金）](https://www.bilibili.com/video/BV14x4y197Lc)  
 [Nickess，3.4深渊下半（0金）](https://www.bilibili.com/video/BV1Ss4y187AH)  

DPS参考：
> 0

#### 1&2. 超+烈绽放（草水雷火）

##### ① 草X+水Y+雷泽+班尼特(6)

---

###### 柯莱 行秋 雷泽 班尼特(6)

> 四星版彩虹雷泽

评分参考：
> 输出： （环境-，配置-，练度-，手部-）  
 生存：  
 破盾：  
 成本：

手法参考：
> 0

视频参考：
> [Nickess，4.0深渊下半（0金）](https://www.bilibili.com/video/BV1qK4y1c7Kw)  
 [Nickess，3.8深渊下半（0金）](https://www.bilibili.com/video/BV1uP411t778)  
 [Nickess，3.5深渊上半（0金）](https://www.bilibili.com/video/BV17s4y1H7nr)  
 [Nickess，3.4深渊上半（0金）](https://www.bilibili.com/video/BV11D4y1T7Dk)  

DPS参考：
> 0

---

##### ② 草X+水Y+雷Z+托马

---

###### 瑶瑶 行秋 菲谢尔 托马

> 0

评分参考：
> 输出： （环境-，配置-，练度-，手部-）  
 生存：  
 破盾：  
 成本：

手法参考：
> 0

视频参考：
> [Nickess，3.6深渊上半（0金）](https://www.bilibili.com/video/BV1pT411n7CE)  
 [Nickess，3.5深渊上半（0金）](https://www.bilibili.com/video/BV1fV4y1X7L1)  
 [Nickess，3.3深渊下半（0金）](https://www.bilibili.com/video/BV1Xy4y1Q7De)  

DPS参考：
> 0

---

#### 3. 冻绽放（水草冰+草/水/冰/风）

第四人是火/雷/岩干扰反应，不考虑。  
原理为“冻结护草”，见带冰超绽一节。  
主要的水系选择为芭芭拉，可以用行秋但是比较浪费，也可以坎蒂丝但缺乏开发。  

芭芭拉冻绽原理：  
i) 水环附着序列为100/100/000/000/000/000/000/000（"bug"修复前为8个"100"而不是2个），刷新时间2.5s，对每个单位独立  
ii) 水环附着判定间隔为1.5s，但当有单位进入水环时，立即对水环接触的所有单位进行一次附着判定  
iii) “冻结护草”  

##### ① 草X+草Y+水Z+冰N（双草冻绽）

---

###### 瑶瑶/绮良良/草主/柯莱（四选二） 芭芭拉 罗莎莉亚/迪奥娜

> 最常见的冻绽。配队选择不少，但是非常吃怪物阵容、聚怪操作以及元素论水平。  

评分参考：
> 输出： （环境-，配置-，练度-，手部-）  
 生存：  
 破盾：  
 成本：

手法参考：
> 0

视频参考：
> [时雨琦罗，4.1深渊12-1下半&12-2上半（草主柯莱迪奥娜，0氪0抽）](https://www.bilibili.com/video/BV1EV411c7yz)  
 [时雨琦罗，4.0深渊12-3上半（草主柯莱迪奥娜，0抽）](https://www.bilibili.com/video/BV1nu4y147eP)  
 [弹药福娃，3.8深渊上半（绮良良柯莱罗莎莉亚，0金）](https://www.bilibili.com/video/BV1Ju4y1d7dX)  
 [Nickess，3.8深渊上半（瑶瑶柯莱罗莎莉亚，0金）](https://www.bilibili.com/video/BV1v8411U7Su)  
 [Nickess，3.6深渊下半（瑶瑶柯莱罗莎莉亚，0金）](https://www.bilibili.com/video/BV1bh4y1p7b9)  

DPS参考：
> 0

---

##### ② 草X+水Y+冰M+冰N（双冰冻绽）

---

###### 柯莱 芭芭拉 凯亚 罗莎莉亚

> 双冰版本，由于同色缓解了充能压力，可以选择一些高倍率的冰系后台输出增加队伍直伤。  

评分参考：
> 输出： （环境-，配置-，练度-，手部-）  
 生存：  
 破盾：  
 成本：

手法参考：
> 0

视频参考：
> [Nickess，4.1深渊上半（0金）](https://www.bilibili.com/video/BV11C4y1d7Bm)  

DPS参考：
> 0

---

##### ③ 草X+水Y+冰Z+风N（带风冻绽）

---

###### 草主/柯莱 芭芭拉 罗莎莉亚 砂糖

> 0

评分参考：
> 输出： （环境-，配置-，练度-，手部-）  
 生存：  
 破盾：  
 成本：

手法参考：
> 0

视频参考：
> [Nickess，3.8深渊上半（草主，0金）](https://www.bilibili.com/video/BV1AM4y1s74g)  

DPS参考：
> 0

---

#### 4. 原/卡绽放（水草）

暂缺

### （五）未分类/时代眼泪

收录一些未分类，或者因为强度问题不再上场的队伍。  

[雷泽 菲谢尔 迪奥娜 行秋，香香怪coco，1.3~1.4深渊下半（0金）](https://www.bilibili.com/video/BV1BK4y1m7Yg)  
[砂糖 北斗 菲谢尔 迪奥娜，鐮夜，1.5深渊半（0金）](https://www.bilibili.com/video/BV1564y117Hc)  
[香菱 菲谢尔 砂糖 迪奥娜，香香怪coco，1.6深渊上半（0金）](https://www.bilibili.com/video/BV1Tv411H7Ua)  
[班尼特 行秋 凯亚 重云，香香怪coco，1.6深渊下半（0金）](https://www.bilibili.com/video/BV1Tv411H7Ua)  
[班尼特 行秋 凯亚 重云，香香怪coco，2.0深渊上半（0金）](https://www.bilibili.com/video/BV1244y117rA)  
[香菱 菲谢尔 迪奥娜 风主，香香怪coco，2.0深渊下半（0金）](https://www.bilibili.com/video/BV1244y117rA)  
[香菱 班尼特 风主 雷泽，评论区说客，2.6深渊下半（0金，低配三星武器）](https://www.bilibili.com/video/BV16u411i7TF)  

## 四、纯四星最大配队示例

“最大配队”——不使用重复角色，尽量多地组出有满星强度的队伍：

1. 班尼特蒸融  
   > 班尼特 香菱/烟绯 (凯亚 罗莎莉亚)/(行秋 任意雷风冰甚至草岩)  

2. 砂糖武装/激化  
   > 砂糖 菲谢尔 北斗 行秋/瑶瑶  

3. 伤命打纯风  
   > 珐露珊 鹿野院平藏 琳妮特/重云 莱依拉  

4. 超绽/冻绽  
   > 草主 柯莱 芭芭拉/坎蒂丝 久岐忍/迪奥娜  

5. 刮痧纯岩  
   > 诺艾尔 五郎 凝光 云堇  

6. 刮痧物理  
   > 雷泽/辛焱/菲米尼 米卡 多莉 丽莎/托马/绮良良  

7. 剩余角色  
   > 卡维：可选种门，但需要行秋  
   早柚：可选融化，替换罗莎莉亚启动泥头车  
   九条：可选砂糖武装换行秋打纯雷，一风三雷缓解充能问题  
   安柏：可选融化，替换香菱打融化核爆，需要高命高练高手部乘区  

## 五、纯四星配队角色强度锐评

---
---

T0-公务员  
> 行秋 班尼特 香菱  

T1-常客  
> 菲谢尔 北斗 砂糖 凯亚 罗莎莉亚  

T2-强力对策  
> 鹿野院平藏 珐露珊(6) 瑶瑶 旅行者(草) 柯莱 久岐忍 重云  

T3-偶尔能上  
> 珐露珊(0~5) 琳妮特 芭芭拉 烟绯 绮良良 托马 迪奥娜 莱依拉 夏洛蒂  

T4-仅限整活  
> 旅行者(风) 旅行者(雷) 雷泽 菲米尼 卡维 坎蒂丝 早柚 丽莎 凝光 诺艾尔 五郎 云堇 旅行者(岩)  

T5-难以配队  
> 米卡 多莉 辛焱 安柏 九条  

T6-登峰造极  
> 旅行者(水)  

---
---

T0  
行秋：低配即可挂水，高配还有不错的对单直伤。稳定减伤。  
班尼特：巨量攻击拐+治疗，双冰双火队还可以通过e打不少直伤。  
香菱：稳定后台挂火，纯四星最高上限配队砂国，0命伤害爆炸，高命更加爆炸。  

---

T1  
菲谢尔：砂北皇核心之一，激化队的灵魂。  
北斗：砂北皇核心之二，稳定减伤，对双倍率怪，E上限高。  
砂糖：砂北皇核心之三，削抗+聚怪+挂元素+协同攻击发射器+精通拐。  
凯亚/罗莎莉亚：双冰双火常用，整体伤害不如带行秋但是够用。  

---

T2  
鹿野院平藏：砂国代餐鹿国，省下砂糖组成砂北皇。高命时带珐露珊也可以速切。  
珐露珊(6)：风系伤命打配队。  
瑶瑶：砂北皇+瑶瑶激化队，伤害比砂武略低，但生存压力低且能省下行秋。也可以进单/双草行秋种门。  
旅行者(草)/柯莱：低配种门后台挂草位。保证充能和正确的轴时附着量勉强够用，但最大问题是画地为牢。  
久岐忍：低配种门核心，可用低配置解决一些boss从而省出强力角色给另一路，但上限较低。  
重云：双冰双火可选，倍率低产球少，但是可附魔破盾快。  

---

T3  
珐露珊(0~5)：充能压力大，四星风C持续输出乏力，输出上限不足。  
芭芭拉：低配种门前台挂水位，代替行秋。超绽放中直伤对单吃亏，对群效果还可以，有治疗专打流血狗。原绽放尽管水环被削仍有足够伤害，前提是环境合适。  
烟绯：最强火前台，但最大的问题也在于是前台，难以跟香菱竞争。烈绽较冷门且刚需行秋。  
绮良良：草盾，长E人下人机制，四命前毫无后台挂草基本与四星种门绝缘，但偶尔能客串激化队。  
托马：火盾+火后台，由于四星队塞不下纯辅一般打烈绽。由于西风枪的高白值和没有祭礼枪，充能精通很难兼顾，1秒间隔上限还可以，真对群比超绽舒服。  
迪奥娜：冰盾奶，功能性强，但由于纯四星永冻伤害比较拉胯，出场率较低。但偶尔能进冻绽放，6命加精通也有应用场景。  
莱依拉：冰盾，大多数时候为迪奥娜下位，但是唯一能带千岩的四星盾辅，有时有特殊左右。  
夏洛蒂：治疗冰法，可作为超绽驾驶员，或冻绽冰位等。  

---

T4  
旅行者(风)：实在没风系角色时的聚怪选择，用于对付骗骗花、镀金旅团等。  
旅行者(雷)：练度碾压时的充能插件，比如雷主国家队等。  
雷泽：物理大剑，平民不友好。可以玩超绽/彩虹。  
菲米尼：物理大剑，平民不友好。可以当超绽驾驶员。  
卡维：草前台。打种门设计矛盾，打输出伤害不足，大部分时候只能当前台挂草工具人。  
坎蒂丝：水后台+水附魔，范围挂水效果还可以，满命可在种门中勉强代替行秋，蒸发体系比较吃厨力。  
早柚：风奶+泥头车，泥头车强制站场且无法协同攻击，属于人下人机制，但娱乐效果尚可。  
丽莎：雷后台，蓄力E属于人下人设计，但由于减防，在练度碾压时可以进很多队伍客串，如丽莎国家队等。  
凝光：岩速切，对单暴力，但索敌高血压。  
诺艾尔：岩站场大剑主C，比较刚需满命，平民不友好，练度需求高，属于老玩家/华馆常客的玩具。  
五郎：岩辅，四星纯岩队组件之一，命座需求大。  
云堇：岩辅，四星纯岩队组件之一。  
旅行者(岩)：岩辅，四星纯岩队不常见的组件，倍率不错，甚至能拐暴击，但岩柱过胖导致体验很差。  

---

T5  
米卡：物理辅，压力给到主C，同时还有修女这种强力竞争对手。  
多莉：雷充能拐+奶，但雷直伤的砂北皇不缺充能治疗，超激化没位置，后台挂雷对伤害贡献又没有。  
辛焱：火盾/物理大剑，前者不重要可替换角色多，后者平民不友好。  
安柏：火弓，嘲讽+充能拐+高频挂火，但是确实干不过香班。  
九条：雷攻击(爆伤)拐，过于充能大户，机制勉强，可以强行就业纯雷。  

---

T6  
旅行者(水)：强度反向登顶，整活一骑绝尘。

---
