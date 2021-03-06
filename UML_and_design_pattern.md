# 序言
编程有趣，开发高质量的软件却困难。（这一说法在人月神话中也被提到）
# 前言
本书可以给予你的：学习优秀的设计，过程线路图，UML建模，设计模式，吸取经验与教训，从实际案例中学习，设计到编码，TDD与重构，分层架构，设计框架
# 第一章：面向对象分析和设计(OOA/D object-oriented analysis/design)
UML是个很好的表示法但只是个工具，如何用对象进行思考更重要
OO开发中，*最重要的能力是熟练地为软件对象分配职责*
分析：强调调查研究问题以及需求，而不是解决方案
设计：满足需求的 *概念上* 的解决方案而非实现
面向对象分析中，强调在问题领域内发现和描述对象
面向对象设计中，强调的是定义软件对象以及他们如何协作以实现需求
定义用例->定义领域模型->定义交互图->定义设计类图
用例(use case)：人们如何使用应用的情节或场景
领域模型或又称概念对象模型(domain model or conceptual object model)：面向对象分析的结果，问题里的重要概念，属性和关联
顺序图(sequence diagram)：展示软件对象间的信息流和信息引起的方法调用
设计类图(design class diagram):用于有效的表示类定义的静态视图，描述类的属性和方法
统一建模语言(UML)是描述，构造和文档化系统制品的可视化语言
应用UML的三种透视图：
- 概念透视图：用图来描述现实世界或者关注领域中的事物
- 规格说明（软件）透视图：用图（使用与概念透视图中相同表示法）来描述软件的抽象物或具有规格说明和接口的构件，但不约定特定实现
- 实现（软件）透视图：用图来描述特定技术中的实现（实际使用中会一步到这步）

几个概念：
- 概念类：现实世界中的概念或事物
- 软件类：无论是过程或是方法中，都表示软件构件在规格说明或实现透视图中的类
- 实现类：特定OO语言（如JAVA）中的类

# 第二章：迭代，进化与敏捷
统一过程（Unified Process）
迭代开发（iteratice development）：开发被组织成一系列固定的短期小项目（如三个星期），成为迭代。每次迭代都经过测试，集成并可执行的局部系统。每次迭代都具有各自的需求分析，设计，实现和测试活动.
迭代的输出不是实验性或将丢弃的原型，迭代开发也不是构造原型。与之相反，其输出是最终系统的产品子集
迭代与统一开发并不提倡不受控制，反应式的驱动过程，而是一方面认同和稳定一组需求，一方面接受需求不断变化的事实。以求能够快速反馈，螺旋上升
迭代中关键思想：时间定量。必须依照时间表来集成，测试，稳定局部系统。如难以满足期限要求，应从本次迭代中去除任务或需求，分配于将来的迭代。
瀑布生命周期：试图在编程前(详细)定义所有或大部分需求，试图在编程前创建出完整的设计或模型集，试图在开始前定义可靠的计划或时间表
瀑布方法对于绝大多数软件项目是拙劣的实践
不要用不健康的瀑布思维侵蚀迭代或up项目
瀑布模型的关键错误：假设规格说明时刻预知的和稳定的，并且在项目开始时就能正确定义
然而软件开发是变更大且不稳定的领域，也被认为是新产品开发（new product development）的领域。
也并没有人说编程前的分析和设计无用，重要的是中庸和平衡
UP的核心：短时间定量迭代，进化和可适应性开发
UP项目将其工作和迭代组织为四个主要阶段：
- 初始（inception）：大体上的构想，业务案例，范围和模糊评估
- 细化（elaboration）：已精华的构想，核心架构的迭代实现，高风险的解决，确定大多数需求和范围以及更为实际的评估
- 构造（construction）：对遗留下来的风险较低和比较简单的元素进行迭代实现没准备部署
- 移交（transition）：进行beta测试和部署

一个开发周期由多个迭代组成
# 第二章：案例研究
