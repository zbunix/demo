测试1
=====

方法1
----

方法2
----

测试2
=====
1. 阿阿

2. 不不不





这是项目 [demo](https://github.com/zbunix/demo) ，
欢迎访问。

这个项目的版本库是 **Git格式** ，在 Windows、Linux、Mac OS X
平台都有客户端工具可以访问。虽然版本库只提供Git一种格式，
但是你还是可以用其他用其他工具访问，如 ``svn`` 和 ``hg`` 。

## 版本库地址

支持三种访问协议：

* HTTP协议: `https://github.com/zbunix/demo.git` 。
* Git协议: `git://github.com/zbunix/demo.git` 。
* SSH协议: `ssh://git@github.com/zbunix/demo.git` 。

## 克隆版本库

操作示例：

    $ git clone git://github.com/zbunix/demo.git
    
测试1

## 测试2

## nwd测试3
dB无量纲，仅有数值意义，并不是物理单位，只是将原始数值换算为对数。
但为什么人们喜欢错误认为dB是单位，个人认为这是源自我国初中物理课本的一个错误教学案例，
物理课本中关于声音的讲述中很简单的将声音强度的单位表述分贝，是为了简化描述并不科学严谨，
实际上，声音强度是有真实物理单位的，因为声音是压缩空气传播，所以衡量声音强度的单位就是空气压强值（单位为帕），
也就是专业扩声领域经常提到的声压。可是，由于人耳可闻的声压其数值动态范围极大，
最大值与最小值相差高达10的12次方倍，那么直接用普通数值去描述，太麻烦了，
动辄描述一个声音就需要写十来个0，即不方便表述，也不方便理解。
所以，人们定义了一个基准声压，也就是人耳刚刚能听到的1000Hz声音，大概的声压值为2*10的-5次方帕，
所以，要描述其它的声音，那么先与这个基准声压相除，得到一个倍数即可，然后对这个倍数取一个对数，
就方便的把一个动态范围在10E12次方的描述值域，缩减到0~120的描述值域，并给了一个不代表任何物理意义，
只有数值意义的单位：dB，也就是分贝，大大方便了描述表达。
但是，由上述可知，dB其实就是把一个纯数值而已，只是进行了一个log对数运算，本身没有任何物理意义，初中物理教科书丝毫不提及前因后果，简单粗暴的将分贝列为声音的单位，让很多人都误认为分贝就是一个具有物理意义的单位，实则为不严谨表
