title: 关于标识符
date: 2015-09-21 14:12:33
tags: 标识符
---
#### 标识符是什么

在编程语言中，标识符就是程序员自己规定的具有特定含义的词，比如类名称，属性名称，变量名等。一般我们用英文单词做标志符，常用动词或者名词。
<!--more-->
比如

```
class user {

  public String name;

  public String getName() {
    return this.name;
  }

}
```
以上的 user ， name ， getName 就是标识符。 其中前两个是名词，后一个是动词+名词。

#### 命名

不同的编程语言不同的命名规定，一般来说，标识符可以由一下四种字符构成 $,字母，数字，下划线。一般不能以数字开始，有些语言中，下划线开始表示private的实体（可能只是约定，而非编译器行为）。

#### 常用缩写

标识符一般用英语单词组成，有时候单词过长，我们可以用一些***熟知***的缩写代替。比如：

tempory --> tmp

document --> doc

generator --> gen

specific --> spec


当你不知道改用什么缩写时，可以询问同事，看看公司项目的约定。尽量不要生造缩写。


#### 其他

当年在银行做程序员，收到***广播***邮件，开头称呼是各位***高经***,经推测是高级经理的意思。不知道是否正确。



