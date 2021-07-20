## 入门必看网络安全法

https://www.fjcpc.edu.cn/jgdzz/2020/0424/c2231a65107/page.htm

## CTF

[CTF 在现实中真的存在吗？](https://www.zhihu.com/question/406929241)

[针对CTF，大家都是怎么训练的？](https://www.zhihu.com/question/30505597) (前期刷题即可入门)


### web安全入坑指南

web安全简介
web安全是什么 -  web应用程序(网站,简单来说可以通过浏览器访问的程序)层面可能产生的安全问题.


语言基础(推荐菜鸟教程)(当然也可以从黑盒先学起,黑盒--不看代码测试参数): 
1. 简单了解下HTTP协议, https://www.bilibili.com/video/BV165411A7ef
2. 简单了解下HTML,JavaScript 尚硅谷前端课程: https://www.bilibili.com/video/BV1XJ411X7Ud (看前面34p)
3. PHP(了解基本的语法)
4. 简单了解下数据库基础知识,了解SQL增删改查.



(ctfweb要学的东西很多, 需要快速学习能力,还有接受不完美--先了解大概,用到不会的时候再去看)

web安全基础入门: 
1. pikachu平台 https://www.bilibili.com/video/BV1q4411S7XB
2. Web安全学习路线 https://moxiaoxi.info/2016/10/22/Websecurity/
刷题靶场:
1. ctfshow: https://ctf.show/ (web入门强烈推荐)
2. buuoj (https://buuoj.cn/challenges): web刷题参考 https://ca01h.top/ (分类刷题)
3. ctfhubweb技能树: https://www.ctfhub.com/#/skilltree

### Misc基础入门:

1.首先你得了解文件的16进制编码格式

[16进制文件头](https://blog.csdn.net/qq_41079177/article/details/79221638)

2.你需要下载很多的工具，但这些工具不需要你去集中下载，而应该是在你刷题的过程中逐步积累（PS：有些工具需要激活可以去压榨学逆向的）

3.大量的刷题是必不可少的,下面我主要推荐两个靶场

[Bugku CTF](https://ctf.bugku.com/challenges/index/gid/1/tid/4.html)

[Buuoj](https://buuoj.cn/login?next=%2Fchallenges%3F)

4.做Misc最重要的就是思路，在你做题时如果实在没有头绪，不要害怕，不愿意去看别人的WP，可能这就是一个你没有接触过的东西，可能就是需要某个你没有用过的工具。其实Misc应该是最好提升的一个部分，因为只要你题目做的多，你就能比别人厉害。

5.学好一门编程语言（特别是python）对做Misc是有极大帮助的（众所周知，大佬做题都是现写脚本嗯跑（bushi）

### pwn入坑指南

***https://kr0emer.com/2021/07/19/pwn%E5%85%A5%E9%97%A8%E6%8C%87%E5%8D%97/***

# reverse入门

## 1.逆向分析是什么

		逆向分析是根据对相应的应用程序进行分析，得到其内部代码的学科，一般会涉及到的有windows程序逆向，linux程序逆向和Android程序逆向。通过对相应的程序进行反编译得到伪码再结合汇编和运行情况，对软件进行分析就是逆向分析。

## 2.逆向分析需要什么知识

		首先要对汇编语言代码有一定的了解，熟悉C语言代码，可以对C语言写的算法进行分析，还要熟悉C语言中的结构体的实现方法，可以通过相应的算法推出相应的结构体，要了解一些python和java知识，可以看懂相应的python代码和java代码，最好会使用python进行脚本的编写，因为python可以快速实现相应的算法，当然也可以使用C语言相应的代码进行代替。

### 2.1动态分析和静态分析

		进行逆向分析时要会使用相关的分析工具，最常见的就是IDA，IDA可以进行很好的静态分析，也可以进行动态分析，当然也可以使用其他的动态分析软件进行相应的分析，要能够熟练的使用这些分析工具对程序进行分析，动态分析和静态分析是相互辅助的，对于复杂的代码要使用两种分析方法进行同时的分析。

### 2.2逆向分析的态度

		其实给与足够的时间，无论多么复杂的程序都可以分析得到相应的代码逻辑，所以在进行逆向分析时要有足够的耐心，也要有相应的激情，没有对逆向的兴趣和激情，在面对复杂代码时是很难可以坚持分析下去的，还要足够的细心，不能落下任何一个关键的代码。

## 3.逆向入门方法

		逆向是一个如果你经验越多分析起来越快的学科，所以前期的刷题很是关键，也是可以产生成就感，所以逆向进行刷题是可以很快入门的。

相应的刷题网站有BUUCTF

https://buuoj.cn/

如果刷题刷累了，也可以看一些跟逆向有关的论坛上的一些有趣的东西进行缓解，吾爱破解就很好

https://www.52pojie.cn/

# 密码学(Crypto)入门

## 1.什么是密码学

		密码学是保证通信时对相应的信息进行加密，使只有你想得到这个信息的得到，而其他人都得不到。

## 2.CTF中的密码学

		CTF中的密码学跟相应的密码学研究还是有一定的差别的，CTF中的密码学题目主要分为古典密码和现代密码两类。

### 2.1古典密码

		古典密码学主要是对经验和脑洞的考察，一般会直接给你相应的密文和一些藏起来的提示，一般会考察的有凯撒加密，维吉尼亚加密，base64加密，栅栏加密，等相应的古典加密方法。

替换密码爆破https://quipqiup.com/

维吉尼亚密Vigenerehttps://www.qqxiuzi.cn/bianma/weijiniyamima.php

维吉尼亚爆破解密https://www.guballa.de/vigenere-solver

在线Bugku培根加密https://tool.bugku.com/peigen/

E-mail编码在线解密http://www.mxcz.net/tools/QuotedPrintable.aspx
编码形式=加两个十六进制数

在线md5解密https://www.cmd5.com/

在线轮盘解密工具https://inventwithpython.com/cipherwheel/

栅栏密码在线加密解密https://www.qqxiuzi.cn/bianma/zhalanmima.php

中文电码查询http://code.mcdvisa.com/

在线猪圈密码解密http://www.metools.info/code/c90.html

### 2.2现代密码

		现代密码比较贴近真实的密码学研究，首先会给你相应的加密算法和相应的加密后的密文，一般会分为对称加密和非对称加密，一般的对称加密有流密码和块密码(分组密码)，相应的通过对加密算法的分析，找到相应的密码中的薄弱点，实现对相应的密码学攻击，流密码最常见的攻击就是相应的密码复用，导致的安全问题，而相应的非对称加密中，最常见的就是RSA，是一种基于大数分解难题的加密方式，所以只要可以将大整数进行分解就可以进行解密。

大整数分解www.factordb.com

## 3.密码学相应的知识

		对相应的算法要熟悉，要熟悉python算法，要能够读懂相应的python代码，也要有一定的数学知识，要有一定的数论知识，可以利用相应的知识，进行数学的分析，并用算法进行实现。相应的刷题网站是BUUCTF，其中的题目名字是简单的进行分类。

https://buuoj.cn/

