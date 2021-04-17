# 尚硅谷java学习笔记
## java基础知识

### 我的第一个java程序

``` java
/*
对第一个java程序进行总结
1. java程序编写-编译-运行的过程
编写：我们将编写的java代码保存在以".java"结尾的源文件中
编译：使用javac.exe命令编译我们的java源文件。格式：javac 源文件名.java
运行：使用java.exe命令解释运行我们的字节码文件。 格式：java 类名

2.在一个java源文件中可以声明多个class。但是，只能最多有一个类声明为public的。
而且要求声明为public的类的类名必须与源文件名相同。

3. 程序的入口是main()方法。格式是固定的。

4. 输出语句：
System.out.println():先输出数据，然后换行
System.out.print():只输出数据

5.每一行执行语句都以";"结束。

6.编译的过程：编译以后，会生成一个或多个字节码文件。字节码文件的文件名与java源文件中的类名相同。

*/
public class Hello {
	public static void main(String[] args) {//public static void main(String a[]) {//arguments:参数
		System.out.print("Hello World!");
		System.out.println();//换行
		System.out.println("Hello World!");
		}
}

class Person{

}

class Animal{
	
}

```

### 注释

``` java

/*
1. java规范的三种注释方式：
单行注释
多行注释
文档注释(java特有)

2.
单行注释和多行注释的作用：
① 对所写的程序进行解释说明，增强可读性。方便自己，方便别人
② 调试所写的代码

3. 特点：单行注释和多行注释，注释了的内容不参与编译。
         换句话说，编译以后生成的.class结尾的字节码文件中不包含注释掉的信息

4. 文档注释的使用：
    注释内容可以被JDK提供的工具 javadoc 所解析，生成一套以网页文件形式体现的该程序的说明文档。

5. 多行注释不可以嵌套使用


*/

/**
文档注释
@author shkstart
@version v1.0
这是我的第一个java程序！非常的开森！

*/
public class HelloJava{
	/*
	多行注释：
	如下的main方法是程序的入口！
	main的格式是固定的！
	*/
	/**
	如下的方式是main()，作用：程序的入口。
	*/
	public static void main(String[] args){
		//单行注释：如下的语句表示输出到控制台
		//System.out.println("Hello World!")
		System.out.println("Hello World!");
	}
}

```

