## Notes on some basic Python syntax, coding styles

For private methods, coding convention is to keep an underscore before the method name. Using double underscores makes the use of the method by others more difficult.

```Python

_myPrivateMethod()

__superPrivateMethod()


```

Any whole number is an *integer* e.g 1 is a whole number, 1.0 is a floating point. integers are represented by int data type. –9,223,372,036,854,775,808 and 9,223,372,036,854,775,807 range is any number for int in 64 bit variable. 

**float data type** The maximum value that a floating‐point variable
can contain is ±1.7976931348623157 × 10308 and the minimum value that a floating point variable can contain is ±2.2250738585072014 × 10‐308 on most platforms.

**complex number** consists of a real number and an imaginary number that are paired together. The **imaginary number always appears with the j after it**

```Python

myComplexNumber = 4 + 5j


```

**logical operators require Boolean values** using the **bool** type. A variable of this type has only two values, True or False. e.g. 

```Python

myBool = 1 > 2 //false

```

Operator :

= Assigns value found in the right operand to the left operand

+= Adds the value found in the right operand to the value found in the left operand and places the result in the left operant e.g. myVar += 2, will mean 



