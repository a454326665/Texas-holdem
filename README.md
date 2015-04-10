# Texas-holdem 
# 德克萨斯扑克（玩家对玩家的公共牌类游戏）
以下摘自 百度百科<br/>
德克萨斯扑克全称Texas Hold’em poker，中文简称德州扑克。它是一种玩家对玩家的公共牌类游戏。一张台面至少2人，最多22人，一般是由2-10人参加。德州扑克一共有52张牌，没有王牌。每个玩家分两张牌作为“底牌”，五张由荷官陆续朝上发出的公共牌。开始的时候，每个玩家会有两张面朝下的底牌。经过所有押注圈后，若仍不能分出胜负，游戏会进入“摊牌”阶段，也就是让所剩的玩家亮出各自的底牌以较高下，持大牌者获胜。

# 执行方法
1.将所有文件下载后执行SimpleWebSever.exe，该程序会开启一个web服务。（注意：请勿关闭窗口）<br/>
2.启动浏览器，在地址栏输入127.0.0.1:9999，可以查看执行结果。

# 程序实现要点

# 已完成部分
1.模拟将一副52张牌的扑克发给复数玩家。（每人5张手牌+3张公牌）<br/>
2.根据玩家的手牌及公牌，排出最佳组合。<br/>
	例如：公牌:[♦11]-[♦3]-[♥1] <br/>
	手牌：[♠9]-[♠11]-[♥9]-[♠13]-[♠10]    最佳组合： [♥1]-[♠9]-[♥9]-[♠11]-[♦11]
	手牌：[♦4]-[♣4]-[♦10]-[♣6]-[♠6]      最佳组合： [♥1]-[♦4]-[♣4]-[♣6]-[♠6]
	手牌：[♣2]-[♥8]-[♣8]-[♦5]-[♥5]       最佳组合： [♥1]-[♦5]-[♥5]-[♥8]-[♣8]
	手牌：[♠3]-[♦6]-[♥13]-[♣10]-[♠4]     最佳组合： [♥1]-[♠3]-[♦3]-[♠4]-[♦11]
	手牌：[♥2]-[♣5]-[♦12]-[♥10]-[♦9]     最佳组合： [♥1]-[♦3]-[♦9]-[♦11]-[♦12]
	手牌：[♣1]-[♠2]-[♥6]-[♦8]-[♥3]       最佳组合： [♣1]-[♥1]-[♥3]-[♦3]-[♦11]
	手牌：[♣12]-[♣3]-[♣7]-[♣11]-[♥11]    最佳组合： [♣3]-[♦3]-[♣11]-[♥11]-[♦11]
	手牌：[♣13]-[♠1]-[♠12]-[♦1]-[♣9]     最佳组合： [♠1]-[♦1]-[♥1]-[♦3]-[♦11]
	手牌：[♥12]-[♥7]-[♠5]-[♠7]-[♥4]      最佳组合： [♥1]-[♦3]-[♥7]-[♠7]-[♦11]

# 未完成部分<br/>
3.以此为基础制作成网页卡片游戏<br/>
4.以此为基础制作胜负概率计算器<br/>