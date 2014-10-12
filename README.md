oh-my-variable-names
====================

给你的变量取个好名字~

---

编程中有一些事,重要之极,非做不可，虽然每天接触，却又常常让人不知如何下手

给变量命名便是其一

对于新手而言，就更是如此了

近来又翻了一遍《代码大全》(《CODE COMPLETE》)，读到第十一章《变量名的力量》，其中谈论了许多实用的技巧，和具体例子，真是觉得字字珠玑，整理摘录过来，方便自己查阅，也分享给大家

有好的建议也欢迎Pull Requests


##  引言:一个糟糕的例子
java示例

```
x = x-xx;
xxx = fido + SelesTax( fido );
x = x + LateFee( x1 , x ) + xxx;
x = x + Interest( x1 , x );
```

你能看出它是干什么的吗？x,xx,xxx代表什么？fido又是什么意思

这段代码其实是基于一项余额和一组新开销来计算一位顾客的支付总额。

下面是另一种写法

```
balance = balance -lastPayment;
monthlyTotal = newPurchases + SelesTax( newPurchases );
balance = balance + LateFee( customerID, balance ) + monthlyTotal;
balance = balance +Interest( customerID, balance );
```
一个好的变量名让一段代码清晰可读，让其成为不需注释的自说明代码

##  最重要的命名注意事项
...
##  以问题为导向

##  最适当地名字长度

##  作用域对变量名的影响

##  变量名中的计算值限定词

##  变量名中的常用对仗词

##  为循环下标命名

##  为状态变量命名

##  为零时变量命名

##  为布尔变量命名

##  为枚举类型命名

##  为常亮命名
