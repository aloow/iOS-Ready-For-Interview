# iOS-Ready-For-Interview
* 每天清晨睁开眼，都愿你开心一点！
* 按计划愉快有效的前行！

## Tip
对于看官方文档或者国外博客吃力的朋友，可以用google的翻译功能，跟原文差别比较大的部分再看英文原文，这样看文档或者博客效率高很多，毕竟我们是吸收知识，而不是来学英语的。

## 思维导图
<img src="https://github.com/aloow/iOS-Ready-For-Interview/blob/master/images/BrainMapping.png" alt="BrainMapping" height="400" >

## 源代码到App
* 《程序员的自我修养》非常推荐的一本书
* [读书笔记之第一部分](https://www.jianshu.com/p/c6ab07042c7e)
* [读书笔记之第二部分](https://www.jianshu.com/p/4c153b34f75f) 未完待续...

## 单元测试
《iOS Test Driven Development by Tutorials》

## 语言
* OC
 * 内存管理、内存优化、内存布局 《iOS与OS X多线程和内存管理》《52个有效方法》
 * Runtime [无痕埋点](https://xietao3.com/2017/05/dataStatistics/)
 * Runloop
* Swift
 * Swift源码中基本数据结构实现
 * 进阶用法《objccn-swifter-tips》《objccn-advanced-swift》

## UIKit
* UIView、UIViewController生命周期
* 事件响应链
* UItableView优化
* 单元测试

## 多线程
* 创建线程与线程保活。[线程管理](https://developer.apple.com/library/archive/documentation/Cocoa/Conceptual/Multithreading/CreatingThreads/CreatingThreads.html#//apple_ref/doc/uid/10000057i-CH15-SW2)、[线程保活](https://developer.apple.com/library/archive/documentation/Cocoa/Conceptual/Multithreading/RunLoopManagement/RunLoopManagement.html#//apple_ref/doc/uid/10000057i-CH16-SW1)
* Operation [Raywenderlich](https://www.raywenderlich.com/5293-operation-and-operationqueue-tutorial-in-swift)
* GCD原理
* [锁和锁的应用](https://www.jianshu.com/p/8173d0e6dcee)

## 性能检测
* Instruments工具 [raywenderlich教程](https://www.raywenderlich.com/397-instruments-tutorial-with-swift-getting-started) 1.检测内存泄漏 2.内存增长 3.线程执行时间
* [官方视频](https://developer.apple.com/videos/play/wwdc2019/411/)
* Instruments help

## 数据库&缓存
* 缓存
 * SQLLife 极客时间课程 差异和性能优化
 * Realm
* 缓存
 * [YYCache](https://github.com/ibireme/YYCache)
 * [Kingfish](https://github.com/onevcat/Kingfisher)

## 网络编程
* Http/Https 《图解http/https》
* TCP/IP 《图解TCP/IP》
* 极客时间 趣谈网络协议
* 原生URLSession与[Alamofire](https://github.com/Alamofire/Alamofire)区别

## 跨平台
* Fullter使用
* 实现机制
* [Flutter中文网](https://flutterchina.club/)
* [Flutter电子书](https://book.flutterchina.club/)

## 数据结构&算法
* [我的另外一个库](https://github.com/aloow/DataStructure-Algorithm/blob/master/README.md)
* 字符串
* 数组与排序
* 链表与数
* 动态或贪心
* [LeetCode中文网](https://leetcode-cn.com/explore/interview/card/bytedance/)
* [面试精选100题](https://leetcode-cn.com/problemset/top/)
#### 其他重要概念
* [Hash](https://mp.weixin.qq.com/s/Q0w59YQmZN7tWxSXPR1vrA)

## 其他参考资料 关于面试题
* [iOS开发舆图](https://xiaozhuanlan.com/topic/7365849012)
* [极客时间](https://time.geekbang.org/)
* [面试题](https://juejin.im/post/5da6d14ae51d4524b601b78a)
* [面试题](https://www.iweslie.com/index.php/archives/93/)
* [掘金翻译计划](https://github.com/xitu/gold-miner)
* [bestswifter blog](https://github.com/bestswifter/blog)
* [iOS-InterviewQuestion-collection](https://github.com/liberalisman/iOS-InterviewQuestion-collection)
* [bat-offer](https://github.com/bestswifter/blog/blob/master/articles/bat-offer.md)
* [awesome-ios](https://github.com/vsouza/awesome-ios#cache)



## 暂用
### 第一阶段
1. Runtime
* 对象结构
* 消息转发流程

1.1 实践：
无痕埋点
1.页面展示路径 UIViewController  
目标：页面展示次数 停留时间
2.用户点击按钮事件  
目标：页面 哪个按钮 点击了多少次
3.上下滑动scroll view \ table view
目标：scrollview 监听draging，tableView点击row section


2. Runloop
* 与线程的关系

3. 多线程与锁



### 第二阶段
1. UIKit

2. 性能检测

3. 性能优化

4. 单元测试


### 第三阶段
1. 网络编程

2. 数据库&缓存

3. 开发框架与设计模式

### 第四阶段
1. 跨平台
2. 计算机组成原理
