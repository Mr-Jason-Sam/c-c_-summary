# C++继承和多态
* 私有继承和组合的关系

	> 相同点：都可以表示”有一个“关系。<br>
	> 不同点：能访问基类的protected成员，并且可以重写基类的虚函数，甚至当基类是抽象类的情况。组合不具有这些公能。<br>

 `注意：选择它们的原则为尽可能使用组合，万不得已才用私有继承`

* 什么是多态

	`多态定义：同一操作作用于不同对象，可以有不同解释，产生不同的执行结果。`
	
	> 编译时的多态：编译时的多态性是通过重载来实现的。对于非虚成员来说，系统在编译时，根据传递的参数、参数个数等信息来决定实现何种操作。<br>
	> 运行时的多态：运行时的多态性就是指直到系统运行时，才根据实际情况决定实现何种操作。C++中，运行时的多态性通过虚成员实现。<br>
	
* 