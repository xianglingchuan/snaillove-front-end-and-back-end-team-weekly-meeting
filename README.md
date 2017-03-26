# snaillove-front-end-and-back-end-team-weekly-meeting
公司每周前端和后台部门内部会议总结。


### 5、RESTful
1)[RESTful API最佳实践](https://zhuanlan.zhihu.com/p/25647039)    
2)Web接口管理工具，开源免费，接口自动化,MOCK数据自动生成，自动化测试，企业级管理。阿里妈妈MUX团队出品！阿里巴巴都在用！1000+公司的选择！   
  [RAPWeb接口管理工具](https://github.com/thx/RAP)
  
        

### 4、[Fiddle抓取https协议(ios)](http://blog.csdn.net/xianglingchuan/article/details/57122268)


### 3、十分钟掌握markdown语法
    > [在线的markdown编辑器](https://www.zybuluo.com/mdeditor)    
    [十分钟掌握markdown语法](https://www.zybuluo.com/JauYang/note/665506)
    
   
### 2、React 简介
#### React是Facebook开发的一款JS库，那么Facebook为什么要建造React呢，主要为了解决什么问题，通过这个又是如何解决的？

##### 从这几个问题出发我就在网上搜查了一下，有这样的解释。

Facebook认为MVC无法满足他们的扩展需求，由于他们非常巨大的代码库和庞大的组织，使得MVC很快变得非常复杂，每当需要添加一项新的功能或特性时，系统的复杂度就成级数增长，致使代码变得脆弱和不可预测，结果导致他们的MVC正在土崩瓦解。认为MVC不适合大规模应用，当系统中有很多的模型和相应的视图时，其复杂度就会迅速扩大，非常难以理解和调试，特别是模型和视图间可能存在的双向数据流动。

##### 解决这个问题需要“以某种方式组织代码，使其更加可预测”，这通过他们(Facebook)提出的Flux和React已经完成。

> Flux是一个系统架构，用于推进应用中的数据单向流动。React是一个JavaScript框架，用于构建“可预期的”和“声明式的”Web用户界面，它已经使Facebook更快地开发Web应用

##### 那么React是解决什么问题的，在官网可以找到这样一句话：

> We built React to solve one problem: building large applications with data that changes over time.

##### 构建那些数据会随时间改变的大型应用，做这些，React有两个主要的特点：

1. 简单

简单的表述任意时间点你的应用应该是什么样子的，React将会自动的管理UI界面更新当数据发生变化的时候。

2. 声明式

在数据发生变化的时候，React从概念上讲与点击了F5一样，实际上它仅仅是更新了变化的一部分而已。
React是关于构造可重用组件的，实际上，使用React你做的仅仅是构建组建。通过封装，使得组件代码复用、测试以及关注点分离更加容易。

##### 另外在React官网上，通过《Why did we build React?》为什么我们要建造React的文档中还可以了解到以下四点：
- React不是一个MVC框架
- React不使用模板
- 响应式更新非常简单
- HTML5仅仅是个开始


### 1、MQ服务端配置的安装、Topic设计思路

**内容描述：** Apollo与Mosquitto的安装配置<BR>
    在windows下面的安装和配置，linux下的文档还在整理和测试中。<BR>
    http://blog.csdn.net/xianglingchuan/article/details/54932971


MQTT Topic的设计思路<BR>
    利用消息队列MQTT，打造一款属于自己的IM社交软件,不错的案例分析。<BR>
    http://www.tuicool.com/articles/i2QbUfZ<BR>
    

