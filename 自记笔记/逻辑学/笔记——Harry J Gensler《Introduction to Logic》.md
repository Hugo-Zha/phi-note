内容来自《Introduction to Logic（Third edition）》by Harry J Gensler

Third edition published 2017 by Routledge

英文渣，配合划词程序硬读

不知道专业术语，这下瞎学了（就当学英语吧）

欢迎感谢超级感谢指出我的误读

翻译3年多怎么还没出555





# 1介绍

## 1.1Logic

逻辑是对论证(argument)的分析和评价(appraisal)

——检验各个领域的推理(reasoning)

——阐明(clarify)和评估推理的工具

## 1.2Valid arguments

论证(argument)

是一组前提(premises)——支持的证据(supporting evidence)

加上

结论(conclusion)——以证据为基础(based on this evidence)

论证(argument)——推理文字化



有效论证(valid arguments)

——前提真结论假的对立面

（若前提真结论假，则不可能是有效论证）



"有效"——前提不一定真——结论一定由前提推出

——若前提真，则结论一定真



有效：

若A则B                                    

非B                                                                       

 ∴ 非A    



（Valid：

If A then B 

Not-B

∴ Not-A）



论证有效——形式正确



无效：

若A则B                                    

非A                                                                       

 ∴ 非B  



（Invalid：

If A then B 

Not-A

∴ Not-B）



此处第二个前提（非A）仅仅否定了第一个前提中的若A

而第一个前提(若A则B)确立了A蕴含于B中，即非A仍然可能是B

——无效



同理，前一个有效则是因为否定了第一个前提中的则B

而第一个前提(若A则B)确立了B蕴含A，即非B不可能是A



## 1.3 Sound arguments

有效论证——前提真结论假的对立面

合理论证——论证有效且前提皆为真

不合理：(1)前提有误(2)结论不能由前提得出

（批评对手的论点的两方面——但其结论仍然可能为真）

第三种策略——证明前提不确定(uncertain)



陈述(statements)——正确或错误

论证(arguments)——有效或无效



以上的论证都是演绎(deductive)

归纳(inductive)论证——结论只被宣称(claim)遵循概率(而不是必然性) 

# 2Syllogistic Logic

三段论——最早亚里士多德

## 2.1Easier translations

凡L是C

g是L

∴ g是C

(all L is C

g is L

∴ g is C)



大写字母表示普遍的类(general categories)

小写字母表示特殊个体(specific individuals)



其中

合法的语句(grammatical sentences)

——完构式wffs(well-formed formulas)

包含“all” “no” “some” “is”“not”和大小写字母

一定是以下八种形式之一


wffs形式暗示(implications)了是用大写还是小写：

1.单词(而不是字母，如all)开头时：

皆为大写字母(如some C is D)

而如some c is d则不合法

2.字母(而不是单词，如A)开头时：

第一个为小写(如g is C)，第二个字母可大可小

而如G is C则不合法

下面是练习题，书后和附录有答案

可以配合作者的这个软件练习![image-20211104184756011](C:\Users\HugoZ\AppData\Roaming\Typora\typora-user-images\image-20211104184756011.png)

## 2.2The star test

三段论

——垂直顺序书写的一个或多个wffs组成的序列(vertical sequences)

其中每个字母出现两次——形成一个链(form a chain)

(若wff数>1

每个wff至少有一个与下一个wff相同字母

第一个wff与最后一个WFF至少有一个相同字母)

(最后一个wff是结论,其他wffs是前提)



特殊：

∴ all A is A

——无前提的三段论(premise-less syllogism)

只有结论不可能假时才有效



Distribution
周延性——

在“all”“no”“not”后面的字母

（即其所有内容都皆被指涉出）

即下图下划线出的 ![image-20211104184956098](C:\Users\HugoZ\AppData\Roaming\Typora\typora-user-images\image-20211104184956098.png)

则

“all”后第一个字母是周延的，但第二个不是
“no”后两个字母都是周延的
“not”后字母是周延的

## Star test

1下划线周延的字母

2标星

前提下划线的字母标星，结论没有下划线的字母标星

3数星

当每个字母恰好只被标了一次，同时右边恰好好只有一个字母标星时——有效



一个有效的三段论必须满足两个条件：

1.每个大写字母在一个实例中只能标一次星(小写字母可以任意次)

2.右边(“is”或“is not”后)只有一个字母标星

补充：与“中项在前提中可以周延两次”矛盾
来源:

KyuSan的回答 - 知乎 https://www.zhihu.com/question/296085577/answer/514535973

即只在如下情况：

all A is B

no C is A

∴ some B is not C



## 2.3English arguments

首先凭借直接(intuition)

接着符号化(symbolize)检验

——训练了逻辑直觉

——既凭直觉又靠公式(mechanically)，更可能发现符号错误(capitalization errors)

## 2.4Harder translations

实际中要讲语言翻译成“all” “no” “some”

“every” “only”——all

下图为“all” “no” “some”的不同表达 ![image-20211104185043772](C:\Users\HugoZ\AppData\Roaming\Typora\typora-user-images\image-20211104185043772.png)

![image-20211104185058740](C:\Users\HugoZ\AppData\Roaming\Typora\typora-user-images\image-20211104185058740.png)

![image-20211104185112815](C:\Users\HugoZ\AppData\Roaming\Typora\typora-user-images\image-20211104185112815.png)

“all A is B” 与 “some A is not B”是对立的(contradictories)

“some A is B” 与 “no A is B”是对立的

## 2.5Deriving conclusions

得出结论：
结论两个字母都是大写：

若每个前提都以“all”或“no”开头则结论用“all”或“no”，否则结论用“some”



结论至少一个小写字母：

结论：一个小写字母+“is” 或“is not”+另一个字母



若前提中有“no”或“not”： 

——得到否定的(negative)结论

前提“all” “all” 得到“all”结论

前提“all” “no” 得到“no”结论



任何前提“some”得到“some”结论



若前提有一个小写字母，结论有两个大写字母：结论用“some”



若推论无效——试试能否反转结论中的字母使它有效

## 2.6 Venn diagrams

维恩图——更直观

——用三个重叠的(overlapping)圆来画出前提

——只应用于传统的三段论(没有小写字母的双前提三段论)

如图![image-20211104185354094](C:\Users\HugoZ\AppData\Roaming\Typora\typora-user-images\image-20211104185354094.png) 三个圆重叠(overlap)的中心区域，包含所有三个特征(features)(A、B、C)

阴影——空(empty)

无A是B：

![image-20211104185411817](C:\Users\HugoZ\AppData\Roaming\Typora\typora-user-images\image-20211104185411817.png)

“×”——至少包含一个实体(entity)——未指定的(可空可非空)

有A是B：

![image-20211104185425374](C:\Users\HugoZ\AppData\Roaming\Typora\typora-user-images\image-20211104185425374.png)

有A非B :

![image-20211104190603248](C:\Users\HugoZ\AppData\Roaming\Typora\typora-user-images\image-20211104190603248.png)

操作顺序：

1.画三个重叠的圆，每个都用字母标记

2.首先用阴影画“all”和“no”的前提

3.然后用“×”在无阴影区域画“some”的前提

当“×”可以在无阴影区域中的任何一个时——论证无效

如图 ![image-20211104192803833](C:\Users\HugoZ\AppData\Roaming\Typora\typora-user-images\image-20211104192803833.png)

2.7 Idiomatic arguments
习惯论证
现实生活中论证——费解(convoluted)的措词、无关(extraneous)的材料

表示前提![image-20211104192908185](C:\Users\HugoZ\AppData\Roaming\Typora\typora-user-images\image-20211104192908185.png)


表示结论![image-20211104193014769](C:\Users\HugoZ\AppData\Roaming\Typora\typora-user-images\image-20211104193014769.png)


重建论点时，先找结论，再符号化前提和结论

2.8 The Aristotelian view
“亚里士多德学派”和“现代学派”在某些三段论有效性上存在分歧

空词——关于不指涉任何实在物

empty terms (general terms that don’t refer to any existing beings)

![image-20211104193041429](C:\Users\HugoZ\AppData\Roaming\Typora\typora-user-images\image-20211104193041429.png)

如上中

有猫和有独角兽——额外的假设——前提(assumed additional premise)



亚里士多德——每个词至少指涉一个实在物

即认为上论证有效

现代(modern)逻辑学——允许empty term

如下认为上论证无效 ![image-20211104193057993](C:\Users\HugoZ\AppData\Roaming\Typora\typora-user-images\image-20211104193057993.png)

亚里士多德观点下：

星号测试：每个大写字母至少一个星号(而不是“恰一个”)

维恩图：加上无阴影区域的圆区域加上×”——非空 