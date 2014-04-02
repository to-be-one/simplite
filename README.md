simplite
========
simplite是一个超轻量的js模板引擎，支持所有原生js的逻辑语法，
支持各种嵌套子模板和嵌套逻辑。在嵌套子模板的时候，可以指定使用的数据集，在模板里面可以使用_this来访问传入的数据。
举例来说，比如现在导入a模板<%include('a', map)%>，比如现在map={one:12,two:22}，那么可以在模板中使用<%=one%>或者<%=_this.one%>
来访问。如果嵌套模板的时候，没有指定数据集，那么默认使用父模板中的_this数据集，即父模板的全部数据。
使用类似于jsp的语法来书写模板逻辑，学习成本低。
支持面向对象方式使用和静态函数方式使用。
支持重定义模板语言的标签符，默认为<%和%>
代码量少，学习成本低。

欢迎交流：10844242
