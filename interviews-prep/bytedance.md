作者：Top_xiao
链接：https://www.nowcoder.com/discuss/454734
来源：牛客网

7.1 下午两点 一面
一个深度为5的满二叉树的节点个数有多少个。
B树 和 B+ 树的区别。
Mysql innodb 引擎的结构
进程的通信。
乐观锁和悲观锁有了解吗
怎么看占用内存比较多的进程
虚拟内存和物理内存之间的关系
分页和分段
用户态和内核态
哪些系统调用会进到内核态
所有的系统调用到会进入到内核态吗
Linux某个目录下怎么找名字包含 txt 的文件。 find /home -name "*.txt "
用过 ping 命令吗 ： ping命令是不能检测端口,只能检测你和相应IP是否能连通.
ttl 是什么意思。 ：存在于 IP 头部， 经过路由器的个数，减到0报文就自动消失。
怎么判断一个主机是不是开放某个端口：telnet 192.168.25.133 22
DNS 的解析过程。
TCP的可靠性传输是怎么保证的。
为什么建立连接需要三次，断开连接为什么要四次。
time_wait 是在哪个步骤。
tcp的粘包问题
http的常见状态码
get 和 post 有什么不一样
浏览器的跨域问题
session 和 cookie 的问题。
Ddos攻击。这个没听清。
慢查询，数据库。
 struct{ char a; int b; }p;
sizeof(p) 是多大。
public private, 和保护
vector的内存管理。
vector 的size(), 和 cap 的区别, ： 一个是元素个数，一个是可用内存大小
push_back() 把元素放在什么位置。
为什么会有虚函数。
delete delete[] 什么区别
c++ 内存泄漏
 int i = 1; while(i < n){  i *= 2; }
问时间复杂度
力扣链接 这个题目数组是有序的， 但是面试官出的题数组里面是无序的。 要求时间复杂度 O(n), 空间复杂度 尽可能的小。
二面 7.7晚上八点
malloc realloc
进程间通信有哪些
tcp 和 udp 有什么区别
C++ 的一些 stl 容器
vector 和 list 有什么区别
hash_map 和 map 有什么区别
滑动窗口是什么。
多路复用 IO
linux 中的文件是有个数的吗
浏览器中输入 url 会发生什么。
对称加密算法 具体有哪些。
指针和引用有什么区别
static 修饰有什么作用。
static 修饰一个函数，函数有什么变化
C++ 如何调用C 里面的库
如何封装一个库
a = 1， b = 4， 如何交换， 但是不能使用第三个变量。
我就是憨憨，

 a = a + b b = a - b a = a - b       a = a ^ b b = a ^ b a = a ^ b,  怎么都可以。
如何判断一个单链表是不是有环。
linux下查看机器的全称 hostname
给你一个数组，求三个数字之和为100.
有n个数字，比如 9 2 9 2 4， 每个数字代表一个实心立方体的高度，现在要放水在这些立方体上，一共能有多少水， 例子 一共就是 9
前面答的不怎么样， 最后算法题问了我三个， 最后一个又没有想出来， emmm， 之后问了学长，把我点醒了， 艹， 怎么可以这么简单。

基础知识答的不好， 算法题也没有回答好， 之后还约了三面， 真的是太开心了。

三面
自我介绍，

然后问最深刻的事情事什么，

就是项目或者比赛上： ， 但是我讲的支支吾吾的， 没有表达好， 还是因为自己不太会表达。

下次要提前想好， 然后写下来，这个才可以说的流畅。

然后就是情景题， 反正我不会， 也表达不好。

之后就是算法题了，

给你一个数组， 问有多少个 (i,j) a[i] + a[j] == k, 给的数组是有序的，

要求 时间复杂度 n， 空间复杂度 n，

tmd 我脑子又短路了， 嘤嘤嘤。 简单的问题还能想这么长时间。 还让面试官提醒之后才想起来有错误。


作者：window3cc
链接：https://www.nowcoder.com/discuss/454446?type=2&order=0&pos=4&page=1&channel=-2&source_id=discuss_tag
来源：牛客网

字节 客户端 1 2 3 面

1面

操作系统调度算法？

list 删除元素  调用 iterator的 remove方法，写一下

leetcode原题   从一个数 l 一直 与 操作到 r  ，怎么做最快，复杂度最小

二叉树的非递归后序遍历

说一下hashmap的原理，特性，手写一个myhashmap

2面

主要是java基础相关的问题

进程和线程的区别联系

java双亲委派模型

怎么判断一个对象被回收

多线程了解吗，说下线程池几个重要参数

线程池原理

static synchronized 和synchronized的区别

两个被 synchronized 修饰的方法可以同时运行吗

volatile 是什么，特点

手写一个双重检查单例，追问为什么里面要用到volatile


做道题，k个一组反转链表



3面

问了下项目相关

然后问了  我访问一个网站，到这个网站给我返回结果的整个过程

osi模型  七层  哪七层，各层分别有什么样的协议

tcp和udp区别

http 和https

https怎么加密的，能说下具体过程吗，非对称和对称加密

做道题，我有一副牌，第一步，从牌顶拿一张放在桌子上，第二步，将当前牌顶的牌取出来放到牌的最底部，重复1  2两步，最终得到一个 有序的 数组(1 2 3 4 5 6 7 8 9)，问 这副牌最初的顺序是怎么样的？



海量字符串的排序？面试官不让用哈希


作者：穿牛仔裤的红番茄
链接：https://www.nowcoder.com/discuss/453278?type=2&order=3&pos=37&page=1&source_id=discuss_tag&channel=0
来源：牛客网

渣渣来还愿了，面试准备过程中在牛客学习到了很多，对自己帮助很大，回馈一下牛友们
一面（6.30 1h）
1. 项目介绍

2. 说一说retrofit

3. okhttp中的责任链模式讲一下

4. TCP三次握手四次挥手

5. Synchronized和volatiled的区别

6.乐观锁和悲观锁

7. Synchronized的锁升级机制

8. handler机制

9. App的启动过程

10. CAS

11. Activity的启动过程和启动模式，分别的应用场景

12. Tcp/Udp的区别

13. tcp可靠性的保证

14.动态代理的实现原理

15. 算法题：根据前中序重构二叉树

二面（7.7 50min）
二面只想起来一部分内容

1. hashmap

2. 能否自己写出一个求hash值的函数（算是半个算法题吧）

3. 讲一讲okhttp

4. http中如何实现缓存

5.那在okhttp中如何实现缓存

6. DNS的解析过程

7. 算法题：场景题，能否写一个函数给定安卓界面上最顶层的view得到安卓界面中view得深度

三面（7.13 50min）
1. 项目介绍

2. ==和equals的区别，Stringbuilder和StringBuffer的区别等等java基础

3. 项目中的难点

4. 项目中学到了什么

5. 算法：螺旋矩阵

不知道为何三面突然问起了java基础，项目里的内容也没有深究，可能是因为非科班，安卓端又非常缺人。

hr面（7.14 30min）
1. 自我介绍

2.  优缺点

3.  为什么选择字节

等等一些常规的hr问题。。。。

根据自己的实际想法答即可，提到字节舔就完事了 哈哈

总体来说，在面试难度上，安卓端的题目难度确实不太大，主要还是java基础和网络还有安卓一些常见的知识，可能是安卓比较缺人侥幸拿到了字节的offer。整个面试体验非常棒，每个面试官都比较和善，会耐心的听你讲完，有不会地方还会适当提醒一下。


作者：AlfChen
链接：https://www.nowcoder.com/discuss/453272?type=2&order=3&pos=38&page=1&source_id=discuss_tag&channel=0
来源：牛客网

今天收到抖音hr这里的消息offer已经在审批了。也算是提前批秋招的第一个大厂offer，前来还愿。以后的秋招面经也一并更新到这里了。

之前实习的面经总结移步：https://www.nowcoder.com/discuss/407310?source_id=profile_create&channel=2002
字节跳动 抖音 后台开发(共四面)--已offer意向
一面
1.介绍项目
2.介绍redis的底层数据结构(项目中提及)
3.介绍redis中zset的实现
4.介绍ACID特性
5.介绍OSI七层模型
6.问路由器在OSI七层模型中的哪一层
7.算法题。给定m和n，输出从1~n中任意多个数字，且和为mu的组合(数字不能重复使用)

二面
1.算法题(求第n个丑数,leetcode原题,难度mid)
2.介绍项目(前面的面试官有记录，所以就顺着记录接着问)
3.数据库题，给两个table，问left join、right join和inner join的结果

三面
1.数学题，54张牌，三人斗地主，问一个人同时拥有大小王的概率(注:地主有20张牌)
2.算法题二选一，第一题是求开根号n的值，第二题是输出交错后的链表(比如链表a-b-c-d-e,交错后输出为a-e-b-d-c)
3.反问

四面/加面
1.自我介绍
2.问项目
3.情景设计，如何设计出类似百度搜索这样的搜索补全功能？大概说思路
4.因为我之前回答搜索补全时都是基于前缀的搜索，又问如果不是前缀时该怎么办
5.提问
6.问感兴趣的方向，什么让自己有成就感？

总结
因为之前有面试过字节的实习，这次秋招给我的感觉不算特别难，从算法题的难度都有所下降，基础问题的部分增多(实习时的岗位是客户端开发，更多问及C++语言特性相关)。
总体来说，字节的面试难度属于中上，除了好好背书外也要多刷一些题，个人感觉easy~mid足够了。


Tp-Link 软件开发 后台方向(共三面)--offer
一面
1.问项目
2.指针和引用的区别
3.介绍一下虚基类
4.常量指针和指针常量有什么区别
5.提问

二面
1.做题，求一颗二叉树最大路径和
2.智力题，2个鸡蛋，100层楼，要测哪一层刚好不碎，要试几次(高楼扔鸡蛋问题，实际是一道hard的DP)
三面(在hr面之后)
1.问项目
2.问一些发散性的问题，比如个人职业规划、如果项目进展有问题该怎么办之类

总结
TP的bar总体来说是比较低的，不过类似二面这样的技术面也不能毫无准备，还记得当时是从一个word的题库里找题给我做的哈哈哈


百度语音 C++开发(面试中)
一面
1.介绍项目
2.介绍实习经历
3.C++和C有什么区别
4.介绍一下面向对象
5.详细介绍下封装、继承、多态
6.介绍一下虚函数的机制
7.new和malloc有什么区别
8.堆和栈有什么区别
9.手写一个单例模式
10.手写一个智能指针
11.手写一个字符串拷贝函数
12.反问
新浪微博 广告部 C++开发(面试中)
一面
1.自我介绍
2.介绍C++11的新特性
3.介绍STL中的vector、list和map的底层实现以及应用场合
4.TCP的timewait发生在什么时候以及作用
5.如果服务器中有大量的close_wait的端口,原因是什么,怎么解决
6.线程和进程的区别
7.进程间通信的方法(IPC)
8.linux下怎么查看内存和cpu的使用率？
9.linux中交换分区有什么用
10.各种排序算法的时间复杂度
11.手写快排



腾讯 PCG 搜索 后台开发(面试中)
一面
1.介绍项目
2.介绍C++11、C++14、C++20
3.线程和进程的区别
4.线程的私有内容
5.进程间通信有哪些
6.介绍TCP三次握手
7.为什么TCP要三次握手
8.算法题，一个字符串，假设空足够，将其中所有空格替换为"%20"，要求不开辟额外新空间
9.算法题，说思路，100台机器，每台机器上10亿个数，求里面最大的100个数
10.介绍一下协程
11.介绍io多路复用
12.介绍select和epoll
13.提问(我说以前实习面过了，就不问了wwww)

作者：cornorghost
链接：https://www.nowcoder.com/discuss/453261?type=2&order=3&pos=39&page=1&source_id=discuss_tag&channel=0
来源：牛客网

真的问的很简单，不过我太弱了，最后的反转链表出错了，找不到bug，吸取教训吧，多刷题

自我介绍
虚函数
cast（显式转换，三种）
说说socket的基本步骤
进程间通信方式
TCP和UDP区别
TCP属于哪一层
网络层有什么协议
http请求头有什么关键字段
https了解吗，说说
https怎么加密的，对称和非对称加密说一下（不知道）
反转链表（这个我真的服了，很简单，就是有bug，面试官说这个解不出来你肯定过不了），下面是我当时写的，多写了一行p2


作者：ever°201812032041517
链接：https://www.nowcoder.com/discuss/452755?type=2&order=3&pos=50&page=1&source_id=discuss_tag&channel=0
来源：牛客网

1.自我介绍
2.挑了个项目讲
3.sizeof 的作用
4.结构体大小（内存对齐相关，为啥要内存对齐，不同操作系统sizeof大小一样吗）
5.TCP,UDP区别，四次挥手详细过程，为啥 TIME_WAIT
6.虚函数原理， 继承多个类的时候虚函数指针是啥样的
7.C++有那些多态
8.刷题 ： 2*N的格子 1*2的格子填满它有多少种方法， 给个数组，找出右边第一个比它大的元素， 链表两两反转

7月2号捞的面试，7月1号挂过一次广告部门三面， 这次面试上来感觉面试官那边不像要招人的样子？ 毕竟约面隔这么久，
另外最后链表那个当时一开始写递归想成链表反转的递归了，楞是没调出来，最后改成循环，最后还是有bug，疯狂被diss，前两道
倒是马上ac， 应该是凉了，下午5点面的，到现在也没消息。。。
听说字节教育这部门很多人一面凉？？？


作者：VodkaR
链接：https://www.nowcoder.com/discuss/454712?type=2&order=3&pos=7&page=1&channel=0&source_id=discuss_tag
来源：牛客网

一二面
自我介绍
c++（多态等）
计网（https（我不熟）tcp，udp）
操作系统（问得比较简略）
项目（我项目小）
算法题（合并链表、求岛屿个数）
提问

结束后hr小姐姐很快通知三面（声音好温柔的）

三面
自我介绍
操作系统（LRU、虚拟内存、进程线程之类的各种）
算法题（树找两节点最长距离、找第一个值为k的数下标）枯了，算法我苦手
提问


作者：我爱offer爱我
链接：https://www.nowcoder.com/discuss/454667?type=2&order=3&pos=8&page=1&channel=0&source_id=discuss_tag
来源：牛客网

1.打印 1 2 3 .。。10（三个线程顺序打印）
2.tcp 服务，客户端发送给服务器数据，服务端返回。写socket？
3实时更新，找出话题榜热度前十
4.1243534543634交换各位的数字，找出大于目前这个数的最小的一个数。
面试官人真好~~会引导。


作者：Scout_N
链接：https://www.nowcoder.com/discuss/454623?type=2&order=3&pos=11&page=1&channel=0&source_id=discuss_tag
来源：牛客网

面试分两部分，第一部分写代码，第二部分针对项目做一些提问；
一、代码题
有两个人，有开始上班时间和下班时间，这两个人上班期间会有会议时间；求这两个人上班期间的共同空余时间，不算难，牛客写的没来得及跑；
二、项目问答
2.1 数据库查询优化怎么做的
2.2 分页查询的话，如果数据库非常大，start和limit有什么局限性，这个我不会，等下去百度；
2.3 断点上传 讨论了一通也问了iNode和hdfs，最后问我看过hdfs相关的论文没，我没看过，唉，最近在看网络相关的论文；
2.4 oAuth2.0基本解释了一下，问我令牌在认证服务器是如何解析并判定这个token的(我心想，token不就一大串的字符，无非解密然后认证呗，想想算了还是别瞎说了，等下去查查)


作者：没有拿到offer的小老弟
链接：https://www.nowcoder.com/discuss/454612?type=2&order=3&pos=12&page=1&channel=0&source_id=discuss_tag
来源：牛客网

之前狂看面经，现在反馈的机会来了

一面50min
1、自我介绍，项目介绍
2、算法题，
1
2
3
4
5
6
7
8
9
10
修完课程需要至少几个学期，每个课程需要一个学期修完且必须在前面的学期修完它的先行课
{
    1 -> []
    2 ->[]
    3 -> [1,2]
    4 -> [1]
    5- > [1,3,4]
    6 -> [5]
}
1~6的先行课如上，返回结果[[1,2][3,4][5][6]]
3、多线程并行，单核CPU和多核CPU区别
4、一个类怎样不调用构造函数去创建对象（这个不会。。）
5、MySQL事务的特性ACID,展开讲讲
5、A、B两人掷硬币，A先掷, 先掷出正面的获胜，求A, B胜率
6、一个用户一个小时内最多访问50个短视频，怎么在服务器设计？
服务器为每个用户维护一个deque,记录当前时间到一个小时前的的访问纪录，实时更新deque,频率1s

二面 50min
1、算法题：(1)设计sqtr(x)
(2)一个射击运动员打靶，靶一共有10环，打10枪打中90环的可能性有多少种?(两种方法：递归、动态规划） 要先写出递归表达式、动态规划状态转移方程
2、socket编程，tcp/udp用到的各个接口函数
3、C++编译的过程
4、动态链接对比静态链接
5、MySQL的幻读？ 怎么处理？（next-key locks,行锁，间隙锁）
6、Innodb默认隔离级别—可重复读，简单介绍MVCC原理

三面 50min
1、自我介绍，项目介绍、毕业论文
2、算法题：(1)判断回文链表
(2)对于给定的数据，找出比这个数大的最小回文数（正反读都一样的数），如 12310 -> 12321



作者：努力上岸的咸鱼
链接：https://www.nowcoder.com/discuss/454502?type=2&order=3&pos=17&page=1&channel=0&source_id=discuss_tag
来源：牛客网

强化学习算法工程师 base 北京

—————————————————————

6.30电话约面试，但是我平时实习没有时间，就约到了两周后的周末。



7.12 下午13:00一面

7.12 下午14:30二面

（一二面的小哥哥都是比较年轻的，气氛也很棒）



7.14 晚八点实习下班途中电话约三面



7.17 下午16:00三面，时长一个小时，感觉是部门的大佬，和蔼可亲，但是问的问题还是挺难的，比较有深度…好在都答上来了，当场说欢迎考虑他们部门😂



7.17 下午17:30 hr加我微信说业务面试通过后续会发放意向书。


作者：牛客记录我的菜鸡时刻
链接：https://www.nowcoder.com/discuss/454329?type=2&order=3&pos=24&page=1&channel=0&source_id=discuss_tag
来源：牛客网

面试官超级好，可惜自己很菜
全程50分钟

1.自我介绍
2.狂问项目，一直问到不会为止，一直是要是你做你怎么做😣
3.mysql索引，索引是怎么保存的？以什么形式保存？
3.redis持久化，AOF怎么恢复？
4.做个题，等概率输出不重复数组里面的数，等概率返回一个新的数组？不会
5.换一个括号匹配。
6.要是抖音卡了一下，因为什么？
7.还有什么想问的？没了，人都没了还问啥

😭

全程没问基础，准备了好久os和计网…



作者：陈折半
链接：https://www.nowcoder.com/discuss/454216?type=2&order=3&pos=25&page=1&channel=0&source_id=discuss_tag
来源：牛客网

题外
看其他面经的计网OS都没有问，主要还是看自我介绍问，我提了一嘴课程项目用过一次的SpringBoot直接送了，别给自己挖坑！！！！！

面试官人巨好，一直给我答疑解惑给提示，然而我表现特别差，对不起他（跪下

正题
自我介绍

如何看待SpringBoot

SpringBoot约定优于配置理解

SPI接口理解

Java泛型使用、机制、类型擦除

C++模板是否了解

内部类使用

单例模式

指令重排是怎么回事

volatile特性

进程与线程

线程互相如何通信

synchronized了解吗

不可重入锁有哪些（直接死亡）

==、equals机制

如何重写equals，需要注意什么（除了hashCode（）外）

直接打印对象出现的@xxxxxx是什么（这个对象的toString()函数的结果，toString()这个函数是定义在Object类中的，代码如下，JDK官方是推荐我们所有的类都应该重写此类）

1
2
3
public String toString() {
    return getClass().getName() + "@" + Integer.toHexString(hashCode());
}
引用有哪些，虚引用的作用详细描述一下

minor gc和full gc

动态代理有写过吗，说说

算法（有点像是逻辑题 我墨迹了好久 最后没让实现出来 但是问了想实现的话该怎么办：状态机、树）：甲乙两位去打油，甲有一个5斤油瓶，乙有一个3斤油瓶，共打回来8斤油。甲和乙都只需要4斤油。乙有一个10斤的空油瓶。如何利用这只空油瓶，倒来倒去让甲的5斤油瓶里只装4斤油回家？

反问


作者：as_
链接：https://www.nowcoder.com/discuss/454157?type=2&order=3&pos=26&page=1&channel=0&source_id=discuss_tag
来源：牛客网

7.6一面
1. 自我介绍 聊项目(被怼死 挺多问题根本没想过)
2. 简要介绍mvcc
3. 多线程怎么实现？ 做一个高可用系统要考虑什么？（这儿完全不知道自己在说啥）
4. 通信过程中安全性如何保证？加密时密钥如何分发保证不被中间人攻击？（忘了 gg）
5. 数据传输时如何保证可靠性？消息摘要有什么作用？
6. 数据库如何优化效率？什么情况下要建索引？B树和B+树的区别，索引为什么不用二叉树、红黑树等？
7. 为什么要用线程池？如何实现？
8. 算法题 按字典序全排列输出（给了半小时没写出来 凉了）

7.12二面
1. 自我介绍
2. 对称加密与非对称加密的区别？
3. 消息摘要的作用？SHA256为什么比MD5安全？RSA与DSA有什么区别？
4. http与https的区别？具体证书是怎么获取的？密钥如何分发？
5. wireshark用过吗？实现原理是什么？（完全不会）
6. java中实现多线程的方法？使用线程池时参数有哪些？继承和实现接口哪个更好？
7. 非static的内部类如何访问static的外部成员变量或方法？原理是什么？（忘了）
8. base64算法与其他加密算法的区别？base64的流程是什么？
9. 了解哪些编码？utf-8和utf-16有什么区别？（凉凉）
10. 算法题 跳台阶 变种如果能跳1、2、3级台阶怎么实现？

7.16感谢信
彻底没了


作者：HelloKitty123
链接：https://www.nowcoder.com/discuss/453839?type=2&order=3&pos=30&page=1&channel=0&source_id=discuss_tag
来源：牛客网

7.6号 一面
1.算法题: 求一棵完全二叉树的最底层的最右节点
我说的是层次遍历, 面试官希望进行优化
2.两道有关虚函数的算法题，问输出正确与否？
考察点：虚函数、构造函数、基类与派生类
3.一道考察结构体内存的题，问输出？
重点考察：结构体和类的对齐操作
4.考察项目细节，主要是图形方面
涉及方向：深度纹理、帧缓冲区、ShadowMap 算法
5.图形渲染管线
每个流程每个细节必须熟练掌握，经常会考到
6.如何判断点是否在三角形内部？如何根据三角形三个点的纹理坐标求出三角形内部点的纹理坐标？
7.C++的面向对象的三大基本要素？请详述？
8.设计模式
9.智能指针
10.mipMaps 如何确定调用的纹理级别?
11.反问环节
7.8号  二面
二面忘记录音了，所以其实记得不是很清楚了
1.设计模式
主考单例模式（因为之前没有手撸过，所以基本上是现场写的，然后也存在很多问题，面试官指出后会继续引导我去解决这个问题）、线程安全、类模板、锁机制等
2.智能指针
3.项目细节
4.高斯滤波器为啥效果优于其他滤波算子
5.其实还有些问题，记不起来了。😥
7.14号 三面
三面基本上就没有考太多技术问题了，主要是问研究方向、项目细节、在项目中的角色等，然后出了一道题（给5个点，其中两个点可以构成一条空间直线，另外三个点能构成空间平面，求它们之间相交的情形（相交、不相交、不确定））。
7.16号 hr 面
hr 是个漂亮小姐姐。
1.手上是否有其他 offer?
2.项目中的角***>
补充一下：我同学好像被问到了: dynamic_cast 和 const_cast 的区别
整个面试过程感觉特别好，面试官会逐步的引导你回答问题，如果你哪方面说不了解，面试官也不会继续追问这一方面。😁😁


作者：芝麻不加饼
链接：https://www.nowcoder.com/discuss/453633?type=2&order=3&pos=33&page=1&source_id=discuss_tag&channel=0
来源：牛客网

字节一面：

处理过拟合的方法

ALS算法的实现

优化器的种类和区别 adam rmsprop adagrad sgd

beamsearch和greedysearch

算法：

1.判断左右括号是否合理

2.朴素贝叶斯的算法实现

3.两个很大的数据集存着url 找到两个数据集共有的url

4.一个二维矩阵由小到大排列 找target数字

5.二叉树按行输出

字节二面：

ALS的原理

用ALS 为啥不用逻辑回归做推荐 他俩应用场景有啥区别

逻辑回归为什么损失函数是交叉熵

进程和线程的区别

python处理多进程和多线程的底层原理

算法：

1.给二叉树前序遍历和中序遍历 输出这个树

2.翻转链表

3. 把只包含质因子2、3和5的数称作丑数。例如6、8都是丑数，但14不是，因为它包含质因子7。 习惯上我们把1当做是第一个丑数。求按从小到大的顺序的第N个丑数。



3面:

感觉凉了就面了我一道算法，最后写上来但是时间复杂度有点高

给一个类似树的结构，每个节点都可以有多个节点（不止两个树）然后每个根节点和字节点间的路径不一样，求叶子结点到叶子结点的最大路径



作者：菜鸡feng
链接：https://www.nowcoder.com/discuss/453499?type=2&order=3&pos=34&page=1&source_id=discuss_tag&channel=0
来源：牛客网

缓存穿透
布隆过滤器+过程+优缺点
B+树 红黑树
Java 泛型
hashmap
equals与hashcode
Mysql聚簇索引+非聚簇索引
SQL调优
JVM最新技术
http状态码
关系型与Nosql对比
CAP
分布式缓存策略
算法题：链表每k个翻转
（字节面试官人很好，赞！）


作者：dreamoffer
链接：https://www.nowcoder.com/discuss/451672?type=2&order=3&pos=81&page=1&source_id=discuss_tag&channel=0
来源：牛客网

面经：（已凉，写点东西给自己攒人品）
1.我提到用Oracle数据库，问了我Mysql跟Oracle的区别，Oracle使用上的优势。
2.问了有数据库有哪些锁。
3.我提到了页锁，问了什么是页锁。
4.问了I/O多路复用，多路复用运用的场景。 5.问了拥塞，怎么解决。
6.问了TCP怎么保持稳定的传输数据，我回答了3次握手，4次挥手。
7.问了协程是什么（这是啥？）
8.问了进程间通信，问了管道是怎么传输数据的，是不是像队列 一样先进先出。
9.我简历里有ZK，问了ZK相关，是分布式协调框架。
10.问了索引，问了联合索引，问了联合查询
11.问了B+树，我回答跟B树B-树相比的优势。
12.问了Concurrentmap的底层（这么拼写吗？）相关，怎么实现线程安全的。Senex数组是如何对TABLE进行分段的。
13.64匹赛马问题 14.最惨最悲壮额事，一道算法没有O出来，我都能感受到面试官的嘲讽了
第一题，一个int数组，找出两个异或最大的数字，时间要求O(n)
第二题，四个int数组，从每个数组里边挑一个数，加起来等于指定数，要求打印出所有非重复的组合，要求最大n2。 有会的教教我，不胜感激！555555555凉的太快了，果然手撕代码的公司都太狠了
链表题，二叉树准备半天用不上，Concurrentmap的底层也准备了，果然还是太菜了，以后要勤刷题才行。
另外我觉得我遭重是因为64匹马的时候，我说我好像看过，结果人算法就没给出高频的二叉树遍历啥的。
请记住我的经验教训，下个路口见。

作者：汪小包子
链接：https://www.nowcoder.com/discuss/451650?type=2&order=3&pos=82&page=1&source_id=discuss_tag&channel=0
来源：牛客网

一共聊了56分钟，本以为以我的垃圾水平，面试官小姐姐跟我聊15分钟顶天了，也不知道是面试官觉得我开放问题答的还行还是她的专业素养要求她遇见再垃圾也要完成这个指标

这是本渣渣第一次参加互联网公司面试。目前复习进度整体偏慢，就是李航那本书看到了SVM，编程python只会最最基本的，其余全部用R实现，SQL上个月刷了计提，最近又在写论文放下了。可视化吃的去年实习的老底。

整理一下：

零、自我介绍
就说了下本硕学校，然后说了下自己投的相关岗位，我本硕都是统计专业，本科上海末流985，研究生英国前100水硕
一、项目经历方面：

1.介绍下对数据挖掘的看法

答：不知道怎么回答，感觉太广了。说做EDA，然后做特征工程，然后选模型，调参。

2. 介绍一下自己的实习经历，项目经历。

答：实习自己捣鼓了4张tableau报表，项目就学校的ECG分类，然后kaggle房价预测。主要集中在特征选择，比如去除高相关啥的

3. 对数据分析的看法。

答：就说做kaggle时候搞的那些。画画直方图，箱线图，看相关性。给评价，为后面特征选择服务的。

4. KNN如何选取K值，与K-means的区别。

答：选取K值说不能大也不能小，大了没意义，小了过拟合。用交叉验证选。K-means是聚类算法，无监督学习。

5. 介绍下K-means怎么用。

答：好久之前用的，忘了。没答上来。头脑中有印象，但是讲不出来。

6. 介绍下过拟合和欠拟合。

答：根本没想到这个问题，问这么基础的问题么。。。回答说过拟合是高偏差。用交叉验证解决过拟合，K折。

搜了下答案，这个说的不错，备着：https://www.jianshu.com/p/f2489ccc14b4(原来这么多没答上来)


二、开放问题方面：

问用过字节产品么：抖音

1.如何刻画用户画像。

答：只想到了从点赞数评论数，使用时间段，最喜欢哪些视频考虑的。想不出其他的了，晚点搜一下答案看看别人怎么说的。

2. 你提到了使用时间段，怎么理解

答：比如说上班时间刷的，就是老年人，无业人员，自由职业者。如果晚上9点之后，就是工薪族balabala

3. 那如果一个时间段用户活跃度不高，怎么从数据挖掘角度看呢？

答：我真没想过这样的问题。就说，第一从外部因素角度，可能最近有什么事件。比如我是个学生，最近高考，考研或者考公，那肯定考试之前刷的很少，考完又接着回去刷了；或者说是那次消防员牺牲事件（这里说错了。。其实是4月6号悼念新冠肺炎牺牲的英雄），一整天都是灰的，只有这方面消息，但是有人只想看有趣的视频，就不看了。第二可能推荐算法有问题了，我经常就刷着刷着连续几个视频都是半个月甚至一个月以前的了，我个人比较喜欢看最新的，这也让我直接关了抖音了。

4. 那从哪些方面分析呢，可以给相关业务部门提供帮助。

答：可能我没描述清楚这个问题。就是说之后怎么给这个人推荐视频呢。我就说从看他以前的画像，分析他是哪类人群，从实际角度考虑，比如宝妈生孩子了，学生期末了，考完了，生完了，再继续推送消息，推送相关的，宝妈就推送育儿视频，学生考完了就推送游戏视频之类的。


三、SQL题。

就三题很简单的sql，只记得是统计分数段占比的。但是我很久没刷了，估计就写出来一个。


四、你有什么想问我的：

我问了问是不是数据挖掘岗要看数据结构，她说不同公司不一样，但是她觉得更偏重怎么去建模，去做特征工程。


五、结语

很感谢字节的小姐姐。这是我第一次面互联网，小姐姐说我底子很好(听完我很汗颜，真的太多不会了)。这次算是积累经验，见识一下互联网面试的环节和题目类型。提前批能面我已经很感谢了，更不用说跟我聊了56分钟。我真在10分钟的时候就感觉已经快结束了。结尾我说了一大段感谢的话，小姐姐居然还问我对base有没有要求啥的。。。我觉得我这才一面。答的这么屎，居然问我base，哈哈哈小姐姐人真的很有趣。看我答不上编程题还一直说可以用R和python，但我当时真的太紧张了，直接放弃了。


面完也有动力了，之前颓了快半个月，题目也没刷，东西也没做，机器学习算法还没看完，英硕最近写论文，又在家隔离了4个月了，整个人非常非常没精神。面成这样也是意料之中。这面完又有动力了。不过我是真不了解为啥小姐姐能跟我聊这么久，如果我当面试官碰到我自己，那10分钟我估计就让我滚蛋了。有小伙伴能解答一波么。



作者：闭关修炼的小菜鸟
链接：https://www.nowcoder.com/discuss/451296?type=2&order=3&pos=88&page=1&source_id=discuss_tag&channel=0
来源：牛客网

1. 项目相关

2. Spring介绍一下

3. SpringMVC工作流程

4. 常见注解说一下

5. Java用过什么集合框架

6. HashMap源码说一下（细说，从初始化到put、get、扩容、红黑树、1.8做了哪些优化）

7. ConcurrentHashMap源码看过吗？讲一下吧

8. 如何保证线程安全，1.7呢？

9. JUC包下还知道什么类，讲一下？

10. synchronized实现原理？和Lock的区别？

11. volatile呢？怎么实现的？

12. 类加载、双亲委派、自己实现的话怎么做

13. GC讲一下

14. 说一下你知道的垃圾回收器

15. Class类文件怎么回收（不是对象，太菜了，想了半天不知道咋回收，没答上）

16. 浏览器输入url发生了什么？（细说，包括每一层涉及到的协议）

17. 刚刚提到TCP三次握手，详细说一下吧

18. 四次挥手最后等待为什么2MSL

19. RIP协议怎么解决的环路问题

20. 数据库范式讲一下（没答好）

21. 引擎讲一下

22. 隔离级别

23. 有哪些索引，为什么用B+树

24. 项目哪里用到了redis，说一下常用数据类型的使用场景

25. 三大问题解决

26. 刚刚提到的分布式锁怎么实现的

27. Unicode和UTF-8和ASCLL之间的关系？（不知道）

28. Spring里面的设计模式

29. 还知道哪些

30. 写个单例吧

31. 时间差不多了，写个简单的题目吧（单词翻转）



13日下午两点场，字节提前批广告后端Java。
体验很好。
本人菜鸡一枚，原以为简历都过不去，有个机会就不错啦！

作者：wymwymwym
链接：https://www.nowcoder.com/discuss/451281?type=2&order=3&pos=89&page=1&source_id=discuss_tag&channel=0
来源：牛客网

1。算法题，两个链表了类型的整数求和，如1->2->5与3->6求和得到1->4->1。用栈或者反转链表

2。Java线程如何同步的。什么叫CAS。锁这些在cpu层面实现还是虚拟机层面。volatile怎么实现的保证读到的是最新的值。

3。堆内存和栈内存的区别。使用场景。

4。内存页的置换算法。分别怎么实现的。lru，lfu

5。中断的过程。

6。数据库的锁。什么时候用表锁，什么时候用行锁。我说的是能够使用索引的用行锁，不能使用索引的用表锁。不知道对不对，求大神告知。意向锁了解吗。这是个啥。。

7。如果一个sql查询特别慢，怎么办。

8。主键索引和普通索引哪个更快，为什么

9。客户输入一个https的url，发生了什么

10。http的方法有哪些。除了get和post还有吗。幂等性是什么意思。猜一猜delete是不是幂等的。

11。redis的持久化方法。rdb和aof的区别。解释copy on write。

12。写线程安全的单例模式。DCL的volatile为什么需要。静态内部类的方式为什么线程安全。



作者：kaifang
链接：https://www.nowcoder.com/discuss/451047?type=2&order=3&pos=96&page=1&source_id=discuss_tag&channel=0
来源：牛客网

总体感觉，比想象中简单？
一面 7.13日 17：00开始 共 58分钟
自我介绍 共30+分钟
介绍了一下自己从本科到研究生期间的历程，主要说的是自己写的一些项目，比较感兴趣

https
http 和 https 的区别 ，以及https加密的过程
get post 区别
get能把参数放body吗，post能把参数放在url里面吗
mysql
给了几个sql语句分析使用什么索引，以及索引是否能命中。(不擅长sql语句，但是有模有样分析了下，对了一半)

1
2
select a,b from table where a > 0 and b == 1
select a from table where a like ....
redis
redis 数据类型
redis 跳表，查询和插入复杂度
持久化方式 RDB 和 AOF，然后说了一堆指令，不清楚
语言(python/go)
python 多线程你觉得怎么样，能跑满cpu吗，GIL解释下
python2 python3 区别。xrange ,range 的区别
goroutine 为什么轻量
手撕算法 (最后10分钟不到了)
查找有序数组中一个目标值出现的第一次位置，没有找到返回 -1
我先口述了直接遍历，哈希表，然后提出要用二分，他说那就写个二分吧。
一开始写的是正常的二分，发现没有考虑重复元素的情况，然后改成查找左边界了。然后给面试官解释了一下，面试官明白了就没出题了。

反问
让我多看下redis 和 mysql，今天先就这样了。

总结
总有某些知识点触及到知识盲区，此时你可以结合自己的学习经验，提出自己的看法，而不是直接说不知道。

作者：小王大王
链接：https://www.nowcoder.com/discuss/451027?type=2&order=3&pos=98&page=1&source_id=discuss_tag&channel=0
来源：牛客网

爬楼梯，写了非递归实现要求写递归，分析递归时间复杂度出了点问题，后面测试N=50出现了INT越界没解决
一道智力题？狼和羊巴拉巴拉 答出来了不知道对不对
session和cookie区别，如何实现登录
TCP三次握手写序号（没太理解面试官意思，询问后感觉有点不耐烦就按照自己想的画了个三次握手）
结束（没有反问环节，面试官就古德拜了，面完就觉得应该是被刷了吧，哎。）

作者：牛客000000000000001号
链接：https://www.nowcoder.com/discuss/451009?type=2&order=3&pos=99&page=1&source_id=discuss_tag&channel=0
来源：牛客网

楼主投的是杭州西瓜视频，面试官提前几分钟进了房间，刚开始就是让自我介绍，我简单说了下。
接着就是一个简单的问题，TCP三次握手，这个复习的时候看了挺久我觉得我回答的还行，然后问为什么是三次两次不行吗，接着问TCP怎么做到可靠传输的，最后又让我讲了TCP的拥塞控制，网络的部分就告一段落了，到现在应该还没什么大问题。
再往后就是问操作系统的知识，问我进程的处理机状态，我忘记了（楼主的操作系统是选择性复习的，只看了银行家算法死锁什么的），然后面试官就问知不知道死锁，我说知道，讲了发生死锁的条件，接着他问那死锁了怎么办，我一时不知道怎么回答，那就解除死锁呗，可是怎么解除啊，一点印象都没有了，又说不知道，这个时候面试官应该就有点失望了，他问我你操作系统怎么复习的，我就说有针对性的复习的，然后就被教育了，要系统 复习巴拉巴拉，这个方面就过去了，心态爆炸。
接着是问JAVA，问了重载与重写的区别，应用场景，脑子一时短路答的也不好，刚刚一被怼心态爆炸，这个就明显慌了不能好好思考了，坑坑巴也算讲出来了，接着问synchronized作用于成员方法和静态方法的区别，这个答出来了，然后问具体开发中有什么要注意的，我虽然知道区别可是我没用过啊，心态爆炸*2，接着问我了解hashmap吗，我说了解，心想送分题啊刚刚才看过，就讲了底层使用数组加链表，jdk1.8之后还使用了红黑树，拉链法处理冲突，然后面试官问我那put一个元素的流程是什么呢，，楼主表示直接懵逼，只记了个流程不知道原理，就说不知道，然后说岗位需要的话会尽快学习，说完这句话又被怼了，面试官说这不是岗位需不需要的问题，而是你必须掌握的知识，巴拉巴拉。然后就是写代码，让写单例模式的双重校验锁，我说我不会，我会写懒汉模式，饿汉模式，枚举方式的，可是我就是不会这个啊，他又问那你能讲讲这个吗，我说可以讲单例但是双重校验锁单例讲不出来，然后面试官说你写个快排吧，感觉这是面试官故意出了个简单的题目让我缓一缓，可是不争气的楼主此时快排也写不出来了，思考了一会写了大部分出来，关键处应该用while的用成了if，还有一步怎么操作的也忘记了，最后也没能完整写出来，看得出面试官挺失望的，说今天就到这里吧，问我有什么想问的，我苦笑了一下说道，本来有想问的，但是已经得到答案了，最开始想问的是给我一些学习上的经验，在刚刚的交流中已经领悟到了只刷面经是不行的，还是要深挖底层，系统学习，谢谢您，再见。。然后就结束了。
总结一下：面试官人很好，整个过程多次想用送分题拯救楼主，奈何楼主太菜，只突击准备了两天，所有的都是只知道结论不知道原理，准备的安卓知识算法题也没用上，兄弟们要吸取经验，千万记住要深挖底层，只说个面经上的结论是没有用的。不管怎么说也是人生中第一次面试，也收获了很多，有了更清晰的学习方向，未来可期，加油 ！

作者：我妻雪乃
链接：https://www.nowcoder.com/discuss/450984?type=2&order=3&pos=101&page=1&source_id=discuss_tag&channel=0
来源：牛客网

刚刚一面面完了，说实话面的很不好，没有反问环节应该是挂了，我虽然挂了希望这篇面经能对其他人有用。
因为我说熟悉c++，所以是c++的问题多一些。
1:上来先做题，给一个int形数组，从里面取3个数能构成三角形，并且该三角形周长最长。（我想的是先排序，然后从后遍历，后面的就是最大的，可惜没写出来就被叫停了，面试官表示明白我的想法，紧张到sort()函数的头文件都忘记了）。
2:用栈实现队列，leetcode简单程度，只让我说了思路。
3:结构体和类的区别（默认权限不一样）。
4:chat int long 32位机器的sizeof大小。
5:http是怎样保持登录状态的，https和http的区别，为什么我们需要端口，比如http80https443我们为什么需要这个端口。
6:进程通信方式，线程通信方式。
7:线程可以共享进程的哪一部分内存。
8:virtual关键字（虚函数，纯虚函数）。
9:然后问到了可以转Java么，并询问了你觉得java和c++的区别。
10:智能指针，如果循环引用了应该怎么办。

总的来说，问的问题还蛮基础的，没有问到stl的相关知识，但是我经常就是只知道是什么，不知道为什么，这样的话是很扣分的，引用别人面经的一句话。“我们并不指望你掌握所有知识，当今社会这也是不现实的，我们更加希望你对你会的东西有自己的理解，能作一点你自己的推断”
希望大家以后在回答面试官问题的时候也可以加一些自己的理解自己的看法，或许就不会落到我这种地步了。
虽然出师不利，但是秋招还是要继续，大家继续加油吧。

作者：老鼠遇到猴
链接：https://www.nowcoder.com/discuss/450977?type=2&order=3&pos=102&page=1&source_id=discuss_tag&channel=0
来源：牛客网

7.13下午第一次面试(1h)。面试官人很友善、会给提示，聊得很愉快。许愿通过。
自我介绍(介绍学习情况、项目情况)
要不要考研、个人规划
说思路：实现一个栈，o(1)时间找最大值
写代码：矩阵从左上到右下找最小路径
说思路：删除单链表的倒数第k个节点
说思路：数据库日志文件记录了登录登出操作，怎么求最大在线人数
说思路：二叉树的最近公共祖先
java的垃圾回收(了解不多，没后续问)
tcp为什么是三次握手四次挥手
Linux如何杀进程
kill 还能发什么信号
孤儿进程
kill -9 能不能杀孤儿进程
主键索引和普通索引，回表
索引，为什么用B树
介绍websocket(项目相关)
介绍p2p，stun/turn (项目相关)
为什么实习，要不要校招提前批
反问
7.15日第二次面试（1h）
自我介绍
红黑树、AVL树
B树、B+树
tcp 三次握手、拥塞控制
写代码：模拟页面置换算法：替换掉最久未使用的页面
进程间的通信
操作系统锁的实现
反问
作者：彷徨の比企谷
链接：https://www.nowcoder.com/discuss/450909?type=2&order=3&pos=104&page=1&source_id=discuss_tag&channel=0
来源：牛客网

面试官很准时，也很友好
1.自我介绍
可能我项目太简单没问项目。。
2.说一下打开一个网页的全过程
3.OSI七层模型
4.定义一个变量，内存是怎么分配的
5.内存的分区，堆栈区，代码区什么的，分别储存什么
6.进程和线程的区别
7.算法题：
一个链表，同时有next结点和child结点，将此链表转化为一个普通的单向链表，转换规则如下：
如果当前结点a有child结点，则将child结点放在a和a->next之间。如：


作者：HumphreyHao
链接：https://www.nowcoder.com/discuss/450561?type=2&order=3&pos=114&page=2&source_id=discuss_tag&channel=0
来源：牛客网

7月1号内推,7号约面试,11号一口气面完,20分钟后hr打电话通知过了,一共11天

难度比百度阿里浅一些,但是比其他的又深一些,有的细节记不清楚了,可能有顺序错误,连面了5个半小时太累了.

一面
闲聊吹逼阶段,比较放松
自我介绍
介绍一下实习
你好像用到了MQ,主流MQ有哪些?
为什么选RMQ?
RMQ的主要有哪些组成部分?
讲讲消费模式和刷盘策略吧
基础知识问答,开始严肃
Java泛型机制了解吗?
在哪用到了?(答集合类)
集合类源码看过吗?
介绍一下String三个类的区别吧,源码看了吗?(答看了)
哪个线程安全?怎么实现的?
String拼接是咋做到的?
反射了解吗?
Spring里哪用到了反射(答动态代理)
静态代理和动态代理的区别?JDK代理的条件?
(非常生硬的转回到集合类)上面你说看了一些源码,我们聊聊HashMap吧
HashMap线程安全吗?(答不安全)
为啥不安全?(我开玩笑回了一个,因为他没锁门,面试官一听也笑了笑,主要是看气氛太紧张了)
怎么实现线程安全?(集合类方法/concurrentHashMap)
HashMap内部是咋实现的?(数组+红黑树/链表)
扩容了解吗?为啥因子是0.75不是别的?JavaDoc有看吗?(这个记不太清楚了,印象里是javadoc里有写,是服从一个lambda为0.75的泊松分布)
扩容之后的数据落在哪?为啥容量一定是2的倍数?为啥引入红黑树?红黑树要啥参数?并发的时候咋处理的?
.....这一块聊了好久好久,主要是我正好看了源码,面试官应该也对这一块比较感兴趣,就balabala聊了快20+分钟
计算机网络
很明显上面的hashmap那一块面试官问超时了,所以计算机网络就问的很快.

tcp和udp的区别
三握四挥,为啥不是2握
tcp的流量控制,拥塞控制
http的报文结构
https的连接请求过程(这一题没答好,我忘记了中间还有一步是客户端和服务器约定加密等级,被面试官点出来了,心里一慌)
操作系统
cat,tail,grep,top,df..问了一堆命令
内核态和用户态,如何切换
算法题
01矩阵最大正方形,经典题了,dp选左上最小+1,随便写了一下,没让跑test.

面完面试官直接让我原地等着,5分钟之后下一轮.

二面
闲聊
实习咋样,现在在哪干什么
面美国还是中国岗位?美国有转正,为啥要回国呀?(喷了一顿美国签证策略和大统领的疫情治理)
介绍一下RMQ,咋配置的
介绍一下你那个实习项目,上线了吗?(答还没上,在测试环境等测试通过)有几个人用啊?(没几个人,就测试环境的几个师傅在写test)?上线之后呢?(差不多有50+partner会访问我们网站)
实习收获了啥(答:钱!,还有对实际开发框架的一些认识,code review啥的)
Redis分布式锁了解不?(答不了解,只用过单机版)
基础知识
讲讲垃圾回收?新生代老年代?为啥这么划分?
内存泄漏?怎么解决?
设计模式知道哪些(14个随便选了7,8个说了一下)?单例模式?线程安全吗?(不安全)咋改成线程安全?(内部类,加锁,枚举)
面试官点了点头,好像心情还不错
开闭原则?迪米特法则?
读过啥源码?(我心下一慌,不会又要扯hashmap那一堆吧?)结果并没继续问
计算机网络
http1.0和1.1区别
三握四挥,握手发了啥,syn的英文全称是啥(这个真忘了,随便说了一个synchronized number)
https加密过程
操作系统
linux iNode是啥?(没听说过)
日志中查找关键字(cat+grep)
日志太大咋处理?(给运维的人打电话)你们公司平常咋处理日志的(买第三方服务啊!)
算法题
二叉树找target路径,他先问我见过没,我实在是不好意思厚着脸皮说没见过,就说这是算法课例题.
然后随便写了一下.

反问环节
觉得哪还能提高,答Redis分布式锁那个地方要了解一下,然后linux系统了解一下
不知道过了没,很紧张,毕竟有俩问都完全不会,大概40分钟之后通知3轮,长出一口气.

三面
字节好像是过了二面就捞了,所以心里没啥压力,有点放飞自我
##闲聊

自我介绍
你们公司是干啥的?哦我好像用过xxx那个软件,是你们公司的吗?(并不是,是我们头号竞争对手的,面试官是来拆台的吗?),最近疫情对公司业务影响大不(我基于q2财报和q3预期以及最近的公司资本市场运作稍微聊了一下,大意就是有影响,但在逐渐好转)
你本科不是cs的,那操作系统/计算机网络/数据库你都上过吗?(大二上的这三门)
讲讲Nosql?
为啥你要选这个?(公司给的这个啊,我也改不了)
为啥Nosql比sql快?主要有什么优缺点?为啥你下面的项目又用sql去了?(给他讲了快20分钟,什么业务流程需要强一致性啊,用户这边要求快速更新页面sql太慢了啊,实习的业务不需要事务隔离啊balabala)
基础知识
看了哪些源码?
ConcurrentHashMap为啥同步?1.8做了哪些优化?
讲讲JVM,平台迁移性
算法题
二叉树转单链表,常规题,递归一下完事了.

闲聊2
做完算法题还有不少时间,面试官好像对我实习做的那个项目的具体内容还是很感兴趣,就和我聊了聊异步发送请求那一块的实现,正好我昨天还在写项目的doc,就又聊了10几分钟.没问啥问题,有点像平常组会的时候讨论技术.

面完20分钟通知过了.

面完感觉就是实习真的太重要了,是一个实力的证明,以及一个很好的开启话题的起点.三轮面试遇到的面试官技术实力都很强,尤其是第三轮的面试官对我的技术栈似乎了如指掌,我也学到了很多新的认识.面试的时候也没有遇到刻意压力面什么的,更像是讨论一些技术的选型,框架选择,流程走的也快,比其他一线大厂的面试体验都好很多.


作者：HumphreyHao
链接：https://www.nowcoder.com/discuss/450561?type=2&order=3&pos=114&page=2&source_id=discuss_tag&channel=0
来源：牛客网

7月1号内推,7号约面试,11号一口气面完,20分钟后hr打电话通知过了,一共11天

难度比百度阿里浅一些,但是比其他的又深一些,有的细节记不清楚了,可能有顺序错误,连面了5个半小时太累了.

一面
闲聊吹逼阶段,比较放松
自我介绍
介绍一下实习
你好像用到了MQ,主流MQ有哪些?
为什么选RMQ?
RMQ的主要有哪些组成部分?
讲讲消费模式和刷盘策略吧
基础知识问答,开始严肃
Java泛型机制了解吗?
在哪用到了?(答集合类)
集合类源码看过吗?
介绍一下String三个类的区别吧,源码看了吗?(答看了)
哪个线程安全?怎么实现的?
String拼接是咋做到的?
反射了解吗?
Spring里哪用到了反射(答动态代理)
静态代理和动态代理的区别?JDK代理的条件?
(非常生硬的转回到集合类)上面你说看了一些源码,我们聊聊HashMap吧
HashMap线程安全吗?(答不安全)
为啥不安全?(我开玩笑回了一个,因为他没锁门,面试官一听也笑了笑,主要是看气氛太紧张了)
怎么实现线程安全?(集合类方法/concurrentHashMap)
HashMap内部是咋实现的?(数组+红黑树/链表)
扩容了解吗?为啥因子是0.75不是别的?JavaDoc有看吗?(这个记不太清楚了,印象里是javadoc里有写,是服从一个lambda为0.75的泊松分布)
扩容之后的数据落在哪?为啥容量一定是2的倍数?为啥引入红黑树?红黑树要啥参数?并发的时候咋处理的?
.....这一块聊了好久好久,主要是我正好看了源码,面试官应该也对这一块比较感兴趣,就balabala聊了快20+分钟
计算机网络
很明显上面的hashmap那一块面试官问超时了,所以计算机网络就问的很快.

tcp和udp的区别
三握四挥,为啥不是2握
tcp的流量控制,拥塞控制
http的报文结构
https的连接请求过程(这一题没答好,我忘记了中间还有一步是客户端和服务器约定加密等级,被面试官点出来了,心里一慌)
操作系统
cat,tail,grep,top,df..问了一堆命令
内核态和用户态,如何切换
算法题
01矩阵最大正方形,经典题了,dp选左上最小+1,随便写了一下,没让跑test.

面完面试官直接让我原地等着,5分钟之后下一轮.

二面
闲聊
实习咋样,现在在哪干什么
面美国还是中国岗位?美国有转正,为啥要回国呀?(喷了一顿美国签证策略和大统领的疫情治理)
介绍一下RMQ,咋配置的
介绍一下你那个实习项目,上线了吗?(答还没上,在测试环境等测试通过)有几个人用啊?(没几个人,就测试环境的几个师傅在写test)?上线之后呢?(差不多有50+partner会访问我们网站)
实习收获了啥(答:钱!,还有对实际开发框架的一些认识,code review啥的)
Redis分布式锁了解不?(答不了解,只用过单机版)
基础知识
讲讲垃圾回收?新生代老年代?为啥这么划分?
内存泄漏?怎么解决?
设计模式知道哪些(14个随便选了7,8个说了一下)?单例模式?线程安全吗?(不安全)咋改成线程安全?(内部类,加锁,枚举)
面试官点了点头,好像心情还不错
开闭原则?迪米特法则?
读过啥源码?(我心下一慌,不会又要扯hashmap那一堆吧?)结果并没继续问
计算机网络
http1.0和1.1区别
三握四挥,握手发了啥,syn的英文全称是啥(这个真忘了,随便说了一个synchronized number)
https加密过程
操作系统
linux iNode是啥?(没听说过)
日志中查找关键字(cat+grep)
日志太大咋处理?(给运维的人打电话)你们公司平常咋处理日志的(买第三方服务啊!)
算法题
二叉树找target路径,他先问我见过没,我实在是不好意思厚着脸皮说没见过,就说这是算法课例题.
然后随便写了一下.

反问环节
觉得哪还能提高,答Redis分布式锁那个地方要了解一下,然后linux系统了解一下
不知道过了没,很紧张,毕竟有俩问都完全不会,大概40分钟之后通知3轮,长出一口气.

三面
字节好像是过了二面就捞了,所以心里没啥压力,有点放飞自我
##闲聊

自我介绍
你们公司是干啥的?哦我好像用过xxx那个软件,是你们公司的吗?(并不是,是我们头号竞争对手的,面试官是来拆台的吗?),最近疫情对公司业务影响大不(我基于q2财报和q3预期以及最近的公司资本市场运作稍微聊了一下,大意就是有影响,但在逐渐好转)
你本科不是cs的,那操作系统/计算机网络/数据库你都上过吗?(大二上的这三门)
讲讲Nosql?
为啥你要选这个?(公司给的这个啊,我也改不了)
为啥Nosql比sql快?主要有什么优缺点?为啥你下面的项目又用sql去了?(给他讲了快20分钟,什么业务流程需要强一致性啊,用户这边要求快速更新页面sql太慢了啊,实习的业务不需要事务隔离啊balabala)
基础知识
看了哪些源码?
ConcurrentHashMap为啥同步?1.8做了哪些优化?
讲讲JVM,平台迁移性
算法题
二叉树转单链表,常规题,递归一下完事了.

闲聊2
做完算法题还有不少时间,面试官好像对我实习做的那个项目的具体内容还是很感兴趣,就和我聊了聊异步发送请求那一块的实现,正好我昨天还在写项目的doc,就又聊了10几分钟.没问啥问题,有点像平常组会的时候讨论技术.

面完20分钟通知过了.

面完感觉就是实习真的太重要了,是一个实力的证明,以及一个很好的开启话题的起点.三轮面试遇到的面试官技术实力都很强,尤其是第三轮的面试官对我的技术栈似乎了如指掌,我也学到了很多新的认识.面试的时候也没有遇到刻意压力面什么的,更像是讨论一些技术的选型,框架选择,流程走的也快,比其他一线大厂的面试体验都好很多.



作者：askey
链接：https://www.nowcoder.com/discuss/450552?type=2&order=3&pos=115&page=1&source_id=discuss_tag&channel=0
来源：牛客网

6-23号hr面试邀请，1-2面约到6-30号

6-30号：

第一面：简单自我介绍，然后谈了一下在现在在腾讯的实习，然后就腾讯的实习工作，深入问了一些问题，主要是优化算法设计方面，涉及内容：树，排序，hash，大数据处理。没有出算法题。然后询问了一些操作系统方面的内容：内存管理（虚拟内存等），进程线程等。反问有什么问题要问的。

第二面：简单自我介绍，问对腾讯和字节发展的看法。算法题：从左上角走到右下角有多少种不同的路线（面试官说不是用dp给我整蒙了。。。实际他就是希望我用递归记忆华搜索的方式。。。也是有点迷？）然后问了一些基础问题：讲一下各种锁，以及自旋锁在什么情况下使用，讲一下内存管理等等吧，记不太清楚了。对了还问了能不能去字节实习。

7-3号：

第三面：简单自我介绍，然后问ptmalloc, tcmalloc（不了解。。。），然后问了下hash的实现，然后手写一个用拉链法实现的hash table（用的vector>实现的，面试官在结束的时候才跟我说希望我用链表的写法，尴尬，当时就觉得这么写简单。。。。）然后问怎么实现线程安全的hash table，然后问如何优化。分布式系统的问题：一致性hash以及各种情况下的处理。反问环节（问还有下一面吗？答还有一个leader的leader面试。摊手，好吧）。同样问了能不能去实习

7-9号：

四面面试官有事，再约时间

7-10号：

第四面；简单自我介绍。腾讯和字节实习的感受和对比。代码题：实现求一个整数流的下中位数。然后问了一下CAP理论，（一开始说问网络的，但是对网络真的不是很有把握。。。）以及zookeeper，一致性协议等等， 然后是项目介绍。反问环节。

7-12号：

hr面：简单自我介绍，聊一下腾讯和字节的实习感受。。。。聊能不能去字节实习，聊秋招offer的问题。时间大概20min，就说自己的想法就好？这一面就纯聊天。
