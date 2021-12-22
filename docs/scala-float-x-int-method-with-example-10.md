# Scala Float > (x: Int)方法示例

> 原文:[https://www . geesforgeks . org/Scala-float-x-int-method-with-example-10/](https://www.geeksforgeeks.org/scala-float-x-int-method-with-example-10/)

如果浮点值大于指定的 Int 值，则使用 **> (x: Int)** 方法返回 true。

> **方法定义:** (Float_Value)。> (Int_Value)
> **返回类型:**如果浮点值大于指定的 Int 值，则返回 true。

**示例#1:**

```
// Scala program of Float >(x: Int)
// method

// Creating object
object GfG
{ 

    // Main method
    def main(args:Array[String])
    {

        // Applying >(x: Int) function
        val result = (100.0).>(50)

        // Displays output
        println(result)

    }
} 
```

**Output:**

```
true

```

**例 2:**

```
// Scala program of Float >(x: Int)
// method

// Creating object
object GfG
{ 

    // Main method
    def main(args:Array[String])
    {

        // Applying >(x: Int) function
        val result = (65.0).>(100)

        // Displays output
        println(result)

    }
} 
```

**Output:**

```
false

```