# 组合模式
Composite模式也叫组合模式，是构造型的设计模式之一。
通过递归手段来构造树形的对象结构，
并可以通过一个对象来访问整个对象树。

## 角色
**Component （树形结构的节点抽象）**
    - 为所有的对象定义统一的接口（公共属性，行为等的定义）(IFile)
  
    - 提供管理子节点对象的接口方法(add(),remove())

    - [可选]提供管理父节点对象的接口方法

**Leaf （树形结构的叶节点）**
Component的实现子类

**Composite（树形结构的枝节点）**
Component的实现子类