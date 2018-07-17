# FirstE

***

__前言__

> The practice of Github.

此文档用于学习markdown在GitHub上的一些基本操作

![GitHub Logo](http://static.oschina.net/uploads/img/201304/17033907_yA2V.jpg)

[官方文档](https://guides.github.com/features/mastering-markdown/)

[内容参考](https://www.yaosansi.com/post/markdown-on-github/ "双引号添加链接说明,需要与链接在同一括号内")

***

__主要包括以下内容__

**有序列表为数字+一个英文句号**
1. markdown基础
2. 引用
3. 粗体和斜体
4. 删除线
5. 列表
    * 有序列表(\*号或\-)
    * 无序列表(嵌入式前面两个空格缩进)
6. 代码格式化
7. 链接和图片
8. GitHub扩展语法
9. 其它


图片测试: ![click](http://static.oschina.net/uploads/img/201304/17033908_N1hN.jpg)

***图片为\! + 方括号\[加入一些标识信息\] + 括号\(括号内为URL\)

### 基础内容

大部分markdown格式指令后需要一个空格然后接内容，否则会无效

就如#哈哈哈，该一级标题未生效

段落以单行或多行空白为界

如未留空则
回车也没用，要留空白行会分段

*先试试强调吧*

**再试试加粗(两个\*号或\_的加粗)**

*一个\*（或\_）号的强调*

***三个\*（或\_）号的斜体***

_看起来可以**复合**使用_

### 二级标题，代码格式化
> 代码引用主要用的反引号，位于数字1左边。
> 单行代码使用前后各一个反引号，多行时段前段后各3个反引号

` print("单行代码格式化") `

``` c
#include<iostream>
using namespace std;
void main()
{
   cout<<"多行代码格式化"<<endl;
}
```



### 关于标题以及删除号
> 标题大小由其前面有多少#号决定。
> 前后1 __`紧挨`__ 着两个“ ~~ ”既有删除号。(大部分需要空一格)

如

## ~~两个#号~~
#### ~~四个#号~~

### 表格

暑假干什么 | 寒假干什么 
--------- | ---------
contentone | contenttwo
test | consquence 

### 引用

[如何在 Markdown 中引用诗词或歌词](https://yihui.name/cn/2018/07/quote-poem/)

> ***在 Markdown 语法中，普通的换行（敲一下回车键）是没有意义的，它跟空格没有区别。  
只有在代码块中，普通换行才会被保留。在非代码环境中，如果需要一个硬换行，那么需要在行末加两个空格。***

> __图灵传__  
> 你可曾想象，所谓智能，其实是一大堆神经元之间，那些复杂而抽象的小动作？  
 你可曾想象，用蚂蚁代替神经元，将这个巨大的蚂蚁网络看成一个大脑？  
 你可曾想象，用晶体管代替神经元，让这个人工神经网络产生自主思想？  
 你可曾想象，用软件来模拟这个结构，使一台普通的计算机拥有智能、灵魂和自由的意志？  
 你可曾想象，无论是生物还是电子，各种不同的物理基础都能产生思维和感觉？  
 你可曾想象，一台机器能够流畅地使用人类的语言，与人类一起畅所欲言？  
 你可曾想象，这台口齿伶俐的机器，其实如计算器和打字机一样，空虚而缺乏思想？  
 你可曾想象，如何分辨真正的自我思维和这种口齿伶俐的机器假象？  
 你可曾想象，在意识和思维方面，人类以其傲慢与偏见，一直都在误解机器？  
 你可曾想象，机器可以由它自己做出独立的决策？  
 >> 多级引用（两个\>）
 >>> 多级引用（三个\>）

**以上每行诗句后含有两个**空格**以实现换行**
