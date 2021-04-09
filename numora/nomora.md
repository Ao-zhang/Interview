# NOMURA

## Self introduction

## Q&A

1. Talk about your bookstore

	网页前端用react框架，实现功能较为详实，除去基本浏览、搜索、购买书籍的功能外，还包含管理员数据统计、数据修改等功能；后端使用springboot框架，分成了6个部分组成（面试时只想起来了4个），包括controller——处理request请求，entity——对数据库类做映射，repository——与数据交互，service——对repository进行包装，dao——逻辑上对service进一步包装处理，utils——包含一些比较通用的函数功能，如log输出，日期转化，接口config等。

2. Why do you use mongoDB

	因为对于图片这类非结构化信息来说，使用mysql存储太大了，不利于mysql存储查找。

3. Why don't you store the path of image instead?

	我回答的是因为老师建议我们使用一下monggodb这样的非结构化数据库，对比了解sql和nosql的区别。我个人觉得使用path来存储图片信息是非常不错的，这样不用在两个数据库中查询，也是现在很多应用、网站存储图片的方式。

	后来宽宽说存path的话会造成两次服务器请求，而用MongoDB的话用户只需要发送一次请求就OK了。

4. What is the difference between SQL and NoSQL?

	- SQL数据库提供关系型的表来存储数据，NOSQL采用json键值对的方式存储数据
	- SQL更加规范化，需要先定义数据模式，而mongodb记录数据无需事先定义文档和集合
	- SQL有数据完整性（完整性约束，外键），NOSQL没有
	- 简单来说，sql适合对数据一致性有要求，且离散数据之间有逻辑相关的数据存储；nosql时候不想管，不确定，方便随时扩展的数据存储

5. Spring configuration

	这个问题没有get到点，回复的是我后端中分了几层，然后用了annotation注解进行配置？

6. What language do you use

	用的最多的是C++，java在写互联网项目的时候用过，python平时会用来写点小脚本，如爬虫，数据处理等。

7. Talk about const

	const定义常量，表示这个变量只读，不能被修改

	```c++
	  const char* p2 = greeting;          // 指针变量，指向字符数组常量（const 后面是 char，说明指向的字符（char）不可改变）
	    char* const p3 = greeting;          // 自身是常量的指针，指向字符数组变量（const 后面是 p3，说明 p3 指针自身不可改变）
	```

8. what is the difference between point and reference

	指针有自己的空间——用于存指向对象的地址，而引用与被引用对象直接共用同一块地址空间

9. data structure do you use in cpp

	map，vector，set，list，queue这些

10. what is the difference between map and set.

	map存储的是键值对，set一般存值，都是红黑树实现，**map和set都不允许重复！！**回答错了，multimap才允许重复

	补充：map的迭代器不允许修改key，可以修改value，而set的迭代器是const的。

11. iterator

	迭代器可以用来遍历容器中所有的元素

12. How the memory is managed in cpp

	堆：从低地址向高地址生长，用于程序动态分布，如malloc，new操作

	栈：从高地址向低地址生长，存放局部变量，函数参数，函数返回值等。

13. how often do you use java/python

	不常用

14. Any other question?

	advise？time table？暑期实习项目招多少人？

	暑期项目大部分还是国人，但是也可能有国外的朋友，所以英语比较重要的。



