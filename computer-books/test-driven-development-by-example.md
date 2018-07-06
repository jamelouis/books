# [Test-Driven Development By Example](https://book.douban.com/subject/1771049/)

## Note

* 代码整洁可用是TDD所追求的目标
* 在TDD中，我们要这样做：
	1. 只有自动测试失败时，我们才重写代码
	2. 消除重复设计，优化设计结构
* TDD开发阶段：
	1. 不可运行 -- 写一个不能工作的测试程序，一开始这个测试程序甚至不能编译
	2. 可运行 -- 尽快让这个测试程序工作，为此可以在程序中使用一些**不合情理**的方法
	3. 重构 -- 消除在让测试程序工作中产生的重复设计，优化设计结构
* 不可运行->可运行->重构 -- 这是TDD的口号
* TDD的内容组成：
	1. 资金实例 -- 典型的TDD例子
	2. xUnit -- 简单自动测试框架的构建
	3. TDD模式

## Others

* [googletest](https://github.com/google/googletest) for c++

