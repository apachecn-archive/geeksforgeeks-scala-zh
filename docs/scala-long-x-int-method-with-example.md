# 斯卡拉龙！=(x: Int)方法示例

> 原文:[https://www . geeksforgeeks . org/Scala-long-x-int-method-with-example/](https://www.geeksforgeeks.org/scala-long-x-int-method-with-example/)

在 Scala 中，long 是 64 位有符号整数，相当于 Java 的 Long 基元类型。**！=(x: Int)** 方法检查给定的 Long 和 Int 值是否相等。

> **方法定义–**def！=(x: Int):布尔值
> 
> **返回–**如果该值不等于 x，则返回真，否则返回假。

**示例#1:**

```
// Scala program to explain working 
// of Long !=(x: Int) function

// Creating object
object GfG
{ 

    // Main method
    def main(args:Array[String])
    {

        // Applying !=(x: Int) function
        val result = (10).toLong.!= (10:Int)

        // Displays output
        println(result)

    }
} 
```

**输出:**

```
false
```

**例 2:**

```
// Scala program to explain working
// of Long !=(x: Int) function

// Creating object
object GfG
{ 

    // Main method
    def main(args:Array[String])
    {

        // Applying !=(x: Int) function
        val result = 1186000000.toLong.!= (1296:Int)

        // Displays output
        println(result)

    }
} 
```

**输出:**

```
true
```