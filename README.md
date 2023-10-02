# 完全洗点+MOD内容扩展情况下的队友职业RP加点思路
## 前言

编写这个MOD向队友BD思路，主要目的是给我的老婆用，有些可能不合理，最佳BD也不是一成不变的，完全看队伍搭配和玩法思路。 打不公平难度是绰绰有余的。

**MOD来源和使用方法为以下两个网站**：

- **MOD中文介绍、下载链接和外挂汉化工具**：[【正义之怒】内容扩展型MOD收集计划](https://github.com/nixgnot/WOTR-CONTENTS-MODS-CN)，看到这里写的**新职业、新专长和新法术**之类在这个网站里 Ctrl+F 搜索文本找到对应MOD。
- **MOD安装方法**：[如何为拥王者或正义之怒安装MOD](https://github.com/1onepower/KM-WotR_Modding_Wiki/blob/main/%E4%B8%AD%E6%96%87%E7%89%88.md)
- 临时分享的 ACTestingGrounds 的完整汉化文件 [ACTestingGrounds.zip](https://github.com/nixgnot/WOTR-CONTENTS-MODS-CN/files/12715542/ACTestingGrounds.zip)。配合[MOD外挂汉化工具QuickLocalization](https://github.com/nixgnot/WOTR-CONTENTS-MODS-CN#mod外挂汉化工具quicklocalization)使用。

**所谓完全洗点以后还要RP向，这个又是什么意思**？

- 完全洗点指，用[**Respec Mod**](https://github.com/BarleyFlour/RespecMod)洗到0级开始加点重选职业和属性分配；

- **RP向主要是满足以下条件**：
  - 不改变总购点。
  - 不改变背景。
  - 不改变队友主要属性构成，比如席拉是主力量副魅力，不会改成主力量和副感知。
  - 不改变队友种族。
  - 除了索希尔以外保证队友信仰不变，这个主要是完全洗点MOD会导致索希尔洗点为圣使以后不能选择雪琳主神，导致失去圣使领域掌控拿到的次领域法术。
  - 初始职业尽量符合队友初始画风和剧情，比如小烬有炭化诅咒和庇护主，小贼是有施法能力的近战游荡者，聂纽是知识渊博的施法者（智力高）、索希尔是牧师、席拉是圣武士、柯米丽雅是萨满、雷吉尔是地狱骑士、岱兰有知命诅咒（它者）、加钱哥是杀手。

## 特别注意！！！！

- **TabletopTweaks-Base** 这个MOD虽说是桌面化调整，事实上也存在各种私设的修改（是桌面规则里完全没有的部分，属于作者私货），其中有部分是历史遗留问题，但是游戏本身修复了以后，这个部分作者就是不删，也不默认关闭，强推自己的私货。**这也是现在又不推荐纯新人装TTT的原因**。你需要按照自己的需求关闭其中很多的改动。
  - 在BUG修复部分，某些原版后面明确改动，表明不再是BUG的玩意，作者也给当成BUG修复了。比如神话专长可以多次换为神话能力，TTT还当成BUG修复保留着，还是默认开启，这就很蠢了。我记得这MOD是叫桌面化调整MOD而不是游戏平衡性调整MOD吧。
  - 有些原版已经用不同方式修复的BUG，作者也没有把这个部分删除，比如敌人预BUFF的施法者等级，TTT里敌人的施法者等级是按照敌人生命骰来计算的，这就很不符合常理，难道敌人一个个都能是超20cl的施法者？而原版在预BUFF的施法者等级上的修复更好。比如元素狂潮，原版当成BUG修复了，TTT-BASE里的元素狂潮还是另一套。
  - 还有就是强行桌面化调整导致看上去很蠢的行为，比如顺势斩系列削弱，然后让你强行点出 神话顺势斩 来恢复成原版的顺势斩系列的效果。甚至有部分改动让我怀疑作者连基本的规则书都没读懂，比如作者把剑圣的4级完美重击变成需要消耗2奥能（我直接？？？？），喜欢的可以去 d20pfsrd 网站读一下英文原文（搜索 kensai ---这个是剑圣的英文）。
- **TabletopTweaks-Rework** 这个MOD是作者基于自己考虑的各种平衡性修改，**全都是村规**（包括增效超魔变成升2环、神话精通重击削弱、诡计大师神话诡计改动、双持久需要10分钟才能变成24小时的改动等）。装这个MOD的话，**务必先关闭全部改动**，然后手动勾选自己喜欢的改动（一般就勾选 学派掌握 和 神话偷袭，这两个改动非常合理）。
- **目前连锁施法有BUG，队友用连锁施法只有固定的两次，不会随着神话等级提升**。

## 备选滥强职业

宁静德鲁伊（感觉适合小烬？）

## 目录

[TOC]

- [**席拉**](#席拉)
- [**柯米丽雅**](#柯米丽雅)
- [**兰恩**](#兰恩)
- [**雯朵格**](#雯朵格)
- [**沃尔吉夫**](#沃尔吉夫)
- [**小烬**](#小烬)
- [**聂纽**](#聂纽)
- [**岱兰**](#岱兰)
- [**索希尔**](#索希尔)
- [**雷吉尔**](#雷吉尔)
- [**爱露莎蕾**](#爱露莎蕾)
- [**葛雷博**](#葛雷博)
- [**乌布里格**](#乌布里格)

## 队友BD思路

### 席拉

初始购点：28

#### 14圣武士1受诅巫师1鳞甲之拳1启迪贤者+3级随意

拿长剑，转无甲以后搭配 圣战连击（长剑）+神圣武器技法（爱奥梅黛），禁忌学识可以扩表拿法师法术护盾术等，配合圣武士4环死亡化身和次元斩击，属于是能抗能打，辅助能力一流。

**加点**：18力、13敏、12体、10智、10感、17魅



### 柯米丽雅

初始购点：32

#### 6萨满10冬巫1混血术士3博学士

**简要介绍**：一切元素系转为寒冷，DC高、CL高、伤害高，相当于原本小烬加点的超级加强版。

**部分玩法和装备介绍可以参考此贴**：[（build推荐）最强咒法塑能师，不服来辩](https://tieba.baidu.com/p/8325404298)

> 核心MOD：
>
> - [TabletopTweaks-Base](https://github.com/nixgnot/WOTR-CONTENTS-MODS-CN#TabletopTweaks-Base)
> - [HomebrewArchetypes ](https://github.com/nixgnot/WOTR-CONTENTS-MODS-CN#HomebrewArchetypes)和 他的子MOD【AC】 
> - ~~[CharacterOptionsPlus](https://github.com/WittleWolfie/CharacterOptionsPlus) ---新增奥法血统（又称悠远血脉）~~
>
> 额外要求：手动取消TTT-BASE关于凛冬之握的改动、手动取消TTT-BASE关于博学士（Lore master）的削弱。
>
> 说明：
>
> - TTT-BASE修复了法术专精在部分进阶职业中不能更换的BUG。
> - TTT修复了冬巫8级转伤害导致伤害变低的BUG，所以冬巫可以加到满级了；
> - 【AC】里有连锁施法，可以获得相当于2+神话阶层的奥法契约。这样就算没有【流体魔法】扩表，靠连锁施法也可以把精魂法术玩出花了。【目前连锁施法有BUG，队友用连锁施法只有固定的两次，不会随着神话等级提升】
> - 目前存在一个BUG（原版就有），在计算巫术等级的时候，冬巫的等级不会跟萨满叠加，而是只计算萨满的等级。要用好邪眼，就需要保证萨满8级，所以只能放弃邪眼这类8级强化的巫术了。
> - 切换游荡精魂的时候，如果事先把精魂法术超魔并且放置在精魂法术位，则这个法术不会消失。所以通过切换游荡精魂+超魔，可以把每环的精魂法术都选成最好的。【这算是上面那个BUG的补偿吧】

**加点**：10力、16/17敏、12体、10智、20感、13/10魅

**这套加点的效果如下**：

- 由于水元素血脉可以将所有拥有元素描述符的法术（火焰、寒冷、酸蚀、电击和音波）转换为寒冷法术，所以都能吃到寒冷加成。
- 额外伤害骰是术士血脉（白龙和银龙）+2，<奥法歼灭革甲>+1，<寒齿>轻盾+1，超魔（法术增效）+2，元素注能法袍+2。
- 额外CL是冬巫+2寒冰，混血术兼职-1，纹身+1塑能。
- 额外DC是双专攻+2塑能，双元素专攻+2寒冷，冬巫+3寒冷，凛冬之握等效+2寒冷，~~奥术学派+2塑能，瞬发邪眼等效4DC~~
- 地狱烈焰射线一发可以60×12×1.5=1080。颂圣可以秒杀或者麻痹大部分敌人（有七罪法袍和灰烬制造者权杖的话）。还有风暴束、热风、凛冬之握等控制，也能放陨落术（切换精魂为-苍天）。还有双发赤焰击可以打40×12×1.5=780AOE。
- 关键是这套加点不跟主要奥术人抢装备，队伍可以再养一个完全体奥术人。

**专长加点**：

```
----通用道途加点参考--------------
1萨满：【魂域】：冰霜、【魔宠】：野兔、【种族替换】：技能专攻（神秘/世界）、元素专攻（寒冷）
2萨满：【巫术】：避灾
3萨满：高等元素专攻（寒冷）
4萨满：【巫术】：诵咒、【游荡精魂】---自由切换（比较关键是火焰、苍天等）
5萨满：法术专攻（塑能）
6萨满：获得【游魂巫术】（可以临时切出祈福等巫术、或者其他好用的巫术）
7冬巫：高等法术专攻（塑能）
8冬巫：【巫术】：超魔（法术顽强）
9冬巫：瓦瑞西安刺青（塑能）
10冬巫：【巫术】：超魔（法术增效）
11混血术士：法术专精（炽炎击）--升级以后自由替换、超魔（法术强效）、【血承】：水元素+银龙
12冬巫
13冬巫：擅长盾牌（这是为了使用圣教军模式合成的神器-<寒齿>轻盾）、【巫术】：超魔（法术延时）
14博学士：【法师法术】-地狱烈焰射线、
15博学士：精通先攻、【替换法术专精为地狱烈焰射线】
16博学士：【牧师法术】-颂圣之语、【替换法术专精为颂圣之语】
17冬巫：自选专长/法术穿透、
18冬巫：【巫术】：超魔（法术强化）
19冬巫：超魔（法术双发）/高等法术穿透/自选专长/异种武器擅长（穿甲剑）-为了拿<夜空闪>或者<位面抹灭者>、
20冬巫：【巫术】-冻皮（配合霜护，后期AC还挺高的）/自选
.
后面补法术穿透，主要是考虑到这个BD的装备加法穿比较少，而且TTT修复了结盟施法者，导致法穿不一定够用，如果够用的话就无所谓了。
```

**神话加点**：1连锁施法、2反应施术、3偏好超魔（增效）、4偏好超魔（强效）、5第二血脉（白龙）、6精通先攻（神话）、7偏好超魔（强化）、89学派掌握（塑能）/自选

**关键装备配置**：

- 武器盾牌：<紫色石刀>+<寒齿>、<灰烬制造者>、<夜空闪>+<寒齿>、<夜空闪>+<位面抹灭者>
- 戒指：<奔流之戒>、<纵火狂之戒>（加法穿用的）
- 法袍：无阻法袍、元素注能法袍、不宣之实法袍、七罪法袍、流水法袍
- 盔甲：元素杀戮革甲
- 护腕：灼热护腕

#### 精魂猎手

战斗自然域，TTT还原了萨满的显圣（即萨满魂域现在有类似先知秘示域的大招了），萨满在满级会有猛扑，但是可惜没做【流体魔法】（可以将精魂法术用普通法术位记忆，相当于扩表；没有这个巫术的话萨满的施法能力太差了），也没做知识魂域（可以偷6个法师法术）。所以BD维持原版纯职业走的九环近战，但是改变初始属性，以便前期更好地发挥辅助作用。

**加点**：10力、17敏、12体、10智、20感、10魅



### 兰恩

初始购点：31

#### 狩魔猎手/圣职杀手--[多重变体](https://github.com/Vek17/WrathMods-MultipleArchetypes)

狩魔猎手/圣职杀手是审判官完全体（偷袭骰+研究目标+战斗自然秘示域+扩表金鹰之魂和神使灵光，配合新法术死亡化身、次元斩击和神灵化身，前期就很强，8级开始就是超级战神），人类开局可以发挥最大强度，兰恩用这个也厉害。

**加点**：19力、18敏、12体、10智、18感、5魅；这里多了购点是混种人用洗点MOD的BUG，让兰恩可以额外选择一次种族加值，我们把他放感知属性上。

**专长加点**：

```
---通用加点参考---------
1猛力攻击、【秘示域】：战斗、【启示】：军械大师
3顺势斩
5强力顺势斩
6【团队专长】：包抄、【启示】：动物伙伴【注：这个是神话1的时候选择第二秘示域（自然）】
7终势斩
8【杀手特技】：异种武器擅长、【启示】：武器大师[武器专攻（斩矛）、精通重击（斩矛）]、【启示】：任意
9战斗反射、【团队专长】：双重借机
11精通终势斩
12高等武器专攻（斩矛）[源于启示：武器大师]、【团队专长】：抓准时机
13
15
16
后续超魔（法术延时）、精通先攻、粉碎防御等
```

#### 僧兵

兰恩洗点的僧兵不是完全体（相比人类少个专长，成型慢了），但是他的强度还是非常离谱。[MicroscopicContentExpansion](https://github.com/alterasc/MicroscopicContentExpansion) 这个MOD做了桌面的死亡化身法术，武僧用气力也可以释放死亡化身。导致僧兵6级直接变成绞肉机，攻击次数爆炸，额外AB爆炸，额外伤害爆炸，这个时候拿新月战斧配合锐锋术非常离谱。

**加点**：19力、18敏、12体、10智、18感、5魅；这里多了购点是混种人用洗点MOD的BUG，让兰恩可以额外选择一次种族加值，我们把他放感知属性上。

### 雯朵格

初始购点：25

### 沃尔吉夫

初始购点：31

#### 贼裔

【HomebrewArchetypes】的子MOD【ACTestingGround】，改沃尔吉夫职业为【贼裔】---自发施法版奥法暴徒+扩充魔战士奥秘（远见打击空间斩之类）。这个职业可以说也是个滥强，在奥法暴徒的基础上新增了5个【贼裔天赋】（可以用来选游荡者天赋），还多了直觉闪避。配合TTT的长臂咒，前期生存能力也很高，触及范围也不错。

**加点(保持不变)**：10力、20敏、12体、18智、10感、10魅

**技能**：灵巧、巧手、隐匿、察觉，最后给世界/使用魔法装置

**专长加点**：

```
---通用加点参考---------
1双武器战斗
2【贼裔天赋】：弱化创伤
3双斩
4【贼裔天赋】：奥法精准
5熟练偷袭者
6【贼裔天赋】：远见打击
7包抄
8【贼裔天赋】：战斗特技-精通双武器战斗
9突刺
10【贼裔天赋】：机会主义者
11精通重击（匕首）
12【贼裔天赋】：空间斩
13精通先攻
14【贼裔天赋】：野兔魔宠
15高等双武器战斗
16
有远见打击和空间斩了，就没必要去整什么粉碎防御了，后续可以补超魔（法术延时）、奥术打击等。还有一些MOD扩充的高等游荡者天赋也不错。或者整一些魔战士的法术超魔能力。
```

神话加点：1变化自如、2神话双武器战斗/待定、3大法师护甲/待定、4

### 小烬

初始购点：25

#### 炼药巫师/受诅巫师--[多重变体](https://github.com/Vek17/WrathMods-MultipleArchetypes)

**加点**：7力 16敏 12体 14智 10感 18魅

**简介**：平时用高DC的巫术（沉眠/冰冢/送葬），前期遇到大群敌人用咒法系法术群控（凛冬之握+冰矛术、闪光尘和臭云），中后期还可以用惑控系法术群控，打BOSS可以甩邪眼降低其豁免或者AC，加BUFF能力也不错（变巨、缩小、猫之轻灵、加速术、行动自如、防死结界、变形术、高等变形术）。炼药巫师可以给队友提供属性上的炼金加值（之前+2，10级以后+4），极其符合小烬的画风。巫术【凋零】+高等岁月抵抗还可以让队友额外多3点精神属性，属于是法系超级辅助。纯职也能拿巅峰的完化身心+8魅力，可以说非常不错了。

> 核心MOD：
>
> - [Tome Of The Fire bird](https://github.com/nixgnot/WOTR-CONTENTS-MODS-CN#TomeOfTheFirebird)，让受诅巫师可以选择庇护主
> - [CharacterOptionsPlus](https://github.com/WittleWolfie/CharacterOptionsPlus)，新增冰矛术和冰冢巫术等
> - [TabletopTweaks-Base](https://github.com/Vek17/TabletopTweaks-Base)，让炼药巫师变得可以选择，让基础职业获得巅峰（20级大招可以替换为其他能力，以前没有大招的则获得巅峰）。
> - [HomebrewArchetypes ](https://github.com/nixgnot/WOTR-CONTENTS-MODS-CN#HomebrewArchetypes)和 他的子MOD【AC】 ，新增连锁施法
>
> 额外要求：手动取消TTT-BASE关于凛冬之握的改动

```
1法术专攻（咒法）、机敏庇护主、渡鸦魔宠
2【巫术】：沉眠
3高等法术专攻（咒法）
5元素专攻（寒冷）
6【巫术】：邪眼
7高等元素专攻（寒冷）---元素专攻还可以给巫术【冰冢】加DC
9诅咒巫术
10【巫术】：冰冢
11分裂巫术
12【巫术】：凋零
13精通先攻
```

神话加点：1替换为神话专长-神话专攻（咒法），2反应施术、3连锁施法、4扩充战法（惑控）

#### 传古学者

我感觉游戏里小烬应该是先知，岱兰应该是受诅巫师（因为它者），可是毛子偏偏把这个反过来，现在我们直接拨乱反正。

> 核心MOD：
>
> - [TabletopTweaks-Base](https://github.com/nixgnot/WOTR-CONTENTS-MODS-CN#TabletopTweaks-Base)
> - [HomebrewArchetypes ](https://github.com/nixgnot/WOTR-CONTENTS-MODS-CN#HomebrewArchetypes)和 他的子MOD【AC】 
> - [CharacterOptionsPlus](https://github.com/WittleWolfie/CharacterOptionsPlus) ---新增奥法血统（又称悠远血脉）
>
> 额外要求：
>
> 说明：
>
> - [HomebrewArchetypes ](https://github.com/nixgnot/WOTR-CONTENTS-MODS-CN#HomebrewArchetypes)新增变体传古学者，可以每2级选择一个奥术法术添加到先知法表。

#### 研究法师/密契法师--[多重变体](https://github.com/Vek17/WrathMods-MultipleArchetypes)

加点：7力18敏20智，剩下全10

要素：有庇护主，有诅咒，奥术人，这不就是小烬么。这套加点要改主要属性，变成20智力开局，你可以适当把魅力加高一些以符合小烬的人设。BD跟聂纽那套一样

### 聂纽

初始购点：20，这个建议改成25，跟佣兵一个购点确实说不过去。

#### 研究法师/密契法师--[多重变体](https://github.com/Vek17/WrathMods-MultipleArchetypes)

这个多重变体我愿称为全游戏最强施法者，元素庇护主+知命诅咒，然后主塑能+（主角则是后期全能）。先攻无敌，DC和CL极高（强能魔法），豁免极高，有自发施法转换---伤害极高（第二章6级就可以将3环增效燃烧之弧等法术自发转换为增效的火球术，配合第二章强效超魔权杖打（10d6+20）*1.5的强效增效火球术，一发82.5期望，化身炸比）。

初始加点不变，背景需要改成奥术专家拿抄录卷轴，聂纽洗点需要到第二章做完任务，发现自己的真实身份以后才行。

**专长加点**：

```
---通用加点参考-----------
1法术专攻（塑能）、法术专精（法术飞弹）、【强能魔法】、【元素庇护主】
3超魔（法术增效）
5瓦瑞西安刺青（塑能）、【知命】、【快速研读】、【替换法术专精为火球术】
7超魔（法术顽强）
9精通先攻、【延时超魔】
11额外奥术发现：理想化
13超魔（法术强效）、【野兔魔宠】
15解法余波
17暴力解法、【超魔（法术强化）】
19超魔（法术双发）
```

神话加点1（队伍有其他九环奥术比如小烬加buff，或者有6环奥术人点了充裕施法的前提下才能这样玩）：1连锁施法、2偏好超魔（顽强）、3偏好超魔（延时）、4反应施术、5偏好超魔（增效）、6神话精通先攻

神话加点2：1充裕施法、2精通充裕施法、3偏好超魔（延时）、4反应施术、5高等充裕施法、6神话精通先攻

#### 敏剑圣

用来测试MOD环境的敏剑圣强度和玩法（不考虑用MOD还原元素狂潮这种），主要依赖的资源是源自MOD还原的魔战士桌面法术和能力。

这个BD算是集合了原版游戏仅存几个非道途相关的主要附伤BUG（将原版魔能射手法打的附伤BUG、接触伤害的附伤BUG、神话冲锋的附伤BUG），具体专长加点待实测。

预计的附伤如下：

- A类附伤：机敏之刃、法打（冻伤）、纵火狂之戒、马兰德的耻辱腰带、圣触（空间斩/~~次元斩击~~ 打接触攻击）、元素狂潮（被冰封禁制超魔以后一半转火焰触发）
- B类附伤：神话冲锋、破敌、神圣公正附魔、诡诈烈焰手套
- 配合道途附伤，一刀500+轻轻松松。可惜这套玩法不能用飞刃袭之类的法术战斗也不能用次元斩击了，施法会导致冻伤的持续效果消失（类似专注一样）。这套玩法敏剑圣或者双手力剑圣一样可以玩，只要学个元素超魔（火焰）就行。

**加点**：5力 20敏 13体 20智 7感 7魅

```
---通用加点参考-----------
1武器娴熟、自选武器（穿甲剑）
3优雅刺击（穿甲剑）、【魔战士奥秘】-奥法精准
5超魔（元素法术-火焰）、精通先攻
6【魔战士奥秘】-持久刀锋
7包抄
9精通重击（穿甲剑）
11灵狐猛扑、暂定
12【魔战士奥秘】-远见打击/空间斩
```

**神话加点**：1变化自如/充裕施法 2巅峰元素（火） 3元素狂潮 4神话冲锋

#### 研究法师

#### 法术大师

#### 卷轴专家



### 岱兰

初始购点：27

#### 海洋之声

加点和背景不变，初始秘示域改成战斗，主用音波系法术，海洋之声会将秘示域法术替换（2音鸣爆、4咆哮术、5狂乱之歌、6高等咆哮术、7辉煌启言），配合先知本身就有的颂圣之语+风暴束等。

#### 炼药巫师/受诅巫师--多重变体

我感觉游戏里小烬应该是先知，岱兰应该是受诅巫师（因为它者），可是毛子偏偏把这个反过来，现在我们直接拨乱反正。

### 索希尔

初始购点：30

#### 10圣使10观星者

这个加点要改信仰为璞露拉（因为洗点MOD不能重选雪琳信仰，导致索希尔洗点成圣使会缺少领域掌控的很多法术），主领域为防御子领域，次领域为幸运。【注：仅限索希尔洗点才能洗出来这样的，璞露拉本身是没有保护和幸运领域的。】

这样就是巫术（避灾+邪眼+冻皮/诵咒）+领域（防御+幸运+疯狂+星辰+联盟）+九环牧师BUFF+树肤工具人，可以主惑控用星辰子域6环的神威如岳/主塑能用颂圣。先攻由于有野兔魔宠和星座，共计额外+6，也不错。防御方面自带护盾术和10AC的类法师护甲。

玩法有两种：

- 要动物伙伴，则靠专长点出动物伙伴，配合【精通法术共享】【注：这个团队专长需要动物伙伴和索希尔一起点出来，但是动物伙伴身上的精通法术共享不要激活，只激活索希尔的；否则动物伙伴分享到的BUFF时间会虚空减半---因为会再平分给一个并不存在的角色】，养一个强力动物伙伴（说实话比起强力菜刀，动物伙伴的输出再怎么搞也是菜得抠脚，输出占比在5%左右，最多也就10%；要是你队伍各个位置都已经有成型队友，就不需要额外弄这种资源利用效率低的动物伙伴了）。
- [CharacterOptionsPlus](https://github.com/WittleWolfie/CharacterOptionsPlus) 有个默认关闭的选项，即共享法术（动物伙伴），还原了桌面的动物伙伴职业能力。开启以后，有动物伙伴的职业，可以把仅限自身的法术对动物伙伴释放。这个选项比 精通法术共享 会更好一些，因为这样还能吃到双持久的加成。
- 不要动物伙伴，主塑能系法术（观星者星座能力之一可以给火焰描述符的法术+2施法者等级）。

**加点**：14力、14敏、12体、10智、19感、14魅

### 雷吉尔

初始购点：30

#### 1鳞甲之拳4游荡者5突变斗士10地狱骑士

#### 12原怒者5突变斗士1鳞甲之拳1受诅巫师1地狱骑士

#### 16原怒者2鳞拳1受诅1地狱骑士

### 爱露莎蕾

保持谍报专家拿重弩，用神话专长-神话弩箭训练来做到敏上伤【来自HomebrewArchetypes的子MOD】，加上TTT恶魔宿敌合并到异界，伤害和AB瞬间就起来了。注意 ACTestingGround 会将爱露莎蕾的职业改成游荡者里的间谍专家，这样比原版游侠弱了（有表人直接退化成无表游荡者），自己洗点整回来吧。

### 葛雷博

#### 契约杀手

**简单介绍**：能短时间体上防+自带四环法表+送高等武器专攻、武器专精和高等武器专精（杀手天赋换的），比普通杀手强了很多，也不会过于脆弱了。还能跟异嗣杀手混合变体，变成契约杀手/异嗣杀手，对抗大体型敌人有额外研究目标加成。跟葛雷博的画风非常像。武器思路为要么双持手斧、要么双手巨斧（坟中歌者）。

> 核心MOD：
>
> - 【HomebrewArchetypes】和其子MOD【ACTestingGround】

### 乌布里格

#### 狮鹫之心
