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
###封装
>更多的隐藏对象字段，不用public生命类对象字段 



###重构 
>#####重构的作用
>1.使软件更容易理解
>2.帮助找到Bug
>3.提高编译速度
>4.
>#####重构方法
>1.尽量简洁
>2.使用三位运算符
>3.使用常量替换硬编码
>4.使用方法替换反复出现的表达式
>5.及早结束非正常逻辑
>6.满足条件立即跳出循环
>7.使用表结构分离公共逻辑，避免重复（坚持DRY原则）
>8.分离变化参数，使用格式化方法 
>9.使用方法抽取公共逻辑
>10.尽量使用已有的Java API 
>11.使方法通用化
>12.避免空语句 
>13.公共逻辑后置
>14.公共逻辑前置
>15.使用清晰的布尔型变量替换逻辑表达式 
>16.减少重复计算
>17.何时需要何时创建
>18.利用已有的计算结果
>19.替换switch结构
>20.避免对参数赋值 
>21.使用类替换类型代码 [示例5](http://wenku.baidu.com/view/034d5837a32d7375a417806b.html)
>22.使用对象封装参数
>23.封装集合操作 
>24.避免一次性临时变量
>25.一个变量一种作用 

[](http://wenku.baidu.com/view/27423a5c3b3567ec102d8a0c.html)



>####《重构》这本书真扯淡。读了才知道重构重要，但不是这本书  
示例：
[Java重构示例一](http://wenku.baidu.com/view/8920278ca0116c175f0e48fe.html?re=view)    
>使用变量替换硬编码  
[Java重构示例二](http://wenku.baidu.com/view/34eb7110f18583d0496459d8.html?re=view)  
[Java重构示例三](http://wenku.baidu.com/view/eda2535bbe23482fb4da4c7e.html?re=view)  
[Java重构示例四](http://wenku.baidu.com/view/8920278ca0116c175f0e48fe.html?re=view)  
[Java重构示例五](http://wenku.baidu.com/view/034d5837a32d7375a417806b.html?re=view)  
[Java重构示例四]()  
	                                        
#####1 重构原则
>![](https://raw.githubusercontent.com/learn-OS/DesignPatterns/master/img/QQ20150109144912.png)
>![](https://raw.githubusercontent.com/learn-OS/DesignPatterns/master/img/QQ20150109144922.png)

#####2 代码的坏味道
- 重复代码（Duplicated Code）
- 过长函数（Long Method）
- 过大的类（Large Class）
- 过长参数列（Long Parameter List）
- 发散式变化（Divergent change）
- 散弹式修改（Shotgun surgery）
- 依赖情结（Feature Envy）
- 数据泥团（Data Clumps）
- 基本类型偏执（Primitive Obsession）
- switch 惊悚现身（Switch Statements）
- 平行继承体系（Parallel InheritanceHierarchies）
- 冗赘类（Lazy Class）
- 夸夸其谈的未来性（Speculative Generality）
- 令人迷惑的暂时字段（Temporary Field）
- 过度耦合的消息链（Message Chains）
- 中间人（Middle Man）
- 狎昵关系（Inappropriate Intimacy）
- 异曲同工的类（Altemative Classes with Different Interfaces）
- 不完美的库类（incomplete Library Class）
- 纯稚的数据类（Data Class）
- 被拒绝的遗赠（Refused Bequest）
- 过多注释（Comments）




#####3 构筑测试体系
>![](https://raw.githubusercontent.com/learn-OS/DesignPatterns/master/img/QQ20150109145010.png)
>![](https://raw.githubusercontent.com/learn-OS/DesignPatterns/master/img/QQ20150109145018.png)

#####4 重构列表
>![](https://raw.githubusercontent.com/learn-OS/DesignPatterns/master/img/QQ20150109145131.png)


#####5 重新组织函数
	> 降低代码粒度.   
	> 增加代码可复用度  
	> 移除临时变量，降低资源消耗
	> 减少计算、判断次数，提高运行性能
	> 增加可读性


- 提取.方法\[函数]\(Extract Method)
>从方法中抽取出更细力度的代码块，增加可复用度
>![](https://raw.githubusercontent.com/learn-OS/DesignPatterns/master/img/QQ20150109103742.png)


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
>Java 的按值传递，使对参数的任何修改都不回返回给调用对象，
>通过final 对替换参数的临时变量赋值，强制遵循“不对参数赋值”这一原则
![](https://raw.githubusercontent.com/learn-OS/DesignPatterns/master/img/QQ20150108175244.png)  
![](https://raw.githubusercontent.com/learn-OS/DesignPatterns/master/img/QQ20150108175401.png)
![](https://raw.githubusercontent.com/learn-OS/DesignPatterns/master/img/QQ20150109101953.png)


- 以函数对象取代函数(Replace Method with Method Object)
>![](https://raw.githubusercontent.com/learn-OS/DesignPatterns/master/img/QQ20150109103002.png)


- 替换算法(Substitute Algorithm)
>![](https://raw.githubusercontent.com/learn-OS/DesignPatterns/master/img/QQ20150109103351.png)




#####6.在对象之间迁移特性
- 搬移函数（Move Method）      
>减少类之间的多余合作行为，降低耦合度，使类更加简明  
- 搬移字段（Move File）  
>某个字段被所在类之外的另一个类频繁调用，移动字段  
- 提炼类（Extral Class）  
>建立一个新类，将相关字段和函数从旧类搬移到新类  
- 将类内联化（Inline Class）  
>(某个类没有做太多事情)将这个类的所有特性搬移到一个类中，然后移除  
- 隐藏“委托关系”（Hide Delegate）  
>![](https://raw.githubusercontent.com/learn-OS/DesignPatterns/master/img/QQ20150109110711.png)
>![](https://raw.githubusercontent.com/learn-OS/DesignPatterns/master/img/QQ20150109110731.png)
>![](https://raw.githubusercontent.com/learn-OS/DesignPatterns/master/img/QQ20150109110802.png)
>![](https://raw.githubusercontent.com/learn-OS/DesignPatterns/master/img/QQ20150109110817.png)

- 移除中间人（Remove Middle Man）
>![](https://raw.githubusercontent.com/learn-OS/DesignPatterns/master/img/QQ20150109111602.png)

- 引入外加函数（Introduce Foreign Method）
>![](https://raw.githubusercontent.com/learn-OS/DesignPatterns/master/img/QQ20150109112115.png)

- 引入本地扩展（Intoduce Local Extension）
>![](https://raw.githubusercontent.com/learn-OS/DesignPatterns/master/img/QQ20150109112356.png)









#####7. 重新组织数据
- 自封字段（Self Encapsulate Field）
![](https://raw.githubusercontent.com/learn-OS/DesignPatterns/master/img/QQ20150109135912.png)


	class IntRange{
		IntRange(int low,int high){
			initialize(low,high);
		}
	    private void initialize(int low, int high) {
			// TODO Auto-generated method stub
			_low=low;
			_high=high;
		}
	
		boolean includes(int arg){
			return arg >=getLow()&&arg<=getHigh();
		}
		
		void grow(int factor){
			setHigh(getHigh()*factor);
		}
		
		private int _low , _high;
	
		 int getLow() {
			return _low;
		}
	
		 void setLow(int _low) {
			this._low = _low;
		}
	
		 int getHigh() {
			return _high;
		}
	
		 void setHigh(int _high) {
			this._high = _high;
		}
		
			
	}
	
	class CappedRange extends IntRange{
		CappedRange(int low,int high, int cap){
			super(low, high);
			_cap = cap;
		}
		
		private int _cap;
		int getCap(){
			return _cap;
		}
	
		int getHigh(){
			return Math.min(super.getHigh(),getCap());
		}
	}



- 以对象取代数据值（Replace Data Value with Object）
- 将值对象改为引用对象
- 将引用对象改为值对象
- 以对象取代数组
- 复制“被监视数据”
- 将单项关联改为双向关联
- 将双向关联改为单项关联
- 以字面常量取代魔法书
- 封装字段
- 封装集合
- 以数据类取代记录
- 以类读取类代码
- 以子类取代类型吗
- 以State/Strategy取代类型码
- 以字段取代子类

#####8.简化条件表达式

#####9.简化函数调用

#####10.处理概括关系

#####11.大型重构

#####12.重构，复用与实现

#####13.重构工具








