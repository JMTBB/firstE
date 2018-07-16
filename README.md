# FirstE

> The practice of Github.

此文档用于学习markdown在GitHub上的一些基本操作

主要包括以下内容
1. markdown基础
2. 引用
3. 粗体和斜体
4. 删除线
5. 列表
    * 有序列表
    * 无序列表
6. 代码格式化
7. 链接和图片
8. GitHub扩展语法
9. 其它

[内容参考于此处](https://www.yaosansi.com/post/markdown-on-github/ "双引号添加链接说明")


### 二级标题，代码格式化
> 代码引用主要用的反引号，位于数字1左边。
> 单行代码使用前后各一个反引号，多行时段前段后各3个反引号

` print("单行代码格式化") `

```
#include<iostream>
using namespace std;
void main()
{
   cout<<"多行代码格式化"<<endl;
}
```



### 关于标题以及删除号
> 标题大小由其前面有多少#号决定。
> 前后1`紧挨`着两个“ ~~ ”既有删除号。(大部分需要空一格)
如

## ~~两个#号~~
#### ~~四个#号~~
