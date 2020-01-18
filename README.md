# 设计模式

- 时隔半年再次回顾设计模式。

| 序号 |          模式名称和代码链接          |          模式类型          | 描述 |
| :--: | :----------------------------------: | :--: | :--: |
|  1   | [抽象工厂模式](./AbstractFactory.php) | 创建型 | **抽象工厂模式**在不指定具体类的情况下创建一系列相关或依赖对象。 通常创建的类都实现相同的接口。 抽象工厂的客户并不关心这些对象是如何创建的，它只是知道它们是如何一起运行的。 |
|  2   | [建造者模式](./Builder.php) | 创建型 | **建造者模式**是将一个复杂的对象的构建与它的表示分离，使得同样的构建过程可以创建不同的表示。创建者模式隐藏了复杂对象的创建过程， 它把复杂对象的创建过程加以抽象，通过子类继承或者重载的方式，动态的创建具有复合属性的对象。 |
|  3  | [工厂方法模式](./FactoryMethod.php) | 创建型 | 在**工厂方法模式**中，工厂父类负责定义创建产品对象的公共接口，而工厂子类则负责生成具体的产品对象，这样做的目的是将产品类的实例化操作延迟到工厂子类中完成 |
|  4   | [多例模式](Multi.php) | 创建型 | **多例模式**是指存在一个类有多个相同实例，而且该实例都是该类本身。 多例类可以有多个实例， 多例类必须自己创建、管理自己的实例，并向外界提供自己的实例。 多例模式实际上就是单例模式的推广。 |
|  5   | [对象池模式](Pooler.php) | 创建型 | **对象池模式**是一种提前准备了一组已经初始化了的对象『池』而不是按需创建或者销毁的创建型设计模式。 |
|  6   | [原型模式](./PrototypePattern.php) | 创建型 | **原型模式**是用于创建重复的对象，同时又能保证性能。 |
|  7   | [简单工厂模式](./SimpleFactory.php) | 创建型 | **简单工厂模式**是一个精简版的工厂模式。 它与静态工厂模式最大的区别是它不是『静态』的。 |
|  8   | [单例模式](./Singleton.php) | 创建型 | 在应用程序调用的时候，只能获得一个对象实例。 |
|  9   | [静态工厂模式](./StaticFactory.php) | 创建型 | 与抽象工厂模式类似，此模式用于创建一系列相关或相互依赖的对象。 **『静态工厂模式』**与**『抽象工厂模式』**的区别在于，只使用一个静态方法来创建所有类型对象， 此方法通常被命名为 `factory` 或 `build`。 |
|  10  |                                      |                                      |      |
|  11  |                                      |                                      |      |
|  12  |                                      |                                      |      |
|  13  |                                      |                                      |      |
|  14  |                                      |                                      |      |
|  15  |                                      |                                      |      |
|  16  |                                      |                                      |      |
|  17  |                                      |                                      |      |
|  18  |                                      |                                      |      |
|  19  |                                      |                                      |      |
|  20  |                                      |                                      |      |
|  21  |                                      |                                      |      |
|  22  |                                      |                                      |      |
|  23  |                                      |                                      |      |
|  24  |                                      |                                      |      |
|  25  |                                      |                                      |      |


