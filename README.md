          ========================================================================
				控制台应用程序：Calculater 项目说明
	  ========================================================================
	  本控制台应用程序，支持常见的20种数学函数运算，另外支持（（））嵌套运算：分别如下：
	  "SIN","COS","TAN","ARCSIN","ARCCOS","ARCTAN","SINH","COSH","TANH","LOG10","LN",
	  "EXP","FACT","SQRT","CUBEROOT","LOG","POW","MOD","YROOT","AVG","SUM","VAR","VARP",
	  "STDEV","STDEVP"
	  ==============================================================================
				      测试用例如下：
				   (1+(1/1)）*(1*1)=2
	  ==============================================================================
	  编译环境，vs2012，vc++控制台应用程序，直接fork，即可获取源代码
          ===============================================================================
	  思想：通过语义检测函数名称，分割表达式，用数据结构去封装，两个栈，一个用来表示函数
	  之间的嵌套结构，一个用来计算运算表达式。 
