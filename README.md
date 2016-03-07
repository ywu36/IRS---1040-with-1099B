# IRS---1040NR-with-1099B
北美留学生股票报税终极指南：

今天终于把税务问题解决了，今年报税由于有了股票和基金略显焦灼，google相关信息不多，写一个总结放上来给大家分享．
需要提交表格：1040NR, 8843, W2, 1042S, Schedule D (affiliated to 1040NR), 8949, 1099-DIV


详细说明（具体情况还需要具体分析，如下只是我的填表经历）:
＝＝＝＝＝＝＝＝＝＝＝＝＝＝＝＝＝＝＝＝＝＝＝＝＝＝＝＝＝＝＝＝＝＝＝＝＝＝
1040NR:
一．如果结婚了，non-resident alien只可以选择: marriage filing seperate.　
(1) 代价：Captial lost只可以报1,500,而single可以报3,000
(2) Capital gain起征点不同，需要详细查明
２．有1099-DIV需要填写 Schedule NEC，因为股票分红属于周期性收益
３．有1099-B需要填写schedule D以及（或）8949

二.　1040NR填表规则：
line 8: Ｗ2工资单上写的
line 14:计算后的capital gain/loss,　详见schedule D
line 22:写上5000，对应的schedule OI里面L(a)：China; L(b):20(c) ; L(d):$5,000 (这是1984年赵紫阳签的tax treaty协议，当时$5000可不少呢）
line 23: line 8 + line 14
line 36, 37，３９: same as 23
line 40:需要查询今年个税起征点
line 41: line 39 - line 40
line 42:需要查询个税表格
line 45, 53: same as line 42
line 54: 分红税 (computed from schedule NEC)
line 61*:line 53+ line 54 : 这是全年需要交的税！
line 62a: W2扣税数额
line 71 same as line 62a
line 72*: line 71 - line 61, 这是全年退税额！

三. 1040NR-schedule NEC填表规则
1. 这张表对应着1099-DIV
2. 因为留学生分红全部按照30%收税，所以直接在１a或1b上填写总额，并在line 15里算出乘以30%后的数额即可，把line 15填入1040NR的line 54.

四. Schedule D填报重点：　小心wash sale
这是炒股的同学们报税最复杂的一项工程，我前后投入了至少２０个小时才最后明白每笔交易．但这只是我自己的理解还希望大神们纠正．
1. 需要准备好1099B（们）
2. 如果你的broker很负责的在1099B统计了所有的交易并且在1099B上标注了basis was reported to the IRS，那么你稍微可以心中窃喜一下．因为你只需要check一件事情，就是年底前有没有wash sale就可以直接把数额填到part 1a 中了
3. 如果你的brocker很邪恶的把某些交易搞乱了，比如连玩石油比如ＵＣＯ的同学可能会发现broker把你的交易单放在了一张表上而且有很多ＮＡ，那么很不幸的告诉你，你需要自己把每笔交易通过查询交易记录写到8949(with box B checked)，并自己统计wash sale．
4. 最后统计完成后，把1a和2b的值相加放到line ７里面
5. 如果基金里产生了capital distribution请放到line １３里面．
6. 如果持有一年之内的按照short-term capital算，超过一年按照long-term capital算．税率不同，同学们请自行查表
7. 勾上line 17后最后把数额填到line 18或line 21内

五．Form 8949
根据IRS的instruction，如果broker把所有的basis reported to the IRS就不用写这个了．如果没有的话你需要人工统计每笔交易,with box B checked.但你需要小心wash sale．
Wash sale*:
这个是老大难了.IRS自己都说不清楚,请自行科普下什么叫wash sale. 大多wash sale已经被broker统计在1099B中上报IRS了.但也有例外:
1. 如果两个账户进行wash sale
1. Wash sale虽然很难统计,但大多数wash sale并不影响最后退税, 因为当你产生wash sale后卖出,wash sale就被清洗了.这里还有一些诀窍避免wash sale的影响.
1) 如何避免对税务产生实质影响:
方法1: 尽量避免12月份卖出,1月份买入
方法2: 12月份close任何之前产生了wash sale的交易.提前卖出那些股票,避免带到下一年.
2) 什么情况下wash sale不被broker所统计:


我最后没弄懂的问题：
１．Capital dividend填到schedule ＮＥＣ上还是1040NR里的10b里,　我个人倾向于填到schedule NEC里．更符合ＩＲＳ对于dividend的描述
２．如果1099B里with box A checked的交易里有wash sale，需要填入8949里的1a还是8949里的1b（那就累死爸爸了要）．我之前填入了１a，但g里就不能填入adjustment金额了.我处理的方法是用e减去了g凑够了h.
