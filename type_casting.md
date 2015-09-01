title : Type Casting
___

Something I am getting used to while learning Java is Type Casting. Type Casting is the assignment of one type of variable to another type.

There are two different types of Type Casting in Java. The widening casting from byte up to double, including everything in between (these take up increasing amounts of memory) and narrowing casting (a decreasing amount of memory) from double down to byte, also including everything in between.

It is important that the type cast objects share the same type hierarchy, meaning that they have a parent child relationship between them. If this is not the case, the compiler will throw a ClassCastException. Narrowing casting needs to be explicitly set in that you need to be explicit in the type of casting required. 

Type casting is mainly used to get access to fields and methods declared on a target type or class and I am sure I will be using more of them as I get more familiar with Java.
