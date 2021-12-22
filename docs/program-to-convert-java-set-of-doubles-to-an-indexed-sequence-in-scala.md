# 在 Scala 中将 Java 双精度集合转换为索引序列的程序

> 原文:[https://www . geesforgeks . org/program-to-convert-Java-set-of-double-to-an-indexed-in-sequence-Scala/](https://www.geeksforgeeks.org/program-to-convert-java-set-of-doubles-to-an-indexed-sequence-in-scala/)

利用 Scala 中 java 的*to Indexed eq*方法，可以将一组 Java 双精度值转换为 Scala 中的索引序列。在这里，我们需要导入 Scala 的 JavaConversions 对象，以便进行转换，否则会出现错误。
现在，让我们看一些例子，然后详细讨论它是如何工作的。
**例:1#**

```
// Scala program to convert Java set
// to an Indexed Sequence in Scala

// Importing Scala's JavaConversions object
import scala.collection.JavaConversions._

// Creating object
object GfG
{ 

    // Main method
    def main(args:Array[String])
    {

        // Creating set of doubles in Java
        val set = new java.util.HashSet[Double]()

        // Adding doubles to the set
        set.add(3.2)
        set.add(5.6)
        set.add(9.23)

        // Converting set to an Indexed Sequence
        val ind = set.toIndexedSeq

        // Displays Indexed Sequence
        println(ind)

    }
}
```

**Output:**

```
Vector(5.6, 3.2, 9.23)

```

**例:2#**

```
// Scala program to convert Java set
// to an Indexed Sequence in Scala

// Importing Scala's JavaConversions object
import scala.collection.JavaConversions._

// Creating object
object GfG
{ 

    // Main method
    def main(args:Array[String])
    {

        // Creating set of doubles in Java
        val set = new java.util.HashSet[Double]()

        // Adding doubles to the set
        set.add(3.66)
        set.add(123.66)
        set.add(96.66)

        // Converting set to an Indexed Sequence
        val ind = set.toIndexedSeq

        // Displays Indexed Sequence
        println(ind)

    }
}
```

**Output:**

```
Vector(3.66, 123.66, 96.66)

```