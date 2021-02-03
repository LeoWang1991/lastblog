### 参考资料

[1. 廖雪峰java教程](https://www.liaoxuefeng.com/wiki/1252599548343744/1255876875896416)

### 笔记

1. 编译型和解释性语言，java编译过程，先编译成字节码，然后针对不同平台arm x86来编写不同的虚拟机jvm来运行(编译后的字节码)。命令行里的话 `javac`负责编译.java代码到.class字节码文件，然后通过`java` 来执行.class文件

2. JDK JRE，JDK包括JRE和编译工具，JRE提供字节码的运行环境包括了JVM和一些类库。

3. java程序类名需要和文件名一致，建议大写，是因为java语言是解释性语言，遇到import时候才会去响应的文件目录查找对应的class文件，名字一致的话，可以提高查找效率。

4. 一个简单的java程序 固定入口`main()`

5. java的基本数据类型

   1. 整数： byte short long int
   2. 浮点：float double
   3. 字符串：chart
   4. boolean

6. 声明类型 public private protected的使用

7. `final`声明常量，用`var` 声明可以省略变量类型，可以自动补充

8. 类和对象，类是对象的模板，对象是类的实例

9. 每个class都有构造方法，没有则默认存在一个, 可以有多个构造函数，在实例化的时候 通过传参的来识别，调用哪个构造方法

10. 重写override和重载overload区别

11. 多态，Java的方法调用总是作用于运行期对象的实际类型

12. 抽象类，如果父类方法没有任何作用，只是为了定义方法签名，让子类重写Override的话，可以把父类的方法声明为抽象方法, 类本身也需要加上`abstract`声明

    ```java
    abstract class Person {
    	public abstract void run() {}
    }
    ```

13. 



