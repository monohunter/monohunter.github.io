---
layout: post
title: 这两年用MacBook Pro的经历和经验谈
comments: true
tags: [朝花夕拾]
---

2年前，2011年的暑假，某夜我不小心把一杯啤酒倒在了我的ThinkPad X201上，于是第二天送去修理。由于急着用电脑，我就买了一个MacBook Pro 2011。内存有4G，硬盘320G机械硬盘。之后就不怎么用小黑了，我觉得macbook的键盘挺好使的。于是开始了蛋疼的经历：

1. 有的时候需要用windows，怎么办？我在硬盘上割了一个windows的分区，安装了win 7。
2. 内存有4G，某日我再买了俩4G的内存，升级到了8G。速度提高了不少，十分欣喜。
3. 但是机械硬盘用久了确实会变慢，某日我就把光驱拆下来，换上了一个镁光的固态硬盘，把新的系统OS X系统装到固态硬盘上作为主系统。速度有质的飞跃，开关机都是几秒钟的事，我在见识了高科技之后达到了高潮。老硬盘有俩系统，把那个老的OS X系统格式化为mac os extended格式的存储盘，win 7系统不变。
4. 固态硬盘在运行的时候，是没有任何声音的。但由于备份time capsule，或者做检索时需要扫描老的机械硬盘，每过一段时间老机械硬盘就会转起来，产生声音，这让我很不爽。而且在机械硬盘上的win 7系统巨慢无比，经常成功击败全国1%的电脑，也挺不容易的。一怒之下，又买了一个三星的固态硬盘，换到了硬盘位了。老的机械硬盘，搭载着mac分区和win 7操作系统，用朋友给的硬盘壳做成一个外接硬盘。
5. 遗憾的是，此时电脑虽然是有俩固态硬盘，但只有一个OS X系统，无法使用win 7了。于是想用同样的办法，在新固态硬盘上装个win 7。但是失败了，因为MacBook Pro 2011版的boot camp不支持U盘、外接光盘（无论是不是苹果的superdrive)、虚拟光驱装windows，只能通过自带的光驱才可以。既来之则安之，说服自己不用Windows了。
6. 但有些程序必须在windows下运行，比如matlab。某日下午，当看到我的MAC版的matlab运算1+1，用时2分钟的时候，我做了一个艰难的决定。我把硬盘位的固态硬盘，安装了一个全新的OS X系统，作为启动boot camp的盘。收拾桌子，把装在光驱位的硬盘拆下，换回去拆下的光驱。从新的os x开机（硬盘位），启动boot camp，这时因为有内置光驱，顺利在本固态硬盘中分割空间、安装好了一个win 7! 关机，再把光驱拆下，换回固态硬盘。从光驱位老os x系统启动，格式化新装的os x系统（硬盘位）为mac格式的存储盘。【中间安装的OS X系统，相当于一个中介，只在装win 7的过程中发挥过作用。这是一种过河拆桥的手法。】

至此，我的电脑，有2个固态硬盘，没有光驱，一个硬盘上有一个系统，光驱位的是OS X，硬盘位的是win 7。速度都非常快。我兴奋异常、万分欣喜，认为我的电脑已经是世界上最先进最牛逼的电脑了。用了一段时间，爽的不行。

转眼用这个本有2年了。某夜我喝咖啡，不小心把一杯香浓的咖啡，泼在了此本的键盘上。。。

<u>MacBook Pro的键盘进水和进饮料是最难修理的。说下我的处理方式和一些经验。</u>

把咖啡泼到Macbook上了，顿时电脑香飘四溢。我马上关机，**打开后盖，把电池的接口拔下来**，先凉了一周。筒子们，我泼上的不是水，而是一种非牛顿流体。咖啡（和啤酒之类的饮品）非常的粘稠，凝固了会固定住按键的。本来想着从外面把键盘按键抠下来直接清理，这是不可能的，应该面对现实：机器的内部有大量的凝固液体，需要大修，而且此时键盘再怎么修也无法恢复当初的质感了。

直到一周之后，我才开始动手拆机清理内部。费了很大的劲儿，直到弄清楚Macbook Pro的内部构造，和键盘的结构。咖啡已经流到主板和键盘的接口那里了，并且已经凝固，包裹住了整个的接口。下图：

![](http://www.fengimg.com/data/attachment/forum/201309/21/063313oyyylnmih565ofr6.jpg)

键盘当然是废了，不要妄图换键盘，换键盘是一个“不可能的任务”，万分不建议这么做，这需要你是极度心灵手巧之人。因为键盘有着几层很精密和脆弱的结构，让人蛋疼。如果真的要换键盘的话，有100多个很小的螺丝固定在topcase上，需要一一拆下，然后把买来的新硬盘，一一安上去。螺丝稍微一用劲就滑丝了，再难拆卸安装。这个过程可能改变你的人生观。（问题是：真的心灵手巧的就不泼键盘了不是么）我没有换键盘，而是直接换了一个topcase，所谓topcase就是本来就带有键盘在上面，是承载所有内部结构的case.结果如下图：

![](http://www.fengimg.com/data/attachment/forum/201309/21/070921ux6pmx2fxxwxuu5b.png)



几点经验：

1. 如果泼上的是粘稠的液体，应该键盘朝下的放置，防止液体往下渗透，流到主板等位置，腐蚀排线。
2. 泼上液体之后，最先要处理的是，打开后盖，把电池的接口线disconnect了。因为在我关机后，由于液体的进入，可能某些部位短路了，出现了风扇转动、屏幕白屏的自动启动的现象。
3. 当即拆机。如果最后还是得拆机的话，那就马上做、不要等。有专门的拆机教程，其实并不困难。这是为了防止液体凝固而腐蚀内部固件。
4. 桌上别放饮料。如果你不是心灵手巧之人。

**久病成医就是哥这样的。**

----

注：原文发表在威锋网。