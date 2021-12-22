# 斯卡拉双

T2】原文:[https://www.geeksforgeeks.org/scala-double-x-long-method-5/](https://www.geeksforgeeks.org/scala-double-x-long-method-5/)T5】

在 Scala 中，double 是一个 64 位的浮点数，相当于 Java 的 Double 原语类型。如果该值小于 x，则使用 **< (x:龙)**方法返回真，否则返回假。

> **方法定义–**定义< (x:长):布尔值
> 
> **返回–**如果该值小于 x，则返回真，否则返回假。

**示例#1:**

```
// Scala program to explain the working 
// of Double <(x: Long) method

// Creating object
object GfG
{ 

    // Main method
    def main(args:Array[String])
    {

        // Applying <(x: Long) function
        val result = (12.00123.toDouble).<(8:Long)

        // Displays output
        println(result)

    }
} 
```

**Output:**

```
false

```