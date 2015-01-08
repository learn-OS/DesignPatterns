DesignPatterns
==============




目录

###设计模式   
	                                        
#####1 创建型模式                                
1.1 工厂方法（FactoryMethod）	            
1.2 抽象工厂（AbstractFactory）             
1.3 建造者模式（Builder）	                
1.4 单态模式（Singleton）	                
1.5 原型模式（Prototype）	                
                                            
#####2 结构型模式	                          
                                            
2.1 适配器模式（Adapter）                   
2.2 桥接模式（Bridge）	                    
2.3 组合模式（Composite）                   
2.4 装饰模式（Decorator）                   
2.5 外观模式（Facade）	                    
2.6 享元模式（Flyweight）                   
2.7 代理模式（Proxy）	                    
                                            
#####3 行为型模式	                            
3.1 责任链模式（Chain of Responsibility）   
3.2 命令模式（Command）	                    
3.3 解释器模式（Interpreter）	            
3.4 迭代器模式（Iterator）	                
3.5 中介者模式（Mediator）	                
3.6 备忘录模式（Memento）	                
3.7 观察者模式（Observer）	                
3.8 状态模式（State）	                    
3.9 策略模式（Strategy）	                
3.10 模板方法（TemplateMethod）	            
3.11 访问者模式（Visitor）                  













----------
	高内聚低耦合
	控制反转
	封装变化
	依赖倒置

	隔离接口
	开闭原则
	使用合成替代继承

	

####[设计模式 百科](http://baike.baidu.com/link?url=QGQbCTD0FKfOYvGwqzCKZinXiyNDvz95wVEjeyH3n_EShw1HoBRWAK-5y0cON0rkAN-roY0ppH8lqJy0S9e4ja)


####[设计模式六大原则](http://www.uml.org.cn/sjms/201211023.asp)


####[设计模式大全](http://blog.csdn.net/longronglin/article/details/1454315)


####[设计模式原则详解](http://blog.csdn.net/hguisu/article/details/7571617)






要深刻理解开源代码，必先掌握丰富的设计模式


DDD开发

[领域驱动设计(DDD:Domain-Driven Design)](http://www.jdon.com/ddd.html)  
[DDD领域驱动设计基本理论知识总结](http://www.cnblogs.com/netfocus/archive/2011/10/10/2204949.html)  
[DDD与TDD比较之——DDD](http://redhat.iteye.com/blog/1538233)  
[《漫谈设计模式》](http://redhat.iteye.com/blog/1007884)   
[以DDD为开发模式的设计步骤](http://blog.sina.com.cn/s/blog_8f1c156d010133fv.html)   



TODO开发



漫谈设计模式 手札
===========
>procedural programming PP   过程编程   
functional programming  FP   函数式编程  
                       OOP  面向对象编程  
  
[Java 设计模式 101](http://www.ibm.com/developerworks/cn/education/java/j-patterns/tutorial/j-patterns.html)

####面向对象语言三个特征
封装  
继承  
多态  

####模式的四个基本要素
模式名称(Pattern name)
问题(Problem)
解决方案(Solution)
效果(Consequence)

	模式：是某一上下文环境中一个问题的常用解决方案。

####模板方法
>模式解决的是DRY方式的开发，Don't repeat yourself 。  
>OAOO (Once and Only Once)---->模板方法

####回调
>在不同语言中实现方式不一样，C语言中使用函数指针实现回调，C#中使用代理(delegate)实现，java中使用内部匿名类实现回调。




####创建对象的方法
>创建对象而不会对客户对象和服务对象之间产生高耦合的模式方法，提高代码的可移植性和重用性。

#####单例模式(Singleton) 
>保证一个类在系统里只有一个对象被实例化  
>[Java 理论与实践: 正确使用 Volatile 变量](http://www.ibm.com/developerworks/cn/java/j-jtp06197.html)
>[单例模式的七种写法](http://cantellow.iteye.com/blog/838473)  
>[Java 设计模式之Singleton](http://hj198703.iteye.com/blog/1824940)  
>[单例模式](http://blog.csdn.net/lujiancs/article/details/8278843)  
>[Java单例模式二](http://www.360doc.com/content/11/0211/11/4154133_92086853.shtml)  
>[单例模式完全解析](http://www.blogjava.net/xylz/archive/2009/12/18/306622.html)  
>[JVM类加载过程学习总结](http://www.open-open.com/lib/view/open1371912222369.html)  
>[JVM类加载机制](http://blog.sina.com.cn/s/blog_4fe01e630100gu3x.html)  
>[JVM Classloader 类加载详解](http://www.open-open.com/doc/view/a9c79527b9db4942a458db55efa9b4ad)  
>[JVM 内存-学习笔记](http://www.open-open.com/doc/view/4d5f30c5cfc84565b722b3ad2a32d6ba)  
#####工厂方法(Factory Method)  
>使实例化对象和使用者之间保持低耦合  
#####原型模式(Prototype)  
>通过copy现有对象快速创建一个新的复杂对象
#####控制反转(IoC)  
>控制反转(IoC) 和 依赖注入(DI)是最流行的两个概念。



















UML建模
=============
[UML](http://www.uml.org.cn)


http://www.cnblogs.com/ywqu/archive/2009/12/29/1634804.html


[类图和对象图](http://www.uml.org.cn/oobject/200903165.asp)

[如此理解面向对象编程](http://www.uml.org.cn/mxdx/201303114.asp)


[UML概览](http://www.uml.org.cn/oobject/OObject.asp)

[UML 建模：创建类图 ](http://www.uml.org.cn/UMLTools/200712073.asp)








IBM Java高级
===============
[文档库](http://www.ibm.com/developerworks/cn/views/java/libraryview.jsp)  
[Java 设计模式与建模专题](http://www.ibm.com/developerworks/cn/java/design/?ca=j-r)  
[Java 8 中的 Streams API 详解](http://www.ibm.com/developerworks/cn/java/j-lo-java8streamapi/index.html)  
[JVM 并发性: 阻塞还是不阻塞？](http://www.ibm.com/developerworks/cn/java/j-jvmc3/index.html)  
[java中volatile关键字的含义](http://www.cnblogs.com/aigongsi/archive/2012/04/01/2429166.html)  
[java中关键字volatile的作用](http://sakyone.iteye.com/blog/668091)
[java多线程中的volatile](http://www.cnblogs.com/yakun/p/3589437.html)
[深入理解Java内存模型（四）——volatile ](http://www.infoq.com/cn/articles/java-memory-model-4/)






------
###重构 
>####重构的作用  
> 降低代码粒度.   
> 增加代码可复用度  
> 移除临时变量，降低资源消耗
> 减少计算、判断次数，提高运行性能
> 增加可读性
	                                        
#####1 重构原则

#####s

#####2 重构原则

#####s

#####3 重构原则

#####s

#####4 重构原则

#####s


#####5 重新组织函数

#####
- 提取.方法\[函数]\(Extract Method)
>从方法中抽取出更细力度的代码块，增加可复用度

- 内联函数(Inline Method)
>在函数调用点插入函数本体，然后移除该函数
>`int getRating(){  return (moreThanFiveLateDeliveries()) ？ 2 ： 1； }`
>`boolean moreThanFiveLateDeliveries(){ return _numberOfLateDeliveries > 5; }`  
>\-----------------  
>`int getRating(){ return(_numberOfLateDeliveries > 5) ? 2 ： 1 }`  

- 内联临时变量(Inline Temp)
>将所有该变量的引用动作，替换为对他的赋值的哪个表达式本身
>`double basePrice = anOrder.basePrice();`
>`return (basePrice > 1000)`  
>\------------------  
>`return (anOrder.basePrice() > 1000)`

- 用查询取代临时变量(Replacet Temp with Query)
>将表达式提炼到一个独立的函数中，将临时变量的多有引用点替换为对新函数的调用。此后，新函数也可以被其它函数使用
>`double basePrice = _quantity * -itemPrice;`  
>`if (basePrice > 1000)`  
>`   return basePrice * 0.95;`  
>`else`   
>`  return basePrice * 0.98;`   
>\-----------------  
>`if (basePrice > 1000)`  
>`   return basePrice() * 0.95;`  
>`else`   
>`  return basePrice() * 0.98;`  
>`....`  
>`double basePrice(){`  
>`    return _quantity * -itemPrice; `   
>` }` 

- 引入解释性变量(Introduce Explaining Variable)
>将复杂表达式（或其中一部分）的结果放进一个临时变量，以临时变量的名称来解释表达式的用途  
>`if((platform.toUpperCase().indexOf("MAC")>-1)&&(browser.toUpperCase().indexOf("IE")>-1)&&wasInitialized()&&resize>0){ //do something  }`  
>\-----------  
>`final boolean isMacOS =platform.toUpperCase().indexOf("MAC")>-1;`  
>`final boolean isIEBrowser =browser.toUpperCase().indexOf("MAC")>-1;` 
>`final boolean wasInitialized = resize>0;`   
>`if(isMacOS&&isIEBrowser&&wasInitialized()&&wasInitialized){  //      do something  }` 
- 分解临时变量(Split Temporary Variable)
>针对每次赋值，创造一个独立的对应的临时变量  
![](https://raw.githubusercontent.com/learn-OS/DesignPatterns/master/img/QQ20150108174354.png)  
![](https://raw.githubusercontent.com/learn-OS/DesignPatterns/master/img/QQ20150108174702.png)  


- 移除对参数的赋值(Remove Assignments to Parameters)
>Java 的按值传递，使对参数的任何修改都不回返回给调用对象
![](https://raw.githubusercontent.com/learn-OS/DesignPatterns/master/img/QQ20150108174702.png)  


- 以函数对象取代函数(Replace Method with Method Object)
- (Remove Assignments to Parameters)
- (Substitute Algorithm)


#####1 重构原则

#####s


#####1 重构原则

#####s


#####1 重构原则

#####s

#####1 重构原则

#####s

#####1 重构原则

#####s

#####1 重构原则

#####s









