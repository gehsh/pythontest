# oop-python面向对象
- python的面向对象
- 面向对象编程
    - 基础
    - 公有私有
    - 继承
    - 组合，Mixin
- 魔法函数
    - 魔法函数概述
    - 构造类魔法函数
    - 运算类魔法函数
    
# 1 面向对象概述（objectoriented,oo）
- oop思想
    - 任务由模型构成
- oo：面向对象
- ooA:面向对象的分析
- ooD:面向对象的设计
- ooI:XXX的实现
- ooP:XXXd的编程
- ooA-->ooD-->ooI：面向对象的实现过程
- 类和对象的概念：
    - 类：抽象名词，代表一个集合，共性的事物
    - 对象：具体的事物，单个个体
    - 类和对象的关系：
        - 一个具象，代表一类事物的某一个个个体
        - 一个是抽象，代表一大类事物
- 类的内容：
    - 表明事物的特征，即属性（变量）
    - 表明事物的功能或动作，成为成员方法（函数）
# 2 类的基本实现
- 类的命名
    - 遵循变量的命名规则
    - 大驼峰
- 类的声明
    - 用class关键字
    - 案例:1.py
        变量 = 类名() #实例化了一个对象
    - 访问对象成员
        - 使用点操作符
            obj.成员属性名称
            obj.成员方法
    - 可以通过默认内置变量检查类和对象的所有成员
        - 对象所有成员检查
        
            # dict前后各有两个下划线
            obj.__dict__
        - 类的所有成员
        
            # dict前后各有两个下划线
            class_name.__dict__


# 3 anaconda基本使用
- anaconda主要是一个虚拟环境管理器
- 又是一个安装包管理器
- conda list:显示anaconda安装的包
- conda env list:显示anaconda的虚拟环境列表
-  conda creat -n XXX python=3.6:创建版本为3.6的虚拟环境，名称为XXX

