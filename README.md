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

